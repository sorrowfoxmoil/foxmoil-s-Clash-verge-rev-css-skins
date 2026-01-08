<p align="center">
  <a href="readme.md">简体中文</a> | <b>English</b>
</p>

# Clash-verge-rev CSS Themes

*Some CSS themes for Clash-verge-rev*

---

## 📺 Transparent Flow Effect Preview
![selected](https://github.com/user-attachments/assets/a010b6d4-6cbd-4c65-8eb1-e8922418f6dc)
![selected](https://github.com/user-attachments/assets/da85768e-d3d1-41fe-8d74-61e583123f9f)

<details>
<summary><h2>➕ Background Shimmering Effect</h2></summary>
<p align="center">
  <img src="https://github.com/user-attachments/assets/36c8ee11-2ead-4f7f-91f3-760aabf9e78a" alt="bg-shimmer-1" width="45%" />
  <img src="https://github.com/user-attachments/assets/1e3240ab-5f21-4231-b12a-69c1ba4af9a1" alt="bg-shimmer-2" width="45%" />
</p>
</details>

<details>
<summary>
<h2> 🕶 Custom: Flowing Effect</summary></h2>

---

### 🎨 Default Effect: Golden Shimmer

The default flowing effect is a golden shimmer.
<p align="center">
<img alt="Golden Shimmer" src="https://github.com/user-attachments/assets/9691293b-2126-4587-b7df-4b8333f7cdbd" width="60%" />
</p>

---

#### 💡 Tip & Reference

* For details, please refer to the comments within the `Definable-Component-Flow` component.

#### 🛠️ Example

- **Default setting: golden shimmer** > `--flow-color: 255, 215, 0;`

- **Change to green (RGB value: $34, 197, 94$)** > `--flow-color: 34, 197, 94;`

- **Result preview:** You will get a green flowing effect.

<p align="center">
  <img alt="Green Shimmer" src="https://github.com/user-attachments/assets/6e8aadbf-4fb3-47bc-99f8-95a03909019a" width="60%" />
</p>
</details>

<details>
<summary> <h2>☁ Removing Hover Highlight and Border </h2></summary>
  
  ## ❓ Why Add the Removal Effect

- **Reason** Refactoring in 2.4.3 broke hover styles, causing border and displacement issues. Removal logic prevents visual inconsistency.
- **Purpose** Ensure consistent theme styles and a unified user experience.
- **Demonstration**
<p align="center">
<img width="45%" alt="image" src="https://github.com/user-attachments/assets/57ff009f-f36a-4396-9b7f-2b5e6f8cdbbd" />
<img width="45%" alt="image" src="https://github.com/user-attachments/assets/d61712cd-b178-4016-9d27-35342138d092" />
</p>

</details>

<details>
 <summary> <h2> 🔧 Fixing Code Editor Readability</h2> </summary>

  ## ❓ Why This Fix Is Needed

- **Reason** The CSS theme applies aggressive global styles. While visually appealing, they break the code editor’s built‑in styling.

- **Purpose** Restore readability in the code editor and ensure proper theme compatibility.

## 🧩 Usage

Simply copy the provided CSS snippet to the end of your existing CSS.

## 🔍 Compare

Example: Black‑Red Theme

<p align="center">
<img width="45%" alt="image" src="https://github.com/user-attachments/assets/addd65a5-f833-4044-a724-1023db5770f2" />
<img width="45%" alt="image" src="https://github.com/user-attachments/assets/5cbbb6f2-49c9-43f8-a5ac-2a9dfb99bb7f" />
</p>

</details>

## 🌑 Dark Themes

### 🔴🔵 Transparent Red & Blue-Violet
<p align="center">
  <img src="https://github.com/user-attachments/assets/057fbaf8-9446-448b-af12-7dd206c852b9" width="45%" />
  <img src="https://github.com/user-attachments/assets/d026ee25-e87f-4593-942b-248e5e9bf740" width="45%" />
</p>

### 🪟 Frosted Glass Red & Blue-Purple
<p align="center">
  <img src="https://github.com/user-attachments/assets/ee9e9268-2104-4796-b05e-23295e4da90f" width="45%" />
  <img src="https://github.com/user-attachments/assets/87dd0230-3789-47f7-80f9-4436b143bcc6" width="45%" />
</p>

### ✨ More Transparent Red & Blue-Violet
<p align="center">
  <img src="https://github.com/user-attachments/assets/8beeaef9-6b95-4629-958e-33e8f9f3d7a8" width="45%" />
  <img width="45%" src="https://github.com/user-attachments/assets/10e77702-b8ae-4fc4-a985-3fce3edf59d7" />
</p>

### ❄️ Completely Frosted Glass Red & Blue-Purple
<p align="center">
  <img src="https://github.com/user-attachments/assets/7d783542-fa1a-4ed0-96ab-42f32d984d8c" width="45%" />
  <img src="https://github.com/user-attachments/assets/8324fe16-6ffb-48cb-8106-7ed2a58c1126" width="45%" />
</p>

---

<details>
<summary><h2>🌕 Light Themes</h2></summary>
  
### ❄️ Decent Light Blue-Violet
<p align="center">
  <img width="50%" alt="image" src="https://github.com/user-attachments/assets/22a65b50-a8fb-442e-8645-741eb76e31d9" />
</p>

### ✨ Deeper Light Blue-Violet
<p align="center">
  <img width="50%" alt="image" src="https://github.com/user-attachments/assets/29aec7c7-921c-4782-8c78-8a12fd731df4" />
</p>
</details>

<details>
<summary> <h2>⚠️ Known Issues</h2></summary>

- **High Transparency**: Some components are too transparent, causing overlap.

<div>
  <img src="https://github.com/user-attachments/assets/046396b3-355f-4e2d-8349-94d53ee91ee9" height="300" /></div>

- **Fixed: Switch Rendering Issue** To align the switch pixels, copy the content of `Switch Fix.css` to the end of your existing CSS.
<div>
  <img src="https://github.com/user-attachments/assets/a1847752-2ee5-43e2-9963-2b99b7aeb0b9" width="120" />
</div>
- **Border Issues**: Border rendering issues on the settings page for some components.
  <img src="https://github.com/user-attachments/assets/bb839306-e53b-4e32-a681-b3d9493e0b71" width="500" />
</details>

---

## 📥 How to Use

1. **Copy Theme CSS** Open the CSS file of the theme you like and copy its content.
2. **Open Settings** Clash Verge Rev → Settings → Theme Settings → CSS Injection.
3. **Paste and Save** Paste the CSS into "CSS Injection" and click Save.

---

## 🔧 Customizable Effects

<details>
<summary><h3> 🌈 How to Add Flowing Effect </h3></summary>

1. **Paste Flowing CSS** Copy the flowing effect CSS from the main branch and paste it at the end of your existing theme CSS.
2. **Open Settings** Clash Verge Rev → Settings → Theme Settings → CSS Injection.
3. **Paste and Save** Click save to enable the flowing effect.
4. **Customize Color & Opacity (Optional)** Edit the RGB values in `--flow-color` or `--bg-flow-color` to change colors; adjust alpha values in `rgba(..., alpha)` (e.g., 0.2, 0.35, 0.5) to change intensity.
</details>

<details>
<summary><h3> 🔧 Removing Hover Highlight and Border </h3></summary>

- **How to Use** Copy the "Remove Hover Highlight and Border" CSS code and paste it at the end of your existing CSS file to activate it.
</details>
