# 让你的  vscode 与众不同

### 先上效果图：

![](https://ws4.sinaimg.cn/large/006tNc79ly1g2bf9hzm24j314b0oodim.jpg)

### 涉及到的插件
* 配置主题：

  * 下载 [https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme), 使用![](https://cdn.nlark.com/lark/0/2018/png/7123/1544842247578-6a87b58d-ee19-43ec-b097-ea2918c85898.png#width=723)


* 配置背景图：

  * 插件： [https://marketplace.visualstudio.com/items?itemName=shalldie.background](https://marketplace.visualstudio.com/items?itemName=shalldie.background) 

  * 相关配置：

```
"background.style": {
    "content": "''",
    "pointer-events": "none",
    "position": "absolute",
    "z-index": "99999",
    "width": "100%",
    "height": "100%",
    "background-position": "center",
    "background-size": "cover",
    "background-repeat": "no-repeat",
    "opacity": 0.1 // 设置下透明度
  },
  "background.customImages": [
    "/Users/shitiao/Desktop/Juggernaunt-Dota-2-Live-Wallpaper-1.jpg" // 自定义的背景图
  ],
  "background.useDefault": false
```

* 配置字体: Inconsolata

  * [https://fonts.google.com/specimen/Inconsolata](https://fonts.google.com/specimen/Inconsolata)

  * 相关配置：

```
"editor.fontFamily": "Inconsolata",
```


* 设置舒服的字体大小、行高与字间距

```
"editor.letterSpacing": 0.5,
"editor.lineHeight": 20,
"editor.fontSize": 13,
```

到此，效果图配置完成了 。

### 附录：[提升效率的 vscode 插件](https://yuque.antfin-inc.com/allencelee.lzq/mark/yy5isk)

