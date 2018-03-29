# Interview-Questions

### [HTML](#html)
### [CSS](#css)
### [JavaScript](#js)
### [emmm...](#emmm)

## <span id="html">HTML</span>

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


<hr>

## <span id="js">JavaScript</span>

##### 1. JavaScript作用域了解吗？有多少种
>全局作用域     
>函数作用域

##### 2. JavaScript有块级作用域吗？
>ES5之前没有，ES6提出了这个概念。

##### 3. let和var的区别
>var能重复声明，let不能     
>let的变量作用范围不同，不存在变量提升。
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

##### 2. Cookie、LocalStorage与SessionStorage区别

>* Cookie大小限制为4kb左右，可以保存登录信息（记住密码=-=）。
一般由服务器生成，可设置失效时间。     
浏览器端生成的，默认关闭浏览器即失效。     
每次都会携带在HTTP头中，保存过多数据会带来性能问题。       
需要自己封装。源生接口不友好。     
>
>* LocalStorage本地永久存储，除非清除。       
SessionStorage仅在当前会话下有效，关闭页面即消失。     
二者一般为5MB，仅在浏览器中保存，不参与服务器通信。    
购物车？   
可再次封装对Object和Array有更好的支持。
