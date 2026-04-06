# Medical Imaging Online Textbook

This repository hosts a draft of an online Medical Imaging textbook developed as part of a research project on AI-assisted educational content.

The website is published at:  
[https://nikhilarao1.github.io/medical-imaging-book/](https://nikhilarao1.github.io/medical-imaging-book/)

## 📘 Current Chapters
- Chapter 1: Introduction to Medical Imaging
- Chapter 2: Signal and System Foundations for Medical Imaging

These chapters are drafts and will be refined collaboratively. Later chapters and quizzes will also be added.

---

## ✏️ How to Edit Chapter Content

Chapter text is written in Markdown. You can edit chapters **directly in your browser** without any local setup.

1. Open the chapter file (`chapter1.md` or `chapter2.md`) in the repository.
2. Click the pencil icon ✏️ to edit the file.
3. Make your changes and commit them to the branch you are working on (see **Tentative Edits Workflow** below).
4. Do **not** edit `_layouts`, `_includes`, or `_config.yml` unless necessary for site functionality.

---

## 🖼️ How to Add Images

1. Upload your image files to the `images/` folder in the repository.
2. Insert images into chapters using this format:

```html
<table align="center">
  <tr>
    <td align="center">
      <img src="images/filename.png" width="400">
      <p style="font-size: 0.8em; color: #555;">
        Figure X. Description of the figure. Include source or indicate "AI-generated".
      </p>
    </td>
  </tr>
</table>
