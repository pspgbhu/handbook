# VIM 速查表

## 常规操作

  - 重复上一次 EX 命令:
    `{n}@@`

## 窗口操作

  - 将一个 window 变为 tab:  
    `:tabedit %` or `<C-w> T`
    
## 调整窗口尺寸

  - 将当前窗口的高度减少n行：
    `:resize -{n}` or `<C-w> {n}-`
    
  - 将当前窗口的高度增加n行：
    `:resize +{n}` or `<C-w> {n}+`
    
  - 将当前窗口的宽度减少：
    `:vertical resize -{n}` or `<C-w> {n}<`
    
  - 将当前窗口的宽度增加：
    `:vertical resize -{n}` or `<C-w> {n}>`

  - 让所有窗口调整至相同尺寸（平均划分）
    `<C-w> =`
  
  - 将当前窗口的宽度调到最大
    `<C-w> |`
