# 📄 CoAudit - Tax Audit AI – Intelligent Invoice Extraction System  
🚀 **AI-powered tool for tax auditors to process and analyze financial documents**  

## 🌟 Overview  
**Tax Audit AI** is a web-based application that helps tax auditors efficiently search and extract key data points from scanned or digital files (PDFs). Using AI, the system detects invoices, extracts relevant details (invoice number, amount, date), and processes files asynchronously, allowing users to continue working while their documents are analyzed.  

## 🔥 Key Features *(Planned)*  
✔️ **AI-Powered Invoice Detection** – Identify invoices in scanned and digital files.  
✔️ **Key Data Extraction** – Extract critical details like invoice numbers, amounts, and dates.  
✔️ **Asynchronous Processing** – Users can continue working while files are being analyzed.  
✔️ **User Authentication** – Secure login system to manage and track uploaded files.  
✔️ **Multi-File Upload Support** – Upload individual PDFs or ZIP archives.  
✔️ **Scalable Architecture** – Expandable to support additional document analysis beyond invoices.  

## 📌 How It Works  
1️⃣ **Upload** PDFs or ZIP files through the web interface.  
2️⃣ **AI scans** each document to detect invoices.  
3️⃣ **Extracted data** is displayed for easy review and export.  
4️⃣ **Asynchronous processing** allows users to continue working while analysis runs in the background.  

## 📈 Roadmap  
✅ **Phase 1**: Build authentication and file upload system  
✅ **Phase 2**: Implement AI-driven invoice detection  
✅ **Phase 3**: Extract invoice details and refine accuracy  
✅ **Phase 4**: Scale for broader financial document processing  

## 💼 Licensing & Commercial Use  
This project is under development and is intended for commercial use. Licensing details will be provided upon release.  

## 👥 Contact & Contributions  
🔹 Interested in testing or partnering? Reach out via [your contact info].  
🔹 Have feedback or feature suggestions? Open an issue!  

---

Stay tuned for updates! 🚀  


# Repository created using Mantine Next.js template

This is a template for [Next.js](https://nextjs.org/) app router + [Mantine](https://mantine.dev/).
If you want to use pages router instead, see [next-pages-template](https://github.com/mantinedev/next-pages-template).

## Features

This template comes with the following features:

- [PostCSS](https://postcss.org/) with [mantine-postcss-preset](https://mantine.dev/styles/postcss-preset)
- [TypeScript](https://www.typescriptlang.org/)
- [Storybook](https://storybook.js.org/)
- [Jest](https://jestjs.io/) setup with [React Testing Library](https://testing-library.com/docs/react-testing-library/intro)
- ESLint setup with [eslint-config-mantine](https://github.com/mantinedev/eslint-config-mantine)

## npm scripts

### Build and dev scripts

- `dev` – start dev server
- `build` – bundle application for production
- `analyze` – analyzes application bundle with [@next/bundle-analyzer](https://www.npmjs.com/package/@next/bundle-analyzer)

### Testing scripts

- `typecheck` – checks TypeScript types
- `lint` – runs ESLint
- `prettier:check` – checks files with Prettier
- `jest` – runs jest tests
- `jest:watch` – starts jest watch
- `test` – runs `jest`, `prettier:check`, `lint` and `typecheck` scripts

### Other scripts

- `storybook` – starts storybook dev server
- `storybook:build` – build production storybook bundle to `storybook-static`
- `prettier:write` – formats all files with Prettier
