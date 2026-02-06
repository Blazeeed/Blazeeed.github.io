---
layout: default
title: "Эра Искусственного Интеллекта"
subtitle: "Размышляя о будущем разума"
---

<style>
:root {
    --ai-primary: #2563eb;
    --ai-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --ai-light: #f8fafc;
    --ai-dark: #1e293b;
}

.ai-hero {
    text-align: center;
    padding: 4rem 1rem;
    background: var(--ai-gradient);
    color: white;
    border-radius: 0 0 20px 20px;
    margin-bottom: 3rem;
}

.ai-hero h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
    font-weight: 800;
}

.ai-hero p {
    font-size: 1.5rem;
    opacity: 0.9;
    max-width: 700px;
    margin: 0 auto;
}

.ai-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin: 3rem 0;
}

.ai-card {
    background: white;
    border-radius: 12px;
    padding: 2rem;
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
    border: 1px solid #e5e7eb;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.ai-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
}

.ai-icon {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: var(--ai-primary);
}

.ai-cta {
    text-align: center;
    margin: 4rem 0;
    padding: 3rem;
    background: var(--ai-light);
    border-radius: 12px;
}

.btn-ai {
    display: inline-block;
    padding: 1rem 2rem;
    background: var(--ai-gradient);
    color: white;
    text-decoration: none;
    border-radius: 50px;
    font-weight: 600;
    transition: all 0.3s ease;
}

.btn-ai:hover {
    transform: scale(1.05);
    box-shadow: 0 10px 20px rgba(37, 99, 235, 0.2);
}

.ai-footer {
    text-align: center;
    margin-top: 4rem;
    padding-top: 2rem;
    border-top: 1px solid #e5e7eb;
    color: #64748b;
}

@media (max-width: 768px) {
    .ai-hero h1 {
        font-size: 2.5rem;
    }
    
    .ai-hero p {
        font-size: 1.2rem;
    }
}
</style>

<div class="ai-hero">
    <h1>Эра ИИ</h1>
    <p>Трансформация технологий, мышления и человеческого потенциала</p>
</div>

<div class="ai-grid">
    <div class="ai-card">
        <div class="ai-icon">🤖</div>
        <h3>Что такое ИИ?</h3>
        <p>Искусственный интеллект — это область компьютерных наук, занимающаяся созданием машин, способных выполнять задачи, требующие человеческого интеллекта: обучение, решение проблем и распознавание образов.</p>
    </div>

    <div class="ai-card">
        <div class="ai-icon">🚀</div>
        <h3>Применение</h3>
        <p>От голосовых помощников до медицинской диагностики, ИИ революционизирует каждую отрасль. Машинное обучение позволяет системам совершенствоваться на основе данных без явного программирования.</p>
    </div>

    <div class="ai-card">
        <div class="ai-icon">⚖️</div>
        <h3>Этика и Будущее</h3>
        <p>С развитием ИИ возникают важные вопросы этики, приватности и безопасности. Ответственное развитие ИИ требует баланса между инновациями и человеческими ценностями.</p>
    </div>
</div>

<div class="ai-cta">
    <h2>Изучайте будущее вместе с нами</h2>
    <p>Присоединяйтесь к исследованию возможностей искусственного интеллекта и его влияния на наше общество.</p>
    <a href="https://github.com" class="btn-ai">Исследовать проекты</a>
</div>

<div class="ai-footer">
    <p>© 2024 Эра Искусственного Интеллекта. Все права защищены.</p>
    <p>Сделано с помощью ИИ и человеческого разума</p>
</div>
