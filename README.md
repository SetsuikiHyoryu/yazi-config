# Yazi Config

## 配置目录

- Unix-like: `~/.config/yazi/`
- Windows: `%AppData%\yazi\config\` (`~\AppData\Roaming\`)

See: <https://yazi-rs.github.io/docs/configuration/overview>

## 管理插件

```bash
# 用法近似 NPM
ya pkg --help
```

- 新电脑中第一次安装 Yazi 时需要 `ya pkg install` 安装依赖。
  - See: <https://yazi-rs.github.io/docs/cli#pm>
- 插件默认安装在 `yazi/config/plugins` 下。
- 主题默认安装在 `yazi/config/flavors` 下。
- 除了 toml 文件以外，`init.lua` 也会参与配置插件。
