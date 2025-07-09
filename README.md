# 印影 (MarkFrame)

一款专业的照片水印添加应用，支持多种精美模板和自定义水印效果。

## 功能特色

### 🎨 多样化模板
- **模板1**: 经典黑色边框，简约优雅
- **模板2**: 白色边框设计，清新明亮
- **模板3**: 胶片风格边框，复古怀旧
- **模板4**: EXIF信息展示，专业摄影
- **模板5**: 自定义文字水印，个性表达

### 📸 智能水印系统
- 自动识别照片EXIF信息
- 支持相机品牌Logo显示
- 可自定义文字内容和样式
- 智能布局适配不同尺寸

### 🎯 用户体验
- 现代化界面设计
- 流畅的动画效果
- 实时预览功能
- 一键保存到相册

## 技术架构

### 核心技术栈
- **SwiftUI**: 现代化UI框架
- **Combine**: 响应式编程
- **Core Graphics**: 图像处理
- **Photos Framework**: 相册访问

### 项目结构
```
FrameU/
├── Models/
│   ├── TemplateModel.swift          # 模板数据模型
│   └── WatermarkModel.swift         # 水印处理核心
├── Views/
│   ├── HomeView.swift               # 主界面
│   ├── PreviewView.swift            # 预览界面
│   ├── AboutView.swift              # 关于页面
│   ├── ImagePicker.swift            # 图片选择器
│   ├── LogoSelectionView.swift      # Logo选择界面
│   └── Template5SettingsView.swift  # 模板5设置界面
├── Extensions/
│   └── String+Localization.swift   # 本地化扩展
├── Assets.xcassets/                 # 图片资源
├── Localizable.strings              # 多语言支持
├── ContentView.swift                # 主界面
├── MarkFrameApp.swift               # 应用入口
└── Info.plist                       # 应用配置
```

## 开发环境

### 系统要求
- iOS 18.2+
- Xcode 16.2+
- Swift 5.0+

### 构建步骤
1. 克隆项目到本地
```bash
git clone [项目地址]
cd FrameU
```

2. 使用Xcode打开项目
```bash
open FrameU.xcodeproj
```

3. 选择目标设备并运行
- 选择模拟器或真机
- 按 `Cmd + R` 运行项目

## 核心功能实现

### 水印生成算法
- 基于Core Graphics的高性能图像处理
- 支持多种混合模式和透明度控制
- 自适应文字大小和位置布局

### 模板系统
- 可扩展的模板架构设计
- 支持动态参数配置
- 预览图自动生成

### 性能优化
- 图像处理异步执行
- 内存使用优化
- 防抖机制避免频繁重绘

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 联系我们

发现更多工具与灵感：
- **微信**: melixc
- **小红书**: @星城影像狮

---

**印影** - 让每一张照片都有故事
