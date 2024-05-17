
API endpoint:

    https://generativelanguage.googleapis.com

调用方法竟然是在后面加参数 key 就可以了！

## list_models

### v1

[
    'models/gemini-1.0-pro',
    'models/gemini-1.0-pro-001',
    'models/gemini-1.0-pro-latest',
    'models/gemini-1.0-pro-vision-latest',
    'models/gemini-pro',
    'models/gemini-pro-vision',
    'models/embedding-001',
    'models/text-embedding-004'
]

### v1beta

```
[
    'models/chat-bison-001',
    'models/text-bison-001',
    'models/embedding-gecko-001',
    'models/gemini-1.0-pro',
    'models/gemini-1.0-pro-001',
    'models/gemini-1.0-pro-latest',
    'models/gemini-1.0-pro-vision-latest',
    'models/gemini-1.5-flash-latest',
    'models/gemini-1.5-pro-latest',
    'models/gemini-pro',
    'models/gemini-pro-vision',
    'models/embedding-001',
    'models/text-embedding-004',
    'models/aqa'
]
```

## Pro or Flash

### Pro

Gemini 1.5 Pro：最先进
Gemini 1.5 Pro 于2 月份首次发布进行早期测试，当时它的最大代币窗口为 128,000 个代币。现在，Gemini Advanced 订阅者可以更广泛地使用它，基准代币窗口为 100 万个，并且可以选择注册 200 万个代币窗口。 

成本：每 100 万个代币 7 美元（对于超过 128K 代币的提示）；每 100 万个代币 3.50 美元（提示最多 128K 个代币）
最适合： 复杂的任务，产生更高质量的结果
响应时间：慢于1.5 Flash
代币窗口： 100万个现已可用，200万个可通过候补名单获得

### Flash

Gemini 1.5 Flash：专为速度而生
Gemini 1.5 Flash 是 Google I/O 大会上推出的一个新的、更精简的模型。它的主要卖点是响应时间，明显比 1.5 Pro 快。 Gemini 1.5 Flash 现已在全球上市。以下是您应该了解的内容。

成本：起价为每 100 万代币 35 美分（提示最多 128K 代币）
最适合：需要尽快完成的狭窄且高频的任务
响应时间： 比1.5 Pro更快
代币窗口： 100万个现已可用，200万个可通过候补名单获得


