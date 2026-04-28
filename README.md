<p align="center">
  <a href="https://github.com/chensongpoixs">
    <img src="https://visitor-badge.laobi.icu/badge?page_id=chensongpoixs.chensongpoixs" />
  </a>
  <a href="https://github.com/chensongpoixs">
    <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fchensongpoixs&query=followers&color=181717&label=GitHub&labelColor=282c34&logo=github&suffix=+follows&cacheSeconds=3600" />
  </a>
  <a href="https://huggingface.co/chensongpoixs">
    <img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-chensongpoixs-blue" />
  </a>
  <!-- 新增 ModelScope 数据集标签 -->
  <a href="https://www.modelscope.cn/datasets/chensongpoixs">
    <img src="https://img.shields.io/badge/ModelScope-Datasets-624aff?style=flat&logo=modelscope&logoColor=white" />
  </a>
  <a href="https://www.zhihu.com/people/chensong-1-90">
    <img src="https://img.shields.io/badge/zhihu-%E7%9F%A5%E4%B9%8E-blue?style=flat&logo=rss" />
  </a>
  <a href="https://blog.csdn.net/Poisx">
    <img src="https://img.shields.io/badge/CSDN-Blog-red?style=flat&logo=rss" />
  </a>
  <a href="https://leetcode-cn.com/u/chen-song-3">
    <img src="https://img.shields.io/badge/LeetCode-%E5%8A%9B%E6%89%A3-green?style=flat&logo=rss" />
  </a>
</p>

> ⚡️ 务必保持谦虚、谨慎、不骄、不躁的作风,保持艰苦奋斗的作风！！！
> 
> 我是一名北漂，和大多数北漂一样，为了生计而奔波，早上坐一个多小时地铁，加班很频繁
> 
> 一个永远积极向上、永远热泪盈眶、永远豪情满怀、永远坦坦荡荡！！！
> 
> 仍然在路上，向往自由和梦想的人！！！

---

### 👨‍💻 About Me

具有 **音视频、流媒体、GPU 加速及 AI 工程化** 等系统能力。  
长期深耕 **WebRTC、实时通信、视频编解码、渲染管线**，并持续投入 **大语言模型训练、推理优化与模型小型化** 方向。

- **核心技术栈**：C/C++、Go、Python、FFmpeg、WebRTC、GStreamer、CUDA、DirectX/OpenGL/Vulkan、Redis、Nginx
- **当前聚焦**：
  - 🔥 **知识蒸馏（Teacher-Student）**：大模型 → 小模型的精度迁移、软标签训练与结构搜索
  - 🔥 **专业小模型训练与部署**：面向垂直场景的高效小模型定制、量化与端侧推理优化
  - **LLM API 交互数据沉淀**：透明代理截获全量请求/响应，落盘 JSONL 以构建训练数据集
  - **Agent/ReAct 编程范式**：思考-行动-观测闭环的编码助手开发
  - **视频超分辨率**：面向 RTC 场景的超分模型落地
  - **流媒体 GPU 加速转码**：基于 NVENC/CUDA 的高吞吐转码服务

---

### 📚 核心领域与项目库


