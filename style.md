/\* ![](Aspose.Words.8ccc3612-47f2-4280-a687-dc7eb4427508.001.png)

═══════════════════════════════════════════ ════════

` `ORIENTA — style.css

` `Palette:

` `--green: #679C7D (primary)

` `--sand: #D6B98D (accent warm)

` `--purple: #78628A (accent cool)

` `--green-d: #4E7A63 (hover / deep)

` `--green-l: #A8CBBA (light tint)

` `--sand-l: #EDD9BC (light sand)

` `--purple-l:#B5A8C4 (light purple)

` `--cream: #FAF7F3 (bg soft)

` `--white: #FFFFFF

` `--ink: #1E1E2C (body text)

═══════════════════════════════════════════

════════ \*/

:root {

` `--green: #679C7D;

` `--green-d: #4E7A63;

` `--green-l: #A8CBBA;

` `--green-xl: #E5F0EB;

` `--sand: #D6B98D;

` `--sand-d: #B8946A;

` `--sand-l: #EDD9BC;

` `--sand-xl: #FBF5ED;

` `--purple: #78628A;

` `--purple-d: #5C4A6E;

` `--purple-l: #B5A8C4;

` `--purple-xl:#F0EBF6;

` `--cream: #FAF7F3;

` `--white: #FFFFFF;

` `--ink: #1E1E2C;

` `--ink-soft: #4A4A5C;

` `--ink-muted:#7A7A8C;

` `--radius-sm: 8px;![ref1]

` `--radius-md: 14px;

` `--radius-lg: 22px;

` `--radius-xl: 32px;

` `--shadow-sm: 0 2px 8px rgba(103,156,125,.10);

` `--shadow-md: 0 6px 24px rgba(103,156,125,.14);

` `--shadow-lg: 0 16px 48px rgba(30,30,44,.12);

` `--font-display: 'Fraunces', Georgia, serif;

` `--font-body: 'Inter', system-ui, sans-serif;

` `--nav-h: 68px;

}

/\* ─── RESET ─── \*/

\*, \*::before, \*::after { box-sizing: border-box; 

margin: 0; padding: 0; }

html { scroll-behavior: smooth; }

body {

` `font-family: var(--font-body);

` `background: var(--cream);

` `color: var(--ink);

` `line-height: 1.65;

` `overflow-x: hidden;

}

img { max-width: 100%; display: block; }

a { text-decoration: none; color: inherit; }

ul { list-style: none; }

button { cursor: pointer; font-family: inherit; 

border: none; background: none; }

/\* ─── CONTAINER ─── \*/

.container {

` `width: min(1140px, 100% - 3rem);

` `margin-inline: auto;

}

/\* ─── TYPOGRAPHY ─── \*/

.section-title {![ref1]

` `font-family: var(--font-display);

` `font-size: clamp(1.9rem, 4vw, 2.8rem);

` `font-weight: 700;

` `line-height: 1.15;

` `color: var(--ink);

}

.section-eyebrow, .panel-eyebrow {

` `display: inline-block;

` `font-size: .75rem;

` `font-weight: 600;

` `letter-spacing: .12em;

` `text-transform: uppercase;

` `color: var(--green-d);

` `margin-bottom: .6rem;

}

.section-desc {

` `color: var(--ink-soft);

` `max-width: 560px;

` `margin-top: .6rem;

}

em { font-style: italic; color: var(--green); }

/\* ─── BUTTONS ─── \*/

.btn {

` `display: inline-flex;

` `align-items: center;

` `gap: .45rem;

` `padding: .7rem 1.6rem;

` `border-radius: 100px;

` `font-weight: 600;

` `font-size: .95rem;

` `transition: all .2s ease;

` `white-space: nowrap;

}

.btn-primary {

` `background: var(--green);

` `color: var(--white);

` `box-shadow: 0 4px 16px rgba(103,156,125,.35);

}

.btn-primary:hover {![ref1]

` `background: var(--green-d);

` `box-shadow: 0 6px 20px rgba(103,156,125,.45);

` `transform: translateY(-1px);

}

.btn-ghost {

` `background: transparent;

` `color: var(--green-d);

` `border: 2px solid var(--green-l);

}

.btn-ghost:hover {

` `background: var(--green-xl);

` `border-color: var(--green);

}

