
## topic 类型

主题分为两类：

1. 公共主题
2. 私有主题

上述两类主题的 mp3 存储在不同的存储桶中，公共主题存放在 R2 的公共 bucket 中，私有主题存放在私有 bucket 中。


## DB

对于不同类型的主题，存储方式不一样。Table topics:

```
  // 10: public topic
  // 11: private topic
  type          Int       @default(0)

  // For public topic
  mp3_url       String    @default("")   // mp3 url
  text          String    @default("")   // text for the topic

  // For private topic
  r2_path       String    @default("")   // r2 path
  presigned_url String    @default("")   // presigned url
  presigned_url_expires_at DateTime?     // presigned url expires at
```


## API

与消息的接口类似，也是采用不同的接口：

1. 公共主题 API

2. 私有主题 API

    POST airoom/topic
    POST airoom/topic/uploaded-to-r2

    DELETE airoom/topic


