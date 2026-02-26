# awesome-dtmb
Everything you need to know about DTMB(Digital Terrestrial Multimedia Broadcast)

## 标准与协议

- [GB 20600-2006 数字电视地面广播传输系统帧结构、信道编码和调制](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=41F48525779777A75F0898B87E9BD24E)
- [MPEG-TS ISO/IEC 13818-1:2025](https://www.iso.org/standard/91403.html)

### 视频标准

#### AVS

[数字音视频编解码技术标准工作组资料下载]https://www.avs.org.cn/index.php/index/list?catid=7

- AVS (CAVS / AVS1-P2 / AVS JiZhun / 基准类 / GB/T 20090.2—2006 / GB/T 20090. 2—2013)
    - [《信息技术 先进音视频编码 第2部分：视频》](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=AD0D3FA994651694F95F9E1364B88193)

- AVS+ (AVS1-P16 / AVS Guangdian / 广播类 / GB/T 20090.16-2016)
    - [《信息技术 先进音视频编码 第16部分：广播电视视频》](https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=1D4AC2D4256C8DE7E0AA286CA7649300)

> [AVS与AVS+的对比](https://blog.csdn.net/weixin_43360707/article/details/131128946)

- AVS2 (GB/T 33475.2-2016 GB/T 33475.2-2024 信息技术 高效多媒体编码 第2部分：视频)
    - [《信息技术 高效多媒体编码 第2部分：视频》](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=C23145CA7C18AC718FDE2589AC626D6E&refer=outter)
- AVS3 (GY/T 368-2023 先进高效视频编码)
    - [《先进高效视频编码》](https://www.nrta.gov.cn/art/2023/8/30/art_3715_65407.html)
- HEVC
- Vivid HDR

### 音频标准

- MPEG-1
- DRA

## 硬件接收设备

### USB 接收棒

- LeTV
    - Drivers
        - Linux Driver
    - Clients

### 电视

### 数字电视机顶盒

### SDR

### 天线


## 驱动程序与系统支持

### Linux

- [Linux DVB API](https://www.kernel.org/doc/html/v5.0/media/uapi/dvb/dvbapi.html)
- DVB Core
- [DtmbUSB](https://github.com/nxdong520/DtmbUSB): 乐视、爱华和CVB电视棒的Linux驱动

### Windows

- [广播驱动架构（Broadcast Driver Architecture）](https://learn.microsoft.com/zh-cn/windows-hardware/drivers/stream/broadcast-driver-architecture-minidrivers)
- [bdadev](https://sourceforge.net/projects/bdadev/): A Sourceforge Project dedicated to the development of Open-Source BDA Drivers and Tools

### Android

## 软件工具

- [AltDVB](): 用户开发的DVB兼容电视接收软件
- [DVB Blast]: a simple and powerful MPEG-2/TS demux and streaming application.
- [hys]

### 播放器
- [VLC Media Player with AVS/AVS+ and DRA support](): 社区改进的VLC播放器，支持AVS+视频解码
- [VLC 3.0.11.1 with AVS3-AVS2-CAVS](https://gitee.com/zhengtianbo/VLC3-AVS3AVS2CAVS): zhengtianbo 为 VLC3.0.11.1 添加AVS,AVS2,AVS3支持。提供基于VLC和ffmpeg的两种修改方案。
- [MPC-HC with AVS3-AVS2-CAVS](https://gitee.com/zhengtianbo/cavs-avs2-avs3_decoder_added_to_mpc_hc): zhengtianbo修改的MPC-HC，添加AVS, AVS2, AVS3 支持

### 解码滤镜
- [LAVFilters CAVS AVS2 AVS3](https://gitee.com/zhengtianbo/LAVFilters-GB-CAVS-AVS2-AVS3-decoder)

### 转码与流媒体处理

- [zhengtianbo/FFmpeg-avs2-avs3](https://gitee.com/zhengtianbo/FFmpeg-avs2-avs3): 添加了AVS2与AVS3支持的FFmpeg


## 频道与频率数据

- 各省市地面波频率表

## 开发资源

- [OpenAVS](https://sourceforge.net/projects/openavs/): AVS1-P2解码器的开源实现
- [xavs](https://xavs.sourceforge.net/): AVS1-P2/AVS1-P8编解码器的开源实现
- []: AVS2的开源实现
- []: AVS3的开源实现

- [avs2_avs3_test_video](https://gitee.com/zhengtianbo/avs2_avs3_test_video): 提供AVS2和AVS3编码的测试文件

- [让TSCutter.GUI支持解码AVS+(AVS1-P16)编码的TS文件](https://github.com/nilaoda/Blog/discussions/87)

## 社区论坛

- 中文寻星论坛

- 