#### 🎥 音视频与流媒体
| Date | Project | 简介 |
|:---|:---|:---|
| 2018-01-28 | [1、音视频基础](https://chensongpoixs.github.io/cmp4_box_avi_flv/) | 容器格式、编解码原理深入梳理 |
| 2021-12-05 | [2、WebRTC专题开嗨鸭](https://chensongpoixs.github.io/WebRTC/#/) | WebRTC 协议栈、信令、NAT 穿透等系统学习 |
| 2022-02-06 | [3、视频的编解码的原理的深度学习](https://chensongpoixs.github.io/cvideo_codec/) | H.264/H.265 原理、码控、主观质量优化 |
| 2023-12-06 | [4、RTSP 媒体服务](https://chensongpoixs.github.io/crtsp_server/) | 自研 RTSP 服务器，支持拉流转发与录制 |
| 2025-07-14 | [5、媒体服务GPU加速转码版本](https://chensongpoixs.github.io/cmedia_transcode/) | 基于 NVENC/CUDA 的高吞吐转码服务 |
| 2025-09-05 | [6、媒体传输协议库](https://chensongpoixs.github.io/libmedia_transfer_protocol/) | 自研跨协议流媒体传输框架，统一封装 WebRTC、RTSP/RTP/RTCP、HLS、FLV、MPEG‑TS、GB28181、SIP 等标准，提供推拉流、会话协商、转封装及媒体分发 API |
  
**RTC 与云游戏生态：**

- [①、云游戏、GPU虚拟化容器(Sandbox技术)和存储的虚拟化](https://chensongpoixs.github.io/ccloud_game_rtc/)
- [②、流媒体SFU](https://chensongpoixs.github.io/cmedia_rtc_server/)
- [③、RTC的学习记录](https://github.com/chensongpoixs/crtc_doc)
- [④、DirectX(D3D9、D3D11、D3D12)、OpenGL、Vulkan渲染原理学习demo](https://github.com/chensongpoixs/cd3d10_d3d11_d3d12_dxgi_opengl)

  
#### 🤖 人工智能与大模型

- [1、AI算法基本功和AI算法进阶技能(项目是在2019年12月份创建的，中间断断续续的更新。2023年初正式投入精力完善项目的内容)](https://chensongpoixs.github.io/cartificial_intelligence/)

- [2、超分辨率技术在实时音视频领域的研究与实践](https://chensongpoixs.github.io/cvideo_super_resolution_technology/)

- [3、大语言模型微调及其应用探索, 2025-11-25 投入精力跟踪行业前沿的技术](https://chensongpoixs.github.io/LLMSAPP/)

- [4、AI编码助手(Agent、ReAct -> 思考-行动-观测) 2026-01-01](https://chensongpoixs.github.io/clude_code/)

- [5、大模型交互日志与数据沉淀代理、直接服务于监督微调、偏好对齐等训练数据的准备工作(2026-04-26)](https://chensongpoixs.github.io/LLMInteractionRecorderProxy/)|


#### 🧩 开源项目 & 源码研习
| Date | Project | 简介 |
|:---|:---|:---|
| 2023-10-18 | [1、OpenGL基础理论、渲染虚拟相机 HDR、LDR、Bloom](https://chensongpoixs.github.io/crendering_virtual_cameras/) | 基础理论、渲染管线与后期特效 |
| 2023-12-17 | [2、线上日志收集系统](https://chensongpoixs.github.io/clog_collecter/) | 分布式日志采集与处理方案 |

**源码学习：**

- [Redis源码的学习](https://github.com/chensongpoixs/credis_source) 
- [STL源码的学习](https://github.com/chensongpoixs/cstl_source) 
- [Nginx源码的学习](https://github.com/chensongpoixs/cnginx_source)  
- [查看更多](https://github.com/chensongpoixs/)	

---

### ✍️ 技术写作

  - [操作系统原理：加载、中断、异常与系统调用](https://chensongpoixs.github.io/2020/05/06/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E5%8E%9F%E7%90%86%E4%B9%8B%E5%8A%A0%E8%BD%BD%E7%B3%BB%E7%BB%9F%E7%9A%84%E6%B5%81%E7%A8%8B-%E4%B8%AD%E6%96%AD-%E5%BC%82%E5%B8%B8%E5%92%8C%E7%B3%BB%E7%BB%9F%E8%B0%83%E7%94%A8/)
  - 更多文章请访问我的博客

---

### 📊 GitHub Analytics

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=chensongpoixs&theme=nord_bright" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=chensongpoixs&theme=nord_bright&utcOffset=8" />
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=chensongpoixs&theme=nord_bright" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=chensongpoixs&theme=nord_bright" />
</p>

---

<p align="center">
  <i>持续学习，持续建造。用工程师的方式，把梦想一件件变成现实。</i>
</p>
