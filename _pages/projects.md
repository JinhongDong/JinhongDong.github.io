---
layout: page
title: Projects
permalink: /projects/
description: A collection of my academic and research projects.
nav: true
nav_order: 2
display_categories: [undergraduate]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">

<!-- 本科项目 -->
<h2 class="category">Undergraduate Projects</h2>
<div class="grid">
  
  <!-- 项目1: 心力衰竭预测 -->
  <div class="card project-card">
    <div class="card-body">
      <h3 class="card-title">Heart Failure Prediction using Machine Learning</h3>
      <div class="project-date">June 2022</div>
      <div class="card-text">
        <p>A machine learning project focused on analyzing and predicting heart failure risks using patient clinical data.</p>
        <ul>
          <li>Performed data preprocessing and feature engineering on clinical datasets</li>
          <li>Optimized multiple ML models (Random Forest, XGBoost, SVM) to achieve best accuracy metrics</li>
          <li>Fine-tuned hyperparameters and implemented cross-validation strategies</li>
          <li>Achieved 92% accuracy in predicting heart failure outcomes</li>
        </ul>
      </div>
      <div class="project-meta">
        <span class="badge bg-primary">Machine Learning</span>
        <span class="badge bg-secondary">Healthcare</span>
        <span class="badge bg-info">Python</span>
      </div>
    </div>
  </div>

  <!-- 项目2: 医学NER系统 -->
  <div class="card project-card">
    <div class="card-body">
      <h3 class="card-title">Medical Named Entity Recognition System</h3>
      <div class="project-date">April 2024</div>
      <div class="card-text">
        <p>Graduation project: Designed and developed a NER system for medical texts using open-source LLMs.</p>
        <ul>
          <li>Leveraged ChatGLM open-source language model for entity recognition</li>
          <li>Developed a comprehensive system for identifying medical entities in text</li>
          <li>Implemented visualization interface for results display</li>
          <li>Added functionality for result export and manual correction</li>
          <li>Achieved 93% F1-score on medical text recognition tasks</li>
        </ul>
      </div>
      <div class="project-meta">
        <span class="badge bg-primary">NLP</span>
        <span class="badge bg-secondary">Healthcare</span>
        <span class="badge bg-info">ChatGLM</span>
        <span class="badge bg-success">Web Development</span>
      </div>
    </div>
  </div>
</div>

<!-- 研究生项目（暂无） -->
<div class="graduate-section">
  <h2 class="category">Graduate Projects</h2>
  <div class="empty-projects text-center py-4">
    <h4>No Current Projects</h4>
    <p class="lead">I'm actively exploring new research directions in computational communication and will update this section soon!</p>
    <div class="mt-3">
      <i class="fas fa-lightbulb fa-2x text-warning"></i>
    </div>
    <p class="mt-2">Check back later for updates on my graduate research projects.</p>
  </div>
</div>

</div>

<style>
.project-card {
  margin-bottom: 1.5rem;
  border: 1px solid #e9ecef;
  border-radius: 8px;
}
.project-card .card-title {
  color: #2c3e50;
  font-weight: 600;
}
.project-date {
  color: #6c757d;
  font-size: 0.9rem;
  font-weight: 500;
  margin-bottom: 0.5rem;
  font-style: italic;
}
.project-meta {
  margin-top: 1rem;
}
.badge {
  margin-right: 0.5rem;
  margin-bottom: 0.5rem;
}
.empty-projects {
  background-color: #f8f9fa;
  border-radius: 10px;
  padding: 30px;
}
.empty-projects h4 {
  color: #6c757d;
}
.category {
  color: #495057;
  border-bottom: 2px solid #6c757d;
  padding-bottom: 0.5rem;
  margin-bottom: 1.5rem;
}
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 1.5rem;
}

/* 新增样式确保研究生部分正确显示 */
.graduate-section {
  clear: both;
  margin-top: 3rem;
  position: relative;
  z-index: 10;
}

/* 确保网格容器不会影响后续内容 */
.grid::after {
  content: "";
  display: table;
  clear: both;
}
</style>
