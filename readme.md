# 塔斯汀小程序模仿项目
- 本项目归塔斯汀所有，只做学习所用，请尊重原厂版权
- 可以去监听访问数据 fiddler 抓包工具抓取图片

- 界面模仿采用markman做标记
  1. 没有设计稿怎么 还原1：1还原小程序
  2. 拍屏得到小程序图片
  3. 使用在线大小[转换工具](https://www.gaitubao.com/)将图片改成750rpx
    以后在写wxss的时候，直接量像素就可以写进去，因为小程序以750rpx作为设计稿标准大小
    帮我们自动适配，很好用
  4. 使用[markman](http://getmarkman.com/) 先标注再写样式
    以后有设计师，就可以

- 项目配置在根目录app.json
  - 隐藏并定制navigationBar（导航栏）
    "navigationStyle": "custom"
  - 启动定位功能

- 使用了BEM国际命名规范
  tst_banners  广告位 block
  tst_banners__img  Element


css 技巧
  1. 能不用定位就不要用定位
    脱离文档流
  2. 移动端多用弹性布局


