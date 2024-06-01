
## Test：google 收录时间

提交 sitemap.txt 5/29 8:15pm

收录时间：5/30 24:00


## videos

跟读，练习发音。浏览量1000w [](https://www.youtube.com/watch?v=EL6gw96u1-U)


仅仅是交谈，比如看了这个视频：[](https://www.youtube.com/watch?v=ZI1ZRqtpvF4)，就可以简单的和ai谈谈。


听力训练 [](https://www.youtube.com/watch?v=orBkNYE4U5o)




## textarea 自动调整高度

[Textarea Auto height](https://stackoverflow.com/a/24676492)

```
function auto_grow(element) {
  element.style.height = "5px";
  element.style.height = (element.scrollHeight) + "px";
}

textarea {
  resize: none;
  overflow: hidden;
  min-height: 50px;
  max-height: 100px;
}

<textarea oninput="auto_grow(this)"></textarea>
```


## BigInt

BigInt 在 JSON.stringify 时报错，因为不知道如何系列化。因此，应当在转成 JSON 格式之前，先把 BigInt 转换为字符串：

    ret.compute_points = user.compute_points.toString();


