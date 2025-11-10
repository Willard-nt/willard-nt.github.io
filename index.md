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
                    <h3>Music Streaming ETL Pipeline</h3>
                    <p>Implements a data pipeline using Apache Airflow to orchestrate ETL operations from Amazon S3 to Amazon Redshift.</p>
                    <div class="tags">
                        <span class="tag">Airflow 3</span>
                        <span class="tag">AWS</span>
                        <span class="tag">Python</span>
                    </div>
                    <a href="https://github.com/Willard-nt/Music-Streaming-ETL-Pipeline" target="_blank" style="color: #667eea; text-decoration: none; display: inline-block; margin-top: 1rem; font-weight: 600; transition: all 0.3s;">
                        View on GitHub →
                    </a>
                </div>
                <div class="card">
                    <h3>IoT Data Lakehouse</h3>
                    <p>Presents an AWS-based lakehouse architecture for a human step trainer manufacturer, ingesting and transforming IoT and customer data for machine learning.</p>
                    <div class="tags">
                        <span class="tag">Python</span>
                        <span class="tag">AWS</span>
                        <span class="tag">Apache Spark</span>
                    </div>
                    <a href="https://github.com/Willard-nt/IoT-Data-Lakehouse" target="_blank" style="color: #667eea; text-decoration: none; display: inline-block; margin-top: 1rem; font-weight: 600; transition: all 0.3s;">
                        View on GitHub →
                    </a>
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
                Feel free to reach out! Check out my resume by clicking the button below.
            </p>
            <div class="cta-buttons">
                <a href="mailto:{{ willardnixoniii@gmail.com }}" class="btn btn-primary">Send Email</a>
                <a href="{{ site.baseurl }}/assets/DE_Resume.pdf" class="btn btn-secondary" target="_blank">View Resume</a>
            </div>
        </div>
    </div>
</section>
