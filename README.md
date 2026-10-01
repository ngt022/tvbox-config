# TVBox 配置

只包含 **iOS 可用格式**（苹果CMS JSON 接口）的点播源，每个源都经过实测验证：
搜索能返回结果 **且** 响应里含真实播放地址。

## 用法

在 TVBox 的「点播接口地址」填入：

```
https://cdn.jsdelivr.net/gh/ngt022/tvbox-config@main/tvbox-working.json
```

备用地址（jsDelivr 不通时）：

```
https://raw.githubusercontent.com/ngt022/tvbox-config/main/tvbox-working.json
```

## 说明

- 为什么不用 `csp_*` 的 JAR 源？iOS 没有 JVM/ART，无法执行 Java/DEX，这类源在 iPhone 的 TVBox 上物理上跑不了。
- 源站会失效，本文件按需更新。
