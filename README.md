# ✦ ZENITH DOCS ENGINE
### Interactive Developer Documentation Hub & API Explorer

<p align="center">
  <strong>Build Better. Ship Faster. Document Smarter.</strong>
</p>

<p align="center">
  A modern, responsive developer documentation platform featuring multi-level navigation, interactive code examples, API references, and a carefully structured documentation experience.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Responsive-Design-635BFF?style=for-the-badge" alt="Responsive Design">
  <img src="https://img.shields.io/badge/JavaScript-Not%20Required-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="No JavaScript Required">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License">
</p>

---

## 📌 01. Project Overview

**Zenith Docs Engine** is a front-end developer documentation platform created to demonstrate modern interface engineering, accessible content organisation, responsive layouts, and advanced CSS interaction techniques.

Inspired by professional developer documentation environments, Zenith provides a structured interface where developers can navigate technical guides, explore API endpoints, examine code examples, and access useful development resources.

The platform is designed around three essential principles:

- **Clarity:** Organised documentation that makes technical information easier to understand.
- **Accessibility:** Semantic HTML and intuitive navigation patterns.
- **Efficiency:** A responsive interface that helps developers find relevant information quickly.

Rather than relying on JavaScript frameworks, this project demonstrates how modern HTML5 and CSS3 can deliver sophisticated interactive interfaces using native browser capabilities.

## ✨ 02. Key Features

### 🧭 Multi-Level Documentation Navigation

- Collapsible sidebar navigation using native HTML `<details>` and `<summary>` elements.
- Categorised documentation sections.
- Nested navigation links for related technical topics.
- Dedicated navigation areas for getting started, core concepts, API references, and advanced guides.

### 💻 Interactive Code Explorer

A CSS-powered code comparison interface that allows users to switch between different code examples.

Available code tabs:

- HTML — Interface structure and semantic markup.
- CSS — Component styling and visual presentation.
- cURL — HTTP request examples and API communication.

The interface uses hidden radio inputs and CSS `:checked` selectors to control tab visibility without JavaScript.

### 🔗 API Reference Documentation

A structured API reference section demonstrating common REST API endpoints.

| HTTP Method | Endpoint | Description |
|:---|:---|:---|
| GET | `/api/v1/users` | Retrieve all users |
| GET | `/api/v1/users/{id}` | Retrieve a specific user |
| POST | `/api/v1/users` | Create a new user |
| PUT | `/api/v1/users/{id}` | Update user information |
| DELETE | `/api/v1/users/{id}` | Delete a user |

*Note: These endpoints are illustrative documentation examples, not connected to a live backend.*

### 📚 Structured Documentation Sections

The platform includes dedicated sections covering:

- Introduction and platform overview.
- Development environment installation.
- Authentication and authorisation.
- API requests and responses.
- JSON response examples.
- Error handling and HTTP status codes.
- Security guidelines.
- Development best practices.
- External developer learning resources.

### 📍 On-Page Table of Contents

- Dedicated right-side documentation navigation.
- Sticky positioning on larger screens.
- Direct navigation to documentation sections.
- CSS `:target` highlighting when a section is opened through its anchor link.

### 📱 Responsive Interface

- Desktop-oriented three-column documentation layout.
- Tablet-friendly navigation.
- Mobile-responsive content presentation.
- Flexible content widths and typography.
- CSS Grid and Flexbox layouts.

### 🖨️ Print-Optimised Documentation

A dedicated print stylesheet using `@media print` to:

- Remove unnecessary navigation elements.
- Simplify the documentation layout.
- Improve printed content readability.
- Display code examples in a print-friendly format.

### 🎨 Modern Visual Design

- Professional purple and indigo colour palette.
- Consistent design tokens using CSS custom properties.
- Fluid typography using `clamp()`.
- Modern cards, information panels, and code windows.
- Subtle transitions and hover interactions.
- Carefully structured content hierarchy.

---

## 🛠️ 03. Technology Stack

Zenith Docs Engine is built using lightweight front-end technologies without external frameworks.

| Technology | Implementation |
|:---|:---|
| HTML5 | Semantic document structure |
| CSS3 | Styling and visual design |
| CSS Grid | Main documentation layout |
| Flexbox | Navigation and component alignment |
| CSS Variables | Reusable design tokens |
| CSS Custom Selectors | Interactive interface states |
| CSS Animations | Transitions and visual feedback |
| Media Queries | Responsive layouts |
| HTML Details/Summary | Collapsible navigation |
| Radio Inputs | Interactive code tabs |

**No JavaScript framework, build tools, or external dependencies are required.**

