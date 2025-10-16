---
layout: page
title: 项目展示
permalink: /projects/
description: 我的学术与实践项目集
nav: true
nav_order: 2
display_categories: [本科, 研究生]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">

<!-- 本科项目 -->
<h2 class="category">本科项目</h2>
  
<!-- 项目1: 心力衰竭预测 -->
<div class="card project-card">
  <div class="card-body">
    <h3 class="card-title">基于机器学习的心力衰竭预测系统</h3>
    <div class="project-date">2022年6月</div>
    <div class="card-text">
      <p>使用患者临床数据分析预测心力衰竭风险的机器学习项目。</p>
      <ul>
        <li>对临床数据集进行数据预处理和特征工程</li>
        <li>优化多种机器学习模型（随机森林、XGBoost、SVM）以达到最佳准确率</li>
        <li>调整超参数并实施交叉验证策略</li>
        <li>在心力衰竭结果预测中达到92%的准确率</li>
      </ul>
    </div>
    <div class="project-meta">
      <span class="badge bg-primary">机器学习</span>
      <span class="badge bg-secondary">医疗健康</span>
      <span class="badge bg-info">Python</span>
    </div>
  </div>
</div>

<!-- 项目2: 医学NER系统 -->
<div class="card project-card">
  <div class="card-body">
    <h3 class="card-title">医学命名实体识别系统</h3>
    <div class="project-date">2024年4月</div>
    <div class="card-text">
      <p>毕业设计：使用开源大语言模型开发医学文本命名实体识别系统。</p>
      <ul>
        <li>利用ChatGLM开源语言模型进行实体识别</li>
        <li>开发了全面的医学文本实体识别系统</li>
        <li>实现了结果可视化展示界面</li>
        <li>添加了结果导出和手动校正功能</li>
        <li>在医学文本识别任务中达到93%的F1分数</li>
      </ul>
    </div>
    <div class="project-meta">
      <span class="badge bg-primary">自然语言处理</span>
      <span class="badge bg-secondary">医疗健康</span>
      <span class="badge bg-info">ChatGLM</span>
      <span class="badge bg-success">Web开发</span>
    </div>
  </div>
</div>

<!-- 研究生项目 -->
<div class="graduate-section">
  <h2 class="category">研究生项目</h2>
  
  <!-- 项目3: 网络视听内容创意方案策划 -->
  <div class="card project-card">
    <div class="card-body">
      <h3 class="card-title">网络视听内容创意方案策划</h3>
      <div class="project-date">2023年12月</div>
      <div class="card-text">
        <p>设计融合AI与旅游的综艺节目《跟着AI去旅游》，完成从创意到落地的全流程策划。</p>
        <ul>
          <li>创意背景：结合AI技术与旅游体验，打造全新综艺模式</li>
          <li>节目流程：AI导游规划路线→明星体验→观众互动→AI生成旅行报告</li>
          <li>融合传播策略：短视频预热+直播互动+AI生成个性化旅行攻略</li>
          <li>可行性分析：技术实现路径、市场接受度评估、商业模式设计</li>
          <li>创新点：AI实时生成旅行路线，观众投票决定行程方向</li>
        </ul>
      </div>
      <div class="project-meta">
        <span class="badge bg-primary">内容策划</span>
        <span class="badge bg-secondary">媒体创新</span>
        <span class="badge bg-info">AI应用</span>
        <span class="badge bg-success">综艺制作</span>
      </div>
    </div>
  </div>
  
  <!-- 研究生项目占位提示 -->
  <div class="more-projects text-center py-4">
    <h4>更多项目筹备中</h4>
    <p class="lead">我正在计算传播学领域探索更多创新项目，将很快更新！</p>
    <div class="mt-3">
      <i class="fas fa-rocket fa-2x text-primary"></i>
    </div>
  </div>
</div>

</div>

<style>
.project-card {
  margin-bottom: 2rem;
  border: 1px solid #e9ecef;
  border-radius: 8px;
  padding: 1.5rem;
  transition: all 0.3s ease;
  background-color: #fff;
}
.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}
.project-card .card-title {
  color: #2c3e50;
  font-weight: 600;
  margin-bottom: 0.8rem;
}
.project-date {
  color: #6c757d;
  font-size: 0.9rem;
  font-weight: 500;
  margin-bottom: 0.8rem;
}
.project-meta {
  margin-top: 1.2rem;
}
.badge {
  margin-right: 0.5rem;
  margin-bottom: 0.5rem;
  padding: 0.5em 0.8em;
  border-radius: 12px;
  font-weight: 500;
}
.category {
  color: #495057;
  border-bottom: 2px solid #6c757d;
  padding-bottom: 0.8rem;
  margin-bottom: 1.8rem;
  font-weight: 600;
}

/* 研究生项目部分样式 */
.graduate-section {
  margin-top: 3rem;
  padding-top: 2rem;
  border-top: 2px dashed #dee2e6;
}

.more-projects {
  background-color: #f8f9fa;
  border-radius: 10px;
  padding: 25px;
  margin-top: 2rem;
}
.more-projects h4 {
  color: #6c757d;
  margin-bottom: 1rem;
}

/* 确保整个项目容器有最小高度 */
.projects {
  min-height: 80vh;
}

/* 项目列表样式 */
.card-text ul {
  padding-left: 1.5rem;
}
.card-text li {
  margin-bottom: 0.7rem;
  line-height: 1.6;
}

/* 研究生项目特殊样式 */
.graduate-section .project-card {
  border-left: 4px solid #4e73df;
}

/* 响应式调整 */
@media (max-width: 768px) {
  .project-card {
    padding: 1rem;
  }
  .project-meta .badge {
    font-size: 0.75rem;
  }
}
</style>
