# imagemin

## 图片压缩

### 安装包

```
cnpm install imagemin --save

// 用于压缩jpg图片
cnpm install imagemin-mozjpeg --save

// 用于压缩png图片
cnpm install imagemin-pngquant --save

// 用于将jpg/png转换为webp格式
cnpm install imagemin-webp --save
```

### imagemin.js文件配置

### 图片路径

压缩前路径:
`assets/images/`

压缩后路径:
`build/images/`

### 执行压缩命令

`node imagemin.js`

### 参考链接

[How Image Optimisation Decreased my Website's Page Weight by 62%](https://freshman.tech/image-optimisation/)

### 现有问题

png图片无法正常压缩，目前还在排查问题原因