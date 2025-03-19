<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>施梦娇的个人简介</title>
    <style>
        /* 基础样式重置 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }
 
        /* 渐变背景 */
        body {
            background: linear-gradient(135deg, #2c3e50, #ecf0f1);
            background-size: 400% 400%;
            animation: gradientShift 15s ease infinite;
            min-height: 100vh;
            padding: 2rem;
        }
 
        /* 背景动画 */
        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
 
        /* 主容器 */
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.9);
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
 
        /* 头部样式 */
        .header {
            text-align: center;
            margin-bottom: 2rem;
            padding-bottom: 1.5rem;
            border-bottom: 2px solid #3498db;
        }
 
        h1 {
            color: #2c3e50;
            font-size: 3rem;
            margin-bottom: 0.5rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
 
        h2 {
            color: #7f8c8d;
            font-weight: normal;
            font-size: 1.5rem;
        }
 
        /* 内容区域 */
        .content-section {
            margin-bottom: 2rem;
            padding: 1.5rem;
            background: rgba(255,255,255,0.8);
            border-radius: 10px;
        }
 
        .contact-info {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 1rem;
            align-items: center;
        }
 
        .contact-icon {
            color: #3498db;
            font-size: 1.5rem;
        }
 
        /* 响应式设计 */
        @media (max-width: 768px) {
            .container {
                padding: 1rem;
                margin: 0.5rem;
            }
 
            h1 {
                font-size: 2.5rem;
            }
 
            .contact-info {
                grid-template-columns: 1fr;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>施梦娇</h1>
            <h2>硕士研究生 | 资源与环境专业</h2>
        </header>
 
        <section class="content-section">
            <h3>🎓 教育背景</h3>
            <p>2024.09 - 至今  |  华中农业大学资源与环境学院</p>
            <p>主修方向：废水处理与可持续发展</p>
            <p>相关课程：环境系统工程、生态经济学、污染控制技术等</p>
        </section>
 
        <section class="content-section">
            <h3>📧 联系方式</h3>
            <div class="contact-info">
                <i class="contact-icon">📧</i>
                <a href="mailto:10768003820@example.com">10768003820@example.com</a>
            </div>
            <div class="contact-info">
                <i class="contact-icon">📱</i>
                <a href="tel:+18277687657">+86 123-4567-8901</a>
            </div>
        </section>
 
        <section class="content-section">
            <h3>📝 个人简介</h3>
            <p>专注于环境资源管理与可持续发展研究，具备扎实的专业理论基础和实践经验。曾参与XX流域生态修复项目，掌握GIS和遥感数据分析技能。热爱科研工作，致力于通过技术创新解决环境问题。</p>
        </section>
    </div>
</body>
</html>
