CodeAlpha_Calculator
A clean, responsive calculator built with vanilla HTML, CSS, and JavaScript — created for the CodeAlpha Frontend Development Internship (Task 2).

HTML5 CSS3 JavaScript

🔗 Live Preview
(Add your GitHub Pages / Netlify link here after deploying — see "Deploying" below)

✨ Features
Full arithmetic support: addition, subtraction, multiplication, division
Real-time display with a running expression line above the result
Decimal input, sign toggle (±), and percentage (%) conversion
Full keyboard support — type numbers and operators, Enter to evaluate, Esc to clear, Backspace to delete
Divide-by-zero and overflow are caught and shown as a friendly Error state (with a shake animation) instead of crashing
Number formatting with thousands separators for large results
Tactile button-press animation and an active-operator highlight so you always know what's selected
Animated, auto-scrolling image header (pure CSS keyframe marquee, no libraries)
Fully responsive — works on desktop and mobile
Respects prefers-reduced-motion for accessibility
🗂 Project Structure
CodeAlpha_Calculator/
├── index.html      # Markup / structure
├── style.css       # Design tokens, layout, animations
├── script.js       # Calculator logic + keyboard handling
└── README.md       # This file
🛠 How It Works
script.js keeps track of the current typed number, the previous operand, and the pending operator in three simple variables — no external libraries or frameworks are used.
Every button click and every matching keyboard key run through the same functions (inputDigit, chooseOperator, equals, etc.), so mouse and keyboard stay perfectly in sync.
Results are rounded to avoid floating-point artifacts (e.g. 0.1 + 0.2 correctly shows 0.3).
▶️ Running Locally
No build step or dependencies required.

Download / clone this folder.
Open index.html directly in any modern browser (Chrome, Edge, Firefox).
Or serve it locally:

npx serve .
🚀 Deploying (Bonus Task)
GitHub Pages

Push this repo to GitHub as CodeAlpha_Calculator.
Go to Settings → Pages.
Under "Source," select the main branch and / (root) folder → Save.
Your live link will appear at https://<your-username>.github.io/CodeAlpha_Calculator/.
Netlify

Drag and drop this folder onto app.netlify.com/drop.
Copy the generated live URL.
📤 Submission Checklist (CodeAlpha)
 Push source code to a GitHub repo named CodeAlpha_Calculator
 Record a short video walkthrough and post it on LinkedIn, tagging @CodeAlpha
 Share internship status post on LinkedIn, tagging @CodeAlpha
 Include the GitHub repo link in the LinkedIn video post
 Submit the task via the official submission form shared in the WhatsApp group
📄 About This Internship
Built for the CodeAlpha Frontend Development Internship — Task 2: Build a Calculator.

Website: www.codealpha.tech
Task requirement: HTML/CSS/JS calculator with all arithmetic operations, input handling, clear screen, and real-time display, with bonus keyboard support and styling.
📜 License
Free to use for learning and internship submission purposes.
