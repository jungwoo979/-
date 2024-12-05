<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>大学生挑战自媒体</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <!-- 首页 -->
        <section class="hero">
            <h1>大学生挑战自媒体</h1>
            <p>加入自媒体行业，你准备好了吗？</p >
            <button class="start-btn" onclick="startChallenge()">开始挑战</button>
        </section>

        <!-- 自媒体简要介绍 -->
        <section class="intro">
            <h2>什么是自媒体？</h2>
            <p>自媒体是利用网络平台，个人或团队发布和传播信息的方式。大学生通过短视频、图文、直播等形式展示自我，成为内容创作者。</p >
            < img src="https://via.placeholder.com/600x300" alt="自媒体示意图">
        </section>

        <!-- 挑战问答 -->
        <section class="quiz">
            <h2>大学生进入自媒体面临的最大挑战是什么？</h2>
            <div class="question">
                <button class="answer-btn" onclick="showAnswer('内容创作')">内容创作</button>
                <button class="answer-btn" onclick="showAnswer('流量获取')">流量获取</button>
                <button class="answer-btn" onclick="showAnswer('变现模式')">变现模式</button>
            </div>
            <div id="answer"></div>
        </section>

        <!-- 成功案例展示 -->
        <section class="cases">
            <h2>成功案例</h2>
            <div class="case">
                <h3>大学生如何通过抖音创业？</h3>
                <p>案例：通过短视频平台积累粉丝，实现自我品牌的建立。了解如何从零开始。</p >
                <video controls>
                    <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
                    你的浏览器不支持 video 标签。
                </video>
            </div>
        </section>

        <!-- 数据可视化展示 -->
        <section class="data">
            <h2>自媒体行业趋势</h2>
            <p>自媒体行业正在快速发展，大学生作为新兴内容创作者的力量逐渐壮大。</p >
            <div class="chart">
                <div class="bar" style="height: 70%"></div>
                <div class="bar" style="height: 50%"></div>
                <div class="bar" style="height: 90%"></div>
            </div>
        </section>

        <!-- 分享按钮 -->
        <section class="share">
            <h2>分享你的自媒体梦想</h2>
            <p>你想如何挑战自媒体？快来分享你的想法吧！</p >
            <button class="share-btn" onclick="shareToSocial()">分享</button>
        </section>
    </div>

    <script src="script.js"></script>
</body>
</html>
