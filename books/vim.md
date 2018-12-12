# VIM 速查表

## 常规操作

  - 重复上一次 EX 命令:
    `{n}@@`

## 窗口（window）操作

  - 将一个 window 变为 tab:  
    `:tabedit %` or `<C-w> T`
    
  - 同右边最近的 window 交换位置:
    `<C-w> x`
    
  - 旋转所有 window 的位置和布局：
    `<C-w> r` or `<C-w> R`

    
## 调整窗口（window）尺寸

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