.btn-lg { padding: .9rem 2.2rem; font-size: 

1\.05rem; }

.btn-sand {

` `background: var(--sand);

` `color: var(--white);

` `box-shadow: 0 4px 16px rgba(214,185,141,.4);

}

.btn-sand:hover { background: var(--sand-d); 

transform: translateY(-1px); }

/\* ══════════════════════════════════════

` `NAVBAR

══════════════════════════════════════ \*/ .navbar {

` `position: fixed;

` `top: 0; left: 0; right: 0;

` `z-index: 100;

` `height: var(--nav-h);

` `background: rgba(250,247,243,.88);

` `backdrop-filter: blur(14px);

` `border-bottom: 1px solid rgba(103,156,125,.12);

` `transition: box-shadow .3s;

}

.navbar.scrolled { box-shadow: var(--shadow-md); }

.nav-inner {

` `height: 100%;

` `display: flex;![ref1]

` `align-items: center;

` `justify-content: space-between;

` `width: min(1140px, 100% - 3rem);

` `margin-inline: auto;

}

.logo {

` `font-family: var(--font-display);

` `font-size: 1.5rem;

` `font-weight: 700;

` `color: var(--ink);

}

.logo span { color: var(--green); }

.nav-links {

` `display: flex;

` `align-items: center;

` `gap: 2rem;

}

.nav-links a {

` `font-size: .9rem;

` `font-weight: 500;

` `color: var(--ink-soft);

` `transition: color .2s;

}

.nav-links a:hover { color: var(--green); }

.nav-cta {

` `background: var(--green) !important;

` `color: var(--white) !important;

` `padding: .5rem 1.3rem;

` `border-radius: 100px;

` `font-weight: 600 !important;

}

.nav-cta:hover { background: var(--green-d) 

!important; }

.hamburger {

` `display: none;

` `flex-direction: column;

` `gap: 5px;

` `padding: 4px;

}

.hamburger span {![ref1]

` `display: block;

` `width: 24px;

` `height: 2px;

` `background: var(--ink);

` `border-radius: 2px;

` `transition: all .3s;

}

/\* ══════════════════════════════════════

` `HERO

══════════════════════════════════════ \*/ .hero {

` `min-height: 100svh;

` `padding-top: calc(var(--nav-h) + 3rem);

` `padding-bottom: 5rem;

` `display: grid;

` `grid-template-columns: 1fr 1fr;

` `align-items: center;

` `gap: 3rem;

` `width: min(1140px, 100% - 3rem);

` `margin-inline: auto;

` `position: relative;

}

.hero-bg-shapes {

` `position: fixed;

` `inset: 0;

` `z-index: -1;

` `overflow: hidden;

` `pointer-events: none;

}

.shape {

` `position: absolute;

` `border-radius: 50%;

` `filter: blur(80px);

` `opacity: .18;

}

.shape-1 {

` `width: 600px; height: 600px;

` `background: var(--green);

` `top: -120px; right: -100px;![ref1]

}

.shape-2 {

` `width: 400px; height: 400px;

` `background: var(--sand);

` `bottom: 5%; left: -80px;

}

.shape-3 {

` `width: 300px; height: 300px;

` `background: var(--purple);

` `top: 50%; left: 40%;

}

.hero-eyebrow {

` `display: inline-block;

` `background: var(--green-xl);

` `color: var(--green-d);

` `padding: .3rem .8rem;

` `border-radius: 100px;

` `font-size: .8rem;

` `font-weight: 600;

` `letter-spacing: .06em;

` `margin-bottom: 1.2rem;

}

.hero-title {

` `font-family: var(--font-display);

` `font-size: clamp(2.8rem, 6vw, 5rem);

` `font-weight: 700;

` `line-height: 1.05;

` `color: var(--ink);

` `margin-bottom: 1.4rem;

}

.hero-title em {

` `font-style: italic;

` `background: linear-gradient(135deg, var(--green), 

var(--purple));

` `-webkit-background-clip: text;

` `-webkit-text-fill-color: transparent;

` `background-clip: text;

}

.hero-sub {

` `color: var(--ink-soft);![ref1]

` `font-size: 1.1rem;

` `max-width: 460px;

` `margin-bottom: 2rem;

` `line-height: 1.7;

}

