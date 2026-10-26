# Wire Frame (UXPin)

https://preview.uxpin.com/3d0fd9654feecffdbca8cdb7cb96734112ec62f4

# Faculty Profile Page

A static HTML/CSS mockup of a faculty profile site, built for the COP4504 Module 2 assignment. It has two pages that share one navigation bar and stylesheet:

- **Profile page:** shows a faculty member's name, role, department, profile picture, biography, and contact information.
- **Edit page:** shows the same information as form fields (text inputs, a file picker for the profile picture, and a bio text area), so you can see what an edit screen would look like.

The site is front-end only. There is no JavaScript or back end, so the Edit page does not save changes.

## Repository Contents

| File | Description |
| --- | --- |
| `index.html` | Profile page that displays the faculty member's information. |
| `edit.html` | Edit page with form fields for updating the profile. |
| `styles.css` | Shared stylesheet for the navbar, layout, and form styling. |
| `ProfilePicture.png` | Profile image used on both pages. |
| `README.md` | This file. |

## Viewing the Pages Locally

### Option 1: VS Code Live Preview (recommended)

1. Open this folder in [Visual Studio Code](https://code.visualstudio.com/).
2. Install the **Live Preview** extension by Microsoft (`ms-vscode.live-server`) from the Extensions view (`Ctrl+Shift+X`).
3. Open `index.html` in the editor.
4. Click the **Show Preview** icon in the top-right corner of the editor, or open the Command Palette (`Ctrl+Shift+P`) and run **Live Preview: Show Preview**.
5. The page opens in a preview tab inside VS Code. Use the **Profile** and **Edit** links in the navbar to move between pages. The preview reloads automatically when you save changes.

To view it in your regular browser instead, run **Live Preview: Start Server** from the Command Palette and go to the address it shows (usually `http://127.0.0.1:3000/index.html`).

### Option 2: Open the file directly

Since the site is plain HTML and CSS, you can also double-click `index.html` to open it in any web browser.
