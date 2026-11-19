# FreshCheck website

A static website prototype made with HTML, CSS and JavaScript.

## Files
- `index.html` — website structure and pages
- `style.css` — styling and responsive layout
- `script.js` — navigation and interactive features

## Run it on your computer
Open `index.html` in a web browser. For a local development server, you can use the VS Code Live Server extension.

## Publish with GitHub Pages
1. Sign in to GitHub and create a **new public repository** (for example, `freshcheck`).
2. Upload `index.html`, `style.css`, `script.js`, and this `README.md` to the top level of the repository (not inside another folder).
3. Open the repository's **Settings**.
4. Select **Pages** in the left-hand menu.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then click **Save**.
7. Wait a few minutes. GitHub will show the published website address in the Pages section. It will usually look like `https://YOUR-USERNAME.github.io/freshcheck/`.

## Important prototype limitations
- Food items and profile details are saved in the visitor's browser using local storage. They are not synchronised between devices or users.
- Login and sign-up are demonstration screens only. A real account system needs a secure authentication service and backend.
- Barcode entry and food-label photo upload are demonstrations; they do not automatically identify products.
- Support messages are not sent to a real support team.
- Expiry dates are reminders only and do not establish whether food is safe to eat.
- Recipe and hero photographs are loaded from Unsplash, so those images require an internet connection.
