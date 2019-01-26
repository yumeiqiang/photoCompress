
### 基于canvas的前端图片压缩


#### 用法如下：

```js
// 前端调用photoCompress这个函数，file为input读取的文件流，
photoCompress(file, {
  quality: 0.6   // 0-1，值越小，图片越模糊
},(base64Codes)=>{
  var bl = this.convertBase64UrlToBlob(base64Codes);
  // bl为压缩后的文件流，在这里可以进行图片的上传操作。
})
```
