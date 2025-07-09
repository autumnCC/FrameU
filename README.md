# MarkFrame (印影)

A professional photo watermarking application that supports multiple beautiful templates and custom watermark effects.

## Features

### 🎨 Diverse Templates
- **Template 1**: Classic black border, simple and elegant
- **Template 2**: White border design, fresh and bright
- **Template 3**: Film-style border, retro and nostalgic
- **Template 4**: EXIF information display, professional photography
- **Template 5**: Custom text watermark, personal expression

### 📸 Smart Watermark System
- Automatically recognize photo EXIF information
- Support camera brand logo display
- Customizable text content and styles
- Smart layout adaptation for different sizes

### 🎯 User Experience
- Modern interface design
- Smooth animation effects
- Real-time preview functionality
- One-click save to photo album

## Technical Architecture

### Core Technology Stack
- **SwiftUI**: Modern UI framework
- **Combine**: Reactive programming
- **Core Graphics**: Image processing
- **Photos Framework**: Photo album access

### Project Structure
```
FrameU/
├── Models/
│   ├── TemplateModel.swift          # Template data model
│   └── WatermarkModel.swift         # Watermark processing core
├── Views/
│   ├── HomeView.swift               # Main interface
│   ├── PreviewView.swift            # Preview interface
│   ├── AboutView.swift              # About page
│   ├── ImagePicker.swift            # Image picker
│   ├── LogoSelectionView.swift      # Logo selection interface
│   └── Template5SettingsView.swift  # Template 5 settings interface
├── Extensions/
│   └── String+Localization.swift   # Localization extensions
├── Assets.xcassets/                 # Image resources
├── Localizable.strings              # Multi-language support
├── ContentView.swift                # Main interface
├── MarkFrameApp.swift               # App entry point
└── Info.plist                       # App configuration
```

## Development Environment

### System Requirements
- iOS 18.2+
- Xcode 16.2+
- Swift 5.0+

### Build Steps
1. Clone the project locally
```bash
git clone [project_url]
cd FrameU
```

2. Open the project with Xcode
```bash
open FrameU.xcodeproj
```

3. Select target device and run
- Choose simulator or real device
- Press `Cmd + R` to run the project

## Core Feature Implementation

### Watermark Generation Algorithm
- High-performance image processing based on Core Graphics
- Support for multiple blend modes and transparency control
- Adaptive text size and position layout

### Template System
- Extensible template architecture design
- Support for dynamic parameter configuration
- Automatic preview image generation

### Performance Optimization
- Asynchronous image processing execution
- Memory usage optimization
- Debounce mechanism to avoid frequent redraws

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact Us

Discover more tools and inspiration:
- **WeChat**: melixc
- **Xiaohongshu**: @星城影像狮

---

**MarkFrame** - Every photo has a story

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
