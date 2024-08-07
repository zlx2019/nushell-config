## 安装 oh-my-posh
- winget
```bash
winget install oh-my-posh
```

- scoop
```bash
scoop install oh-my-posh
```

## 配置 oh-my-posh 主题
- 生成使用的主题配置
```bash
oh-my-posh.exe init nu --config .\dracula.omp.json --print | save ./posh.nu
```
json文件为主题配置。

- 配置到 nushell
在 `config.nu` 文件中追加：
```nu
source ./posh.nu
```