---

## 🧠 04. Advanced CSS Concepts Demonstrated

This project demonstrates practical application of several modern CSS techniques.

**1. CSS Grid and Flexbox**

Used to construct the documentation layout, align interface components, and organise navigation elements.

**2. CSS Custom Properties**

Centralised colour values, spacing-related styling, and reusable design variables using `:root`.

**3. Fluid Typography**

Uses `clamp()` to create flexible typography that adapts to different viewport sizes.

**4. CSS State Management**

Uses hidden radio controls with `:checked` selectors to switch between code examples.

**5. Native HTML Interactions**

Uses `<details>` and `<summary>` for accessible collapsible navigation.

**6. CSS Target Highlighting**

Uses `:target` to visually highlight sections reached through documentation links.

**7. Responsive Media Queries**

Uses carefully selected breakpoints to adapt the layout for desktop, tablet, and mobile devices.

**8. Print Media Queries**

Uses `@media print` to provide a simplified document presentation suitable for printing.

---

## 📂 05. Project Structure

```text
zenith-docs-engine/
│
├── index.html
│   └── Main documentation structure,
│       navigation, API examples and content.
│
├── style.css
│   └── Complete visual styling,
│       responsive layouts and CSS interactions.
│
└── README.md
    └── Project documentation and setup guide.
```

---

## 🚀 06. Getting Started

Follow these instructions to run the project locally.

### Prerequisites

You need:

- A computer running Windows, macOS, or Linux.
- Visual Studio Code or another code editor.
- A modern web browser.
- Git installed on your computer.

### Step 1: Clone the Repository

Open your terminal and run:

```bash
git clone https://github.com/Regalson001/zenith-docs-engine.git
```

### Step 2: Navigate into the Project

```bash
cd zenith-docs-engine
```

### Step 3: Open in Visual Studio Code

```bash
code .
```

### Step 4: Launch the Application

Open `index.html` in your browser.

Alternatively, install the Live Server extension in Visual Studio Code, right-click `index.html`, and select **Open with Live Server**.

Your documentation interface should now be running locally.

---

## 🎯 07. Project Objectives

The primary objective of Zenith Docs Engine is to demonstrate the ability to design and develop a professional documentation interface using core front-end technologies.

The project demonstrates practical understanding of:

- Semantic HTML architecture.
- Accessible navigation patterns.
- Advanced CSS selectors.
- Responsive interface engineering.
- Documentation information architecture.
- Code presentation and technical readability.
- Reusable styling conventions.
- Print-friendly document layouts.

---

## 🔮 08. Future Enhancements

The current implementation provides a functional front-end documentation interface. Future versions could introduce:

| Enhancement | Planned Improvement |
|:---|:---|
| Documentation Search | Real-time search across documentation |
| Clipboard Integration | Functional copy-to-clipboard buttons |
| Theme Switching | Interactive dark and light modes |
| API Playground | Execute real HTTP requests |
| Dynamic Navigation | JavaScript-powered active section tracking |
| Syntax Highlighting | Dedicated syntax highlighting library |
| Backend Integration | Connect to a real API service |
| Documentation CMS | Dynamically manage documentation content |

These enhancements would expand Zenith from a static documentation interface into a more complete developer documentation platform.

---

## ⚙️ 09. Current Implementation Notes

Zenith Docs Engine is currently a **static front-end project**.

The collapsible navigation, CSS code tabs, anchor navigation, responsive layouts, and print stylesheet work in the browser without JavaScript.

Some advanced features, including real API execution, clipboard copying, dynamic search, and backend authentication, are documented as future enhancements rather than implemented functionality.

This distinction keeps the project's technical presentation accurate and transparent.

---

## 👨‍💻 10. Author

**Stephen Oyugi**

Front-End Developer | AI Automation Engineer | Machine Learning Practitioner

Interested in building modern web interfaces, intelligent automation systems, and practical software solutions.

<p>
  <a href="https://github.com/Regalson001">GitHub Profile</a> ·
  <a href="https://linkedin.com/in/stephenoyugi001">LinkedIn Profile</a>
</p>

---

## 📄 11. License

This project is distributed under the MIT License.

You are welcome to study, modify, and extend the project in accordance with the terms of the licence.

---

<p align="center">
  <strong>ZENITH DOCS ENGINE</strong>
  <br>
  <em>Build Better. Ship Faster. Document Smarter.</em>
  <br><br>
  Designed and developed with HTML5 and CSS3.
  <br>
  © 2026 Stephen Oyugi. All Rights Reserved.
</p>
