# php_jump_auto

依赖：
 * ImageMagick

微信跳一跳的 php 版本，但是恕我直言，这个东西跟 php 没有太大的关系，只不过就是用 php 实现了执行命令行，和调用图片库找色而已

目前最高分跳了800多分，还算可以吧。

大家再使用的时候，可以先用一下，看看找色对不对，不对，再去修改人物的色值，就好了。

注意：

```
exec("./adb shell input swipe 100 100 100 100 " . intval($distance * 1.343));
```

需要根据自己手机调整这个比例值，我这边用的是1.343，大家根据自己的手机调整为自己的值。


更多的就看代码里面的注释把，注释比较齐全



![score](https://github.com/crazyhl/php_jump_auto/blob/master/20180106_123526.jpg?raw=true)