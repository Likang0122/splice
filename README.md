# splice
重构splice功能
使其能用作在字符串里边某个位置添加字符串
如：
splice(num, 0, addText);

demo中样句添加到html中显示为：这是我的一句话

当点击改变按钮 
触发 点击函数   
pub = pub.splice(3,0,"demo")

所以会变成：这是我demo的一句话；


当然，如果一直点击会一直添加，这是我demodemodemodemodemodemodemo的一句话


看各自的使用情况，这里只是举例说明
