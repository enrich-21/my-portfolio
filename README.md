# Enrich Malana — Portfolio

Personal portfolio of **Enrich Malana**, a third-year Bachelor of Science in Information Technology student.

Sections: **Home · About · Skills · Projects · Education · Contact**

## View it on your computer
1. Extract the zip. Keep `index.html` and the `assets` folder together.
2. Double-click `index.html`. It opens in any web browser. No install, no server needed.

## Built-in systems (no extra downloads)
All four live inside this portfolio. Click **Projects → Open system**:
1. **Student Record System** – add, search, edit, delete (saved with localStorage)
2. **Task Tracker** – priorities, filters, progress bar (saved with localStorage)
3. **Grade Calculator** – weighted average with live results
4. **IT Basics Quiz** – 10 shuffled questions with explanations

## Add your email & social links
Open `index.html`, scroll to the `<script>` near the bottom, and fill in the `CONFIG` block:
```js
const CONFIG = {
  email: 'your@email.com',
  github: 'https://github.com/your-username',
  facebook: '',
  linkedin: ''
};
```
The email activates the contact form (it opens the visitor's email app). Empty values stay hidden.

## Publish on GitHub Pages
1. Create a new repository on GitHub (e.g. `enrich-malana-portfolio`).
2. Upload **everything inside this folder** (`index.html`, `assets/`, `README.md`) to the repository root.
3. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute your site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Folder structure
```
enrich_malana_portfolio/
├── index.html   (HTML + CSS + JavaScript, your photo is built in, so it always shows)
├── README.md
└── assets/profile.jpg   (original photo file; a copy is also built into index.html)
```
