# Javascript
变量，声明 var i=1；
显示   alert（i）；
通过JavaScript来控制网页行为：DOM(Document Object Model)-文档对象模型，它能使HTML和JavaScript紧密的结合在一起，每个标签可以看成一个对象组成了这个模型，每一个HTML元素都可以被定位。我们要根据元素的id（也就是编号），这个id是唯一的，不可重复设置，像身份证号一样
    HTM中
    <div>
    <P id="p1">这是段落1。</P> 
     <P id="p2">这是段落2。</P> 
    </div> 
Javascript
   var p1=document.GetElementById("p1");
   var p2=document.GetElementById("p1");
 改变元素：我们可以用p1.innerHTML表示p1的内容（这是段落1）；想改变HTML中的元素可以使用：
    var p1=document.getElementById('p1);
    p1.innerHTML='Hello world';
 
 函数
 首先要定义函数：function name(){ }      #name是你要给函数起的名字，在{ }中写上功能代码
一切就绪后，我们调用这个函数：name();
函数可以带参数；
当一个元素上的特定事件发生时，一个函数将会被调用;语法是这样子的:element.onevent=function;
HTML
<button id='b1'>点我</button> 
JavaScript
var b1=document.GetElemmentById('b1')
b1.oneclick=bclick
function bclick(){
    alert(“我被点击了”);
}

还有很多事件
像：onmouseover（鼠标移动到元素）、onmouseup（鼠标按键被松开），你可以用onmouseover代替onclick，是当鼠标移到button上时触发
通过value属性来获取输入框的值


怎么在html文件中加入JavaScript代码:我们是把<script></script>放在body标签的末尾位置;说一个最重要的：代码中的所有标点符号都要用英文的！！
   