.hero-actions {

` `display: flex;

` `gap: 1rem;

` `flex-wrap: wrap;

` `margin-bottom: 3rem;

}

.hero-stats {

` `display: flex;

` `gap: 2.5rem;

}

.stat-num {

` `display: block;

` `font-family: var(--font-display);

` `font-size: 1.8rem;  font-weight: 700;

` `color: var(--green);

}

.stat-label {

` `display: block;

` `font-size: .78rem;

` `color: var(--ink-muted);

` `font-weight: 500;

}

/\* floating cards \*/

.hero-visual {

` `position: relative;

` `height: 500px;

` `display: flex;

` `align-items: center;

` `justify-content: center;

}

.hero-orbit-ring {

` `width: 340px;

` `height: 340px;![ref1]

` `border: 2px dashed rgba(103,156,125,.25);

` `border-radius: 50%;

` `animation: spin 20s linear infinite;

}

@keyframes spin { to { transform: rotate(360deg); } 

}

.card-float {

` `position: absolute;

` `display: flex;

` `align-items: center;

` `gap: .5rem;

` `background: var(--white);

` `border: 1px solid rgba(103,156,125,.2);

` `padding: .6rem 1.1rem;

` `border-radius: 100px;

` `font-size: .88rem;

` `font-weight: 600;

` `color: var(--ink);

` `box-shadow: var(--shadow-md);

` `animation: floatCard 4s ease-in-out infinite;

}

.card-float .card-icon { font-size: 1.1rem; }

.card-a { top: 8%; left: 10%; animation-delay: 

0s; }

.card-b { top: 20%; right: 2%; animation-delay: 

.8s; }

.card-c { top: 48%; left: 0%; animation-delay: 

1\.6s; }

.card-d { bottom: 22%; right: 5%; animation-delay: 

2\.4s; }

.card-e { bottom: 8%; left: 18%; animation-delay: 

1\.2s; }

@keyframes floatCard {

` `0%, 100% { transform: translateY(0); }

` `50% { transform: translateY(-10px); }

}

/\* ══════════════════════════════════════

` `HOW IT WORKS

══════════════════════════════════════ \*/![ref1]

.how-section {

` `background: var(--white);

` `padding: 6rem 0;

}

.how-section .section-title {

` `text-align: center;

` `margin-bottom: 3rem;

}

.steps-grid {

` `display: grid;

` `grid-template-columns: repeat(3, 1fr);

` `gap: 2rem;

}

.step-card {

` `background: var(--cream);

` `border-radius: var(--radius-lg);

` `padding: 2.2rem;

` `border: 1px solid rgba(103,156,125,.1);

` `transition: transform .2s, box-shadow .2s;

}

.step-card:hover {

` `transform: translateY(-4px);

` `box-shadow: var(--shadow-md);

}

.step-num {

` `font-family: var(--font-display);

` `font-size: 3rem;

` `font-weight: 700;

` `color: var(--green-l);

` `line-height: 1;

` `margin-bottom: .8rem;

}

.step-card h3 {

` `font-size: 1.15rem;

` `font-weight: 600;

` `margin-bottom: .6rem;

` `color: var(--ink);

}

.step-card p { color: var(--ink-soft); font-size: 

.95rem; }![ref1]

/\* ══════════════════════════════════════

` `TEST SECTION

══════════════════════════════════════ \*/ .test-section {

` `padding: 7rem 0;

` `background: linear-gradient(160deg, var(--green-

xl) 0%, var(--sand-xl) 50%, var(--purple-xl) 100%);

}

.test-wrapper {

` `max-width: 760px;

` `margin: 0 auto;

}

.test-panel {

` `display: none;

` `background: var(--white);

` `border-radius: var(--radius-xl);

` `padding: 3.5rem;

` `box-shadow: var(--shadow-lg);

}

.test-panel.active { display: block; }

/\* Landing \*/

#test-landing h2 {

` `font-family: var(--font-display);

` `font-size: clamp(2rem, 4vw, 3rem);

` `font-weight: 700;

` `line-height: 1.15;

` `margin-bottom: 1rem;

}

#test-landing p {

` `color: var(--ink-soft);

` `font-size: 1.05rem;

` `margin-bottom: 2rem;

` `max-width: 440px;

}

/\* Progress \*/

