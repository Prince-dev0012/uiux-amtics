# uiux-amtics
Kroma Studio

Design and code in one simple workspace.

A collaborative tool that pairs responsive visual layout with clean code generation — bridging the gap between design drafts and production-ready code.

What It Does

Kroma Studio eliminates the back-and-forth between designers and developers. Build layouts visually, sync design tokens, and collaborate in real time — all from a single workspace.

Intended Users
User	Use Case
UI/UX Designers	Build and iterate layouts without writing code
Frontend Developers	Receive clean, production-ready handoff
Product Teams	Reduce design-to-code cycle time
Agencies & Startups	Streamline cross-functional workflows
Color Theme
Token	Hex	Usage
--color-primary	
#6B5FF8	CTA buttons, accent highlights
--color-bg-light	
#F8F8FC	Light mode background
--color-bg-dark	
#0F0E1A	Dark mode background
--color-surface-dark	
#1A1828	Cards, panels (dark mode)
--color-text-primary	
#1A1830	Headings (light)
--color-text-muted	
#7B7A8E	Subtext, labels
--color-border	
#E4E3F0	Dividers, card borders

Theme: Dual light/dark — users get both out of the box. Dark mode uses deep navy-purple backgrounds rather than pure black, keeping the purple brand identity consistent.

Typography
Role	Typeface	Weight	Notes
Display / Hero	Inter (or similar sans)	700–800	Large, tight line-height
Body	Inter	400	~16px, relaxed line-height
UI Labels	Inter	500	Sentence case, no all-caps
Code / Monospace	JetBrains Mono	400	Code previews only

Scale (approximate):

h1 — 48–56px / bold
h2 — 32–36px / semibold  
h3 — 20–24px / semibold
body — 16px / regular
small / caption — 13–14px / regular
Key Features
Auto Layout Engine — Responsive layout rules that translate directly to CSS
Token Synchronization — Design tokens stay in sync between design and code
Real-time Collaboration — Multiple users, live cursors, no conflicts
Design Principles
Purple-first identity — One accent color used consistently; not decorative, functional
Whitespace over chrome — Minimal borders, generous padding; content does the work
Dark mode native — Not an afterthought; both themes are designed equally



figma link- https://www.figma.com/design/Owpnh66dLAjFPmcOwuknN8/Untitled?node-id=0-1&t=gSVfhdekenvYwmR9-1
Component-driven — Feature cards are isolated, reusable components (shown standalone in the UI)
Tech Stack (assumed)
Framework: Next.js / React
Styling: Tailwind CSS
Icons: Lucide / Radix
Theme: CSS custom properties with prefers-color-scheme + manual toggle
