
<div align="center">

# 📺 iptv-sources
https://github.com/best-fan/iptv-sources/tree/main

## 📁 项目结构
```bash
iptv-sources/
├── 📋 cn_all.m3u8                 # 完整播放列表（46+个频道）
├── 📋 cn_all_status.m3u8          # 完整播放列表（46+个频道 含分辨率、流畅度）
├── 📡 cn_cctv.m3u8                # 央视频道列表
├── 📡 cn_cctv_status.m3u8         # 央视频道列表（含分辨率、流畅度）
├── 🏢 cn_province.m3u8            # 卫视频道列表  
├── 🏢 cn_province_status.m3u8     # 卫视频道列表（含分辨率、流畅度）  
├── 💎 cn_pay.m3u8                 # 付费频道列表
├── 💎 cn_pay_status.m3u8          # 付费频道列表（含分辨率、流畅度）
└── 📖 README.md                   # 项目说明文档
```
</div>

## 📺 支持频道类型

### 🇨🇳 央视频道
- **包含**:📡 CCTV-1 到 CCTV-17，CCTV-4K 等
- **文件**: `cn_cctv.m3u8`

### 🏢 卫视频道  
- **包含**:🏙️ 北京卫视、湖南卫视、东方卫视等 37 个省级卫视
- **文件**: `cn_province.m3u8`

### 💎 付费频道
- **包含**:💰 凤凰中文、金鹰纪实、茶友频道等 45 个付费频道
- **文件**: `cn_pay.m3u8`

### 📋 完整列表
- **包含**: 📺所有 46+ 个频道
- **文件**: `cn_all.m3u8`



## 📡 播放源地址

### 🎯 源播放文件

以下是项目生成的播放列表文件，可以直接在支持 M3U8 格式的播放器中使用：

| 文件名称 | 频道数量 | 描述 | 源链接 | 代理链接 |
|----------|----------|------|----------|----------|
| `cn_all.m3u8` | 46+ | 完整播放列表（包含所有频道） | [下载](https://raw.githubusercontent.com/best-fan/iptv-sources/master/cn_all.m3u8) |[下载](https://raw.staticdn.net/best-fan/iptv-sources/master/cn_all.m3u8) |
| `cn_all_status.m3u8` | 46+ | 完整播放列表（含分辨率、流畅度） | [下载](https://raw.githubusercontent.com/best-fan/iptv-sources/master/cn_all_status.m3u8) |[下载](https://raw.staticdn.net/best-fan/iptv-sources/master/cn_all_status.m3u8) |
| `cn_cctv.m3u8` | 10+ | 央视频道列表 | [下载](https://raw.githubusercontent.com/best-fan/iptv-sources/master/cn_cctv.m3u8) |[下载](https://raw.staticdn.net/best-fan/iptv-sources/master/cn_cctv.m3u8) |
| `cn_cctv_status.m3u8` | 10+ | 央视频道列表（含分辨率、流畅度） | [下载](https://raw.githubusercontent.com/best-fan/iptv-sources/master/cn_cctv_status.m3u8) |[下载](https://raw.staticdn.net/best-fan/iptv-sources/master/cn_cctv_status.m3u8) |
| `cn_province.m3u8` | 37 | 卫视频道列表 | [下载](https://raw.githubusercontent.com/best-fan/iptv-sources/master/cn_province.m3u8) | [下载](https://raw.staticdn.net/best-fan/iptv-sources/master/cn_province.m3u8) |
| `cn_province_status.m3u8` | 37 | 卫视频道列表（含分辨率、流畅度） | [下载](https://raw.githubusercontent.com/best-fan/iptv-sources/master/cn_province_status.m3u8) | [下载](https://raw.staticdn.net/best-fan/iptv-sources/master/cn_province_status.m3u8) |
| `cn_pay.m3u8` | 45 | 付费频道列表 | [下载](https://raw.githubusercontent.com/best-fan/iptv-sources/master/cn_pay.m3u8) |[下载](https://raw.staticdn.net/best-fan/iptv-sources/master/cn_pay.m3u8) |
| `cn_pay_status.m3u8` | 45 | 付费频道列表（含分辨率、流畅度） | [下载](https://raw.githubusercontent.com/best-fan/iptv-sources/master/cn_pay_status.m3u8) |[下载](https://raw.staticdn.net/best-fan/iptv-sources/master/cn_pay_status.m3u8) |




### 📱 使用方式

1. **直接下载使用**：
   - 点击上方链接下载对应的 M3U8 文件
   - 在支持 M3U8 格式的播放器中打开文件

2. **在线播放**：
   - 使用支持网络播放的播放器
   - 输入文件原始链接地址


## 🙏 数据源致谢

本项目的数据源部分数据于以下优秀的开源项目，感谢这些项目的贡献者：

- **mzky/checklist** - https://github.com/mzky/checklist
- **ssili126/tv** - https://github.com/ssili126/tv
- **hujingguang/ChinaIPTV** - https://github.com/hujingguang/ChinaIPTV
- **kaige-cai/live** - https://github.com/kaige-cai/live
- **BurningC4/Chinese-IPTV** - https://github.com/BurningC4/Chinese-IPTV
- **iptv-org/iptv** - https://iptv-org.github.io
- **ibert.me** - https://m3u.ibert.me

## ⚠️ 注意事项

<div align="center">

| 注意事项 | 图标 | 说明 |
|----------|------|------|
| **遵守条款** | 📜 | 请遵守相关网站的使用条款 |
| **定期更新** | 🔄 | 直播源可能会随时失效，需要定期更新 |
| **学习用途** | 🎓 | 仅供学习和研究使用 |
| **法律责任** | ⚖️ | 用户需自行承担使用责任 |

</div>
