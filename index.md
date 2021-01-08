
`<!DOCTYPE html>
<html>

<head>
    <script>
        function back() {
            window.open("CTD.html", "newwindow", "height=100, width=400, toolbar=no, menubar=no, scrollbars=no, resizable=no, location=no, status=no");
        }
    </script>
    <title>CTD官方网站</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        * {
            box-sizing: border-box;
        }
        /* body 样式 */
        
        body {
            font-family: Arial;
            margin: 0;
        }
        /* 标题 */
        
        .header {
            padding: 80px;
            text-align: center;
            /* background: #48f4fa; */
            color: white;
        }
        /* 标题字体加大 */
        
        .header h1 {
            font-size: 40px;
        }
        /* 导航 */
        
        .navbar {
            overflow: hidden;
            background-color: #333;
        }
        /* 导航栏样式 */
        
        .navbar a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        /* 右侧链接*/
        
        .navbar a.right {
            float: right;
        }
        /* 鼠标移动到链接的颜色 */
        
        .navbar a:hover {
            background-color: #ddd;
            color: black;
        }
        /* 列容器 */
        
        .row {
            display: -ms-flexbox;
            /* IE10 */
            display: flex;
            -ms-flex-wrap: wrap;
            /* IE10 */
            flex-wrap: wrap;
        }
        /* 创建两个列 */
        /* 边栏 */
        
        .main {
            -ms-flex: 70%;
            /* IE10 */
            flex: 70%;
            background-color: white;
            padding: 20px;
        }
        /* 测试图片 */
        
        .main {
            -ms-flex: 70%;
            /* IE10 */
            flex: 70%;
            background-color: white;
            padding: 20px;
        }
        /* 测试图片 */
        
        .side {
            -ms-flex: 30%;
            /* IE10 */
            flex: 30%;
            background-color: #f1f1f1;
            padding: 20px;
        }
        /* 主要的内容区域 */
        
        .fakeimg {
            background-color: rgb(255, 253, 253);
            width: 100%;
            padding: 20px;
        }
        /* 底部 */
        
        .footer {
            padding: 20px;
            text-align: center;
            background: rgba(206, 179, 179, 0.466);
        }
        /* 响应式布局 - 在屏幕设备宽度尺寸小于 700px 时, 让两栏上下堆叠显示 */
        
        @media screen and (max-width: 700px) {
            .row {
                flex-direction: column;
            }
        }
        /* 响应式布局 - 在屏幕设备宽度尺寸小于 400px 时, 让导航栏目上下堆叠显示 */
        
        @media screen and (max-width: 400px) {
            .navbar a {
                float: none;
                width: 100%;
            }
        }
    </style>
</head>

<body>

    <div class="header">
        <style type="text/css">
            body {
                /* background */
                background-image: url("http://pic.yupoo.com/myctd/1317bbdd/c61f26bc.png");
                background-attachment: scorll;
                background-repeat: no-repeat;
                background-position: top left;
            }
        </style>
        <link rel="stylesheet" type="test/css" href="autoimg.css">
        <img src="http://pic.yupoo.com/myctd/e9f23a07/3ac73145.png" width="200" height="200" />
        <!-- CTDlogo -->
    </div>

    <div class="navbar">
        <a onclick="back()">返回主页面</a>
        <!-- <button onclick="alertf()">注意事项</button> -->
        <a href="#" class="right"> </a>
    </div>

    <div class="row">
        <div class="main">
            <h2>DARK pixel服务器(68697981)</h2>
            <img src="http://pic.yupoo.com/myctd/e0a31c79/8f0849fe.jpg" height="180px" width="300" />
            <p>主城大方、干净。</p>
            <img src="http://pic.yupoo.com/myctd/5ded016a/aeff92fa.jpg" height="180px" width="300" />
            <p>紧张刺激的四人切糕。</p>
            <img src="http://pic.yupoo.com/myctd/ebb438cb/fa202c3a.jpg" height="180px" width="300" />
            <p>提心吊胆的密室杀手。</p>
            <img src="http://pic.yupoo.com/myctd/b994d0f8/3c76c67b.jpg" height="180px" width="300" />
            <img src="http://pic.yupoo.com/myctd/11ba3d03/08c099d5.jpg" height="180px" width="300" />
            <img src="http://pic.yupoo.com/myctd/5e9456f2/42c0f001.jpg" height="180px" width="300" />
            <p>有趣的双人rush、战桥、微型起床小游戏。</p>
            <img src="http://pic.yupoo.com/myctd/47d87388/d33f8133.jpg" height="180px" width="300" />
            <p>更有20余个小游戏等你来战。</p>
            <img src="http://pic.yupoo.com/myctd/9187187e/7399a9fa.jpg" height="180px" width="300" />
            <img src="http://pic.yupoo.com/myctd/3b558c7f/536fa1fc.jpg" height="180px" width="300" />
            <p>更有双人PVP、空手PVP等4种PVP你来战。</p>
            <p>更多精彩快来我们服务器玩吧！</p>
        </div>
        <div class="side">
            <h2>CTD介绍</h2>
            <video src="https://uvd.yupoo.com/myctd/22321671.mp4" class="fakeimg" controls height="200"></video>
            <p>我的世界服务器宣传网站，可以让大家的服务器在这里分享，也可以让玩家找到适合自己的服务器，在视频中查看详情。</p>
        </div>
    </div>

    <div class="footer">
        <h4>特此声明！因服务器资金问题，暂时选用GitHub挂载官网，网站暂时开源，但代码为CTD原创，未经允许，不得转载或盗用！</h4>
    </div>
</body>

</html>
