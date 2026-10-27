# 🖥️ WebDesk — Browser-Based Mini Desktop

> **Your desktop. Your workspace. Your browser.**
>
> Experience a mini operating-system-style desktop directly in your web browser. Open draggable application windows, write and save notes, perform calculations, explore demo files, and personalize your workspace with customizable wallpapers and accent colors — all powered by HTML, CSS, and JavaScript.

---

## ✨ Features

### 🪟 Interactive Desktop Environment
- Create a desktop interface inspired by modern operating systems.
- Open applications using desktop icons, taskbar shortcuts, and the Start menu.
- Drag application windows around the desktop.
- Resize, minimize, maximize, and close application windows.
- Use a modern glassmorphism-inspired interface.
- Enjoy a responsive layout for desktop and smaller screens.

### 📝 Quick Notes
- Write notes, reminders, ideas, and other text.
- Save notes directly in your browser using local storage.
- Automatically restore previously saved notes when reopening the application.
- Use the keyboard shortcut `Ctrl + S` to save notes.
- Keep your notes available between browser sessions on the same browser profile.

### 🧮 Built-in Calculator
- Perform basic arithmetic calculations.
- Supports addition, subtraction, multiplication, and division.
- Use decimal numbers and parentheses.
- Clear the display or delete the last character.
- View calculation results instantly.

### 📁 File Explorer
- Explore a collection of demonstration files.
- Search files by name.
- Open sample text files and preview their contents.
- Create new demonstration text files.
- View file names, types, and content in an organized interface.

### 🎨 Customizable Wallpapers
- Choose from four built-in wallpaper styles.
- Switch between Purple Aurora, Ocean, Sunset, and Neon-inspired backgrounds.
- Customize the interface accent color.
- Select purple, blue, green, or pink accents.
- Personalize the desktop to match your preferred style.

### ⚡ Desktop Taskbar and Start Menu
- Launch applications from the Start menu.
- Access commonly used apps through taskbar shortcuts.
- View the current time and date.
- Use a clean desktop layout with application icons.
- Manage multiple application windows within one workspace.

### 📱 Responsive Design
- Adapt the interface to different screen sizes.
- Use CSS-based layouts for desktop and mobile browsers.
- Keep the main application controls accessible on smaller displays.

---

## 📂 Project Structure

```text
WebDesk/
│
├── WebDesk.html    ← Complete web application
└── README.md       ← Project documentation
```

The entire application is contained in a single HTML file, including its HTML structure, CSS styling, and JavaScript functionality.

No separate frontend framework, backend server, or database is required.

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/rsamwilson2323-cloud/WebDesk.git
```

### 2️⃣ Open the Project Folder

```bash
cd WebDesk
```

### 3️⃣ Launch the Application

Open `WebDesk.html` in a modern web browser.

**Windows users:** Double-click `WebDesk.html` to open the application in your default browser.

✅ No installation process required.

> **Note:** The filename in your repository should match the actual HTML file. If your file is named `index.html`, open that file instead.

---

## 📦 Requirements

```text
HTML5             Desktop interface and application structure
CSS3              Styling, animations, and responsive layouts
JavaScript        Window management and application logic
Local Storage     Saving notes in the browser
Modern Browser    Chrome, Edge, Firefox, or another compatible browser
```

### No additional development dependencies

- No Node.js
- No Python
- No npm packages
- No database
- No backend server
- No external JavaScript libraries

The application runs directly in the browser.

---

## 🚀 Live Demo

You can publish WebDesk using GitHub Pages after uploading the project files and enabling Pages for the repository.

**GitHub Repository:**

https://github.com/rsamwilson2323-cloud/WebDesk

**Application:**

https://github.com/rsamwilson2323-cloud/WebDesk/blob/main/WebDesk.html

### Publish with GitHub Pages

1. Upload `WebDesk.html` and `README.md` to your repository.
2. Open the repository's **Settings → Pages**.
3. Select the `main` branch and the `/ (root)` folder.
4. Save the configuration.
5. Open the published GitHub Pages URL.

For a simpler homepage URL, you can rename `WebDesk.html` to `index.html` before publishing.

---

## ▶️ Usage

### 🖥️ 1. Explore the Desktop

1. Open WebDesk in your browser.
2. View the desktop icons and taskbar.
3. Double-click an application icon to open its window.
4. Use the Start menu to launch applications.
5. Drag windows by their title bars to reposition them.

### 📝 2. Write and Save Notes

1. Open **Notes** from the desktop or Start menu.
2. Enter your text in the note editor.
3. Click **Save note** to store the content.
4. Reopen Notes to retrieve your saved text.

Notes are stored in the browser's local storage. Clearing browser data or using a different browser profile may remove or hide previously saved notes.

### 🧮 3. Use the Calculator

1. Open the Calculator application.
2. Click the number and operator buttons.
3. Enter an arithmetic expression.
4. Click `=` to calculate the result.
5. Use `AC` to clear the display or `⌫` to remove the last character.

### 📁 4. Explore Demo Files

1. Open **File Explorer**.
2. Search for a file using the search box.
3. Select a sample file to preview its contents.
4. Click **New** to create a demonstration text file.
5. Enter a filename and its content.

**Important:** The file viewer uses application-defined demo data. It does not browse or modify files on your actual computer.

### 🎨 5. Customize the Desktop

1. Open **Personalize**.
2. Select one of the four wallpaper designs.
3. Choose a preferred accent color.
4. Continue using the desktop with your customized appearance.

### 🪟 6. Manage Application Windows

- **Drag:** Move a window using its title bar.
- **Minimize:** Hide a window temporarily.
- **Maximize:** Expand a window across the available workspace.
- **Restore:** Return a maximized window to its previous dimensions.
- **Close:** Close the application window.

---

## 🧠 How It Works

### Desktop Window Management

WebDesk uses JavaScript to control application windows and CSS to display them as floating panels.

```text
          USER ACTION
               │
               ▼
       Desktop or Taskbar
               │
               ▼
        Open an Application
               │
               ▼
       Display Its Window
               │
               ▼
      Drag / Resize / Control
               │
               ▼
       Interactive Workspace
