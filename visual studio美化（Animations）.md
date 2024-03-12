<!--
 * @Author: yuyancheng yuyancheng@meituan.com
 * @Date: 2024-03-12 10:07:47
 * @LastEditors: yuyancheng yuyancheng@meituan.com
 * @LastEditTime: 2024-03-12 10:38:36
 * @FilePath: /setting/visual studio美化（Animations）.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# visual studio美化（Animations）

## 鼠标设置

### 鼠标平滑

如果单独鼠标可以不用插件，直接通过设置进行修改。

[开启Cursor Smooth Caret Animation就可以。](https://www.163.com/dy/article/HOTJMSOE0552DTRT.html)

### 鼠标样式

setting中进行设置

```json
    "editor.cursorStyle": "line",
    "editor.cursorBlinking":"expand",
```

## 全面优化

使用插件[VSCode Animations](https://marketplace.visualstudio.com/items?itemName=BrandonKirbyson.vscode-animations#injection-extensions)

其中会需要其它的插件，目前有[Apc Customize UI++](https://github.com/drcika/apc-extension)以及[Custom CSS and JS](https://github.com/be5invis/vscode-custom-css)选择。如果不熟悉推荐直接用Apc Custromize UI++，安装后有默认设置。Custom可以熟练后再使用，自定义更多，注意两个插件只能安装一个。

其中mac用户要注意将软件放到Application（应用程序下）不然会有权限问题。如果上面插件有问题，大概率是权限没有给到，在页面里都有相应的权限设置。
