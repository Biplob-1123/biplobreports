:root{
  --bg:#fff;
  --text:#111;
  --muted:#666;
  --line:#e8e8e8;
  --max:1100px;
}

*{ box-sizing:border-box; }
body{
  margin:0;
  background:var(--bg);
  color:var(--text);
  font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
}
a{ color:inherit; text-decoration:none; }
a:hover{ text-decoration:underline; }

.topbar{
  position:sticky;
  top:0;
  z-index:10;
  background:rgba(255,255,255,0.92);
  backdrop-filter: blur(8px);
  border-bottom:1px solid var(--line);
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:14px 18px;
}
.logo{
  font-weight:900;
  letter-spacing:0.1em;
  text-transform:uppercase;
}
.nav a{
  margin-left:14px;
  font-size:14px;
  color:var(--muted);
}
.nav a:hover{ color:var(--text); }

.wrap{
  max-width:var(--max);
  margin:0 auto;
  padding:20px 18px 40px;
}

.hero{
  padding:26px 0 18px;
  border-bottom:1px solid var(--line);
}
.kicker{
  margin:0 0 8px 0;
  font-size:12px;
  letter-spacing:0.14em;
  text-transform:uppercase;
  color:var(--muted);
}
.title{
  margin:0 0 10px 0;
  font-size:46px;
  line-height:1.05;
}
.deck{
  margin:0 0 12px 0;
  font-size:18px;
  line-height:1.6;
  color:var(--muted);
  max-width:70ch;
}
.links{
  font-size:14px;
  color:var(--muted);
}
.dot{ margin:0 8px; }

.work{ padding-top:18px; }

.grid{
  display:grid;
  grid-template-columns: repeat(3, 1fr);
  gap:16px;
}

.card{
  border:1px solid var(--line);
  border-radius:16px;
  overflow:hidden;
  background:#fff;
}
.card a{
  display:block;
  padding:16px;
}
.pub{
  margin:0 0 8px 0;
  font-size:12px;
  letter-spacing:0.12em;
  text-transform:uppercase;
  color:var(--muted);
}
.headline{
  margin:0 0 10px 0;
  font-size:18px;
  line-height:1.25;
}
.meta{
  margin:0;
  font-size:13px;
  color:var(--muted);
}

.simple{
  margin-top:30px;
  padding-top:18px;
  border-top:1px solid var(--line);
}
.simple h2{
  margin:0 0 10px 0;
  font-size:18px;
  letter-spacing:0.02em;
}
.simple p{
  margin:0;
  color:var(--muted);
  line-height:1.7;
  max-width:75ch;
}

.footer{
  border-top:1px solid var(--line);
  color:var(--muted);
  text-align:center;
  padding:18px;
}

/* Responsive */
@media (max-width: 980px){
  .grid{ grid-template-columns: 1fr; }
  .title{ font-size:38px; }
  .nav{ display:none; }
}
