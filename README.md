# git-translate 🌐💻

<img width="150" height="150" alt="image" src="https://github.com/user-attachments/assets/84083bb3-0ba3-4911-b750-8d6036d95fa0" />

**git-translate** is an open-source, web-based tool designed to translate scripts and source code from one programming language to another—functioning like Google Translate or Convertio, but built exclusively for developers.

Need to convert UI styles from JavaScript/JSX object literals straight into pure CSS, or map logic rules across frameworks? Just paste your code, select the parameters, and get your compiled syntax instantly.

🔗 **Live Demo:** https://git-translate-three.vercel.app/

---

## ✨ Features

- **Multi-Language Interface:** Clean, dual-panel layout (Input / Output) built for coding efficiency.
- **CamelCase to Kebab-Case Compilation:** Built-in compiler that seamlessly transforms JavaScript Style Objects into structural, production-ready CSS code.
- **Developer UX:** One-click clipboard copy feature, instant input clear, and integrated monospace code font preview.
- **Ultra-Lightweight:** Written in raw semantic HTML, styling injected via Tailwind CSS CDN, and vanilla JS architecture. Zero heavy framework overhead.

---

## 🚀 How It Works

The engine runs completely on the client side using a clean AST-like structural parser in JavaScript to map properties across programming paradigms:

[ JavaScript Object ] ➡️ [ Tokenized Key-Value Check ] ➡️ [ Kebab-case CSS Class Rule ]

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any improvements, bug fixes, or translations features are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

   ---
