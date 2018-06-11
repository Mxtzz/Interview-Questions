# Interview-Questions

#### [HTML](#html)
#### [CSS](#css)
#### [JavaScript](#js)
#### [emmm...](#emmm)

## <span id="html">HTML</span>

##### 1. HTML全称
>Hyper Text Markup Language   
超文本标记语言    
还有一个XHTML，可扩展超文本标记语言。

##### 2. 有几种Doctype？作用？
>DOCTYPE：Document Type 文档类型    
用来指定页面所使用的XHTML或HTML的版本。   
三种DTD（文档类型定义）声明：过渡的（Transition）、严格的（Strict）、框架的（Frameset）。   

##### 3. 

<hr>

## <span id="css">CSS</span>

##### 1. 描述一下CSS盒模型？    
>所有HTML元素可以看做盒子，box model。  
css盒模型封装周围的HTML元素，包括：边距、边框、填充和实际内容。     
`margin`-外边距-    
`border`-边框-      
`padding`-内边距-       
`content`-内容-     

>*标准模式&怪异模式*    
标准模式：`box-sizing:content-box`     
盒子总宽高度=内容区宽高度+padding+border+margin     
怪异模式：`box-sizing:border-box`       
盒子总宽高度=内容区+margin

##### 2. display属性    
>none：此元素不会被显示；   
block：显示为块级元素，前后有换行符；   
inline：内联元素，前后没有换行符，*默认*；    
inline-block：行内块元素；    
inherit：从父元素继承display值；    
list-item：作为列表显示；   
run-in：根据上下文作为块级元素或内联元素显示；    
table：块级表格，类似<table>，前后有换行符；    
inline-table：内联表格，前后没换行符；    

##### 3. 几种布局的概念   
>###### ①静态布局   
传统web设计，对PC设计一个layout，调整屏幕宽高时，用滚动条查阅被遮部分。对于移动设备单独设计布局，使用不同域名如`wap.`或`m.`。   
###### ②弹性布局     
Flexbox布局。窗口变化到一定程度后重新排列容器。
###### ③自适应布局   
为不同分辨率定义布局。布局切换，元素大小不变，位置变化。    
###### ④流式布局     
以百分比为主要形式，让屏幕自适应。移动端结合rem。
###### ⑤响应式布局   
@media那个。

##### 4. 响应式布局方法

##### 5. css3实现动画

##### 6. fixed和absolute区别    
>fixed：固定定位。固定在当前window不动。不会随滚动条移动。      
absolute：绝对定位。会随参照对象元素的高度和宽度变化而变化。随滚动条移动。    

###### 7. 块级元素和内联元素的区别
>1.块级元素的特点：     
总在新行上开始；    
高度、行高以及内外边距都可以控制；    
宽度默认是它容器的100%，除非设置一个值；    
他可以容纳其他块级元素和内联元素。   
常见的块级元素：address,center,div,dir,from,h1-h6,hr,ol,ul,li,table,p,pre, menu。
2.内联元素的特点：
  和其他元素在同一行；
  高度、行高都不可控；
  宽度就是它文字或图片高度，不可改变；    
  内联元素只能容纳文本或其他内联元素。    
  常见的内联元素：a,b,br,em,font,i,img,input,label,select,span,strong,textarea.

>设置了float或者position:absolute|fixed都会使原来的内联元素变为块级元素。

##### 8. 伪元素   
>:first-letter  向文本的第一个字母添加特殊样式。
  :first-line 向文本的首行添加特殊样式。
  :before 在元素之前添加内容。
  :after  在元素之后添加内容。    
  伪元素加position:absolute;可以画图。    

##### 9. div垂直居中    
>


<hr>

## <span id="js">JavaScript</span>

##### 1. JavaScript作用域了解吗？有多少种
>全局作用域     
>函数作用域

##### 2. JavaScript有块级作用域吗？
>ES5之前没有，ES6提出了这个概念。

