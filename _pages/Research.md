<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>研究兴趣与成果</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #3498db;
            --secondary-color: #2c3e50;
            --accent-color: #e74c3c;
            --light-bg: #f8f9fa;
            --dark-bg: #343a40;
            --card-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f5f7fa;
            padding-top: 20px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .header {
            text-align: center;
            margin-bottom: 40px;
            padding: 30px 20px;
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            border-radius: 10px;
            box-shadow: var(--card-shadow);
        }
        
        .header h1 {
            font-weight: 700;
            margin-bottom: 10px;
        }
        
        .header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .section {
            background: white;
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 30px;
            box-shadow: var(--card-shadow);
            transition: transform 0.3s ease;
        }
        
        .section:hover {
            transform: translateY(-5px);
        }
        
        .section-title {
            color: var(--secondary-color);
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 10px;
            margin-bottom: 20px;
            font-weight: 600;
        }
        
        .research-interests {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .interest-card {
            background: var(--light-bg);
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid var(--primary-color);
        }
        
        .interest-card h4 {
            color: var(--secondary-color);
            margin-bottom: 10px;
        }
        
        .courses-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .course-category {
            background: var(--light-bg);
            padding: 20px;
            border-radius: 8px;
        }
        
        .course-list {
            list-style-type: none;
            padding: 0;
        }
        
        .course-list li {
            padding: 10px 15px;
            margin-bottom: 10px;
            background: white;
            border-radius: 6px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            display: flex;
            align-items: center;
        }
        
        .course-list li:before {
            content: "•";
            color: var(--primary-color);
            font-weight: bold;
            margin-right: 10px;
            font-size: 1.2rem;
        }
        
        .current-courses li {
            border-left: 3px solid var(--accent-color);
        }
        
        .past-courses li {
            border-left: 3px solid var(--primary-color);
        }
        
        .badge {
            background: var(--primary-color);
            color: white;
            padding: 3px 8px;
            border-radius: 15px;
            font-size: 0.8rem;
            margin-left: 10px;
        }
        
        .note {
            background: #fff9e6;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #ffcc00;
            margin-top: 30px;
            font-style: italic;
        }
        
        @media (max-width: 768px) {
            .research-interests, .courses-container {
                grid-template-columns: 1fr;
            }
            
            .header h1 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>研究兴趣与成果</h1>
            <p>通过数据发现故事，通过计算理解情感</p>
        </div>
        
        <div class="section">
            <h2 class="section-title">研究概述</h2>
            <p>虽然我目前还没有发表学术论文，但我正在积极探索以下研究项目，并持续努力为该领域贡献有意义的见解。</p>
            
            <h3 class="mt-4">当前研究重点</h3>
            <p>我专注于探索计算方法与传播研究的交叉领域，特别关注计算新闻学和数据驱动的叙事构建。虽然尚未发表学术论文，但我正深入参与开发能够连接数据分析与叙事构建的有意义项目。</p>
            
            <div class="research-interests">
                <div class="interest-card">
                    <h4>计算新闻</h4>
                    <p>数据驱动的新闻发现与自动化报道</p>
                </div>
                <div class="interest-card">
                    <h4>情感分析</h4>
                    <p>公共事件中的情绪动态与观点挖掘</p>
                </div>
                <div class="interest-card">
                    <h4>数据叙事</h4>
                    <p>从大规模社交数据中提取叙事结构</p>
                </div>
                <div class="interest-card">
                    <h4>数据可视化</h4>
                    <p>通过视觉呈现增强故事讲述效果</p>
                </div>
            </div>
            
            <p class="mt-4">我坚信开放科学和透明的研究实践。我定期在GitHub和OSF上分享我的项目进展、代码和方法论。我的工作重点是开发能够帮助揭示数据中隐藏的有意义故事，并理解公共讨论中情感基调的技术。</p>
        </div>
        
        <div class="section">
            <h2 class="section-title">课程学习</h2>
            <p>以下是我在研究生阶段学习的关键课程，这些课程为我的研究提供了坚实的理论基础和方法论支持。</p>
            
            <div class="courses-container">
                <div class="course-category">
                    <h3>当前学期课程 <span class="badge">进行中</span></h3>
                    <ul class="course-list current-courses">
                        <li>网络数据分析</li>
                        <li>高级统计</li>
                        <li>传播理论前沿</li>
                        <li>计算传播导论</li>
                    </ul>
                </div>
                
                <div class="course-category">
                    <h3>已修读课程</h3>
                    <ul class="course-list past-courses">
                        <li>数据结构</li>
                        <li>Python程序设计</li>
                        <li>机器学习</li>
                        <li>深度学习</li>
                        <li>自然语言处理</li>
                        <li>数据库与数据操作</li>
                    </ul>
                </div>
            </div>
            
            <div class="mt-4">
                <h4>课程与研究的相关性</h4>
                <p>这些课程为我提供了坚实的技术基础和研究方法，特别是机器学习、自然语言处理和网络数据分析等课程直接支持我在计算传播学和数据新闻领域的研究工作。</p>
            </div>
        </div>
        
        <div class="note">
            <p><i class="fas fa-info-circle"></i> 注：随着我的研究进展和新项目的出现，此部分内容将持续更新。</p>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
