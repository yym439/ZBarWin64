# VS2019编译Zbar源码

### 介绍

Zbar静态库、动态库编译；重新编译zbar源码，修改iconv.h 导出函数删除LIBICONV_DLL_EXPORTED，
解决引入libiconv静态库符号找不到问题

### 依赖第三方库

[libiconv](https://github.com/yym439/libiconv-windows)