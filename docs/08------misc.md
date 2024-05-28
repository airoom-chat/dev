
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


