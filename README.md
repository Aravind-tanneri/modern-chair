  
A fully responsive, interactive e-commerce product card built to demonstrate the power of **Tailwind CSS v4** and modern CSS selectors. Made as a part of love babbar's web dev course! ❤️

## 🚀 Overview

This project showcases how to build complex UI interactions—like color switching, animations, and dynamic theming—**without JavaScript**. It relies entirely on HTML structure and advanced CSS logic.

## SCREEN RECORDING

https://github.com/user-attachments/assets/35d50ea9-bd01-46fa-bf79-65c4c4a4f869

## ✨ Key Features

* **Zero JavaScript Logic:** State management handles purely via the "Radio Button Hack" and CSS peers.
* **Tailwind v4 Configuration:** Uses the new `@theme` block for custom animations and color variables.
* **Advanced Selectors:** utilizes `body:has()` to control global background gradients from a local component.
* **Custom Animations:** Features a custom "Shake" effect on selection and "Fade Up" entry animations.
* **Responsive Design:** Mobile-first layout that transforms into an overlapping grid on desktop.
* **Dynamic Theming:** "Add to Cart" button automatically adapts its color to match the selected chair.

## 🛠️ Tech Stack

* **HTML5** (Semantic structure)
* **Tailwind CSS v4** (Utility-first styling & Variables)
* **Vite** (Build tool)

## 📦 How to Run
    ```
    git clone [https://github.com/yourusername/modern-chair-card.git](https://github.com/yourusername/modern-chair-card.git)
    cd modern-chair-card
    npm install
    npm run dev
    ```

## 💡 Code Highlights

### The "Chameleon" Selector
Changing the background based on a nested input using the `:has()` selector:

```
<div class="[body:has(#color2:checked)_&]:opacity-100 ...">
  ...
</div>
