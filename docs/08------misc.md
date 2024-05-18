

## BigInt

BigInt 在 JSON.stringify 时报错，因为不知道如何系列化。因此，应当在转成 JSON 格式之前，先把 BigInt 转换为字符串：

    ret.compute_points = user.compute_points.toString();


