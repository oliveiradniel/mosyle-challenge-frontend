# 🧑🏻‍💻 Mosyle Front-End Test - HTML & CSS

This project was developed exclusively for Mosyle’s front-end technical test, using only HTML and CSS.
The goal was to faithfully recreate the provided layout while following best coding practices, without using any external frameworks or libraries.

The challenge was provided as a `.zip` file and also via a Google Drive link.
If you wish to clone this repository, simply run:

```bash
git clone https://github.com/oliveiradniel/mosyle-challenge-frontend.git
```

---

## ✅ HTML Semantics (structure, tags, hierarchy, aria, alt, label, etc.)

- Semantic use of HTML for a clearer and more accessible structure.
- Tags applied correctly to shape the content and maintain logical hierarchy.
- `aria-*` attributes used properly to improve readability and accessibility.
- `alt` attributes correctly added to all images.
- Labels properly associated with their corresponding input elements.

---

## 🎨 CSS (variables, repetition, organization, comments, measurement consistency)

Global CSS variables were created for colors, spacing, and recurring properties, ensuring standardization and visual consistency.
The layout was structured using the 8-point grid system, ensuring proportional and consistent spacing.

The CSS was split into modular files for better organization, maintainability, and scalability.
Some comments were added to explain specific styling choices, and rem units were used for font sizing.

The default arrow on `<select>` elements was replaced with a custom one to ensure fidelity to the original design and better visual alignment.

---

## 📱 Responsiveness (no media queries)

The project was tested across multiple devices and browsers to ensure both visual and functional consistency.
Even without using media queries, the layout naturally adapts to different resolutions through the use of relative units and proportional spacing.

In `<select>` elements, text truncation (`text-overflow: ellipsis`) was implemented to prevent text from overlapping with the arrow icon on smaller screens.

---

## 🧭 Accessibility and best practices (focus states, contrasts, roles, etc.)

Something I always value as a developer is writing maintainable, clean, and accessible code that supports navigation for all users.

Visible focus outlines were added to inputs, checkboxes, and buttons, enabling full keyboard navigation without requiring a mouse.
In the apps section, the title was styled using `text-transform: uppercase` via CSS to preserve proper pronunciation for screen readers and avoid confusion during reading.

Additionally, `aria-hidden="true"` was used for purely decorative images to prevent distractions for screen readers and ensure smoother navigation.

---

## 📂 Project Structure

```
mosyle-challenge-frontend/
├── .vscode/
│   └── settings.json
├── .assets/
│   ├── favicons/
│   └── icons/
├────── css/
│       ├── components/
│       │   ├── assets.css
│       │   ├── buttons.css
│       │   ├── inputs.css
│       │   ├── layouts.css
│       │   ├── texts.css
│       │   └── index.css
│       ├── base.css
│       ├── reset.css
│       └── variables.css
├── .editorconfig
└── index.html
```

---

## 🧩 Final considerations

I’m used to developing projects with modern frameworks and libraries for courses, personal projects, and freelance work.
Recreating this layout using only pure HTML and CSS was a great opportunity to revisit fundamental web development concepts and strengthen my practices in structure, organization, and accessibility.

---

## 🔒 Confidentiality Notice

This project was developed exclusively for Mosyle’s selection process.
Reproduction, in whole or in part, as well as any public disclosure, is strictly prohibited.
The repository will be deleted shortly after the evaluation process.
