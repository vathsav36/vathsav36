<!doctype html>
<html lang="en">aaa
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>My Story — M. Srivathsav</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg: #f7fbff;
      --card: #ffffff;
      --muted: #5b6b7a;
      --accent: #0066cc;
      --glass: rgba(255,255,255,0.7);
    }
    *{box-sizing:border-box}
    body{font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; margin:0; background:linear-gradient(180deg,var(--bg),#eef6ff); color:#102027;}
    header{padding:40px 20px 10px; text-align:center}
    .container{max-width:880px;margin:0 auto;padding:20px}
    .card{background:var(--card);border-radius:14px;padding:26px;box-shadow:0 6px 20px rgba(16,32,48,0.08);}
    h1{font-family:'Playfair Display', serif;margin:0;font-size:28px}
    .meta{color:var(--muted);margin-top:6px;font-size:14px}
    .lead{margin-top:18px;font-size:16px;line-height:1.6;color:#19303f}
    .timeline{margin-top:22px;border-left:3px solid rgba(0,102,204,0.08);padding-left:18px}
    .entry{margin-bottom:18px;padding-left:12px;position:relative}
    .entry:before{content:'';width:12px;height:12px;border-radius:999px;background:var(--accent);position:absolute;left:-24px;top:6px;box-shadow:0 2px 6px rgba(0,102,204,0.18)}
    .entry h3{margin:0;font-size:15px;color:#08324a}
    .entry p{margin:6px 0 0;color:#123344;line-height:1.6}
    footer{margin-top:24px;text-align:center;color:var(--muted);font-size:13px}
    .controls{display:flex;gap:8px;justify-content:center;margin-top:18px}
    .btn{background:var(--accent);color:white;border:none;padding:10px 14px;border-radius:10px;cursor:pointer;font-weight:600}
    .btn.secondary{background:transparent;color:var(--accent);border:1px solid rgba(0,102,204,0.14)}
    @media (max-width:600px){.card{padding:18px}h1{font-size:22px}}
    /* small print styles for printing */
    @media print{body{background:white} .controls, header{display:none} .card{box-shadow:none;border-radius:0}}
  </style>
</head>
<body>
  <header>
    <div class="container">
      <div class="card" style="text-align:left">
        <h1>My Story — <span style="color:var(--accent)">M. Srivathsav</span></h1>
        <div class="meta">A short personal memoir — childhood, cricket &amp; dreams</div>
        <p class="lead">Below is a clean, readable web version of the story you provided. Use the buttons to copy the HTML, download it, or ask for edits (fonts, colors or layout).</p>
        <div class="controls">
          <button class="btn" id="downloadBtn">Download HTML</button>
          <button class="btn secondary" id="copyBtn">Copy Story Text</button>
        </div>
      </div>
    </div>
  </header>

  <main class="container">
    <article class="card" id="storyCard">
      <section>
        <h2 style="margin-top:0;font-size:18px">About the author</h2>
        <p class="meta">Name: M. Srivathsav — Born: May 30, 2013 — Hometown: Warangal</p>
        <p class="lead">My name is <strong>M. Srivathsav</strong>. My mother’s name is <strong>Sandhya</strong>, my father’s name is <strong>Srinivas</strong>, and my sister’s name is <strong>Praharshini</strong>. I was born on May 30, 2013, in Warangal, and I still live in Warangal.</p>
      </section>

      <div class="timeline" aria-hidden="false">
        <div class="entry">
          <h3>Childhood &amp; early goals</h3>
          <p>In my childhood, my aim from 1st class onwards was to become a scientist. But later, in 4th class, my aim changed — I wanted to become a software engineer.</p>
        </div>

        <div class="entry">
          <h3>Discovering cricket (2022)</h3>
          <p>One day in 2022, I watched the IPL for the first time. Before that, I didn’t even know what cricket was. That year, I watched cricket with very little interest — I just watched it because I wanted to skip sleeping. I only watched a few matches.</p>
        </div>

        <div class="entry">
          <h3>Becoming a Virat Kohli fan (2023)</h3>
          <p>My father is a huge cricket fan, and later, in 2023, during the World Cup, I watched Virat Kohli’s batting for the first time. I was amazed and became a huge fan. From that moment, I decided to be as great as Virat Kohli.</p>
        </div>

        <div class="entry">
          <h3>Growing interest &amp; practice</h3>
          <p>I started watching every match of Virat Kohli and supporting him in every game. In the 2024 IPL, I supported RCB very much, but unfortunately, RCB didn’t win the title. However, from that, I learned a lot about cricket. I stopped everything else and fully concentrated on cricket.</p>
        </div>

        <div class="entry">
          <h3>Coaching &amp; first experiences</h3>
          <p>At that time, I was in 6th class. Then I watched the T20 World Cup, which was the best one ever. Virat Kohli’s form was not so good, but in the final, he scored 76 runs. Every run he scored inspired me and boosted me. Because of Virat Kohli, my interest in cricket started. I began practicing cricket daily.</p>
        </div>

        <div class="entry">
          <h3>Joining coaching</h3>
          <p>My parents saw my interest in cricket. I asked them to send me to coaching. After a few days, finally, I went for it — in November ending. On my first day of coaching, I did bowling. I was a left-hand fast bowler, which I had practiced at home. But my sir said that I should change to a spinner. He said that left-arm spinners are rare and very effective. So I turned into a left-arm spinner on the first day itself.</p>
        </div>

        <div class="entry">
          <h3>Kit &amp; ups and downs</h3>
          <p>After that, my father bought me a kit — an SG brand kit — from Hyderabad, which is far from us. We went there because my sister had her college admission at Nine Education, and after her admission, we bought the SG kit. On the first day using my new kit, my batting was poor. It continued for about one month. On January 25, I stopped going to coaching. My father discouraged me, and my coach also said, “Try bowling — you are a bowler, not a batter.”</p>
        </div>

        <div class="entry">
          <h3>Fitness &amp; return</h3>
          <p>After that, I started running on the ground for fitness. My father told me to concentrate on my fitness. After many days, I returned to the same coaching center during the summer holidays. I don’t know what happened, but my batting style had changed. I removed my fear and started playing a famous shot inspired by Virat Kohli — the flick shot. I tried it, and it was a super shot! I became a pro on the leg side, and my bowling also improved. Bowling was no longer a problem for me. During the summer, my batting became excellent.</p>
        </div>

        <div class="entry">
          <h3>Matches at Thimmapur Ground</h3>
          <p>My first match was at Thimmapur Ground, a T20 match. I was the second youngest in my team as well as in the other team. I batted in the last (18th) over and scored 3 runs from 7 balls. Even though it wasn’t much, everyone encouraged me because I was young — and some elder players even scored less than me, like duck outs.</p>
        </div>

        <div class="entry">
          <h3>Later matches</h3>
          <p>In the second innings, unfortunately, we lost the match in the last over. I bowled the 15th over, and though the match finished, it was no problem for me. My second match (Under-14) was also at Thimmapur. In the first innings, our team bowled, and I bowled 4 overs with 0 wickets, but I stopped runs well. In the second innings, I batted at one-down and scored 0.</p>
        </div>

        <div class="entry">
          <h3>Upset &amp; comeback</h3>
          <p>In my third match, I practiced well before the game, but it turned out to be my worst match. We batted first — I went three down and scored 3 runs from 27 balls. Everyone shouted at me — even my coach and dad. My dad discouraged me, and I cried. In the second innings, I bowled 1 over, but it was terrible — I bowled about 5 wides, and the fair deliveries also went for fours, with only one dot ball. After that, my coach told me to sit and not field. I sat there the whole time. That was the worst match ever — but at last, our team won. I didn’t celebrate. After going home, my dad scolded me and even my mother.</p>
        </div>

        <div class="entry">
          <h3>Argument &amp; controversy</h3>
          <p>The next day, there was another match. I batted at 4 down and scored 2 runs from 4 balls, but I got out by outside edge (keeper catch). That was not out, but my bad luck — the umpire gave me out. I argued with the umpire because it was a false decision (match fixing), and everyone in our team agreed that I was not out. <em>continues...</em></p>
        </div>
      </div>

      <footer>
        <p>Story created by <strong>M. Srivathsav</strong>. Want edits? Change colors, add images or convert to printable PDF — ask me.</p>
      </footer>
    </article>
  </main>

  <script>
    // Copy story text to clipboard
    document.getElementById('copyBtn').addEventListener('click', async function(){
      const text = Array.from(document.querySelectorAll('#storyCard p, #storyCard h2, #storyCard h3')).map(n=>n.innerText).join('\n\n');
      try{ await navigator.clipboard.writeText(text); this.innerText='Copied!'; setTimeout(()=>this.innerText='Copy Story Text',1500);}catch(e){alert('Could not copy. You can select the story text and copy manually.');}
    });

    // Download HTML source as file
    document.getElementById('downloadBtn').addEventListener('click', function(){
      const html = `<!doctype html>\n${document.documentElement.outerHTML}`;
      const blob = new Blob([html],{type:'text/html'});
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url; a.download = 'my-story-m-srivathsav.html';
      document.body.appendChild(a); a.click(); a.remove(); URL.revokeObjectURL(url);
    });
  </script>
</body>
</html>
