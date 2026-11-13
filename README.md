# 你好，我是祁莉静 👋

**C++ / Qt 嵌入式方向开发者** | 关注桌面应用、音视频、多线程与网络协议

- 🔭 正在求职：C/C++ 嵌入式 / Qt 开发岗位
- 🌱 技术方向：Linux 用户态编程、多线程并发、Socket 网络编程、FFmpeg 音视频、深度模型 C++ 部署

## 🛠 技能栈

![C](https://img.shields.io/badge/C-语言-A8B9CC?logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-11/14-00599C?logo=cplusplus&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-5.x-41CD52?logo=qt&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-用户态编程-FCC624?logo=linux&logoColor=black)
![FFmpeg](https://img.shields.io/badge/FFmpeg-音视频-007808?logo=ffmpeg&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8?logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX%20Runtime-模型部署-ED1C24)
![SQLite](https://img.shields.io/badge/SQLite-数据库-003B57?logo=sqlite&logoColor=white)
![TCP](https://img.shields.io/badge/TCP-Socket%20编程-blue)

## 📌 精选项目

### 1. [农业大棚环境监控与音视频存储系统](https://github.com/xitno1/SmartSecurityEnvMonitoring)
单机版 Qt/C++ 环境监控系统（个人独立开发）
- **音视频**：FFmpeg 摄像头采集 → 解码 → 实时显示，H.264 编码录像与回放
- **传感监控**：串口采集温湿/光照数据，实时曲线（Qt Charts）+ 阈值告警 + 设备联动
- **架构**：MVC 四层分离，采集/编码/播放多线程，SQLite 单例数据库
`Qt` `C++` `FFmpeg` `QSerialPort` `SQLite` `多线程`

### 2. [智能行车辅助系统 · 客户端（毕业设计）](https://github.com/xitno1/SmartCarAssist-Client)
基于 YOLOv8 的行车辅助客户端（负责客户端全部代码）
- **模型部署**：ONNX Runtime C++ 部署 4 个 YOLOv8 模型（车辆/行人/红绿灯），letterbox 逆映射 + NMS
- **网络协议**：自研 TCP 应用层协议，16 字节定长包头 + CRC 校验 + 图片分片传输与丢失分片定向重传
- **并发**：采集/网络/分片/心跳多线程协作，心跳保活机制
`YOLOv8` `ONNX Runtime` `OpenCV` `TCP` `多线程`

---

 📮 联系方式：1497062475@qq.com

<!---
xitno1/xitno1 是一个 ✨ 特殊 ✨ 的仓库：它的 README.md 会显示在你的 GitHub 个人主页上！
-->
