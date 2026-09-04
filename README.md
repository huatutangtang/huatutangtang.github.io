<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>宋可馨 - 个人主页</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft Yahei", sans-serif;
        }
        body {
            max-width: 1200px;
            margin: 40px auto;
            display: flex;
            gap:40px;
            padding:0 20px;
            color:#333;
        }
        /* 左侧侧边栏 */
        .sidebar {
            width:240px;
            flex-shrink:0;
        }
        .sidebar h2 {
            font-size:20px;
            margin-bottom:8px;
        }
        .sidebar .desc {
            font-size:14px;
            color:#555;
            line-height:1.6;
            margin-bottom:20px;
        }
        .sidebar-item {
            display:flex;
            align-items:center;
            gap:8px;
            font-size:14px;
            margin:10px 0;
        }
        /* 右侧主体内容 */
        .main {
            flex:1;
        }
        .section-title {
            font-size:24px;
            font-weight:bold;
            margin:32px 0 16px;
            padding-bottom:8px;
            border-bottom:1px solid #eee;
        }
        .section-title:first-child {
            margin-top:0;
        }
        .para {
            line-height:1.7;
            font-size:16px;
            color:#444;
        }
        /* 教育经历表格样式 */
        .edu-table {
            width:100%;
        }
        .edu-table tr td {
            padding:10px 0;
            font-size:16px;
        }
        a {
            color:#2b78bb;
            text-decoration:none;
        }
    </style>
</head>
<body>
    <!-- 左侧侧边栏，已删除头像img标签 -->
    <div class="sidebar">
        <h2>宋可馨</h2>
        <div class="desc">
            曲阜师范大学大二学生，计算机科学与技术专业。
        </div>
        <div class="sidebar-item">
            <span>📍</span>
            <span>日照, 山东, 中国</span>
        </div>
        <div class="sidebar-item">
            <span>🎓</span>
            <span>曲阜师范大学</span>
        </div>
        <div class="sidebar-item">
            <span>🌐</span>
            <span><a href="#">Website</a></span>
        </div>
        <div class="sidebar-item">
            <span>✉️</span>
            <span><a href="#">Email</a></span>
        </div>
        <div class="sidebar-item">
            <span>🟢</span>
            <span><a href="#">ORCID</a></span>
        </div>
        <div class="sidebar-item">
            <span>⌨</span>
            <span><a href="#">GitHub</a></span>
        </div>
    </div>

    <!-- 右侧主内容 -->
    <div class="main">
        <div class="section-title">个人信息</div>
        <p class="para">
            宋可馨，女，曲阜师范大学计算机科学与技术专业大二本科生。对计算机相关技术抱有浓厚兴趣，目前正在学习C++、HTML/CSS等程序开发相关知识，同时对非物质文化遗产方向的内容创作有一定的关注。希望不断夯实专业基础，锻炼编程实践能力，探索更多技术与人文结合的方向。
        </p>

        <div class="section-title">教育经历</div>
        <table class="edu-table">
            <tr>
                <td>2025.09 - 至今</td>
                <td>曲阜师范大学</td>
                <td>计算机科学与技术</td>
                <td>本科（大二）</td>
            </tr>
        </table>

        <div class="section-title">技能与兴趣</div>
        <p class="para">
            编程技能：C++、HTML、CSS；<br>
            兴趣方向：前端网页开发、程序设计。
        </p>
    </div>
</body>
</html>
