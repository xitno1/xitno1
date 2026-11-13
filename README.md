<img src="https://capsule-render.vercel.app/api?type=waving&height=220&text=Welcome%20to%20my%20GitHub&fontSize=44&fontColor=ffffff&color=0:41CD52,50:0EA5E9,100:00599C&animation=fadeIn&fontAlignY=36&desc=C%2B%2B%20%2F%20Qt%20%E5%B5%8C%E5%85%A5%E5%BC%8F%E5%BC%80%E5%8F%91%E8%80%85&descAlignY=58&descSize=20" width="100%"/>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=00599C&center=true&vCenter=true&width=560&lines=%E5%85%B3%E6%B3%A8%E5%B5%8C%E5%85%A5%E5%BC%8F%E5%BA%94%E7%94%A8+%C2%B7+%E9%9F%B3%E8%A7%86%E9%A2%91+%C2%B7+%E5%A4%9A%E7%BA%BF%E7%A8%8B%E4%B8%8E%E7%BD%91%E7%BB%9C%E5%8D%8F%E8%AE%AE;FFmpeg+%E9%87%87%E9%9B%86%E7%BC%96%E7%A0%81+%C2%B7+ONNX+Runtime+%E6%A8%A1%E5%9E%8B%E9%83%A8%E7%BD%B2;Let's+build+something+cool+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
</p>

## 👨‍💻 关于我

- 🎯 **求职方向**：C/C++ 嵌入式开发 / Qt 桌面应用开发
- 🛠 **日常武器库**：Linux 用户态编程 · 多线程并发 · Socket 网络编程 · FFmpeg 音视频 · 深度模型 C++ 部署
- 📌 习惯把每个项目做出**完整闭环**：协议设计 → 并发架构 → 算法部署 → 界面呈现
- 📮 联系我：**1497062475@qq.com**

## ⚙️ 技术栈

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=cpp,c,qt,linux,git,github,vscode,md&perline=8" />
  </a>
</p>

![FFmpeg](https://img.shields.io/badge/FFmpeg-音视频编解码-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-模型推理部署-ED1C24?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-数据库-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![TCP Socket](https://img.shields.io/badge/TCP-Socket网络编程-2563EB?style=for-the-badge)

---

## 🚀 精选项目

### 🚗 [智能行车辅助系统 · 客户端](https://github.com/xitno1/SmartCarAssist-Client) `团队项目 · 负责客户端`

> 基于 **YOLOv8 + ONNX Runtime + Qt** 的行车辅助客户端 —— 我负责客户端全部代码

<table>
  <tr>
    <td width="50%"><img src="assets/car-detect.jpg" alt="车辆检测"/></td>
    <td width="50%"><img src="assets/birdview.jpg" alt="鸟瞰模式"/></td>
  </tr>
  <tr>
    <td align="center">行车模式 · YOLOv8 实时车辆检测</td>
    <td align="center">360° 鸟瞰环视</td>
  </tr>
</table>

✨ **亮点技术**
- 🧠 ONNX Runtime C++ 部署 **4 个 YOLOv8 模型**（车辆/行人/红绿灯），letterbox 逆映射 + NMS 后处理
- 📡 自研 TCP 应用层协议：**16 字节定长包头 + CRC 校验 + 图片分片传输 + 丢失分片定向重传**
- 🔀 采集 / 网络 / 分片 / 心跳多线程协作，心跳保活

`YOLOv8` `ONNX Runtime` `OpenCV` `TCP` `多线程`

---

### 🌱 [农业大棚环境监控与音视频存储系统](https://github.com/xitno1/SmartSecurityEnvMonitoring) `个人独立开发`

> 基于 **Qt + FFmpeg + SQLite** 的大棚环境监控与音视频存储桌面应用

✨ **亮点技术**
- 🎥 FFmpeg 全链路：摄像头采集 → 解码 → 实时显示，**H.264 编码录像与历史回放**
- 🌡 串口采集温湿/光照数据：Qt Charts 实时曲线 + **阈值告警 + LED/风扇设备联动**
- 🏗 MVC 四层架构（View/Control/Model/Data），采集/编码/播放多线程分离

`Qt` `C++` `FFmpeg` `H.264` `QSerialPort` `SQLite` `Qt Charts`

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:00599C,100:41CD52&section=footer" width="100%"/>
</p>
