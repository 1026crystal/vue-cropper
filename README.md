# vue-cropper
实现图片的裁剪，压缩，上传，预览11
### 下载安装
```
npm install vue-cropper

yarn add vue-cropper
```
### 使用
```
1、全局引入
main.js里面使用
import VueCropper from 'vue-cropper' 

Vue.use(VueCropper)
2、组件内按需引入
import { VueCropper }  from 'vue-cropper' 
components: {
  VueCropper,
}
```

### 功能
名称|功能|默认值|可选值
--|:--:|--:
刘备|哭|大哥|1
关羽|打|二哥|2
张飞|骂|三弟|3

名称|功能|默认值|可选值
--|:--:|--:
outputSize|裁剪生成图片的质量|1|0.1 - 1

outputType|裁剪生成图片的格式|jpg (jpg 需要传入jpeg)|jpeg || png || webp
info|裁剪框的大小信息|true|true || false
canScale|图片是否允许滚轮缩放|true|true || false
autoCrop|是否默认生成截图框|false|true || false
autoCropWidth|默认生成截图框宽度|容器的80%|0~max
autoCropHeight|默认生成截图框高度|容器的80%|0~max
fixed|是否开启截图框宽高固定比例|true|true | false
fixedNumber|截图框的宽高比例|[1, 1]|[宽度, 高度]
full|是否输出原图比例的截图|false|true | false
fixedBox|固定截图框大小|不允许改变|false|true | false
canMove|上传图片是否可以移动|true|true | false
canMoveBox|截图框能否拖动|true|true | false
original|上传图片按照原始比例渲染|false|true | false
centerBox|截图框是否被限制在图片里面|false|true | false
high|是否按照设备的dpr输出等比例图片|true|true | false
infoTrue|true 为展示真实输出图片宽高 false 展示看到的截图框宽高|false|true | false
maxImgSize|限制图片最大宽度和高度|2000|0-max
enlarge|图片根据截图框输出比例倍数|1|0-max(建议不要太大不然会卡死的呢)
mode|图片默认渲染方式|contain|contain , cover, 100px, 100% auto
