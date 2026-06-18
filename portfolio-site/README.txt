SULAV SINGHAL — PORTFOLIO
=========================

FILES
  index.html        Your portfolio (this is the page).
  support.js        Required runtime — must stay in the same folder as index.html.
  assets/           Your résumé PDFs (linked from the page).

HOW TO PREVIEW LOCALLY
  Easiest: open a terminal in this folder and run
      python3 -m http.server 8000
  then visit  http://localhost:8000  in your browser.
  (Opening index.html by double-click also works in most browsers.)

HOW TO HOST (free options)
  • GitHub Pages — push this folder to a repo, enable Pages on the main branch.
  • Netlify / Vercel / Cloudflare Pages — drag-and-drop this folder, done.
  • Any static host — upload index.html, support.js, and the assets/ folder together.

HOW TO EDIT
  Open index.html in any code editor (VS Code, etc.).
  • Text content (headings, paragraphs, project descriptions): edit directly in the
    HTML markup inside <x-dc> ... </x-dc>.
  • Lists like projects, jobs, skills, testimonials, writing, certifications:
    edit the data arrays inside the <script ...> block near the bottom (in renderVals).
  • Colors / theme: edit the palette() values in that same script (Light and Dark sets).

THINGS TO FINISH
  • Add your portrait: replace the placeholder in the hero (the striped box).
    Drop in an <img> with a 4:5 photo.
  • Project links: all six currently point to your GitHub profile — swap in real
    repo / live-demo URLs (the "link" field in the projects array).
  • Placeholders marked with [ ... ] — Words (testimonials), Writing (articles),
    and two Udemy + one NPTEL certificate titles. Fill them in or delete the section.

NOTE
  Fonts load from Google Fonts, so the page needs an internet connection to show
  its intended typefaces (it falls back to system fonts offline).
