# awesome-dtmb
Everything you need to know about DTMB(Digital Terrestrial Multimedia Broadcast)

## 标准与协议

- [DTMB 标准](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=41F48525779777A75F0898B87E9BD24E) - GB 20600-2006 《数字电视地面广播传输系统帧结构、信道编码和调制》
- [MPEG-TS 标准](https://www.iso.org/standard/91403.html) -  ISO/IEC 13818-1:2025

### 视频标准

#### AVS

[AVS 官方网站](https://www.avs.org.cn/index.php/index/list?catid=7) - 数字音视频编解码技术标准工作组 资料下载

- AVS (CAVS / AVS1-P2 / AVS JiZhun / 基准类)
    - 现行国家标准 GB/T 20090. 2—2013
    - [《信息技术 先进音视频编码 第2部分：视频》](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=AD0D3FA994651694F95F9E1364B88193)

- AVS+ (AVS1-P16 / AVS Guangdian / 广播类)
    - 现行国家标准 GB/T 20090.16-2016
    - [《信息技术 先进音视频编码 第16部分：广播电视视频》](https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=1D4AC2D4256C8DE7E0AA286CA7649300)

- AVS2 - 用于传输 4K 超高清节目
    - 现行国家标准 GB/T 33475.2-2024
    - [《信息技术 高效多媒体编码 第2部分：视频》](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=C23145CA7C18AC718FDE2589AC626D6E)

- AVS3 - 用于传输 8K 超高清节目
    - 现行行业标准 GY/T 368-2023
    - [《先进高效视频编码》](https://www.nrta.gov.cn/art/2023/8/30/art_3715_65407.html)

#### HDR

- HDR Vivid
    - 现行行业标准 GY/T 358—2022
    - 《高动态范围电视系统显示适配元数据技术要求》

#### 其余标准
- MPEG-2 (H.262)
- AVC (H.264)
- HEVC (H.265)
- VVC (H.266)

### 音频标准

- MPEG-1

- DRA
    - 现行国家标准 GB/T 22726-2008
    - [《多声道数字音频编解码技术规范》](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=824F2100959498D71AD5345FD1018364)

- Audio Vivid - 菁彩三维声
    - [ITU-R BS.2493-1 Annex 4](https://www.itu.int/dms_pub/itu-r/opb/rep/R-REP-BS.2493-1-2024-PDF-E.pdf)

## 硬件接收设备

### USB 接收棒

- LeTV
    - Drivers
        - Linux Driver
    - Clients

- CH1 第一波道

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

- [AltDVB](https://www.altx.ro/projects/altdvb/): 罗马尼亚开发者开发的DVB兼容电视接收软件
- [hysAnalyser](https://github.com/zymill/hysAnalyser/) - 专业 MPEG-TS 数据分析和转换工具，支持 AVS1-P2, AVS1-P16, AVS2, AVS3 视频的解码。

### 播放器
- [VLC 2.2.6 with AVS/AVS+ and DRA support](https://gitcode.com/open-source-toolkit/b2eba): 社区改进的 VLC 播放器，支持 AVS1-P16 视频解码和 DRA 音频解码
- [VlcAvsDra](https://github.com/zuifengjianke/VlcAvsDra): 安卓版本的 VLC 播放器，支持 AVS1-P16 视频解码和 DRA 音频解码
- [VLC 3.0.11.1 with AVS3-AVS2-CAVS](https://gitee.com/zhengtianbo/VLC3-AVS3AVS2CAVS): zhengtianbo开发的VLC播放器，支持AVS1-P2, AVS2, AVS3，提供基于VLC和ffmpeg的两种修改方案。
- [MPC-HC with AVS3-AVS2-CAVS](https://gitee.com/zhengtianbo/cavs-avs2-avs3_decoder_added_to_mpc_hc): zhengtianbo修改的MPC-HC，添加AVS, AVS2, AVS3 支持

### 解码滤镜
- [LAVFilters CAVS AVS2 AVS3](https://gitee.com/zhengtianbo/LAVFilters-GB-CAVS-AVS2-AVS3-decoder)

### 转码与流媒体处理

- [zhengtianbo/FFmpeg-avs2-avs3](https://gitee.com/zhengtianbo/FFmpeg-avs2-avs3): 添加了AVS2与AVS3支持的FFmpeg


## 频道与频率数据

- [中国地面波数字电视接收参数](http://dtmb.saoing.com/) - 由爱好者维护的各省市自治区直辖市（包括港澳台）的地面波数字电视接收频率

## 开发资源

- [OpenAVS](https://sourceforge.net/projects/openavs/) - AVS1-P2解码器的开源实现
- [xavs](https://xavs.sourceforge.net/) - AVS1-P2/AVS1-P8编解码器的开源实现
- [xavs2](https://github.com/pkuvcl/xavs2) - 北京大学 AVS2 编码器的开源实现
- [davs2](https://github.com/pkuvcl/davs2) - 北京大学 AVS2 解码器的开源实现
- [uavs3e](https://github.com/uavs3/uavs3e) - AVS3 encoder which supports AVS3-P2 baseline profile.
- [uavs3d](https://github.com/uavs3/uavs3d) - AVS3 decoder which supports AVS3-P2 baseline profile.
- [DRA-Audio-System](https://github.com/tianyigeng/DRA-Audio-System) - DRA 编解码器的开源实现

> 截至目前（2026年2月），没有以开源协议发布的 AVS1-P16 实现。
>
> - https://lists.ffmpeg.org/archives/list/ffmpeg-devel@ffmpeg.org/thread/PR76B6WXNRSDUFC7NWXXBC5SNXLUHNHT/#LTGO6KIURYEDLMVIVBCD6QPWPMFOUN4E
> - https://github.com/intel/libva/pull/738/changes
> - Moore Threads, have finished Chinese AVS&AVS2 hwaccel decoding under FFMpeg-VAAPI framework. All their public products, MTT S10/MTT S50/MTT S80/MTT S2000/... support AVS&AVS+ decoding at max 2K and support AVS2 Main&Main10 decoding at max 8K.

- [avs2_avs3_test_video](https://gitee.com/zhengtianbo/avs2_avs3_test_video): 提供AVS2和AVS3编码的测试文件

- [让TSCutter.GUI支持解码AVS+(AVS1-P16)编码的TS文件](https://github.com/nilaoda/Blog/discussions/87)

- [AVS与AVS+的对比](https://blog.csdn.net/weixin_43360707/article/details/131128946)

## 社区论坛

- 中文寻星论坛

- 
