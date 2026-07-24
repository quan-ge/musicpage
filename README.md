# MusicList

一个简洁优雅的个人歌单展示页面，轻松部署个人歌单

## ✨ 特性

- 🎵 **歌单展示** - 清晰展示歌曲名称和艺术家信息
- 🔗 **多平台链接** - 支持为每首歌配置多个音乐平台链接
- 🌓 **暗色/亮色主题切换** - 自动跟随系统主题，支持手动切换
- 📱 **响应式设计** - 完美适配桌面端和移动端
- 📦 **数据驱动** - 歌单和图标数据通过 JSON 文件管理，方便修改
- 🎵 **轻松部署部署** - 无需服务器，GithubPages一键部署

## Demo

[https://music.quange.qzz.io/](https://music.quange.qzz.io/)

## 快速开始

1. Fork本项目

2. 修改data目录下的musiclist.json文件，替换成你的歌单

3. 修改data目录下的config.json文件，更改站点名称和图标以及你的头像

3. 进入Settings -> Pages

4. 开启Pages服务

## Tips

1. 添加更多网站Logo请修改 '/data/icons.json'

   建议使用矢量图标，支持代码或svg文件

2. 歌单储存在 'musiclist.json' 中

   共有三项：name,artist,links

   每一项都不是必填的