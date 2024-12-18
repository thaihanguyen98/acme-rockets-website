# Acme Rockets - Tailwind Project

This repository hosts the codebase for **Acme Rockets**, a simple static website implementing Tailwind CSS and following CSS best practices. The website is deployed on Render and can be accessed at [https://a-rockets.onrender.com](https://a-rockets.onrender.com).

---

## Get Started with Tailwind CSS

### 1. Initialize a Project with npm
```bash
npm init -y
```

### 2. Install Tailwind CSS as a Development Dependency
```bash
npm install -D tailwindcss@latest
```

### 3. Initialize a Tailwind CSS Configuration File
```bash
npx tailwindcss init
```

### 4. Configure `tailwind.config.js`
Modify the `content` property in the `tailwind.config.js` file to include the paths of your HTML and JavaScript files:
```javascript
content: ["./build/*.html", "./build/js/*.js"],
```

### 5. Add Tailwind Directives to Your CSS
Create an `input.css` file in the `src` folder and include the following directives:
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### 6. Resolve "Unknown At-Rule @tailwind" Error (Optional)
If you encounter the error "unknown at-rule @tailwind" in VSCode, you can resolve it by:
- Modifying VSCode settings for future projects, OR
- Adding a `.vscode/settings.json` file with the following code:

```json
{
  "files.associations": {
    "*.css": "tailwindcss"
  }
}
```
[See more details here.](https://stackoverflow.com/questions/65247279/unknown-at-rule-tailwind-cssunknownatrules)

### 7. Compile CSS with a Script
Add the following script to your `package.json` to compile the CSS file:
```json
"tailwind": "npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch"
```

Run the following command to generate the CSS file in the `build/css` folder:
```bash
npm run tailwind
```

---

## Topics Covered
- **Class Names:** Logical structure and using Emmet to speed up workflow.
- **Responsive Design:** Breakpoints and media queries.
- **Light & Dark Mode:** Adapting to user preferences.
- **Hamburger Menu:** Using HTML symbols or pseudo-elements (`::before`, `::after`) for better accessibility and animations.
- **Custom Classes & Arbitrary Values:** Extending and overriding Tailwind classes (see `tailwind.config.js`).
- **Full-Height Sections:** CSS configuration for sections to adjust to the viewport.
- **Prettier Plugin for Tailwind CSS:** Install with:
  ```bash
  npm install -D prettier-plugin-tailwindcss
  ```

---

## Deployment
# Acme Rockets - Tailwind Project

This repository hosts the codebase for **Acme Rockets**, a simple static website implementing Tailwind CSS and following CSS best practices. The website is deployed on Netlify and can be accessed at [https://a-rockets.netlify.app](https://a-rockets.netlify.app).

---

## Get Started with Tailwind CSS

### 1. Initialize a Project with npm
```bash
npm init -y
```

### 2. Install Tailwind CSS as a Development Dependency
```bash
npm install -D tailwindcss@latest
```

### 3. Initialize a Tailwind CSS Configuration File
```bash
npx tailwindcss init
```

### 4. Configure `tailwind.config.js`
Modify the `content` property in the `tailwind.config.js` file to include the paths of your HTML and JavaScript files:
```javascript
content: ["./build/*.html", "./build/js/*.js"],
```

### 5. Add Tailwind Directives to Your CSS
Create an `input.css` file in the `src` folder and include the following directives:
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### 6. Resolve "Unknown At-Rule @tailwind" Error (Optional)
If you encounter the error "unknown at-rule @tailwind" in VSCode, you can resolve it by:
- Modifying VSCode settings for future projects, OR
- Adding a `.vscode/settings.json` file with the following code:

```json
{
  "files.associations": {
    "*.css": "tailwindcss"
  }
}
```
[See more details here.](https://stackoverflow.com/questions/65247279/unknown-at-rule-tailwind-cssunknownatrules)

### 7. Compile CSS with a Script
Add the following script to your `package.json` to compile the CSS file:
```json
"tailwind": "npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch"
```

Run the following command to generate the CSS file in the `build/css` folder:
```bash
npm run tailwind
```

---

## Topics Covered
- **Class Names:** Logical structure and using Emmet to speed up workflow.
- **Responsive Design:** Breakpoints and media queries.
- **Light & Dark Mode:** Adapting to user preferences.
- **Hamburger Menu:** Using HTML symbols or pseudo-elements (`::before`, `::after`) for better accessibility and animations.
- **Custom Classes & Arbitrary Values:** Extending and overriding Tailwind classes (see `tailwind.config.js`).
- **Full-Height Sections:** CSS configuration for sections to adjust to the viewport.
- **Prettier Plugin for Tailwind CSS:** Install with:
  ```bash
  npm install -D prettier-plugin-tailwindcss
  ```

---

## Deployment
The website is deployed on Netlify and can be accessed here: [https://thaiha-acme-rockets.netlify.app/](https://thaiha-acme-rockets.netlify.app/).

