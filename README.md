# keyboard
小程序模拟键盘组件

### 模拟键盘操作

 #### 优点： 
 1. 推荐金额快捷选择
 2. 可自助选择充值
 

#### 遇到的问题：
> 组件看起来不难，但是要注意的小细节好多。

* 输入小数点后，不能在输入第二个小数点。
* 小数点后两位朝外，再输入无效。
* 推荐金额和自助充值切换时要相互重置。
* 

#### 为何要写此组件？

小程序原生的`<input type="digit" placeholder="带小数点的数字键盘"/>`不够灵活，不能自由的操纵数字面板！！用的不爽！！

下面是效果gif：

<image src="./keyboard.gif"></image>
