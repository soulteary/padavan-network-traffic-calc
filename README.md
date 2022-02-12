# Padavan Network Traffic Calculator

这个工具用于展示 Padavan 设备中的流量数据。

## 在线地址

https://soulteary.github.io/padavan-network-traffic-calc/

## 使用方式

双击 `index.html` ，在浏览器新页面中输入从设备页面保存的数据，然后点击计算按钮即可。

数据格式可以使用：

```js
daily_history = [
    [0x790709, 0xfb2135, 0x449859]
    , [0x79070a, 0x12686c0, 0x3fc6e0]
];
monthly_history = [
    [0x770100, 0x27a3c88, 0xcb1774]
    , [0x770200, 0x194a04e7, 0x237acea]
];
```

或者：

```js
[
    [0x770100, 0x27a3c88, 0xcb1774]
    , [0x770200, 0x194a04e7, 0x237acea]
];
```

# License

数据转换代码取自 Padavan 项目，故协议和 https://bitbucket.org/padavan/rt-n56u/src/master/trunk/License 保持一致。
