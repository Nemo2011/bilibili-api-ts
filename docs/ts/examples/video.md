# 示例：获取视频信息

``` typescript
import { Video } from "bilibili-api-ts/video";

// 实例化 Video 类
var v = new Video({
    bvid: "BV1uv411q7Mv"
});
// get_info 是 async 函数
v.get_info({}).then(
    function (value) {
        // value 即为结果
        console.log(value);
    }
)

```
