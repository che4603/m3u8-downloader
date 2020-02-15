m3u8文件下载合并工具
===

主要功能是依据指定的m3u8网址，下载内含的视频片段，并合并为单一的ts视频文件。  
之后即可通过其它工具将单一ts视频文件转换为其它格式。
支持视频加密（目前仅AES）

## 编译打包

```shell
mvn package
```

文件位于`target/m3u8-downloader-0.0.1.jar`.

## 使用

```shell
jar -jar <path>/m3u8-downloader-0.0.1.jar <url>
```

合并后的文件为工作目录下的`final.ts`
