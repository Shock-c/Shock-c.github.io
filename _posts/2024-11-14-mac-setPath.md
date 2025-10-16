---
title: Mac brew
date: 2024-11-14 21:53:00 +0800
categories: [技术, Mac]
tags: [记录,Mac,环境配置]
---

# brew 
## 安装

``` ruby
## 国内源
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
## 官方源（不推荐 可能被墙了）
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
## 卸载

```ruby
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/HomebrewUninstall.sh)"
```

## 常用命令

- 安装软件：brew install xxx
- 卸载软件：brew uninstall xxx
- 搜索软件：brew search xxx
- 更新软件：brew upgrade xxx
- 查看列表：brew list
- 更新brew：brew update
- 清理所有包的旧版本：brew cleanup
- 清理指定包的旧版本：brew cleanup $FORMULA
- 查看可清理的旧版本包，不执行实际操作：brew cleanup -n
- 查看软件安装地址：brew info name
- 查看建议，例如升级等：brew doctor
