---
title: Hello World
password: 1234abb
abstract: 有东西被加密了, 请输入密码查看
message: 您好, 这里需要密码.
wrong_pass_message: 抱歉, 这个密码看着不太对, 请再试试.
wrong_hash_message: 抱歉, 这个文章不能被校验, 不过您还是能看看解密后的内容.
---

## This is my first article!

<html>
  <head>
    <script>
      // 定义一个回调函数
      function showBmap() {
        // 获取 iframe 元素
        var iframe = document.getElementById("bmap");
        // 设置 iframe 元素的 src 属性为本地的 bmap_base.html 网页
        iframe.src = "bmap_base.html";
      }
    </script>
    <style>
      /* 定义一个 CSS 规则，选择 button 元素 */
    button {
        /* 设置 text-align 属性为 center */
        text-align: center;
        /* 设置 color 属性为白色 */
        color: white;
        /* 设置 background-color 属性为蓝色 */
        background-color: pink;
        /* 设置 border 属性为无边框 */
        border: 10px;
        border-radius: 10px;
        /* 设置 padding 属性为 10 像素 */
        padding: 10px;
        /* 设置 font-size 属性为 20 像素 */
        font-size: 20px;
        margin: auto;
        display: block
        }
    iframe {
        /* 设置 display 属性为 block */
        display: block;
        /* 设置 margin 属性为 auto */
        margin: auto;
        margin-bottom: 10px;
        }
    </style>
  </head>
  <body>
    <button onclick="showBmap()">显示百度地图</button>
    <br />
    <iframe id="bmap" width="600" height="400"></iframe>
  </body>
</html>
