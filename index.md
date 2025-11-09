---
layout: default
title: Home
---

<section id="home">
    <div class="container">
        <div class="hero">
            <h1>Hi, I'm {{ site.title }}</h1>
            <div class="subtitle">Data Engineer & Creative Problem Solver</div>
            <p>I’m a data engineer passionate about building scalable data pipelines, optimizing data workflows, and enabling data-driven decision-making. I specialize in.</p>
            <div class="cta-buttons">
                <a href="#projects" class="btn btn-primary">View My Work</a>
                <a href="#contact" class="btn btn-secondary">Get In Touch</a>
            </div>
        </div>
    </div>
</section>

<section id="about">
    <div class="container">
        <div class="content-box">
            <h2>About Me</h2>
            <p class="about-text">
                I'm
            </p>
        </div>
    </div>
</section>

<section id="projects">
    <div class="container">
        <div class="content-box">
            <h2>Featured Projects</h2>
            <div class="grid grid-3">
                <div class="card">
                    <h3>Project One</h3>
                    <p>A modern web application built with cutting-edge technologies. Features real-time updates and seamless user experience.</p>
                    <div class="tags">
                        <span class="tag">React</span>
                        <span class="tag">Node.js</span>
                        <span class="tag">MongoDB</span>
                    </div>
                </div>
                <div class="card">
                    <h3>Project Two</h3>
                    <p>An innovative solution for data visualization with interactive charts and comprehensive analytics dashboard.</p>
                    <div class="tags">
                        <span class="tag">Python</span>
                        <span class="tag">D3.js</span>
                        <span class="tag">PostgreSQL</span>
                    </div>
                </div>
                <div class="card">
                    <h3>Project Three</h3>
                    <p>A mobile-first progressive web app with offline capabilities and push notifications for enhanced engagement.</p>
                    <div class="tags">
                        <span class="tag">Vue.js</span>
                        <span class="tag">Firebase</span>
                        <span class="tag">PWA</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="skills">
    <div class="container">
        <div class="content-box">
            <h2>Skills & Technologies</h2>
            <div class="grid grid-4">
                <div class="skill-card">Python</div>
                <div class="skill-card">Git</div>
                <div class="skill-card">Docker</div>
                <div class="skill-card">AWS</div>
            </div>
        </div>
    </div>
</section>

<section id="contact">
    <div class="container">
        <div class="content-box">
            <h2>Get In Touch</h2>
            <p class="contact-text">
                I'm always open to new opportunities and collaborations. Feel free to reach out!
            </p>
            <div class="cta-buttons">
                <a href="mailto:{{ site.email }}" class="btn btn-primary">Send Email</a>
                <a href="https://github.com/{{ site.github_username }}" class="btn btn-secondary" target="_blank">View GitHub</a>
            </div>
        </div>
    </div>
</section>
