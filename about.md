---
layout: default
title: About
permalink: /about/
---

<div class="hero-section" style="padding: 40px 0; background: var(--background-color); border-bottom: 1px solid var(--border-color); text-align: center;">
    <div class="container">
        <h1 style="font-size: var(--font-size-3xl); letter-spacing: -0.02em; color: var(--text-primary);">About</h1>
        <p style="color: var(--text-secondary); opacity: 0.7; max-width: 600px; margin: 0 auto; font-weight: 300;">Information regarding Jacob and this Portfolio</p>
    </div>
</div>

<div class="about-content">
    <div class="container">
        
        <section class="about-section">
            <h2>Who is Jacob?</h2>
            <p>I grew up in Austin, Texas, and I'm now a sophomore studying engineering at Texas A&M University, College Station. My major is Multidisciplinary Engineering Technology (MXET), Mechatronics track, with a minor in Embedded Systems, and set to graduate in May 2029.</p>
            <p>I'd describe myself as someone who learns best by doing rather than reading about something first. If I don't know how to do something, my instinct is usually to just start figuring it out instead of waiting around for someone to teach me. I'm comfortable stepping up and organizing something when I see it needs to happen. I also genuinely like helping other people learn things, whether that means mentoring someone newer or just explaining something I happen to know.</p>
            <p>I like being around school, work, hobbies, and people who push me to figure something out or get better at whatever I'm doing. There's usually something new I want to try, some skill I haven't picked up yet, or some problem I haven't solved that keeps me going. I don't get bored easily because there's always another thing worth mastering, which has left me where I am today.</p>
        </section>

        <section class="about-section">
            <h2>Connect</h2>
            <p>Connect with me on the following platforms:</p>
        
            <div class="cta-buttons">
                </a>
                <a href="mailto:jacobgintx@gmail.com" class="btn-primary">
                    <i class="fas fa-envelope"></i> Email
                </a>
                <a href="www.linkedin.com/in/jacob-gaines-b57405341" class="btn-linkedin" target="_blank">
                    <i class="fas fa-linkedin"></i> LinkedIn
                </a>
                <a href="https://github.com/JacobGainesMXET" class="btn-primary" target="_blank">
                    <i class="fab fa-github"></i> GitHub
                </a>
            </div>
        </section>

        <section class="about-section">
            <h2>Built With</h2>
            <div class="tech-stack">
                <div class="tech-item">
                    <i class="fab fa-html5"></i>
                    <span>HTML5</span>
                </div>
                <div class="tech-item">
                    <i class="fab fa-css3-alt"></i>
                    <span>CSS3/SCSS</span>
                </div>
                <div class="tech-item">
                    <i class="fab fa-js-square"></i>
                    <span>JavaScript</span>
                </div>
                <div class="tech-item">
                    <i class="fas fa-gem"></i>
                    <span>Jekyll</span>
                </div>
                <div class="tech-item">
                    <i class="fas fa-cube"></i>
                    <span>Three.js</span>
                </div>
                <div class="tech-item">
                    <i class="fab fa-github"></i>
                    <span>GitHub Pages</span>
                </div>
            </div>
        </section>

    </div>
</div>

<style>
.about-content {
    padding: var(--spacing-2xl) 0;
}

.about-section {
    margin-bottom: var(--spacing-3xl);
}

.about-section h2 {
    color: var(--text-primary);
    margin-bottom: var(--spacing-lg);
    padding-bottom: var(--spacing-sm);
    border-bottom: 1px solid var(--border-color);
    font-size: var(--font-size-2xl);
    letter-spacing: -0.01em;
}

.features-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: var(--spacing-xl);
    margin-top: var(--spacing-lg);
}

.feature-item {
    padding: var(--spacing-lg);
    background-color: var(--surface-color);
    border-radius: var(--radius-sm);
    border: none;
    box-shadow: 0 4px 20px var(--shadow-color);
    transition: transform var(--transition-normal), box-shadow var(--transition-normal);
}

.feature-item:hover {
    transform: translateY(-4px);
    box-shadow: 0 12px 30px var(--shadow-hover);
}

.feature-item h3 {
    display: flex;
    align-items: center;
    gap: var(--spacing-sm);
    color: var(--text-primary);
    margin-bottom: var(--spacing-md);
}

.feature-item h3 i {
    color: var(--primary-color);
    font-size: var(--font-size-lg);
}

.perfect-for-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: var(--spacing-lg);
    margin-top: var(--spacing-lg);
}

.perfect-for-item {
    text-align: center;
    padding: var(--spacing-lg);
    background-color: var(--surface-color);
    border-radius: var(--radius-lg);
    border: 1px solid var(--border-color);
}

.perfect-for-item h4 {
    color: var(--primary-color);
    margin-bottom: var(--spacing-sm);
}

.tech-stack {
    display: flex;
    flex-wrap: wrap;
    gap: var(--spacing-lg);
    justify-content: center;
    margin-top: var(--spacing-lg);
}

.tech-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: var(--spacing-sm);
    padding: var(--spacing-lg);
    background-color: var(--surface-color);
    border-radius: var(--radius-lg);
    border: 1px solid var(--border-color);
    min-width: 120px;
}

.tech-item i {
    font-size: var(--font-size-2xl);
    color: var(--accent-color);
}

.tech-item span {
    font-weight: var(--font-weight-medium);
    color: var(--text-primary);
}

.getting-started-steps {
    background-color: var(--surface-color);
    padding: var(--spacing-xl);
    border-radius: var(--radius-lg);
    border: 1px solid var(--border-color);
    margin: var(--spacing-lg) 0;
}

.getting-started-steps li {
    margin-bottom: var(--spacing-md);
    line-height: var(--line-height-relaxed);
}

.cta-buttons {
    display: flex;
    gap: var(--spacing-md);
    justify-content: center;
    flex-wrap: wrap;
    margin-top: var(--spacing-xl);
}

@media (max-width: 640px) {
    .features-list {
        grid-template-columns: 1fr;
    }
    
    .perfect-for-grid {
        grid-template-columns: 1fr;
    }
    
    .tech-stack {
        justify-content: center;
    }
    
    .cta-buttons {
        flex-direction: column;
        align-items: center;
    }
}
</style>
