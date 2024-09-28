## Hi there 👋<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>杨长春教授的个人主页</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: space-around;
            background: #444;
            padding: 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            background: #555;
            border-radius: 5px;
        }
        nav a:hover {
            background: #666;
        }
        section {
            padding: 20px;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .search-container {
            text-align: center;
            margin: 20px 0;
        }
        .search-container input[type="text"] {
            width: 300px;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ddd;
        }
        .search-container button {
            padding: 10px 15px;
            border: none;
            background: #333;
            color: #fff;
            border-radius: 5px;
        }
        .content-box {
            background: #fff;
            margin: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>

    <!-- 页眉 -->
    <header>
        <h1>杨长春教授的个人主页</h1>
        <p>中国科学院地质与地球物理研究所 · 资深研究员</p>
    </header>

    <!-- 导航栏 -->
    <nav>
        <a href="#intro">个人简介</a>
        <a href="#achievements">学术成就</a>
        <a href="#projects">科研项目</a>
        <a href="#contact">联系方式</a>
        <a href="https://www.cas.cn" target="_blank">中国科学院主页</a>
    </nav>

    <!-- 搜索框 -->
    <section class="search-container">
        <input type="text" id="searchInput" placeholder="请输入关键词进行搜索...">
        <button onclick="searchContent()">搜索</button>
    </section>

    <!-- 主内容 -->
    <section id="intro" class="content-box">
        <h2>个人简介</h2>
        <p>杨长春教授是中国科学院地质与地球物理研究所的资深研究员，现任油气资源研究重点实验室主任。他主要研究地球物理勘探、复杂地质结构预测以及油气资源开发，在地质学领域取得了卓越的成就。</p>
        <p>1991年，杨长春在法国波尔多大学获得博士学位，1994年回国后开始在中科院工作，逐步成为复杂地质结构预测领域的领军人物。</p>
    </section>

    <section id="achievements" class="content-box">
        <h2>学术成就</h2>
        <ul>
            <li>发表了数十篇高影响力论文，涵盖地球物理勘探新方法、复杂地质结构预测模型等。</li>
            <li>曾获得中国科学院杰出科技成就奖、国家科技进步奖等多项荣誉。</li>
            <li>多次作为核心专家参与国内外地球物理学术会议。</li>
        </ul>
    </section>

    <section id="projects" class="content-box">
        <h2>科研项目</h2>
        <ul>
            <li>主持了多个国家自然科学基金重点项目，专注于复杂地质结构的预测与油气资源开发。</li>
            <li>参与了深地资源装备技术工程实验室的多个研究项目，推动了深部资源探测理论的技术应用。</li>
        </ul>
    </section>

    <section id="contact" class="content-box">
        <h2>联系方式</h2>
        <p>电子邮件：yangcc@igg.cas.cn</p>
        <p>电话：010-82998000</p>
        <p>地址：中国科学院地质与地球物理研究所，油气资源研究重点实验室</p>
    </section>

    <!-- 页脚 -->
    <footer>
        <p>© 2024 中国科学院地质与地球物理研究所 | 杨长春教授个人主页</p>
    </footer>

    <!-- JS 搜索功能 -->
    <script>
        function searchContent() {
            const searchInput = document.getElementById('searchInput').value.toLowerCase();
            const contentSections = document.querySelectorAll('.content-box');
            
            contentSections.forEach(section => {
                const textContent = section.textContent.toLowerCase();
                if (textContent.includes(searchInput)) {
                    section.style.display = 'block';
                } else {
                    section.style.display = 'none';
                }
            });
        }
    </script>

</body>
</html>


<!--
**yang-changchun/yang-changchun** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
