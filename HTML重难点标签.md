# 《HTML常用标签》
## 1. a 标签的用法
### 属性
* href
```HTML
<a href="#xxx" >id</a>
<a href="//baidu.com" >超链接</a>
<a href="/a/b/c.html">c.html</a>
<!-- <a href="mailto:584882416@qq.com">发邮件给我</a> -->
  ```
* target
```HTML
  <a href="//baidu.com" target="_top">baidu</a>
  <a href="//baidu.com" target="_blank">baidu</a>
  <a href="//baidu.com" target="_self">baidu</a>
  
  ```
  top一般在iframe效果才能展示出来
### 作用
* 跳转到外部的网页 
* 跳转到指定的邮箱或者电话
* 跳转到内部的锚点

## 2. img 标签的用法
发出get请求，展示一张图片
### 属性
 * src 后面加照片的地址
 * alt 图片展示不出来的时候的文字提示
 * height 可以设置图片的高度
 * width 可以设置图片的跨度
 
 不能同时设置宽度和高度，容易使图片变形。
```HTML
<img src="baby.png" alt="小恬恬" >
  ```
## 3. table 标签的用法
```HTML
 <table>
    <thead>
      <tr>
        <th>英语</th>
        <th>翻译</th>
      </tr>
    </thead>
    <tbody>
      <tr> 
        <th>hype</th>
        <th>超级</th>
      </tr>
      <tr> 
        <th>target</th>
        <th>目标</th>
      </tr>
      <tr> 
        <th>reference</th>
        <th>引用</th>
      </tr>
    </tbody>
    <tfoot>
      <tr> 
        <th>空</th>
        <th>空</th>

      </tr>
    </tfoot>
  </table>
  ```
  ```HTML
  table{
      width: 500px;
      table-layout: auto;
      border-collapse: collapse;
      border-spacing: 0ch;
    }
    ```
    table 包括thead,tbody,tfoot.
