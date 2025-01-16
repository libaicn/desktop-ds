deepseek最近发布了app,但是没有桌面端,我就帮deepseek做了一个桌面端,哈哈哈
仅仅是吧网页嵌入应用


## 安装说明


### 从源码构建

构建产物位置：

- Windows: `src-tauri/target/release/bundle/msi/`
- macOS: `src-tauri/target/release/bundle/dmg/`
- Linux: `src-tauri/target/release/bundle/appimage/`

### 预编译版本

从 [Releases](../../releases) 页面下载对应系统的安装包：

#### Windows

- 下载并运行 `.msi` 安装包

#### macOS

- 下载 `.dmg` 文件
- 将应用拖入 Applications 文件夹

#### Linux

- 下载 `.AppImage` 文件
- 添加执行权限：`chmod +x *.AppImage`
- 运行应用：`./DeepSeek.AppImage`

## 推荐的开发工具

- [VS Code](https://code.visualstudio.com/)
- [Tauri VS Code 扩展](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode)
- [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## 常见问题

1. **构建失败**

   - 确保已安装所有系统依赖
   - 更新 Rust 到最新版本：`rustup update`

2. **Windows 运行报错**

   - 检查是否安装了 WebView2 运行时
   - 确保 Visual Studio 构建工具安装正确

3. **macOS 权限问题**
   - 确保已安装 Xcode Command Line Tools
   - 检查应用权限设置

## 贡献指南

欢迎提交 Pull Request 或提出 Issue。

## 许可证

[MIT License](LICENSE)
