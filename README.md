:root{
  --bg:#fff;
  --text:#111;
  --muted:#666;
  --line:#e6e6e6;
  --max:1100px;
}

*{box-sizing:border-box}
body{
  margin:0;
  font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  color:var(--text);
  background:var(--bg);
}
a{color:inherit; text-decoration:none}
a:hover{ text-decoration:underline; }

.topbar{
  position:sticky; top:0; z-index:10;
  background:rgba(255,255,255,0.92);
  backdrop-filter: blur(8px);
  border-bottom:1px solid var(--line);
  display:flex; align-items:center; justify-content:space-between;
  padding:14px 18px;
}
.logo{
  font-weight:800;
  letter-spacing:0.08em;
  text-transform:uppercase;
}
.nav a{
  margin-left:14px;
  font-size:14px;
  color:var(--muted);
}
.nav a:hover{color:var(--text)}

.wrap{ max-width:var(--max); margin:0 auto; padding:18px; }

.front{
  display:grid;
  grid-template-columns: 2fr 1fr;
  gap:18px;
  margin-top:10px;
}

.hero{
  border:1px solid var(--line);
  border-radius:16px;
  overflow:hidden;
}
.hero-link{ display:block; }
.hero-img{ width:100%; height:320px; object-fit:cover; display:block; }
.hero-text{ padding:16px; }
.kicker{
  margin:0 0 6px 0;
  font-size:12px;
  letter-spacing:0.12em;
  color:var(--muted);
  text-transform:uppercase;
}
.hero-title{
  margin:0 0 10px 0;
  font-size:34px;
  line-height:1.1;
}
.deck{ margin:0 0 10px 0; color:var(--muted); }
.byline{ margin:0; font-size:14px; color:var(--muted); }

.rail{
  border:1px solid var(--line);
  border-radius:16px;
  padding:14px;
}
.rail-title{ margin:0 0 10px 0; font-size:16px; }
.rail-item{
  display:block;
  padding:12px 0;
  border-top:1px solid var(--line);
}
.rail-item:first-of-type{ border-top:none; padding-top:0; }
.rail-headline{ margin:4px 0 6px 0; font-weight:700; }
.rail-meta{ margin:0; font-size:13px; color:var(--muted); }

.section{ margin-top:28px; }
.section-head{
  display:flex; align-items:baseline; justify-content:space-between;
  border-top:1px solid var(--line);
  padding-top:14px;
}
.section-head h2{ margin:0; font-size:18px; letter-spacing:0.02em; }
.smalllink{ font-size:14px; color:var(--muted); }

.grid{
  margin-top:14px;
  display:grid;
  grid-template-columns: repeat(3, 1fr);
  gap:16px;
}
.card{
  border:1px solid var(--line);
  border-radius:16px;
  overflow:hidden;
}
.card a{ display:block; padding:14px; }
.thumb{
  width:100%;
  height:150px;
  border-radius:12px;
  object-fit:cover;
  display:block;
  margin-bottom:10px;
}
.placeholder{
  background:linear-gradient(90deg, #f2f2f2, #fafafa, #f2f2f2);
}
.card-title{ margin:6px 0 8px 0; font-size:18px; line-height:1.2; }
.card-deck{ margin:0 0 10px 0; color:var(--muted); }
.card-meta{ margin:0; font-size:13px; color:var(--muted); }

.topics{
  margin-top:12px;
  display:flex;
  flex-wrap:wrap;
  gap:10px;
}
.topic{
  border:1px solid var(--line);
  border-radius:999px;
  padding:8px 12px;
  font-size:14px;
  color:var(--muted);
}
.topic:hover{ color:var(--text); }

.footer{
  border-top:1px solid var(--line);
  margin-top:40px;
  padding:18px;
  color:var(--muted);
  text-align:center;
}

/* Responsive */
@media (max-width: 900px){
  .front{ grid-template-columns: 1fr; }
  .hero-img{ height:240px; }
  .grid{ grid-template-columns: 1fr; }
  .nav{ display:none; } /* simple: hide on mobile */
}