##### 3. let和var的区别？const？
>var能重复声明，let不能     
>let的变量作用范围不同，不存在变量提升。

##### 4. 数组去重？

##### 5. 遍历对象属性？

##### 6. call和apply的作用、区别


##### 7. Jasonp

##### 8. Ajax

##### 9. 对ES6的了解    

##### 10. Array对象方法   
>concat()连接两个或更多的数组，并返回结果。   
join()把数组的所有元素放入一个字符串。元素通过指定的分隔符进行分隔。    
pop() 删除并返回数组的最后一个元素。    
push()  向数组的末尾添加一个或多个元素，并返回新的长度。    
reverse() 颠倒数组中元素的顺序。    
shift() 删除并返回数组的第一个元素。    
slice() 从某个已有的数组返回选定的元素。    
sort()  对数组的元素进行排序。
splice()  删除元素，并向数组添加新元素。    
toSource()  返回该对象的源代码。    
toString()  把数组转换为字符串，并返回结果。    
toLocaleString()  把数组转换为本地数组，并返回结果。    
unshift() 向数组的开头添加一个或更多元素，并返回新的长度。    
valueOf() 返回数组对象的原始值。    

##### 11. js继承有哪些？原型继承是什么样的？    
>

<hr>

## <span id="emmm">emmmm... </span>

##### 1. HTTP状态码了解下？
> `1**` 信息，服务器收到请求，需要请求者继续执行操作。     
  `2**` 成功，操作被成功接收并处理。    
  `3**` 重定向，需要进一步的操作以完成请求。   
  `4**` 客户端错误，请求包含语法错误或无法完成请求。   
  `5**` 服务器错误，服务器在处理请求的过程中发生了错误。
>  
>  200--请求成功    
  301--资源被永久转移到其他URL。   
  404--请求的资源不存在。  
  500--内部服务器错误。

> get、post区别？   
  GET请求在浏览器回退时是无害的，POST会再次提交请求。
  get请求产生的URL地址可以被收藏，post不会。
  get请求会被浏览器主动缓存，post不会，除非主动设置。
  get请求只能进行URL编码，post支持多种编码方式。
  get请求参数会被完整的保留在浏览器历史记录里，post中的参数不会被保留。
  get请求在URL中传递的参数是有长度限制的，post没有限制。
  get请求只接受ASCII字符，而post对参数的数据类型没有限制。
  get请求不安全，因为直接暴露在URL上，不能传敏感信息。
  get请求参数通过URL传递，而post放在request.body上。


##### 2. Cookie、LocalStorage与SessionStorage区别

>* Cookie大小限制为4kb左右，可以保存登录信息（记住密码=-=）。
一般由服务器生成，可设置失效时间。     
浏览器端生成的，默认关闭浏览器即失效。     
每次都会携带在HTTP头中，保存过多数据会带来性能问题。       
需要自己封装。原生接口不友好。     
>
>* LocalStorage本地永久存储，除非清除。       
SessionStorage仅在当前会话下有效，关闭页面即消失。     
二者一般为5MB，仅在浏览器中保存，不参与服务器通信。    
购物车？   
可再次封装对Object和Array有更好的支持。

##### 3. css动画与js动画区别？    
>*js动画*   
缺点：①JavaScript在浏览器主线程中运行，主线程运行的其他种种造成阻塞，掉帧。   
②代码复杂   
优点：①控制能力强，开始暂停回放终止都可以。   
②效果丰富，曲线运动、冲击闪烁等只有js可做。   
③没有兼容性问题   
*css动画*   
缺点：①运动控制弱，无法附加事件绑定回调函数。   
②代码长。   
优点：①浏览器可以对动画进行优化。requestAnimationFrame。    

##### 4. 排序   

##### 5. HTTP和TCP的关系    
>TCP的三次握手。 
    1. 客户端-->SYN-->服务器
    2. 服务器-->SYN/ACK-->客户端
    3. 客户端-->ACK-->服务器   
HTTP建立在TCP之上