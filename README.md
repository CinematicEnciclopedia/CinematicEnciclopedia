# Daniel Arenas Sedano

Web developer and AI systems architect · Sallent (Bages, Barcelona) · [danielarenas.cat](https://danielarenas.cat)

I build websites, private dashboards and AI assistants for small businesses in Catalonia.  
I don't hand-write most of the code. I direct a crew of AI agents, read what they produce, and verify it before anything ships.

**How the crew works**  
CASE · Claude (cloud) · coordination, crew orders, final verification  
K-2SO · Claude Code · local builds, git, deploy packages  
TACHIKOMA · Codex · data, security checks, visual QA (Playwright)  
SAMANTHA · DeepSeek · documents, QA, text review  
JOSHUA · OpenCode · web builds and client pages  
FRIDAY · GitHub Copilot CLI · read-only audits

Every order is a file with acceptance gates. Every reply carries evidence (path + full SHA-256). Nothing is "done" without it.

**Gates (the harness)**  
porta_sortida · every outbound text is checked for banned claims, and every third-party name must have a written source  
lint_enc · crew orders are linted before they go out (paths that exist, decisions the agent may take alone, risks)  
porta_acta_trucada · meeting minutes with doubtful key data need a second source (recording transcript)  
porta_enllacos_creuats · after every deploy, cross-links are crawled; any 404 blocks "live"  
porta_paritat_formacio · CV and website must list the same credentials, in all three languages  
REGLES_VIVES · 21 live rules distilled from 468 numbered lessons; a repeated failure becomes an automatic gate, not a new note

**Stack**  
HTML/CSS/JS (single-file, no bundler) · Python 3.11 · Node 24 · Playwright  
Supabase (Postgres, Auth, RLS) · Netlify  
Whisper (local transcription) · OpenSpec-style spec-driven workflow

**Learning in public**  
[fullstackopen-exercices](https://github.com/CinematicEnciclopedia/fullstackopen-exercices) · Full Stack Open, University of Helsinki  
[fullstackopen-bloglist](https://github.com/CinematicEnciclopedia/fullstackopen-bloglist) · Part 4: blog list backend  
[fullstackopen-bloglist-frontend](https://github.com/CinematicEnciclopedia/fullstackopen-bloglist-frontend) · Part 5: frontend, component tests, Playwright E2E  
[fullstackopen-part7](https://github.com/CinematicEnciclopedia/fullstackopen-part7) · Part 7: React hooks, Vite, bloglist extensions

**Private work**  
Client sites and dashboards (Bages) · samples on [danielarenas.cat](https://danielarenas.cat)  
CE-448131 · personal audiovisual encyclopedia (films, series, soundtracks), with its own data pipeline and quizzes

Catalan · Spanish · English
