<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HANAMANT POTARADDI | Cybersecurity Professional</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@300;400;500&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: #0a0a0a;
            color: #00ff00;
            font-family: 'Source Code Pro', monospace;
            line-height: 1.6;
            padding: 20px;
            overflow-x: hidden;
            position: relative;
        }
        
        body::before {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: repeating-linear-gradient(
                0deg,
                rgba(0, 255, 0, 0.05),
                rgba(0, 255, 0, 0.05) 1px,
                transparent 1px,
                transparent 2px
            );
            pointer-events: none;
            z-index: 1000;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            position: relative;
            z-index: 1;
        }
        
        .terminal {
            border: 1px solid #00ff00;
            border-radius: 5px;
            padding: 20px;
            box-shadow: 0 0 15px rgba(0, 255, 0, 0.3);
            margin-bottom: 20px;
            position: relative;
            overflow: hidden;
        }
        
        .terminal::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(transparent 50%, rgba(0, 255, 0, 0.03) 50%);
            background-size: 100% 4px;
            z-index: -1;
        }
        
        .blinking-cursor {
            animation: blink 1s infinite;
            color: #00ff00;
        }
        
        @keyframes blink {
            0%, 50% { opacity: 1; }
            51%, 100% { opacity: 0; }
        }
        
        .header {
            text-align: center;
            margin-bottom: 30px;
            position: relative;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-shadow: 0 0 10px rgba(0, 255, 0, 0.7);
            letter-spacing: 2px;
        }
        
        .header p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin-bottom: 20px;
        }
        
        .contact-info a {
            color: #00ff00;
            text-decoration: none;
            transition: all 0.3s;
        }
        
        .contact-info a:hover {
            text-shadow: 0 0 8px rgba(0, 255, 0, 0.9);
        }
        
        .section {
            margin-bottom: 30px;
        }
        
        .section-title {
            font-size: 1.5rem;
            margin-bottom: 15px;
            border-bottom: 1px solid #00ff00;
            padding-bottom: 5px;
            display: inline-block;
        }
        
        .content {
            padding-left: 20px;
        }
        
        .content p {
            margin-bottom: 10px;
        }
        
        .content ul {
            list-style-type: none;
            padding-left: 20px;
        }
        
        .content li {
            margin-bottom: 8px;
            position: relative;
        }
        
        .content li::before {
            content: "> ";
            color: #00ff00;
            position: absolute;
            left: -15px;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 15px;
        }
        
        .skill-category {
            margin-bottom: 15px;
        }
        
        .skill-category h4 {
            margin-bottom: 8px;
            color: #00cc00;
        }
        
        .glitch {
            position: relative;
            display: inline-block;
        }
        
        .glitch::before, .glitch::after {
            content: attr(data-text);
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        
        .glitch::before {
            left: 2px;
            text-shadow: -2px 0 #ff00ff;
            clip: rect(44px, 450px, 56px, 0);
            animation: glitch-anim 5s infinite linear alternate-reverse;
        }
        
        .glitch::after {
            left: -2px;
            text-shadow: -2px 0 #00ffff;
            clip: rect(44px, 450px, 56px, 0);
            animation: glitch-anim2 5s infinite linear alternate-reverse;
        }
        
        @keyframes glitch-anim {
            0% { clip: rect(42px, 9999px, 44px, 0); }
            5% { clip: rect(12px, 9999px, 59px, 0); }
            10% { clip: rect(48px, 9999px, 29px, 0); }
            15% { clip: rect(42px, 9999px, 73px, 0); }
            20% { clip: rect(63px, 9999px, 27px, 0); }
            25% { clip: rect(34px, 9999px, 55px, 0); }
            30% { clip: rect(86px, 9999px, 73px, 0); }
            35% { clip: rect(20px, 9999px, 20px, 0); }
            40% { clip: rect(26px, 9999px, 60px, 0); }
            45% { clip: rect(25px, 9999px, 66px, 0); }
            50% { clip: rect(57px, 9999px, 98px, 0); }
            55% { clip: rect(5px, 9999px, 46px, 0); }
            60% { clip: rect(82px, 9999px, 31px, 0); }
            65% { clip: rect(54px, 9999px, 27px, 0); }
            70% { clip: rect(28px, 9999px, 99px, 0); }
            75% { clip: rect(45px, 9999px, 69px, 0); }
            80% { clip: rect(23px, 9999px, 85px, 0); }
            85% { clip: rect(54px, 9999px, 84px, 0); }
            90% { clip: rect(45px, 9999px, 47px, 0); }
            95% { clip: rect(37px, 9999px, 20px, 0); }
            100% { clip: rect(4px, 9999px, 91px, 0); }
        }
        
        @keyframes glitch-anim2 {
            0% { clip: rect(65px, 9999px, 100px, 0); }
            5% { clip: rect(52px, 9999px, 74px, 0); }
            10% { clip: rect(79px, 9999px, 85px, 0); }
            15% { clip: rect(75px, 9999px, 5px, 0); }
            20% { clip: rect(67px, 9999px, 61px, 0); }
            25% { clip: rect(14px, 9999px, 79px, 0); }
            30% { clip: rect(1px, 9999px, 66px, 0); }
            35% { clip: rect(86px, 9999px, 30px, 0); }
            40% { clip: rect(23px, 9999px, 98px, 0); }
            45% { clip: rect(85px, 9999px, 72px, 0); }
            50% { clip: rect(71px, 9999px, 75px, 0); }
            55% { clip: rect(2px, 9999px, 48px, 0); }
            60% { clip: rect(30px, 9999px, 16px, 0); }
            65% { clip: rect(59px, 9999px, 50px, 0); }
            70% { clip: rect(41px, 9999px, 62px, 0); }
            75% { clip: rect(2px, 9999px, 82px, 0); }
            80% { clip: rect(47px, 9999px, 73px, 0); }
            85% { clip: rect(3px, 9999px, 27px, 0); }
            90% { clip: rect(26px, 9999px, 55px, 0); }
            95% { clip: rect(42px, 9999px, 97px, 0); }
            100% { clip: rect(38px, 9999px, 49px, 0); }
        }
        
        .scanline {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 2px;
            background: rgba(0, 255, 0, 0.7);
            box-shadow: 0 0 10px rgba(0, 255, 0, 0.9);
            z-index: 999;
            animation: scan 8s linear infinite;
        }
        
        @keyframes scan {
            0% { top: 0%; }
            100% { top: 100%; }
        }
        
        .matrix-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.1;
        }
        
        @media (max-width: 768px) {
            .header h1 {
                font-size: 1.8rem;
            }
            
            .contact-info {
                flex-direction: column;
                align-items: center;
            }
            
            .skills-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="scanline"></div>
    <canvas class="matrix-bg" id="matrix"></canvas>
    
    <div class="container">
        <div class="terminal">
            <div class="header">
                <h1 class="glitch" data-text="HANAMANT POTARADDI">HANAMANT POTARADDI</h1>
                <p>🛡️ Cybersecurity Professional | 🔍 Security Operations Analyst</p>
                <p>📍 Bengaluru, Karnataka, India</p>
                
                <div class="contact-info">
                    <a href="tel:+919632218368">📞 +91-96322-18368</a>
                    <a href="mailto:hanamantipotaraddi360@gmail.com">📧 hanamantipotaraddi360@gmail.com</a>
                    <a href="https://linkedin.com/in/hanamantipotaraddi24" target="_blank">💼 linkedin.com/in/hanamantipotaraddi24</a>
                    <a href="https://github.com/HanamantPotaraddi" target="_blank">🐱 github.com/HanamantPotaraddi</a>
                    <a href="https://tryhackme.com/p/hanamantipotarad27" target="_blank">🔴 tryhackme.com/p/hanamantipotarad27</a>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">💻 SYSTEM SUMMARY</h2>
                <div class="content">
                    <p><span class="blinking-cursor">_</span></p>
                    <p>Entry-Level Cybersecurity Professional and SOC Analyst, CEH Master (v13 + AI) and CEH Practical certified, with hands-on experience in security monitoring, incident response, vulnerability assessment, and threat detection.</p>
                    <p>Skilled in SIEM tools (Splunk, QRadar), MITRE ATT&CK mapping, and dedicated to strengthening enterprise security posture and responding effectively to evolving cyber threats.</p>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">🎓 EDUCATION</h2>
                <div class="content">
                    <p><strong>Bachelor of Computer Applications | 2021-2025 | CGPA: 7.32</strong></p>
                    <p>Shri S.R. Kanthi Degree College, Mudhol</p>
                    <p><strong>Pre-University Course (PUC) | 2019-2021</strong></p>
                    <p>M.K. PU Commerce & Arts College, Mudhol</p>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">🔐 CERTIFICATIONS</h2>
                <div class="content">
                    <ul>
                        <li>EC-Council Certified Ethical Hacker (CEHv13) Master</li>
                        <li>EC-Council Certified Ethical Hacker (CEHv13) Practical</li>
                        <li>EC-Council Certified Ethical Hacker (CEHv13)</li>
                        <li>Hacker School Certified Cyber Security Professional (HSCCSP) – Jul 2025</li>
                    </ul>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">💼 EXPERIENCE</h2>
                <div class="content">
                    <p><strong>Cybersecurity Intern (CSP + SOC) — Hacker School (Cartel Software Pvt. Ltd.)</strong></p>
                    <p>January 2025 - July 2025</p>
                    <ul>
                        <li>Completed hands-on internship covering Network Security, Vulnerability Management, Penetration Testing, and Security Operations using Splunk and IBM QRadar.</li>
                        <li>Gained practical experience in Linux Administration, Active Directory Pentesting, Web & Mobile Application Security, and Threat Intelligence.</li>
                        <li>Conducted Network and Web Application VAPT, analyzed firewall/IDS logs, and implemented incident response workflows.</li>
                        <li>Worked with Cryptography, Wi-Fi Security, and Cloud Security aligned with CEH exam objectives and enterprise security standards.</li>
                        <li>Developed Python and Bash scripts to automate log analysis, alert triage, and vulnerability scanning tasks.</li>
                        <li>Strengthened SOC-level skills in monitoring, detection, and mitigation of cyber threats following NIST and ISO 27001 frameworks.</li>
                    </ul>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">🛠️ TECHNICAL SKILLS</h2>
                <div class="content">
                    <div class="skills-grid">
                        <div class="skill-category">
                            <h4>🔍 Cybersecurity & Network Security</h4>
                            <p>Vulnerability Assessment, Penetration Testing (Web, Network, and AD), Threat Analysis, and Incident Response using tools like Burp Suite, Metasploit, Nmap, Nessus, Wireshark, and Nikto.</p>
                        </div>
                        
                        <div class="skill-category">
                            <h4>💻 Operating Systems & Administration</h4>
                            <p>Proficient in Linux system administration, file permissions, user/group management, process control, and command-line operations.</p>
                        </div>
                        
                        <div class="skill-category">
                            <h4>📊 Security Operations & Monitoring</h4>
                            <p>Hands-on with SIEM tools (IBM QRadar, Splunk) for log/flow analysis, offense management, and alert generation.</p>
                        </div>
                        
                        <div class="skill-category">
                            <h4>🌐 Web & Application Security</h4>
                            <p>Knowledge of OWASP Top 10, authentication bypass, SQLi, XSS, and file inclusion testing using tools such as OWASP ZAP, sqlmap, and waTw00f.</p>
                        </div>
                        
                        <div class="skill-category">
                            <h4>🔒 Cryptography & Compliance</h4>
                            <p>Understanding of encryption algorithms, SSL/TLS, hashing, and standards like ISO 27001, GDPR, HIPAA, and PCI-DSS for risk governance.</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">🚀 PROJECTS</h2>
                <div class="content">
                    <ul>
                        <li><strong>Advanced Penetration Testing (CEH Master):</strong> Executed end-to-end penetration testing and VAPT across network and web applications; identified critical vulnerabilities and delivered actionable remediation plans.</li>
                        <li><strong>Security Operations & Monitoring:</strong> Configured and monitored security events in IBM QRadar and Splunk, analyzing logs to detect anomalies, brute-force attempts, phishing, and insider threats.</li>
                        <li><strong>Incident Investigation & Correlation:</strong> Performed incident investigations by correlating alerts, identifying Indicators of Compromise (IOCs), and escalating verified incidents for remediation.</li>
                        <li><strong>Practicing Capture The Flag (CTF):</strong> Engaged in CTF challenges on TryHackMe to strengthen hands-on skills in SOC analysis, incident response, and threat detection.</li>
                    </ul>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">🔗 CONNECTIONS</h2>
                <div class="content">
                    <p>System ready for secure connections...</p>
                    <p>> Establishing encrypted channel...</p>
                    <p>> Connection established with GitHub</p>
                    <p>> Connection established with LinkedIn</p>
                    <p>> Connection established with TryHackMe</p>
                    <p class="blinking-cursor">_</p>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Matrix background effect
        const canvas = document.getElementById('matrix');
        const ctx = canvas.getContext('2d');
        
        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;
        
        const chars = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789$#@%&*()[]{}';
        const charArray = chars.split('');
        const fontSize = 14;
        const columns = canvas.width / fontSize;
        const drops = [];
        
        for (let x = 0; x < columns; x++) {
            drops[x] = 1;
        }
        
        function drawMatrix() {
            ctx.fillStyle = 'rgba(0, 0, 0, 0.04)';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            
            ctx.fillStyle = '#00ff00';
            ctx.font = fontSize + 'px monospace';
            
            for (let i = 0; i < drops.length; i++) {
                const text = charArray[Math.floor(Math.random() * charArray.length)];
                ctx.fillText(text, i * fontSize, drops[i] * fontSize);
                
                if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
                    drops[i] = 0;
                }
                
                drops[i]++;
            }
        }
        
        setInterval(drawMatrix, 35);
        
        // Handle window resize
        window.addEventListener('resize', function() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        });
        
        // Typewriter effect for summary
        document.addEventListener('DOMContentLoaded', function() {
            const summaryText = "Entry-Level Cybersecurity Professional and SOC Analyst, CEH Master (v13 + AI) and CEH Practical certified, with hands-on experience in security monitoring, incident response, vulnerability assessment, and threat detection. Skilled in SIEM tools (Splunk, QRadar), MITRE ATT&CK mapping, and dedicated to strengthening enterprise security posture and responding effectively to evolving cyber threats.";
            const summaryElement = document.querySelector('.content p:nth-child(2)');
            const cursor = document.querySelector('.blinking-cursor');
            
            let i = 0;
            summaryElement.textContent = '';
            
            function typeWriter() {
                if (i < summaryText.length) {
                    summaryElement.textContent += summaryText.charAt(i);
                    i++;
                    setTimeout(typeWriter, 20);
                } else {
                    cursor.style.display = 'inline';
                }
            }
            
            setTimeout(typeWriter, 1000);
        });
    </script>
</body>
</html>
