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
姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟 

名称|功能|默认值|可选值
--|:--:|--:
img|裁剪图片的地址|空|url 地址 || base64 || blob
outputSize|裁剪生成图片的质量|1|0.1 - 1
