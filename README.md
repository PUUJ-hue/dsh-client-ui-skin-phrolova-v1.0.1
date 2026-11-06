# dsh-client-ui-skin-phrolova-v1.0.1

弗洛洛主题皮肤 v1.0.1：绯红演奏厅配色、玫瑰与音符装饰、四表情 Q 版角色 —— DeepSeek Harness 界面皮肤

> DeepSeek Harness（dsh）第三方插件。本仓库提供可直接安装的发布包。

## 下载

- [`dsh-client-ui-skin-phrolova-v1.0.1.zip`](./dsh-client-ui-skin-phrolova-v1.0.1.zip) —— 完整发布包（31.8 MB）

## 安装

1. 解压 `dsh-client-ui-skin-phrolova-v1.0.1.zip`，得到目录 `dsh-client-ui-skin-flollo`
2. 把 `dsh-client-ui-skin-flollo` 整个目录放到：

   ```
   %USERPROFILE%\.dsh\external\
   ```

3. 在 dsh 的 profile 配置里启用（`%USERPROFILE%\.dsh\profiles\desktop\package.json` 的 `dsh.profile.bundles` 加入 `@dsh-external/dsh-client-ui-skin-flollo`），
   或使用 dsh 的插件管理面板安装。
4. 重启 DeepSeek Harness。

> 提示：皮肤类插件同一时间只能启用一个，同时启用多个会导致启动卡在 Loading。

## 兼容性

| 项目 | 值 |
| --- | --- |
| 插件版本 | 1.0.1 |
| 声明的宿主版本范围 | `0.1.0-rc.6 - 0.2.1-rc.5` |
| 宿主平台 | web |
| 许可 | CC-BY-NC-SA-4.0 |

超出声明范围运行不保证稳定，可能出现加载失败或界面异常。

## 主要文件

| 文件 | 大小 |
| --- | --- |
| `assets/splash.mp4` | 28417.9 KB |
| `lib/client.js` | 2789.1 KB |
| `preview/dark.png` | 1270.0 KB |
| `preview/light.png` | 856.4 KB |
| `lib/index.js` | 12.6 KB |
| `LICENSE` | 7.4 KB |

## 说明

本仓库仅托管发布包与说明文档，源码与问题反馈请在仓库 Issues 中提出。