.progress-bar-wrap {

` `background: var(--green-xl);![ref1]

` `border-radius: 100px;

` `height: 6px;

` `margin-bottom: .6rem;

` `overflow: hidden;

}

.progress-bar {

` `height: 100%;

` `background: linear-gradient(90deg, var(--green), 

var(--purple-l));

` `border-radius: 100px;

` `transition: width .4s ease;

` `width: 5%;

}

.progress-label {

` `font-size: .82rem;

` `font-weight: 600;

` `color: var(--ink-muted);

` `margin-bottom: 2rem;

` `text-align: right;

}

.question-text {

` `font-family: var(--font-display);

` `font-size: 1.3rem;

` `font-weight: 600;

` `color: var(--ink);

` `margin-bottom: 1.8rem;

` `line-height: 1.4;

}

.options-grid {

` `display: grid;

` `grid-template-columns: 1fr 1fr;

` `gap: .9rem;

` `margin-bottom: 2rem;

}

.option-btn {

` `background: var(--cream);

` `border: 2px solid transparent;

` `border-radius: var(--radius-md);

` `padding: .9rem 1.1rem;

` `text-align: left;![ref1]

` `font-size: .92rem;

` `font-weight: 500;

` `color: var(--ink-soft);

` `transition: all .18s;

` `cursor: pointer;

` `line-height: 1.4;

}

.option-btn:hover {

` `border-color: var(--green-l);

` `background: var(--green-xl);

` `color: var(--ink);

}

.option-btn.selected {

` `border-color: var(--green);

` `background: var(--green-xl);

` `color: var(--green-d);

` `font-weight: 600;

}

.option-btn.selected::before {

` `content: '✓ ';

` `color: var(--green);

}

.multi-hint {

` `font-size: .8rem;

` `color: var(--ink-muted);

` `margin-bottom: 1.2rem;

` `font-style: italic;

}

.test-nav {

` `display: flex;

` `justify-content: space-between;

` `align-items: center;

` `margin-top: .5rem;

}

#next-btn:disabled, #prev-btn:disabled {

` `opacity: .4;

` `pointer-events: none;

}

/\* Results \*/![ref1]

#test-results h2 {

` `font-family: var(--font-display);

` `font-size: clamp(1.8rem, 3.5vw, 2.6rem);

` `font-weight: 700;

` `margin-bottom: 1.8rem;

` `color: var(--ink);

}

.results-eye { color: var(--purple); }

.affinity-bars { margin-bottom: 2.5rem; }

.affinity-item {

` `display: grid;

` `grid-template-columns: 140px 1fr 42px;

` `align-items: center;  gap: .8rem;

` `margin-bottom: .9rem;

}

.affinity-label {

` `font-size: .88rem;

` `font-weight: 600;

` `color: var(--ink-soft);

` `white-space: nowrap;

}

.affinity-track {

` `background: var(--cream);

` `border-radius: 100px;

` `height: 10px;

` `overflow: hidden;

}

.affinity-fill {

` `height: 100%;

` `border-radius: 100px;

` `transition: width .8s ease;

` `width: 0;

}

.affinity-score {

` `font-size: .8rem;

` `font-weight: 700;

` `color: var(--ink-muted);

` `text-align: right;

}![ref1]

.results-sub {

` `font-size: 1.1rem;

` `font-weight: 700;

` `color: var(--ink);

` `margin-bottom: 1.2rem;

}

.results-careers {

` `display: grid;

` `grid-template-columns: 1fr 1fr;

` `gap: 1rem;

` `margin-bottom: 2rem;

}

.result-career-card {

` `background: var(--cream);

` `border-radius: var(--radius-md);

` `padding: 1.2rem;

` `border-left: 4px solid var(--green);

` `cursor: pointer;

` `transition: transform .2s, box-shadow .2s;

}

.result-career-card:hover {

` `transform: translateY(-3px);

` `box-shadow: var(--shadow-md);

}

.result-career-card h4 {

` `font-size: .97rem;

` `font-weight: 700;

` `color: var(--ink);

` `margin-bottom: .3rem;

}

.result-career-card p { font-size: .82rem; color: 

var(--ink-soft); }

.result-match {

` `font-size: .75rem;

` `font-weight: 700;

` `color: var(--green-d);

` `margin-bottom: .4rem;

}

