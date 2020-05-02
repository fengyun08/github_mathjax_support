## 让 github 在 chrome 浏览器中正确显示数学公式

- 首先在这个网址下载 chrome 的 mathjax 插件源码

  https://github.com/orsharir/github-mathjax/

- 得到 github-mathjax-master.zip 文件后，原地解压得到源码文件，目录名就是 github-mathjax-master

- 启动 chrome 浏览器。鼠标放在浏览器右上方的竖三点按钮上，会显示“自定义及控制 Google Chrome”提示

- 点击竖三点按钮，弹出菜单中选“设置”，出现“设置”页面

- 打开页面的左侧菜单的底部，点击倒数第2项“扩展程序”菜单，出现“扩展程序”页面

- 在新页面中点“打包扩展程序”，弹出的面板中点击“扩展程序根目录”下直接输入 mathjax 源码文件夹所在路径（path\to\github-mathjax-master）。

- 或者点击右边的“浏览”按钮，会弹出一个窗口。然后进到刚刚解开的 mathjax 源码文件夹（github-mathjax-master），点击“选择文件夹”按钮

- 回到“打包扩展程序”面板，点“打包扩展程序”

- 在“扩展程序页面”点击“加载已解压的扩展程序”，弹出窗口中选择前面的源码文件夹即可。

- 关闭 chrome ，并重启，打开github项目页面。

现在可以看到，github页面的公式能够正确显示出来了。效果也勉强可以了。
