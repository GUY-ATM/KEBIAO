# 福建财经政法大学课表

一款专为福建财经政法大学学生打造的精美课表应用，支持课程表展示、考试安排、主题定制等功能。
<img width="270" height="600" alt="微信图片_20260627162812_353_13" src="https://github.com/user-attachments/assets/e639f789-339c-4e42-9892-64c807a29096" />
<img width="270" height="600" alt="微信图片_20260627162001_350_13" src="https://github.com/user-attachments/assets/65e7e047-1994-4792-bde6-d1b4849d9ed7" />
<img width="270" height="600" alt="微信图片_20260627163410_354_13" src="https://github.com/user-attachments/assets/2e7c7bc0-a8b3-4f93-bf2f-1d4a34f470a1" />

## ✨ 功能特性

### 📅 课程管理
- **双视图切换**：支持列表视图和表格视图两种展示方式
- **日期滑轨**：流畅的横向滑动日期选择器，支持20周课程展示
- **周次计算**：自动根据开学日期计算当前周次
- **课程详情**：点击课程卡片查看详细信息

### 🎨 个性化定制
- **主题配色**：多种预设配色方案，支持自定义5色配色
- **壁纸设置**：支持图片和视频背景设置
- **灵动岛交互**：顶部灵动岛设计，支持快捷上传课程数据

### 📝 考试安排
- **考试信息展示**：清晰展示考试科目、时间、地点
- **数据导入**：支持从教务系统导入考试数据

### 🔐 数据安全
- **本地存储**：课程数据保存在本地，保护隐私
- **加密传输**：支持数据加密，确保数据安全

## 🛠️ 技术栈

- **框架**: HBuilderX (H5+ App)
- **样式**: Tailwind CSS 3
- **图标**: FontAwesome 6
- **加密**: CryptoJS, JSEncrypt
- **图表**: Chart.js

## 📱 支持平台

- Android 5.0+
- H5 移动端浏览器

## 🚀 快速开始

### 开发环境

1. 下载并安装 [HBuilderX](https://www.dcloud.io/hbuilderx.html)
2. 克隆项目到本地
3. 打开 HBuilderX，导入项目

### 运行项目

#### H5 预览
1. 在 HBuilderX 中打开项目
2. 点击工具栏的「运行」->「运行到浏览器」->「选择浏览器」

#### Android 真机调试
1. 连接 Android 设备
2. 点击工具栏的「运行」->「运行到手机或模拟器」->「选择设备」

#### 打包发布

##### Android 打包
1. 点击工具栏的「发行」->「原生App-云打包」
2. 配置应用信息和签名
3. 等待打包完成

##### iOS 打包
1. 配置 iOS 开发者证书
2. 点击工具栏的「发行」->「原生App-云打包」
3. 选择 iOS 平台

## 📁 项目结构

```
福建江夏课表/
├── css/                    # 样式文件
│   └── all.main.css.js     # 主样式文件
├── img/                    # 图片资源
│   ├── view/               # 背景图片
│   ├── 1.png, 2.png, 3.png # 应用图片
├── libs/                   # 第三方库
│   ├── css/                # FontAwesome CSS
│   ├── webfonts/           # FontAwesome 字体文件
│   ├── tailwindcss.js      # Tailwind CSS
│   ├── crypto-js.min.js    # 加密库
│   ├── jsencrypt.min.js    # RSA加密
│   ├── chart.umd.min.js    # 图表库
│   └── forge.min.js        # 加密工具
├── static/                 # 静态资源
│   ├── fwxy.html           # 服务协议
│   ├── fwxy.txt            # 服务协议文本
│   ├── xszc.txt            # 学生手册
│   └── yszc.html           # 用户协议
├── unpackage/              # 打包产物
│   ├── release/            # 发布版本
│   ├── cache/              # 缓存文件
│   └── res/                # 图标资源
├── colors.html             # 配色选择页面
├── encrypt.js              # 加密工具函数
├── kebiao.html             # 主课表页面（图片背景版）
├── kebiao1.html            # 主课表页面（视频背景版）
├── manifest.json           # 应用配置文件
├── swipe-control.css       # 滑动控制样式
├── wallpaper.html          # 壁纸设置页面
└── .gitignore              # Git忽略配置
```

## 🎯 使用说明

### 导入课程数据
1. 点击顶部导航的「导入」按钮
2. 选择从教务系统导入或上传JSON文件
3. 等待数据加载完成

### 切换视图
- 点击「表格」按钮切换到表格视图
- 点击「调节」按钮调整显示参数

### 自定义配色
1. 点击「主题」按钮进入配色页面
2. 选择预设配色或自定义5种颜色
3. 点击保存应用新配色

### 设置壁纸
1. 点击「主题」按钮进入配色页面
2. 点击「壁纸」按钮进入壁纸设置
3. 选择图片或视频作为背景

## 📄 许可证

MIT License

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📧 联系方式

如有问题或建议，欢迎反馈。

---

**不拒本心 是谓自在** ✨
