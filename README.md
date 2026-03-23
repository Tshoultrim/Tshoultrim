<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tshoultrim Dorji Portfolio</title>
    <style>
        :root {
            --glass-bg: rgba(255, 255, 255, 0.03);
            --glass-border: rgba(255, 255, 255, 0.1);
            --accent-cyan: #00b4d8;
            --de-suung-orange: rgba(255, 153, 0, 0.2);
            --green-cyber: rgba(46, 204, 113, 0.2);
            --text-main: #ffffff;
            --text-dim: #8b949e;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: #0d1117;
            background-image: 
                radial-gradient(circle at 10% 20%, var(--de-suung-orange) 0%, transparent 40%),
                radial-gradient(circle at 90% 80%, var(--green-cyber) 0%, transparent 40%);
            color: var(--text-main);
            display: flex;
            justify-content: center;
            min-height: 100vh;
        }

        .container {
            width: 95%;
            max-width: 900px;
            margin: 40px 0;
            padding: 40px;
            background: var(--glass-bg);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border: 1px solid var(--glass-border);
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            text-align: center;
        }

        .banner { width: 100%; border-radius: 15px; margin-bottom: 20px; }

        .tag {
            padding: 5px 15px;
            border-radius: 50px;
            font-size: 0.85rem;
            border: 1px solid var(--glass-border);
            margin: 0 5px;
            background: rgba(255, 255, 255, 0.05);
        }

        h1 { font-size: 2.2rem; margin-bottom: 5px; }
        .subtitle { color: var(--text-dim); margin-bottom: 20px; }

        hr { border: 0; border-top: 1px solid var(--glass-border); margin: 30px 0; }

        .section { text-align: left; line-height: 1.6; }
        .section h3 { color: var(--accent-cyan); margin-bottom: 10px; }

        .tech-stack {
            display: flex;
            align-items: center;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 10px;
        }

        .cisco-badge {
            height: 48px; /* Matches the height of skillicons */
            border-radius: 10px;
        }

        footer { margin-top: 50px; color: var(--text-dim); font-size: 0.9rem; }
    </style>
</head>
<body>

    <div class="container">
        <img class="banner" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0D1117,00b4d8,0D1117&height=220&section=header&text=Tshoultrim%20Dorji&fontSize=70&animation=fadeIn&fontAlignY=38" />

        <div style="margin: 15px 0;">
            <span class="tag" style="color: #ff9900;">De-Suung (Organization)</span>
            <span class="tag" style="color: #2ecc71;">GreenCyberTech</span>
        </div>

        <h1>🔹 Data Science & AI Developer 🔹</h1>
        <div class="subtitle">BCA Data Science Student @ Chandigarh University | Volunteer 🇧🇹</div>

        <div class="section">
            <h3>📖 Professional Summary</h3>
            <p>
                I am an analytical <b>BCA student</b> focused on <b>Data Science</b>, bridging the gap between physical ICT infrastructure and modern AI. 
                With experience managing network uptime at <b>De-Suung (Organization) Headquarter</b> and deploying solutions at <b>GreenCyberTech</b>, 
                I am now mastering the <b>ML lifecycle</b> and LLM integration for data-driven automation.
            </p>
        </div>

        <hr>

        <div class="section">
            <h3>🛠 Technical Arsenal (Intermediate)</h3>
            
            <p><b>🧪 AI & Data Science</b></p>
            <div class="tech-stack">
                <img src="https://skillicons.dev/icons?i=py,sklearn,tensorflow,pytorch,mongodb,mysql,postgres,r&theme=dark" />
            </div>

            <p style="margin-top: 20px;"><b>🌐 Infrastructure & DevOps</b></p>
            <div class="tech-stack">
                <img src="https://skillicons.dev/icons?i=linux,windows&theme=dark" />
                <img src="https://img.shields.io/badge/Cisco-049fd9?style=for-the-badge&logo=cisco&logoColor=white" class="cisco-badge" alt="Cisco CCNA" />
                <img src="https://skillicons.dev/icons?i=js,react,html,css,git,github,vscode,postman&theme=dark" />
            </div>
        </div>

        <hr>

        <div class="section" style="text-align: center;">
            <h3>📊 Dynamic Insights</h3>
            <img src="https://github-readme-stats.vercel.app/api?username=tshoultrim&show_icons=true&theme=transparent&hide_border=true&title_color=00b4d8&icon_color=00b4d8&text_color=ffffff&bg_color=00000000" />
            <br>
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=tshoultrim&theme=transparent&hide_border=true&stroke=00b4d8&ring=00b4d8&fire=00b4d8&currStreakLabel=00b4d8&background=00000000" />
        </div>

        <footer>
            Built with 🤍 from the Land of the Thunder Dragon 🇧🇹
        </footer>
    </div>

</body>
</html>