.retake-btn { margin-top: .5rem; }

/\* ══════════════════════════════════════

` `MODAL![ref1]

══════════════════════════════════════ \*/ .modal-overlay {

` `display: none;

` `position: fixed;

` `inset: 0;

` `z-index: 200;

` `background: rgba(30,30,44,.5);

` `backdrop-filter: blur(4px);

` `align-items: center;

` `justify-content: center;

` `padding: 1.5rem;

}

.modal-overlay.open { display: flex; }

.modal-box {

` `background: var(--white);

` `border-radius: var(--radius-xl);

` `max-width: 680px;

` `width: 100%;

` `max-height: 88vh;

` `overflow-y: auto;

` `padding: 2.8rem;

` `position: relative;

` `box-shadow: var(--shadow-lg);

` `animation: slideUp .3s ease;

}

@keyframes slideUp {

` `from { opacity: 0; transform: translateY(20px); }

` `to { opacity: 1; transform: translateY(0); }

}

.modal-close {

` `position: absolute;

` `top: 1.2rem; right: 1.4rem;

` `font-size: 1.2rem;

` `color: var(--ink-muted);

` `width: 32px; height: 32px;

` `display: flex; align-items: center; justify-

content: center;


` `border-radius: 50%;![ref1]

` `transition: background .2s;

}

.modal-close:hover { background: var(--cream); 

color: var(--ink); }

.modal-icon { font-size: 3rem; margin-bottom: 

.8rem; }

.modal-content h2 {

` `font-family: var(--font-display);

` `font-size: 1.8rem;

` `font-weight: 700;

` `margin-bottom: .4rem;

}

.modal-area-tag {

` `display: inline-block;

` `padding: .25rem .7rem;

` `border-radius: 100px;

` `font-size: .75rem;

` `font-weight: 700;

` `background: var(--green-xl);

` `color: var(--green-d);

` `margin-bottom: 1rem;

}

.modal-content p { color: var(--ink-soft); margin-

bottom: 1.4rem; line-height: 1.7; } .modal-grid {

` `display: grid;

` `grid-template-columns: 1fr 1fr;

` `gap: 1rem;

` `margin-bottom: 1.4rem;

}

.modal-info-box {

` `background: var(--cream);

` `border-radius: var(--radius-md);

` `padding: 1rem;

}

.modal-info-box h4 {

` `font-size: .75rem;

` `font-weight: 700;

` `text-transform: uppercase;

` `letter-spacing: .08em;![ref1]

` `color: var(--ink-muted);

` `margin-bottom: .4rem;

}

.modal-info-box p {

` `font-size: .88rem;

` `color: var(--ink);

` `margin: 0;

` `line-height: 1.5;

}

.modal-tags {

` `display: flex;

` `flex-wrap: wrap;

` `gap: .4rem;

` `margin-top: .4rem;

}

.modal-tag {

` `background: var(--sand-l);

` `color: var(--sand-d);

` `padding: .2rem .6rem;

` `border-radius: 100px;

` `font-size: .76rem;

` `font-weight: 600;

}

.modal-tag-purple {

` `background: var(--purple-xl);

` `color: var(--purple-d);

}

/\* ══════════════════════════════════════

` `CAREERS SECTION

══════════════════════════════════════ \*/

.careers-section {

` `padding: 7rem 0;

` `background: var(--white);

}

.careers-section .section-title { margin-bottom: 

.6rem; }

.filter-bar {

` `display: flex;![ref1]

` `flex-wrap: wrap;

` `gap: .6rem;

` `margin-block: 2rem;

}

.filter-btn {

` `padding: .45rem 1.1rem;

` `border-radius: 100px;

` `font-size: .85rem;

` `font-weight: 600;

` `border: 2px solid var(--green-l);

` `color: var(--ink-soft);  background: transparent;

` `transition: all .18s;

}

.filter-btn:hover, .filter-btn.active {

` `background: var(--green);

` `border-color: var(--green);

` `color: var(--white);

}

.careers-grid {

` `display: grid;

` `grid-template-columns: repeat(auto-fill, 

minmax(260px, 1fr));

` `gap: 1.4rem;

}

