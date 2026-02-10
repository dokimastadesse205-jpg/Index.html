
<html lang="am">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>የተማሪዎች ህብረት የበጎ አድራጎት ክበብ</title>
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #1abc9c;
            --bg-color: #f4f7f6;
            --card-bg: #ffffff;
            --text-color: #333;
        }

        .dark-theme {
            --bg-color: #121212;
            --card-bg: #1e1e1e;
            --text-color: #e0e0e0;
            --primary: #000000;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            transition: 0.5s;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 60px 20px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }

        header h1 { margin: 10px 0; font-size: 1.8rem; }

        #theme-toggle {
            position: fixed;
            top: 20px;
            right: 20px;
            background: rgba(255,255,255,0.2);
            border: 1px solid white;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            cursor: pointer;
            z-index: 1000;
        }

        .container {
            max-width: 850px;
            margin: auto;
            padding: 20px;
        }

        .blog-post {
            background: var(--card-bg);
            border-radius: 15px;
            overflow: hidden;
            margin-bottom: 30px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .post-image {
            width: 100%;
            max-height: 350px;
            object-fit: cover;
        }

        .post-content { padding: 25px; }

        .project-tag {
            background: var(--secondary);
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: bold;
        }

        /* Admin List */
        .admin-list {
            list-style: none;
            padding: 0;
        }
        .admin-list li {
            background: rgba(26, 188, 156, 0.1);
            margin: 5px 0;
            padding: 10px;
            border-radius: 8px;
        }

        /* Comment Section */
        .comment-section {
            background: var(--card-bg);
            padding: 25px;
            border-radius: 15px;
            margin-top: 20px;
        }
        .comment-input {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-family: inherit;
        }
        .submit-btn {
            background: var(--secondary);
            color: white;
            padding: 10px 25px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        footer {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 40px 20px;
            margin-top: 40px;
        }

        .social-btn {
            display: inline-block;
            background: #0088cc;
            color: white;
            padding: 10px 20px;
            border-radius: 25px;
            text-decoration: none;
            margin-top: 10px;
        }

        .back-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: var(--secondary);
            color: white;
            border: none;
            border-radius: 50%;
            width: 50px;
            height: 50px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <button id="theme-toggle" onclick="toggleTheme()">🌙 Dark/Light</button>

    <header>
        <p>ሰላም✌️</p>
        <h1>𝐒𝐭𝐮𝐝𝐞𝐧𝐭𝐬 𝐔𝐧𝐢𝐨𝐧 𝐀𝐬𝐬𝐨𝐜𝐢𝐚𝐭𝐢𝐨𝐧</h1>
        <p>"To help a person, thinking and understanding like a human is enough."</p>
    </header>

    <div class="container">
        
        <article class="blog-post">
            <div class="post-content">
                <h2>እንኳን በደህና መጡ!</h2>
                <p>ይህ በተማሪዎች ህብረት የተመሰረተ የመጀመሪያው የተማሪዎች የበጎ አድራጎት ክበብ ነው። ያለ ማንም ድጋፍ በተማሪዎች አቅም ለወገኖቻችን የምንሰራው ትልቅ የትሩፋት ስራ ነው!</p>
            </div>
        </article>

        <article class="blog-post">
            <img src="https://i.ibb.co/n8NxY3d0/IMG-20260110-111452-097-2.jpg" alt="Project 1" class="post-image">
            <div class="post-content">
                <span class="project-tag">PROJECT ONE</span>
                <h2>የልበ ብሩሃን ግቢ (04)</h2>
                <p>በ04 የሚገኙ የልበ ብሩሃን ተማሪዎችን መጠየቅ እና ጊዜ ማሳለፍ። ይህ ጉዞ ለነፍሳችን ቫልዩ ያለው እና የህይወት ትምህርት የምናገኝበት ነው!</p>
                 <ul>
‎                    <li>ለነፍሳችን ትልቅ ቫልዩ እናተርፋለን</li>
‎                    <li>የህይወት ትምህርትን ከእነሱ እናገኛለን</li>
‎                    <li>ደስታቸውን እንጋራለን</li>
‎                    <li>በተማሪዎች መካከል ትውውቅ ይፈጥራል</li>
            

        <article class="blog-post">
            <img src="https://i.ibb.co/237F8v8Z/IMG-20260208-144341-725.jpg" alt="Project 2" class="post-image">
            <div class="post-content">
                <span class="project-tag">PROJECT TWO</span>
                <h2>የጎዳና ወገኖች ምሳ</h2>
                <p>በየጎዳናው ላይ ላሉ ወገኖቻችን የአንድ ቀን ምሳ በእራሳችን አዘጋጅተን ለመመገብ የተዘጋጀ አዲስ ፕሮጀክት ነው።</p>
            </div>
        </article>

        <article class="blog-post">
            <img src="https://i.ibb.co/HLsJF3KP/IMG-20260208-135236-045.jpg" alt="Project 3" class="post-image">
            <div class="post-content">
                <span class="project-tag">PROJECT THREE</span>
                <h2>የልብስ ልገሳ</h2>
                <p>ያረጁ ወይም አገልግሎት የጨረሱ ልብሶችን እና ጫማዎችን በመሰብሰብ በብርድ ለሚማቅቁ ወገኖች ማድረስ።</p>
            </div>
             <h2>👉ታዲያ ምን ምን ያስፈልጋል ?</h2>


    
‎                    <li>ሰውን ለመርዳት ዝግጁ የሆነ ልብ(ማንነት)</li>
‎                    <li>ያረጀ ፣ የጠበበ ፣ የሰፋ ወይም ለናንተ አገልግሎቱን የጨረሰ ወይም ልትጥሉት ያሰባቹትን ልብስ እና ጫማ መለገስ (መስጠት) ነው።
</li>
‎                    <li>ደስታቸውን እንጋራለን</li>
‎                    <li><p>ጥቅሙ</p> 
በብርድ ከሚማቅቁ ወገኖች መሃል ቢያንስ ህፃናትን ከአስከፊ ብርድ እና እሱን ተከትሎ ከሚመጡ ተላላፊ በሽታዎች በጥቂቱም ቢሆን እንዲከላከሉ ያስችላቸዋል!</li>
‎                
        </article>

        <article class="blog-post">
            <img src="https://i.ibb.co/8g6GTHRK/IMG-20260208-142231-135.jpg" class="post-image">
            <div class="post-content">
                <h2>የስራ ክፍፍል (አድሚኖች)</h2>
                <li><ul>በተማሪዎች ህብረት 
በውይይት እና በእጅ በልጫ መሰረት በዚህ አመት አድሚኖችን መርጠናል 
በዚህም 2 ዋና አድሚን እና 4 ረዳት አድሚኖችን መርጠናል
</ul></li>
                <h3>ዋና አድሚኖች:</h3>
                <ul class="admin-list">
                    <li>🎖 አብዱልከሪም ሰይፉ</li>
                    <li>🎖 ፀደቀ ደስታ</li>
                </ul>
                <h3>ረዳት አድሚኖች:</h3>
                <ul class="admin-list">
                    <li>🏅 ቢኒያም ኮሬ</li>
                    <li>🏅 ሳሬም ከበደ</li>
                    <li>🏅 ጂቱ ደበበ</li>
                    <li>🏅 ቡዛየው ለታ</li>
                </ul>
            </div>
        </article>

        <article class="blog-post">
            <img src="https://i.ibb.co/mCK93MPp/IMG-20260208-143730-528.jpg" class="post-image">
            <div class="post-content">
                <h2>ፋይናንሻል (CFO)</h2>
                <p><strong>አቢሲኒያ ባንክ:</strong> 16594571</p>
                <p><strong>ስም:</strong> ከድር ገበየዉ ሲርባ</p>
                <p style="color: red; font-weight: bold;">🛑 ማሳሰቢያ: የሚሰበሰበው ገንዘብ ለበጎ አድራጎት ስራ ብቻ ይውላል!</p>
            </div>
        </article>

        <div class="comment-section">
            <h3>አስተያየትዎን ያስቀምጡልን 🙏</h3>
            <form>
                <input type="text" placeholder="ስምዎ..." class="comment-input">
                <textarea rows="4" placeholder="አስተያየትዎን እዚህ ይጻፉ..." class="comment-input"></textarea>
                <button type="button" class="submit-btn" onclick="alert('አስተያየትዎ ተልኳል! እናመሰግናለን።')">አስተያየት ላክ</button>
            </form>
        </div>

        <div style="background: var(--secondary); color: white; padding: 20px; border-radius: 15px; margin-top: 30px; text-align: center;">
            <h3>Developer 👨‍💻</h3>
            <p>@Dokimass1</p>
            <p>Cofounder of Students Union 👥</p>
        </div>

    </div>

    <footer>
        <p>🙏 "To help a person, thinking and understanding like a human is enough." 🙏</p>
        <p>Shashemene, Ethiopia | 2018 E.C</p>
        <a href="https://t.me/+U7jISw9GNM40MmY0" class="social-btn">Join our Telegram</a>
    </footer>

    <button class="back-to-top" onclick="window.scrollTo({top: 0, behavior: 'smooth'})">↑</button>

    <script>
        function toggleTheme() {
            document.body.classList.toggle('dark-theme');
        }
    </script>
</body>
</html>
