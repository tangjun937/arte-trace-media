# arte-trace-media

Arte Trace（X 频道 @2122264549180977152）的视频中转仓库。

发布链路：本地 mp4 → 本仓库 `media/` → jsDelivr 直链 → Buffer 发到 X。

- 直链格式：`https://cdn.jsdelivr.net/gh/tangjun937/arte-trace-media@main/media/<file>.mp4`
- jsDelivr 单文件上限 20MB，返回 `video/mp4`，Buffer 可直接抓取
- 上传与发布用 `D:\art-account\video\arte_publish.py post <video> <text.txt>`
- 旧的临时图床（litterbox / catbox）对本机 IP 会间歇封禁，不再使用
