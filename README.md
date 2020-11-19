# FFmpeg-Mac-master

从 [ffmpeg mac源](https://evermeet.cx/ffmpeg) 搬运得到，并用 JSdelivr 作为CDN加速，使用工具 [ReleaseDelivr](https://github.com/One-Studio/ReleaseDelivr)

## 最新FFmpeg下载链接示例：

https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Mac-master@master/dist/ffmpeg-mac-master.7z

## 某个版本的下载链接

通过下面的API接口获取历史版本号，比如 `4.3.1`，下载链接：

https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Mac-master@4.3.1/dist/ffmpeg-mac-master.7z

## 本搬运仓库API：

版本号：https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Mac-master@master/version

下载链接（ `/n` 分割）：https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Mac-master@master/download_link

API接口 Json格式：https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Mac-master@master/api.json

| API          | 类型     | 含义                                          |
| ------------ | -------- | --------------------------------------------- |
| Version      | string   | 版本号                                        |
| VersionList  | []string | 历史版本                                      |
| ReleaseTime  | string   | 最新版本的发布时间 (格式2020-10-20T12:16:01Z) |
| Checktime    | string   | 搬运时检查的时间                              |
| DownloadLink | []string | 下载链接                                      |
| Format       | int      | 格式(1=7z, 2=zip)                             |
| ReleaseNote  | string   | 更新日志                                      |
