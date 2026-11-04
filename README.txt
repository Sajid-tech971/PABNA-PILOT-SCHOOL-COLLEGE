# School Website Project Structure & Setup Guide

## Folders & File Structure

Extract the downloaded ZIP file. The folder layout is organized as follows:

```
school-website/
├── index.html                  <-- Main website code (Open this in browser)
├── README.txt                  <-- Instructions guide
└── images/
    ├── cover.jpg               <-- Your 1920x1080 Custom Cover Banner
    └── teachers/
        ├── teacher1.jpg        <-- Headmaster photo
        ├── teacher2.jpg        <-- Assistant Headmaster photo
        ├── teacher3.jpg        <-- Teacher 3 photo
        └── teacher4.jpg        <-- Teacher 4 photo
```

---

## How to Edit Links & Content (Without Coding)

You can open `index.html` in Notepad, VS Code, or any text editor.

### 1. Changing Sub-Website Links (3-Dot Menu):
Find lines around `#` inside `<aside class="side-drawer">`:
```html
<li>
    <a href="https://your-event-website.com" target="_self" class="drawer-link">
        <i class="fa-solid fa-calendar-star"></i>
        <span>Event Website</span>
    </a>
</li>
```
Simply replace `href="https://your-event-website.com"` with your actual sub-website link!

### 2. Changing Teachers' Links & Details:
Scroll down to the `<script>` section at the bottom of `index.html` where `const teachersData = [...]` is defined:
- Put the teacher's image filename in `image: "images/teachers/teacher1.jpg"`.
- Add links in `facebook`, `whatsapp`, `messenger`, `phone`, `email`, etc.
- **IMPORTANT:** If a teacher does not have a specific account (e.g. `telegram: ""`), leave it empty with `""`. The button will automatically disappear on the website!

---

Enjoy your school website project!
