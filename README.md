# Medical Imaging Online Textbook

This repository hosts an **online draft of a Medical Imaging textbook** developed as part of an undergraduate research project exploring **AI-assisted educational content**.

The goal is to build an open, modular, and collaboratively edited textbook covering the physical principles, system concepts, and engineering foundations of medical imaging.

📂 **GitHub Repository:**  
https://github.com/nikhilarao1/medical-imaging-book

🌐 **Live Website (GitHub Pages):**  
https://nikhilarao1.github.io/medical-imaging-book/

---

## 📘 Current Chapters

- **Chapter 1:** Introduction to Medical Imaging  
- **Chapter 2:** Signal and System Foundations for Medical Imaging  

These chapters are drafts and will be refined collaboratively over time.

---

## ✏️ How to Edit Chapter Content (Browser-Based)

All chapter content is written in **Markdown** and can be edited directly in your browser using GitHub — no local setup required.

### 🔗 Direct Edit Links
- **Edit Chapter 1:**  
  https://github.com/nikhilarao1/medical-imaging-book/edit/main/chapter1.md

- **Edit Chapter 2:**  
  https://github.com/nikhilarao1/medical-imaging-book/edit/main/chapter2.md

### Editing Steps
1. Open the chapter file using one of the links above  
2. Click the ✏️ **Edit** button  
3. Make changes  
4. Click **Commit changes**

⚠️ Please avoid editing files in `_layouts`, `_includes`, or `_config.yml` unless necessary.

---

## 🔄 Contribution Workflow (Tentative Edits → Approval)

To support collaboration while maintaining quality control, this repository uses a review-based workflow.

### Branch Structure
- **`main`**  
  Approved content published on the live website

- **`tentative-edits`**  
  Proposed or experimental edits awaiting review

### Recommended Workflow
1. Make edits in the **`tentative-edits`** branch  
2. Submit a Pull Request to **`main`**  
3. Changes are reviewed and approved before merging

This system allows:
- Clear tracking of proposed changes  
- Editorial oversight  
- Scalable collaboration as more contributors join

---

## 🖼️ How to Add Figures

### Figure Requirements
- Figures should be **originally generated** (e.g., AI-generated for this textbook), or  
- **Clearly cite external sources** in the figure caption

### Steps to Add an Image
1. Upload image files to the `images/` folder  
2. Insert images into chapters using the format below:

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
