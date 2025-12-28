:root{
  --black:#000;
  --white:#fff;
  --purple:#7b4dff;
  --muted:#333;
  --max: 1100px;

  /* Font mapping */
  --font-head: "Archivo Black", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  --font-mast: "Graduate", ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", monospace;

  /* Canva Sans is not publicly hostable by default.
     Using Inter as a temporary body substitute. */
  --font-body: "Inter", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
}

/* Base */
*{ box-sizing:border-box; }
html{ scroll-behavior:smooth; }
body{
  margin:0;
  color:var(--black);
  background:var(--white);
  font-family: var(--font-body);
}
a{ color:inherit; text-decoration:none; }

/* COVER */
.cover{ width:100%; position:relative; }
.cover-link{
  display:block;
  position:relative;
  height: 520px;
  overflow:hidden;
}
.cover-bg{
  position:absolute; inset:0;
  background-image: url("assets/cover.jpg");
  background-size: cover;
  background-position: center;
  transform: scale(1.02);
}

/* Top-left title: Graduate */
.cover-top-left{
  position:absolute;
  top:26px; left:34px;
  color:rgba(255,255,255,0.85);
  font-family: var(--font-mast);
  font-weight:400;
  font-size:30px;
  letter-spacing:0.06em;
  text-transform:uppercase;
  z-index:2;
}

.cover-text{
  position:absolute;
  left:34px;
  right:34px;
  bottom:28px;
  z-index:2;
}

/* Cover headline: Archivo Black */
.cover-headline{
  margin:0 0 10px 0;
  color:var(--white);
  text-transform:uppercase;
  font-family: var(--font-head);
  font-weight:400; /* Archivo Black only has one weight */
  font-size:46px;
  line-height:1.05;
  letter-spacing:0.01em;
  text-shadow: 0 2px 14px rgba(0,0,0,0.25);
}

/* Cover byline: body font (Canva Sans substitute) */
.cover-byline{
  margin:0;
  color: var(--purple);
  font-family: var(--font-body);
  font-weight:700;
  font-size:18px;
  text-shadow: 0 2px 14px rgba(0,0,0,0.25);
}

/* NAV BAR UNDER COVER */
.section-nav{
  display:flex;
  gap:34px;
  justify-content:center;
  align-items:center;
  padding: 18px 12px;
  border-bottom: 1px solid #e9e9e9;
  font-family: var(--font-head);
  font-weight:400;
  letter-spacing:0.02em;
  text-transform:uppercase;
}
.section-nav a{
  font-size:16px;
  padding: 6px 4px;
}
.section-nav a:hover{ text-decoration: underline; }

/* INTRO */
.intro{
  max-width: var(--max);
  margin: 0 auto;
  text-align:center;
  padding: 22px 18px 18px;
}

/* Name: Archivo Black */
.name{
  margin: 6px 0 10px;
  font-family: var(--font-head);
  font-weight:400;
  font-size:38px;
  letter-spacing:0.02em;
  text-transform:uppercase;
}

/* Contact: body font (Canva Sans substitute) */
.contact{
  margin: 0 auto 16px;
  color: var(--purple);
  font-family: var(--font-body);
  font-size:14px;
  font-weight:700;
}
.contact a{ color: var(--purple); }
.contact a:hover{ text-decoration:underline; }
.social{ margin-top:4px; }

/* Bio: body font (Canva Sans substitute) */
.bio{
  max-width: 860px;
  margin: 0 auto;
  font-family: var(--font-body);
  font-size:18px;
  line-height:1.6;
  color: #444;
}

/* PAGE */
.page{
  max-width: var(--max);
  margin: 0 auto;
  padding: 8px 18px 60px;
}

/* SECTION */
.sec{ padding-top: 36px; }

/* Section titles: Archivo Black */
.sec-title{
  margin:0 0 18px;
  font-family: var(--font-head);
  font-weight:400;
  letter-spacing:0.02em;
  font-size:34px;
  text-transform:uppercase;
}

/* STORY BLOCKS */
.story{
  display:grid;
  grid-template-columns: 520px 1fr;
  gap: 26px;
  align-items:start;
  padding: 18px 0;
  border-top: 1px solid #ededed;
}
.story:first-of-type{ border-top:none; }

.story-b{ grid-template-columns: 1fr 520px; }

.story-img{
  width:100%;
  height: 300px;
  background-size: cover;
  background-position: center;
}

.story-text{ padding-top: 4px; }

/* Headlines: Archivo Black */
.story-headline{
  margin:0 0 10px 0;
  text-transform:uppercase;
  font-family: var(--font-head);
  font-weight:400;
  font-size:30px;
  line-height:1.05;
}

/* Byline + dek: Canva Sans substitute */
.story-byline{
  margin:0 0 8px 0;
  color: var(--purple);
  font-family: var(--font-body);
  font-weight:700;
  font-size:18px;
}
.story-pub{
  margin:0 0 18px 0;
  font-family: var(--font-body);
  font-weight:700;
  font-size:18px;
  color:#111;
}
.story-dek{
  margin:0;
  font-family: var(--font-body);
  font-size:18px;
  line-height:1.55;
  color:#333;
}

/* Hover */
.story:hover .story-headline,
.story:hover .story-byline,
.story:hover .story-dek{
  text-decoration: underline;
}

/* Footer */
.footer{
  margin-top: 40px;
  padding-top: 18px;
  border-top: 1px solid #ededed;
  text-align:center;
  color:#666;
  font-family: var(--font-body);
}

/* Responsive */
@media (max-width: 1100px){
  .cover-headline{ font-size: 38px; }
  .story{ grid-template-columns: 1fr; }
  .story-b{ grid-template-columns: 1fr; }
  .story-img{ height: 240px; }
  .section-nav{ gap:16px; flex-wrap:wrap; }
}
