# sy2‑BasicsCodelab
课程实验二：开发环境软件安装与配置

本仓库用于记录 Android Studio、Python+Jupyter Notebook、VS Code 的完整安装配置过程，以 Markdown 格式整理，完成课程实验要求。

## 实验目的
1. 安装 Android Studio 4.1 及以上版本，适配 LiteRT 开发，完成基础 Android 应用编译运行
2. 搭建 Python 环境，安装 Jupyter Notebook，为后续机器学习模型构建做准备
3. 安装 Visual Studio Code，熟悉代码编辑器基础使用
4. 将安装配置过程整理为 Markdown 文档，上传至 GitHub

## 一、Android Studio 安装配置
### 1. 版本选择
选用 Android Studio Panda 3（4.1+），更好支持 LiteRT 框架。

### 2. 安装与加速配置
- 从官网下载安装包，安装时勾选 Android SDK、模拟器、构建工具
- 配置阿里云 Maven 镜像，解决 Gradle 下载缓慢问题
- 等待 SDK、Gradle 工具包、依赖库自动下载完成

### 3. 验证运行
- 新建空白 Android 项目（Empty Activity）
- 首次编译自动下载 Gradle 相关依赖
- 启动模拟器或连接真机，成功运行默认应用，环境验证完成


![截图](https://github.com/dyw525/sy1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-05-18%20002802.png?raw=true)
![截图](https://github.com/dyw525/sy1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-05-18%20002743.png?raw=true)
![截图](https://github.com/dyw525/sy1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-05-18%20002904.png?raw=true)
