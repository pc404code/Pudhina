<!DOCTYPE HTML>
 <head>
  <body>
  </body>
 </head>
</html>

## head标签：
- title-
- meta(单标签)
  - http-equiv告知浏览器行为
  - content-type/refresh
  - name告诉浏览器一些信息的名字
  - keywords/description/viewport
——content行为或内容的具体内容——
- link(单标签)
  - rel——icon/stylesheet
  - href
  - type——text/css

## body(标签)：
- 文本标签
  - br和hr(单标签)
  - p
  - h1 h2 h3 …… h6
- 链接标签
  - a——href/target
  - 
- 多媒体标签
  - video
  - audio
   - vidio(与audio属性值一致)
         - audio
       - src 视频地址
          - controls 添加播放器控件(按钮)
          - width="宽度" height="高度" (宽高只给一个值是等比例缩放, 两个都给是强制缩放)
        - autoplay 自动播放
        - loop 循环播放
              - preload 提前加载准备播放, 不能与autoplay一起使用 poster="视频播放之前展示的图片的地址"
          - muted 静音
          - 定义视频地址, 其属性是src="视频地址"

- 表格标签
  - table
     - border="线宽" width="宽度" height="高度" allgn="表格整体水平位置" 其属性值为: center居中 left居左 right居右 cellspacing="单元格之间的间距" cellpadding="内容与单元格边框的距离"
         - caption 
           - tr
           - allgn
              - center居中
            - left居左
              - right居右
               - th
               - td
- 块级元素：
  - 可以换行
  - 宽度100%
- 行级元素：
  - <img标签 >
  - 图片均可以通过css调整属性displa
  - 