# 0713
使一个宽为200px和高为200px的层垂直居中于浏览器使用百分比和绝对定位与外补丁负值的方法负值的大小为其自身宽度高度一半
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta name="author" content="aiyaya">
    .test {
      width:200px;
      height:200px;
      top:50%;
      left:50%;
      margin-left:-100px;
      margin-top:-100px;
      background-color:red;
    }
    <title>居中</title>
  </head>
  <body>
    <div class="test">
      测试：实现居中
    </div>
  </body>
</html>
