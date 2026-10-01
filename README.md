# 步天 (Butian) 官网、技术支持与隐私政策

本项目是「步天」App（`com.funvalvar.xuan`）的 GitHub Pages 官方站点与文档仓库。

- **官方网站 / 技术支持：** [https://butian.funvalvar.com](https://butian.funvalvar.com)
- **隐私政策 (Privacy Policy)：** [https://butian.funvalvar.com/privacy.html](https://butian.funvalvar.com/privacy.html)
- **标准使用条款 (EULA)：** [Apple Standard EULA](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)
- **联系邮箱：** funvalvar@proton.me

## 核心产品亮点

1. **精准时间解释引擎 (`chart_time_lib`)**：
   - `daylightSaving`：精准识别中国 1986–1991 及全球各历史时期夏令时并支持确认与切换；
   - `overlap`：解决夏令时回拨当夜同一钟点重复出现的歧义，精准选定前后时辰；
   - `daylightSavingGap`：智能检测夏令时快拨导致的跳变不存在时间点并进行合规平移修正；
   - `historicalOffset`：覆盖民国五大时区及新中国早期地方计时标准历史变迁。
2. **多维灵活的经纬度与真太阳时体系**：
   - 地名模糊搜索输入（结合 Apple 原生地理编码服务，毫秒级解析经纬度）；
   - 设备高精度即时定位（GPS，专为即时起局设计）；
   - 全球多级行政区划离线目录（完全无需网络连接）；
   - 经纬度分秒微调与真太阳时（时差方程 + 经度时差）实时精准校准。
3. **优雅的界面设计，丝滑的交互体验**：
   - 东方极简墨盘 `#0B0D0E` 美学，深浅色模式温润纯净，无广告零打扰；
   - 针对 ProMotion 120Hz 高刷新率深度调优，多层级时间轴平滑滑动与九宫切换跟手顺畅；
   - 独创盘面与便签同屏协同展示，支持随盘自动定位阅读位置与离线语音秒级批录。
4. **深度适配 iPhone · iPad · macOS 多端生态**：
   - iPhone 单手优化、安全区适配与细腻触感；
   - iPadOS 支持 Split View 分屏与多列宽屏并列；
   - macOS 宽屏桌面级沉浸体验，大屏多列展开一览无余，无需频繁翻页；
   - 全面支持 Apple 通用购买（Universal Purchase）与 iCloud 私有库跨设备即时漫游。

## 目录结构

```text
.
├── .gitignore         # Git 忽略配置
├── .nojekyll          # 禁用 Jekyll 编译（防止文件被过滤）
├── CNAME              # 自定义域名配置 (butian.funvalvar.com)
├── favicon.png        # 网站图标
├── icon.png           # App 高清墨盘图标
├── index.html         # 官网主页兼技术支持 (Support) 页面
├── privacy.html       # 符合 Apple 5.1.1 规范的中英双语隐私政策页面
└── README.md          # 站点说明文档
```
