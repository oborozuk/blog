---
title: 解析 WebVTT 字幕的最简单方式
published: 2025-03-12
description: 偶然想到的 WebVTT 字幕解析方式，也可以用来解析 SRT 字幕
tags: [代码随笔]
category: 代码
draft: false
---

两三行就能搞定解析 WebVTT 和 SRT 的时间轴和文本，顺便还能解决一些 Corner Case。

```python
cue_pattern = re.compile(r".*\n.*?((?:\d+:)?\d{2}:\d{2}[.,]\d{3} +--> +(?:\d+:)?\d{2}:\d{2}[.,]\d{3}).*?\n")
splits = cue_pattern.split(text.strip())
for time_str, text in zip(splits[1::2], splits[2::2]):
    start, end = time_str.split(" --> ")
    # doc.events.append(Dialog(start, end, text.strip()))
```

可以解析如下例子（虽然不合规范）：

```vtt
404
00:00:03,211 --> 00:00:05,672
00:00:03,211 --> 00:00:05,672
这是

1行字幕

00:00:06.464 --> 00:00:07.966 align:start

这是

一行

字幕




WebVTT
00:00:08,049 --> 00:00:09,676

这是
一行字幕
```

至于其他数据？那还是交给专业的 parser 吧