```

### Notes Storage

The Notes application uses browser local storage to save and retrieve text.

```text
        User Writes a Note
                │
                ▼
          Click Save Note
                │
                ▼
        Browser Local Storage
                │
                ▼
        Retrieve Saved Note
                │
                ▼
          Display in Editor
```

### Calculator Processing

The calculator reads the entered arithmetic expression, checks its permitted characters, evaluates the expression, and displays the result.

```text
       Number and Operator Input
                  │
                  ▼
          Expression Validation
                  │
                  ▼
           Calculate Result
                  │
                  ▼
            Display Output
```

### File Viewer

The File Explorer displays sample file objects defined within the application. JavaScript filters the collection and displays selected file content in a preview panel.

### Wallpaper Customization

CSS gradients provide the wallpaper designs. JavaScript updates the desktop background and the CSS accent variable when a user selects a customization option.

---

## 🛠️ Key Technical Details

| Feature | Implementation |
|---|---|
| Frontend | HTML5 |
| Styling | CSS3 |
| Application logic | Vanilla JavaScript |
| Window management | JavaScript and CSS positioning |
| Desktop interface | Custom desktop and taskbar |
| Notes storage | Browser Local Storage |
| Calculator | JavaScript arithmetic evaluation |
| File Explorer | In-memory demonstration data |
| Wallpaper customization | CSS gradients |
| Accent customization | CSS custom properties |
| Responsive layout | CSS media queries |
| External libraries | None |
| Backend | Not required |
| Database | Not required |
| Installation | Not required |

---

## 📌 Important Notes

- WebDesk is a browser-based desktop simulation, not a real operating system.
- Application windows operate inside the browser page.
- Notes are stored locally in the current browser profile.
- Demo files are held in application memory and are not permanent files on your computer.
- Refreshing the page resets the demo file collection.
- Wallpaper and accent selections are applied to the current page and are not permanently saved.
- The calculator is designed for basic arithmetic, not advanced scientific calculations.
- Browser compatibility and available storage may affect certain features.
- The application does not require an internet connection once the HTML file is available locally.

---

## 🚀 Future Improvements

- 🔐 Add user accounts and authentication.
- 📂 Support importing and exporting text files.
- 💾 Save demo files using browser storage.
- 🖼️ Allow users to upload custom wallpapers.
- 🎵 Add a built-in music player.
- 🌐 Add a browser-style web application.
- 📊 Introduce a system monitor dashboard.
- 🗓️ Add a calendar and reminder application.
- 🧰 Add more built-in productivity tools.
- 🌙 Implement light and dark themes.
- 🎨 Add more desktop themes and customization options.
- 🔔 Introduce desktop notifications.
- 🖱️ Add right-click context menus and desktop shortcuts.
- 📱 Improve mobile window management.
- 🗂️ Add folders and file organization features.

---

## ⚠️ Disclaimer

WebDesk is an educational and personal project demonstrating browser-based interface development using HTML, CSS, and JavaScript.

It simulates selected desktop features inside a web browser and does not replace a full operating system or provide unrestricted access to your computer's files.

---

## 👨‍💻 Author

**Sam Wilson**

🌐 GitHub: https://github.com/rsamwilson2323-cloud

💼 LinkedIn: https://www.linkedin.com/in/sam-wilson-14b554385/

---

## 📜 License

This project is distributed under the license provided in the repository's `LICENSE` file, if one is included.

---

<div align="center">

### 🖥️ WebDesk — Browser-Based Mini Desktop

**Your desktop. Your workspace. Your browser.**

*Built with HTML, CSS, and JavaScript.*

</div>
