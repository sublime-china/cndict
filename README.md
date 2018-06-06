# CNDict

> forked from [https://github.com/divinites/cndict](https://github.com/divinites/cndict)  
> 感谢[@divinites](https://github.com/divinites)  
> 在此基础上, 做了优化和新的功能.  


## 快捷键

- Ctrl+Alt+C: [腾讯文本翻译](https://ai.qq.com/product/nlptrans.shtml#text)  
- Ctrl+Alt+Y: 有道词典 Youdao  
- Ctrl+Alt+J: 金山词典 Jinshan  


## 设置

```
{
    // There are three options here:
    // "popup" is the default, the dictionary will show a pop-up when queried.
    // "phantom" will show the query result as a phantom
    // "pannel" will show the query result in an output pannel
    "format": "popup"
}
```

- "popup":
    弹出框形式展示.  
    <kbd>ESC</kbd> 或 <kbd> Crtl+Shift+D </kbd> 取消.  

- "phantom":
    在当前单词下一行, 以"幽灵方块"的形式展示.  
    <kbd> Crtl+Shift+D </kbd> 清除所有展示.  

- "pannel":
    以传统的调度框展示在Sublime底部.  
