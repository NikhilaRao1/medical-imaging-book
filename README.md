# Medical Imaging Online Textbook

This repository hosts an **online draft of a Medical Imaging textbook** developed as part of a research project exploring **AI-assisted educational content**.

The goal is to build an open, modular, and collaboratively edited textbook covering the theory and engineering foundations of medical imaging.

🌐 **Live site:**  
https://nikhilarao1.github.io/medical-imaging-book/

---

## 📘 Current Chapters

- **Chapter 1:** Introduction to Medical Imaging  
- **Chapter 2:** Signal and System Foundations for Medical Imaging  

These chapters are drafts and will continue to be refined.

---

## ✏️ How to Edit Chapter Content (Browser-Based)

All chapters are written in **Markdown** and can be edited directly on GitHub.

### Direct Edit Links
- **Edit Chapter 1:**  
  https://github.com/nikhilarao1/medical-imaging-book/edit/main/chapter1.md

- **Edit Chapter 2:**  
  https://github.com/nikhilarao1/medical-imaging-book/edit/main/chapter2.md

### Steps
1. Open a chapter file  
2. Click the ✏️ **Edit** button  
3. Make changes  
4. Click **Commit changes**

⚠️ Please avoid editing `_layouts`, `_includes`, or `_config.yml` unless necessary.

---

## 🔄 Contribution Workflow (Tentative Edits → Approval)

To support collaboration and review:

- **Main branch (`main`)**  
  Contains approved, published content

- **Tentative edits branch (`tentative-edits`)**  
  Used for proposed or experimental edits

### Recommended Workflow
1. Make edits in the `tentative-edits` branch  
2. Open a Pull Request to `main`  
3. Changes are reviewed and approved before merging

This structure allows:
- Change tracking
- Quality control
- Clear editorial oversight

---

## 🖼️ How to Add Figures

### Image Requirements
- Figures must be **originally generated** (e.g., AI-generated for this textbook), or  
- Clearly **cite external sources** in the caption

### Steps
1. Upload image files to the `images/` folder  
2. Insert images into chapters using the format below

```html
<table align="center">
  <tr>
    <td align="center">
      <img src="images/filename.png" width="400">
      <p style="font-size: 0.8em; color: #555;">
        Figure X. Description of the figure.
      </p>
    </td>
  </tr>
</table>
