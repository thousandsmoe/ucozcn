# Ucozcn
## 可能是最快的ucoz汉化脚本

---

作者主页：[http://thousandmoe.github.com/](http://thousandmoe.github.com/)  
项目地址：[http://thousandmoe.github.com/ucozcn](http://thousandmoe.github.com/ucozcn)  

---

### 利用规约 ###
* 你可以自由使用Ucozcn来汉化任何Ucoz站点，如果能够在站点上加上「使用Ucozcn汉化」并链接到Ucozcn项目地址，作者会很开心
* 你可以自由的将汉化方法转载，唯需保留Ucozcn项目地址
* 你可以修改Ucozcn的源码并进行二次配布，唯需保留Ucozcn项目地址
* 你可以进行二次配布，唯需保留Ucozcn项目地址

### 注意事项 ###
* 本脚本仅可用于Ucoz.com自助建站（包括ucoz.com/ucoz.net等系列）
* 本脚本无法完全汉化Ucoz，仅可进行部分汉化
* 若之前通过其它的方法汉化过，请自行保留备份
* 本脚本所作操作不可逆
* 作者不提供任何形式的技术支持
* 作者不对使用该脚本造成的任何影响负责

### 功能主治 ###
通过Ucoz自带的`Substitution of default phrases`功能对ucoz建设的站点进行初步汉化。内置一个这货翻译了一整个下午的语言包，请无视翻译错误和缺点。

### 使用方法 ###
1. 转到`http://**你的站点URL**/panel/?a=signs`，可以通过直接在浏览器中输入地址，也可以在ucoz后台戳：`Settings->Substitution of default phrases`。
2. 在浏览器地址栏中复制粘贴以下代码（请使用IE，火狐浏览器；已知Google内核浏览器需要自己手动输入开头的`javascript:`，百度浏览器暂时无法使用该脚本）  
`
javascript:var b=document.createElement('script');b.setAttribute('charset','UTF-8');b.setAttribute('src','http://raw.github.com/thousandmoe/ucozcn/master/ucozcn.js');document.head.appendChild(b);void(0);
`
3. 按下回车，等待弹出一个汉化完成的对话框，点击`save`按钮，即宣告初步汉化完成。
4. 如果需要，点击右上角的`Find phrases in templates`进行进一步的翻译工作。
