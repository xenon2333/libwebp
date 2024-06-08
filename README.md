libwebp
---
一个用于Webp图像编码解码的[aardio](https://www.aardio.com)库，基于[libwebp](https://developers.google.com/speed/webp/docs/api)项目。

与GDI+库联用，实现常见图片格式（PNG、JPEG、BMP等）与Webp格式之间的双向快速转换。也可用于图像的批量压缩。

## 使用方法
远程引用示例：
```js
_IMPORTURL["libwebp"] = "https://github.com/xenon2333/libwebp/releases/latest/download/libwebp.tar.lzma";
import libwebp;
```
也可以在aardio中单独运行以下代码安装扩展库：
```js
import ide;
ide.installLib("libwebp","https://github.com/xenon2333/libwebp/releases/latest/download/libwebp.tar.lzma");
```

具体用法请参考语法智能提示和源代码。

## 参考文档
https://developers.google.com/speed/webp/docs/api