.career-card {

` `background: var(--cream);

` `border-radius: var(--radius-lg);

` `padding: 1.6rem;

` `border: 1px solid rgba(103,156,125,.12);

` `cursor: pointer;

` `transition: transform .2s, box-shadow .2s, 

border-color .2s;

` `position: relative;

` `overflow: hidden;

}

.career-card::before {

` `content: '';

` `position: absolute;![ref1]

` `top: 0; left: 0;

` `width: 100%; height: 4px;

` `background: linear-gradient(90deg, var(--green), 

var(--purple-l));

` `transform: scaleX(0);

` `transform-origin: left;

` `transition: transform .3s;

}

.career-card:hover { transform: translateY(-5px); 

box-shadow: var(--shadow-md); }

.career-card:hover::before { transform: scaleX(1); 

}

.career-card-icon {

` `font-size: 2.2rem;

` `margin-bottom: .8rem;

}

.career-card h3 {

` `font-size: 1rem;

` `font-weight: 700;

` `color: var(--ink);

` `margin-bottom: .4rem;

}

.career-card .career-area {

` `font-size: .75rem;

` `font-weight: 600;

` `color: var(--green-d);

` `text-transform: uppercase;

` `letter-spacing: .06em;

` `margin-bottom: .5rem;

}

.career-card p {

` `font-size: .85rem;

` `color: var(--ink-soft);

` `line-height: 1.5;

` `margin-bottom: .9rem;

}

.career-card-footer {

` `display: flex;

` `align-items: center;

` `justify-content: space-between;![ref1]

}

.career-duration {

` `font-size: .78rem;

` `font-weight: 600;

` `color: var(--sand-d);

` `background: var(--sand-l);

` `padding: .2rem .6rem;

` `border-radius: 100px;

}

.career-more {

` `font-size: .8rem;

` `font-weight: 600;

` `color: var(--green-d);

}

/\* ══════════════════════════════════════

` `UNIVERSITIES

══════════════════════════════════════ \*/

.universities-section {

` `padding: 7rem 0;

` `background: linear-gradient(160deg, var(--purple-

xl) 0%, var(--cream) 60%);\
}

.universities-section .section-title { margin-

bottom: .6rem; }

.uni-search-wrap {

` `margin-block: 2rem;

}

.uni-search {

` `width: 100%;

` `max-width: 420px;

` `padding: .75rem 1.2rem;

` `border-radius: 100px;

` `border: 2px solid var(--purple-l);

` `font-family: var(--font-body);

` `font-size: .95rem;

` `color: var(--ink);

` `background: var(--white);

` `transition: border-color .2s, box-shadow .2s;

` `outline: none;![ref1]

}

.uni-search:focus {

` `border-color: var(--purple);

` `box-shadow: 0 0 0 3px rgba(120,98,138,.12);

}

.universities-grid {

` `display: grid;

` `grid-template-columns: repeat(auto-fill, 

minmax(290px, 1fr));

` `gap: 1.4rem;

}

.uni-card {

` `background: var(--white);

` `border-radius: var(--radius-lg);

` `padding: 1.6rem;

` `border: 1px solid rgba(120,98,138,.12);

` `transition: transform .2s, box-shadow .2s;

}

.uni-card:hover { transform: translateY(-4px); box-

shadow: var(--shadow-md); } .uni-card-header {

` `display: flex;

` `align-items: flex-start;

` `justify-content: space-between;

` `margin-bottom: 1rem;

}

.uni-emoji { font-size: 2rem; }

.uni-country-tag {

` `font-size: .72rem;

` `font-weight: 700;

` `background: var(--purple-xl);

` `color: var(--purple-d);

` `padding: .2rem .6rem;

` `border-radius: 100px;

}

.uni-card h3 {

` `font-size: 1rem;

` `font-weight: 700;

` `color: var(--ink);![ref1]

` `margin-bottom: .3rem;

}

.uni-location {

` `font-size: .82rem;

` `color: var(--ink-muted);

` `margin-bottom: .8rem;

` `display: flex;

` `align-items: center;

` `gap: .3rem;

}

.uni-careers {

` `display: flex;

` `flex-wrap: wrap;

` `gap: .35rem;

` `margin-bottom: 1.1rem;

}

.uni-career-tag {

` `background: var(--sand-l);

` `color: var(--sand-d);  padding: .18rem .55rem;

` `border-radius: 100px;

` `font-size: .72rem;

` `font-weight: 600;

}

