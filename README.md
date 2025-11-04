<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Cybersecurity Professional</title>
    <meta name="description" content="Cybersecurity professional specializing in threat analysis, penetration testing, and security research.">
    
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@300;400;500;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- Main CSS -->
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar" id="navbar">
        <div class="nav-container">
            <div class="nav-logo">
                <a href="#home"><i class="fas fa-shield-alt"></i> CyberSec</a>
            </div>
            <ul class="nav-menu" id="nav-menu">
                <li class="nav-item">
                    <a href="#home" class="nav-link">Home</a>
                </li>
                <li class="nav-item">
                    <a href="#about" class="nav-link">About</a>
                </li>
                <li class="nav-item">
                    <a href="#projects" class="nav-link">Projects</a>
                </li>
                <li class="nav-item">
                    <a href="#skills" class="nav-link">Skills</a>
                </li>
                <li class="nav-item">
                    <a href="#experience" class="nav-link">Experience</a>
                </li>
                <li class="nav-item">
                    <a href="#contact" class="nav-link">Contact</a>
                </li>
            </ul>
            <div class="nav-toggle" id="mobile-menu">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-container">
            <div class="hero-content">
                <div class="hero-text">
                    <h1 class="hero-title">
                        <span class="typing-animation">Cybersecurity Professional</span>
                    </h1>
                    <p class="hero-subtitle">
                        Protecting digital assets through advanced threat analysis, 
                        penetration testing, and security research.
                    </p>
                    <div class="hero-buttons">
                        <a href="#projects" class="btn btn-primary">View Projects</a>
                        <a href="#contact" class="btn btn-secondary">Get In Touch</a>
                    </div>
                </div>
                <div class="hero-visual">
                    <div class="cyber-grid">
                        <div class="grid-line"></div>
                        <div class="grid-line"></div>
                        <div class="grid-line"></div>
                        <div class="grid-line"></div>
                    </div>
                    <div class="floating-icons">
                        <i class="fas fa-shield-alt"></i>
                        <i class="fas fa-lock"></i>
                        <i class="fas fa-bug"></i>
                        <i class="fas fa-search"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">About Me</h2>
                <p class="section-subtitle">Passionate about cybersecurity and digital defense</p>
            </div>
            <div class="about-content">
                <div class="about-text">
                    <p>
                        I am a dedicated cybersecurity professional with expertise in threat analysis, 
                        vulnerability assessment, and security research. My passion lies in protecting 
                        organizations from evolving cyber threats through innovative security solutions.
                    </p>
                    <div class="about-stats">
                        <div class="stat">
                            <h3>50+</h3>
                            <p>Security Projects</p>
                        </div>
                        <div class="stat">
                            <h3>3+</h3>
                            <p>Years Experience</p>
                        </div>
                        <div class="stat">
                            <h3>10+</h3>
                            <p>Certifications</p>
                        </div>
                    </div>
                </div>
                <div class="about-image">
                    <div class="image-placeholder">
                        <i class="fas fa-user-shield"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Featured Projects</h2>
                <p class="section-subtitle">Showcasing my cybersecurity work and research</p>
            </div>
            <div class="projects-grid">
                <!-- Project 1 -->
                <div class="project-card">
                    <div class="project-header">
                        <i class="fas fa-network-wired"></i>
                        <h3>Network Security Scanner</h3>
                    </div>
                    <p class="project-description">
                        Advanced network vulnerability scanner built with Python, capable of 
                        detecting security flaws and generating detailed reports.
                    </p>
                    <div class="project-tech">
                        <span class="tech-tag">Python</span>
                        <span class="tech-tag">Nmap</span>
                        <span class="tech-tag">Security</span>
                    </div>
                    <div class="project-links">
                        <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
                        <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Demo</a>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="project-card">
                    <div class="project-header">
                        <i class="fas fa-bug"></i>
                        <h3>Web App Penetration Testing</h3>
                    </div>
                    <p class="project-description">
                        Comprehensive penetration testing toolkit for web applications, 
                        including OWASP Top 10 vulnerability detection.
                    </p>
                    <div class="project-tech">
                        <span class="tech-tag">Burp Suite</span>
                        <span class="tech-tag">OWASP</span>
                        <span class="tech-tag">SQLi</span>
                    </div>
                    <div class="project-links">
                        <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
                        <a href="#" class="project-link"><i class="fas fa-file-pdf"></i> Report</a>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="project-card">
                    <div class="project-header">
                        <i class="fas fa-shield-virus"></i>
                        <h3>Malware Analysis Lab</h3>
                    </div>
                    <p class="project-description">
                        Isolated environment for malware analysis with automated detection 
                        and behavioral analysis capabilities.
                    </p>
                    <div class="project-tech">
                        <span class="tech-tag">VMware</span>
                        <span class="tech-tag">REMnux</span>
                        <span class="tech-tag">IDA Pro</span>
                    </div>
                    <div class="project-links">
                        <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
                        <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Demo</a>
                    </div>
                </div>

                <!-- Project 4 -->
                <div class="project-card">
                    <div class="project-header">
                        <i class="fas fa-database"></i>
                        <h3>Incident Response Platform</h3>
                    </div>
                    <p class="project-description">
                        Real-time incident response and threat hunting platform with 
                        automated alerting and forensic capabilities.
                    </p>
                    <div class="project-tech">
                        <span class="tech-tag">ELK Stack</span>
                        <span class="tech-tag">SIEM</span>
                        <span class="tech-tag">Forensics</span>
                    </div>
                    <div class="project-links">
                        <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
                        <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Demo</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Technical Skills</h2>
                <p class="section-subtitle">Expertise across cybersecurity domains</p>
            </div>
            <div class="skills-content">
                <div class="skills-category">
                    <h3><i class="fas fa-shield-alt"></i> Security Testing</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <span>Penetration Testing</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="90"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Vulnerability Assessment</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Web Application Security</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="88"></div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="skills-category">
                    <h3><i class="fas fa-search"></i> Threat Analysis</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <span>Malware Analysis</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="82"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Digital Forensics</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="78"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Incident Response</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85"></div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="skills-category">
                    <h3><i class="fas fa-code"></i> Programming</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <span>Python</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="92"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Bash/PowerShell</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>SQL</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="80"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Certifications -->
            <div class="certifications">
                <h3>Certifications & Training</h3>
                <div class="cert-grid">
                    <div class="cert-item">
                        <i class="fas fa-certificate"></i>
                        <span>CISSP</span>
                    </div>
                    <div class="cert-item">
                        <i class="fas fa-certificate"></i>
                        <span>CEH</span>
                    </div>
                    <div class="cert-item">
                        <i class="fas fa-certificate"></i>
                        <span>OSCP</span>
                    </div>
                    <div class="cert-item">
                        <i class="fas fa-certificate"></i>
                        <span>Security+</span>
                    </div>
                    <div class="cert-item">
                        <i class="fas fa-certificate"></i>
                        <span>GCIH</span>
                    </div>
                    <div class="cert-item">
                        <i class="fas fa-certificate"></i>
                        <span>SANS</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="experience">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Professional Experience</h2>
                <p class="section-subtitle">My cybersecurity career journey</p>
            </div>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <h3>Senior Security Analyst</h3>
                        <h4>Tech Company • 2023 - Present</h4>
                        <p>
                            Leading security assessments, managing incident response, and developing 
                            security policies for enterprise infrastructure.
                        </p>
                        <ul>
                            <li>Conducted 20+ penetration tests on web applications and networks</li>
                            <li>Reduced security incidents by 40% through proactive monitoring</li>
                            <li>Trained junior team members on security best practices</li>
                        </ul>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <h3>Cybersecurity Specialist</h3>
                        <h4>Security Firm • 2022 - 2023</h4>
                        <p>
                            Specialized in vulnerability assessments and security consulting 
                            for small to medium businesses.
                        </p>
                        <ul>
                            <li>Performed vulnerability assessments for 50+ clients</li>
                            <li>Developed custom security tools and automation scripts</li>
                            <li>Achieved 95% client satisfaction rating</li>
                        </ul>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <h3>IT Security Intern</h3>
                        <h4>Financial Institution • 2021 - 2022</h4>
                        <p>
                            Gained hands-on experience in enterprise security operations 
                            and compliance frameworks.
                        </p>
                        <ul>
                            <li>Assisted in SOX compliance audits</li>
                            <li>Monitored SIEM alerts and investigated security events</li>
                            <li>Created security awareness training materials</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Get In Touch</h2>
                <p class="section-subtitle">Let's discuss cybersecurity opportunities</p>
            </div>
            <div class="contact-content">
                <div class="contact-info">
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div>
                            <h3>Email</h3>
                            <p>your.email@example.com</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fab fa-linkedin"></i>
                        <div>
                            <h3>LinkedIn</h3>
                            <p>linkedin.com/in/yourprofile</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fab fa-github"></i>
                        <div>
                            <h3>GitHub</h3>
                            <p>github.com/yourusername</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div>
                            <h3>Location</h3>
                            <p>Your City, Country</p>
                        </div>
                    </div>
                </div>
                <div class="contact-form">
                    <form id="contact-form">
                        <div class="form-group">
                            <input type="text" id="name" name="name" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" id="email" name="email" placeholder="Your Email" required>
                        </div>
                        <div class="form-group">
                            <input type="text" id="subject" name="subject" placeholder="Subject" required>
                        </div>
                        <div class="form-group">
                            <textarea id="message" name="message" placeholder="Your Message" rows="5" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-left">
                    <p>&copy; 2025 Your Name. All rights reserved.</p>
                </div>
                <div class="footer-right">
                    <div class="social-links">
                        <a href="#" class="social-link"><i class="fab fa-github"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-linkedin"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="social-link"><i class="fas fa-envelope"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- JavaScript -->
    <script src="js/script.js"></script>
</body>
</html>
