```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Jessie’s Job-Finding Plan – Your Perfect Part-Time Role</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        :root {
            --blue: #1E90FF;
            --green: #32CD32;
            --gray: #f4f4f4;
            --dark: #333;
        }
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background: #f9f9f9;
            color: var(--dark);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        header {
            background: linear-gradient(135deg, var(--blue), #00BFFF);
            color: white;
            padding: 30px 20px;
            text-align: center;
        }
        header h1 { margin: 0; font-size: 2.2rem; }
        header p { margin: 8px 0 0; font-size: 1.1rem; opacity: 0.9; }

        .section {
            padding: 25px;
            border-bottom: 1px solid #eee;
        }
        .section:last-child { border-bottom: none; }

        h2 {
            color: var(--blue);
            border-bottom: 3px solid var(--green);
            padding-bottom: 8px;
            margin-top: 0;
        }

        .profile-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }
        .card {
            background: var(--gray);
            padding: 15px;
            border-radius: 8px;
            font-size: 0.95rem;
        }
        .card strong { color: var(--blue); }

        table {
            width: 100%;
            border-collapse: collapse;
            margin: 15px 0;
            font-size: 0.95rem;
        }
        th {
            background: var(--blue);
            color: white;
            padding: 12px;
            text-align: left;
        }
        td {
            padding: 12px;
            border-bottom: 1px solid #ddd;
        }
        tr:nth-child(even) { background: #f9f9f9; }
        .highlight { color: var(--green); font-weight: bold; }

        .steps {
            counter-reset: step;
            padding-left: 0;
        }
        .steps li {
            list-style: none;
            margin: 18px 0;
            padding-left: 40px;
            position: relative;
        }
        .steps li::before {
            counter-increment: step;
            content: counter(step);
            position: absolute;
            left: 0;
            top: 0;
            background: var(--green);
            color: white;
            width: 28px;
            height: 28px;
            line-height: 28px;
            border-radius: 50%;
            text-align: center;
            font-weight: bold;
        }

        .resume {
            background: #f0f8ff;
            padding: 20px;
            border-radius: 8px;
            font-family: monospace;
            white-space: pre-wrap;
            margin: 15px 0;
            border: 1px dashed var(--blue);
        }

        footer {
            background: var(--dark);
            color: #ccc;
            text-align: center;
            padding: 15px;
            font-size: 0.9rem;
        }
        .btn {
            display: inline-block;
            background: var(--green);
            color: white;
            padding: 10px 18px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 10px;
        }
        @media (max-width: 600px) {
            header h1 { font-size: 1.8rem; }
            .profile-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

<div class="container">

    <!-- HEADER -->
    <header>
        <h1>Jessie’s Job-Finding Plan</h1>
        <p>Your Perfect Part-Time Role – Hands-On, Routine, $22+/hr</p>
    </header>

    <!-- PROFILE SNAPSHOT -->
    <div class="section">
        <h2>🌟 Your Quick Profile</h2>
        <div class="profile-grid">
            <div class="card"><strong>Passion</strong><br>Sorting & organising cards (Pokémon, Magic)</div>
            <div class="card"><strong>Strengths</strong><br>Follows rules • Fast prep • Completes tasks • Great work ethic</div>
            <div class="card"><strong>Work Style</strong><br>Hands-on • No tech • Routine (8/10) • Set hours</div>
            <div class="card"><strong>Goal</strong><br>Part-time • $800–$1,000+/week • $22+/hr</div>
            <div class="card"><strong>Social</strong><br>OK with 1–2 coworkers • Small talk • Customer help if needed</div>
            <div class="card"><strong>Past Wins</strong><br>Woodwork + lunchtime = calm & productive</div>
        </div>
    </div>

    <!-- TOP JOBS -->
    <div class="section">
        <h2>🎯 Top 5 Job Matches</h2>
        <table>
            <tr>
                <th>Job</th>
                <th>Why It Fits You</th>
                <th>Pay (Part-Time)</th>
                <th>Where to Apply</th>
            </tr>
            <tr>
                <td><strong>1. Card Shop Assistant</strong></td>
                <td>Sorting stock, sleeving cards, inventory – <em>your dream!</em></td>
                <td class="highlight">$25–$30/hr</td>
                <td>Good Games, Games Portal, local comic shops</td>
            </tr>
            <tr>
                <td><strong>2. Warehouse Picker</strong></td>
                <td>Scan → sort → place (like cards). Clear lists.</td>
                <td class="highlight">$26–$32/hr</td>
                <td>Australia Post, Kmart DC, Toll</td>
            </tr>
            <tr>
                <td><strong>3. Library Shelving</strong></td>
                <td>Alphabetise, sort returns – ultra-routine.</td>
                <td class="highlight">$25–$28/hr</td>
                <td>Local councils (Sydney, Brisbane, etc.)</td>
            </tr>
            <tr>
                <td><strong>4. Retail Back-of-House</strong></td>
                <td>Stock rotation, price ticketing – set tasks.</td>
                <td class="highlight">$25–$29/hr</td>
                <td>Coles/Woolworths Nightfill</td>
            </tr>
            <tr>
                <td><strong>5. Light Assembly</strong></td>
                <td>Repeat 3–5 steps – like building card decks.</td>
                <td class="highlight">$24–$30/hr</td>
                <td>Chandler Macleod, Programmed</td>
            </tr>
        </table>
        <p><strong>Best Starter:</strong> Card Shop 🚀<br><strong>Safe Backup:</strong> Warehouse or Library</p>
    </div>

    <!-- ACTION PLAN -->
    <div class="section">
        <h2>📅 7-Day Action Plan</h2>
        <ol class="steps">
            <li><strong>Day 1:</strong> Call JobAccess <strong>1800 464 800</strong> → ask for ASD-friendly DES (e.g., atWork Australia)</li>
            <li><strong>Day 2:</strong> Visit 2 local card shops with resume + card binder photos</li>
            <li><strong>Day 3:</strong> Apply online: Australia Post + Coles (use script below)</li>
            <li><strong>Day 4:</strong> Print this 1-page resume</li>
            <li><strong>Day 5:</strong> Ask card shop for a <strong>1-hour paid trial</strong></li>
            <li><strong>Day 6–7:</strong> Meet DES coach – they pay for uniform & transport!</li>
        </ol>
    </div>

    <!-- RESUME -->
    <div class="section">
        <h2>📄 Your 1-Page Resume (Copy & Print)</h2>
        <div class="resume">
JESSIE [LAST NAME]
[Phone] | [Email] | [Suburb, State]

SKILLS
• Organises card collections – sorts 500+ cards/hour  
• Follows written + shown instructions perfectly  
• Fast prep, strong work ethic, completes every task  
• Good with basic numbers, rules, and routines  
• Happy to help customers or work alone  

EXPERIENCE
Card Collection Organiser (Personal) – 5+ years  
→ Sorted, sleeved, catalogued 10,000+ cards  
→ Created systems for storage and retrieval  

Woodwork Assistant (School) – 2023  
→ Built shelves and boxes with clear plans  
→ Worked calmly, finished all tasks  

AVAILABILITY
• Part-time (20–30 hrs/week)  
• Set hours preferred  
• $22+/hour  

REFEREES
Available on request (DES Job Coach: [Name] – [Phone])
        </div>
        <a href="#" class="btn" onclick="window.print()">🖨️ Print Resume</a>
    </div>

    <!-- EMAIL SCRIPT -->
    <div class="section">
        <h2>✉️ Email to Card Shop (Copy-Paste)</h2>
        <p><strong>Subject:</strong> Keen Junior Card Organiser – Can I Help Sort Stock?</p>
        <div class="resume">
Hi [Manager’s Name],

My name is Jessie. I organise Pokémon and Magic cards for hours every day – sorting, sleeving, cataloguing.

I’d love to help in your store with:
- Sorting bulk cards  
- Stock organisation  
- Customer help (if needed)  

I work fast, follow rules, and take work seriously.  
Can I come in for a <strong>1-hour paid trial</strong> to show you?

Thanks,  
Jessie  
[Phone]
        </div>
    </div>

    <!-- SUPPORT -->
    <div class="section">
        <h2>🛠️ Free Support (Call Today!)</h2>
        <table>
            <tr><td><strong>JobAccess</strong></td><td>1800 464 800</td><td>Pays for trials, uniform, transport</td></tr>
            <tr><td><strong>atWork Australia</strong></td><td>1300 080 856</td><td>Free job coach + resume help</td></tr>
            <tr><td><strong>Specialisterne</strong></td><td>specialisterne.com.au</td><td>ASD job placements</td></tr>
        </table>
    </div>

</div>

<footer>
    <p>Made with ❤️ for Jessie – November 11, 2025 | <a href="mailto:yourhelper@email.com" style="color:#ccc;">Need help? Email me</a></p>
</footer>

</body>
</html>
```

---

**How to Use This HTML Page**

1. **Save it**: Copy all the code above → paste into a file named `jessie-job-plan.html`
2. **Open in any browser** (Chrome, Safari, Edge) – no internet needed after saving.
3. **Print or share**: Click the **🖨️ Print Resume** button or send the file via email/WhatsApp.
4. **Mobile-friendly**: Looks great on phone or tablet.

---

**Want me to**:
- Host it online (free link)?
- Add your **suburb/postcode** for local card shops?
- Turn it into a **PDF**?

Just say the word!