.uni-link {

` `display: inline-flex;

` `align-items: center;

` `gap: .4rem;

` `font-size: .85rem;

` `font-weight: 600;

` `color: var(--purple-d);

` `transition: color .2s;

}

.uni-link:hover { color: var(--purple); }

.uni-link svg { width: 14px; height: 14px; }

/\* ══════════════════════════════════════

` `FOOTER

══════════════════════════════════════ \*/

.footer {![ref1]

` `background: var(--ink);

` `color: rgba(255,255,255,.75);

` `padding: 4rem 0 0;

}

.footer-inner {

` `display: grid;

` `grid-template-columns: 2fr 1fr 1fr;

` `gap: 3rem;

` `padding-bottom: 3rem;

` `border-bottom: 1px solid rgba(255,255,255,.1);

}

.footer-brand .logo { color: var(--white); font-

size: 1.6rem; }

.footer-brand .logo span { color: var(--green-l); }

.footer-brand p { margin-top: .6rem; font-size: 

.88rem; line-height: 1.6; max-width: 260px; }

.footer-links h4 {

` `font-size: .8rem;

` `font-weight: 700;

` `text-transform: uppercase;

` `letter-spacing: .1em;

` `color: rgba(255,255,255,.4);

` `margin-bottom: 1rem;

}

.footer-links a {

` `display: block;

` `font-size: .9rem;

` `margin-bottom: .6rem;

` `transition: color .2s;

}

.footer-links a:hover { color: var(--white); }

.footer-bottom {

` `padding: 1.4rem 0;

` `text-align: center;

` `font-size: .8rem;

` `color: rgba(255,255,255,.3);

` `width: min(1140px, 100% - 3rem);

` `margin-inline: auto;

}

/\* ══════════════════════════════════════

` `RESPONSIVE![ref1]

══════════════════════════════════════ \*/ @media (max-width: 900px) {

.hero {

` `grid-template-columns: 1fr;

` `text-align: center;

` `gap: 2rem;

` `}

.hero-sub, .hero-actions { margin-inline: auto; }

.hero-actions { justify-content: center; }  .hero-stats { justify-content: center; }

.hero-visual { height: 260px; }

.hero-orbit-ring { width: 220px; height: 220px; }

.card-a { top: 0%; left: 5%; }  .card-b { top: 10%; right: 3%; }

.card-c { display: none; }

.card-d { bottom: 5%; right: 3%; }

.card-e { bottom: 0%; left: 8%; }

.steps-grid { grid-template-columns: 1fr; }

.options-grid { grid-template-columns: 1fr; }\
.results-careers { grid-template-columns: 1fr; }\
.modal-grid { grid-template-columns: 1fr; }\
.footer-inner { grid-template-columns: 1fr 1fr; }\
.footer-brand { grid-column: 1/-1; }

}

@media (max-width: 640px) {

.test-panel { padding: 2rem 1.4rem; }

.modal-box { padding: 2rem 1.4rem; }  .nav-links {

` `display: none;

` `flex-direction: column;

` `align-items: flex-start;

` `position: absolute;

` `top: var(--nav-h); left: 0; right: 0;

` `background: var(--white);

` `padding: 1.5rem;


` `border-bottom: 1px solid rgba(103,156,125,.15);![](Aspose.Words.8ccc3612-47f2-4280-a687-dc7eb4427508.003.png)

` `box-shadow: var(--shadow-md);  gap: 1rem;

` `}

.nav-links.open { display: flex; }

.hamburger { display: flex; }

.footer-inner { grid-template-columns: 1fr; }

.hero-visual { display: none; }

.affinity-item { grid-template-columns: 120px 1fr 

36px; }

}

/\* ─── UTILITY ─── \*/

.hidden { display: none !important; }

.fade-in {

` `animation: fadeIn .5s ease both;

}

@keyframes fadeIn {

` `from { opacity: 0; transform: translateY(12px); }

` `to { opacity: 1; transform: translateY(0); }

}

@media (prefers-reduced-motion: reduce) {

` `\*, \*::before, \*::after { animation-duration: 

.01ms !important; transition-duration: .01ms 

!important; }

}

[ref1]: Aspose.Words.8ccc3612-47f2-4280-a687-dc7eb4427508.002.png
