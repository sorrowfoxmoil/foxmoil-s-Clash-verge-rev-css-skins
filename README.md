# Clash-verge-rev CSS Themes

一些 Clash Verge 的 CSS 主题展示  
*Some CSS themes for Clash-verge-rev*

---

## 📺 流光效果展示 / Transparent Flow Effect
![选中](https://github.com/user-attachments/assets/a010b6d4-6cbd-4c65-8eb1-e8922418f6dc)
![选中](https://github.com/user-attachments/assets/da85768e-d3d1-41fe-8d74-61e583123f9f)

<details>
<summary><h2>➕背景流光效果 / Background shimmering effect</h2></summary>
<p align="center">
  <img src="https://github.com/user-attachments/assets/36c8ee11-2ead-4f7f-91f3-760aabf9e78a" alt="背景流光版" width="45%" />
  <img src="https://github.com/user-attachments/assets/1e3240ab-5f21-4231-b12a-69c1ba4af9a1" alt="背景流光版1" width="45%" />
</p>
</details>

<details>
<summary>
<h2> 🕶 自定义流光效果 / Custom: Flowing Effect</summary></h2>

---

### 🎨 默认效果：金色流光 / Default Effect: Golden Shimmer

默认的流光效果为金色。
*The default flowing effect is a golden shimmer.*
<p align="center">
<img alt=“金色流光” src="https://github.com/user-attachments/assets/9691293b-2126-4587-b7df-4b8333f7cdbd" width="60%" />
</p>

---

#### 💡 提示与参考 / Tip & Reference

*  具体请参考 `可定义的组件流光-Definable-Component-Flow` 里的注释说明。
*  For details, please refer to the comments within the `Definable-Component-Flow` component.

#### 🛠️ 示例 / Example

- **默认设置为金色流光 / Default setting: golden shimmer**  
  > `--flow-color: 255, 215, 0;`

- **修改为绿色（RGB 值为 $34, 197, 94$） / Change to green (RGB value: $34, 197, 94$)**  
  > `--flow-color: 34, 197, 94;`

- **效果预览 / Result preview:**  
  你将得到绿色流光效果  
  *You will get a green flowing effect*

<p align="center">
  <img alt="绿色流光" src="https://github.com/user-attachments/assets/6e8aadbf-4fb3-47bc-99f8-95a03909019a" width="60%" />
</p>
</details>

<details>
<summary> <h2>☁ 移除悬停强调效果及边框 / Removing Hover Highlight and Border </h2></summary>
  
  ## ❓ 为什么要加入移除效果 / Why Add the Removal Effect

- **原因 / Reason**  
  2.4.3 重构后悬停样式异常，边框与位移失效。为避免视觉混乱，加入移除逻辑。  
  *Refactoring in 2.4.3 broke hover styles. Removal logic prevents visual inconsistency.*
- **目的 / Purpose**  
  保持主题样式一致性，统一用户体验。  
  *Ensure consistent theme styles and user experience.*
- **演示 / Demonstration**
<p align="center">
<img width="45%" alt="image" src="https://github.com/user-attachments/assets/57ff009f-f36a-4396-9b7f-2b5e6f8cdbbd" />
<img width="45%" alt="image" src="https://github.com/user-attachments/assets/d61712cd-b178-4016-9d27-35342138d092" />

</details>

<details>
 <summary> <h2> 🔧修复了代码编辑器的不易读性问题 / Fixing Code Editor Readability</h2> </summary>

  ## ❓ 为什么需要修复 / Why This Fix Is Needed

- **原因 / Reason**  
  CSS 主题使用了非常暴力的全局样式，这虽然能让整个界面变得通透好看，但会破坏 **代码编辑器** 的原生样式。  
  *The CSS theme applies aggressive global styles. While visually appealing, they break the code editor’s built‑in styling.*

- **目的 / Purpose**  
  修复代码编辑器的可读性，并为当前主题做出适配。  
  *Restore readability in the code editor and ensure proper theme compatibility.*

## 🧩 用法 / Usage

直接将 `css部分` 复制到现有的 `css` 末尾即可。  
*Simply copy the provided CSS snippet to the end of your existing CSS.*

## 🔍 对比 / Compare

以黑红主题为例  
*Example: Black‑Red Theme*

<p align="center">
<img width="45%" alt="image" src="https://github.com/user-attachments/assets/addd65a5-f833-4044-a724-1023db5770f2" />
<img width="45%" alt="image" src="https://github.com/user-attachments/assets/5cbbb6f2-49c9-43f8-a5ac-2a9dfb99bb7f" />
</p>

</details>



<h2>深色主题</h2>

### 🔴🔵 流光 / Transparent Red & Blue-Violet
<p align="center">
  <img src="https://github.com/user-attachments/assets/057fbaf8-9446-448b-af12-7dd206c852b9" width="45%" />
  <img src="https://github.com/user-attachments/assets/d026ee25-e87f-4593-942b-248e5e9bf740" width="45%" />
</p>

### 🪟 毛玻璃 / Frosted Glass Red & Blue-Purple
<p align="center">
  <img src="https://github.com/user-attachments/assets/ee9e9268-2104-4796-b05e-23295e4da90f" width="45%" />
  <img src="https://github.com/user-attachments/assets/87dd0230-3789-47f7-80f9-4436b143bcc6" width="45%" />
</p>

### ✨ 更加透明 / More Transparent Red & Blue-Violet
<p align="center">
  <img src="https://github.com/user-attachments/assets/8beeaef9-6b95-4629-958e-33e8f9f3d7a8" width="45%" />
  <img width="45%" src="https://github.com/user-attachments/assets/10e77702-b8ae-4fc4-a985-3fce3edf59d7" />


</p>

### ❄️ 完全毛玻璃 / Completely Frosted Glass Red & Blue-Purple
<p align="center">
  <img src="https://github.com/user-attachments/assets/7d783542-fa1a-4ed0-96ab-42f32d984d8c" width="45%" />
  <img src="https://github.com/user-attachments/assets/8324fe16-6ffb-48cb-8106-7ed2a58c1126" width="45%" />
</p>

---
<details>
<summary><h2>浅色主题</h2></summary>
  
### ❄️ 看着还行的浅色蓝紫 / Decent Light Blue-Violet
<p align="center">
  <img width="50%" alt="image" src="https://github.com/user-attachments/assets/22a65b50-a8fb-442e-8645-741eb76e31d9" />
</p>

### ✨ 更模糊的浅色蓝紫 / Deeper Light Blue-Violet
<p align="center">
  <img width="50%" alt="image" src="https://github.com/user-attachments/assets/29aec7c7-921c-4782-8c78-8a12fd731df4" />
</p>
</details>

<details>
<summary> <h2>⚠️ 已知问题 / Known Issues</h2></summary>

- **透明度过高**：部分组件透明度过高，导致重叠  
  *Some components are too transparent, causing overlap*  
  <img src="https://github.com/user-attachments/assets/046396b3-355f-4e2d-8349-94d53ee91ee9" height="300" />

- ~~- **开关像素问题**~~  
  ~~*Switch pixel rendering issue*~~  
  <img src="https://github.com/user-attachments/assets/a1847752-2ee5-43e2-9963-2b99b7aeb0b9" width="120" />

- **已解决**  
  *Solution*  
  将 <code>开关组件修复-Switch Fix.css</code> 的内容复制到现有 `css` 的末尾即可对齐开关像素
  > To align the switch pixels, copy the content of `<code>Switch Fix.css</code>` to the end of your existing `css`.


- **边框异常**：设置页面部分组件边框渲染异常  
  *Border rendering issue on settings page*  
  <img src="https://github.com/user-attachments/assets/bb839306-e53b-4e32-a681-b3d9493e0b71" width="500" />
</details>

---

## 📥 使用方法 / How to Use

1. **复制主题 CSS**  
   打开你喜欢的主题 CSS 内容并复制  
   *Copy the CSS of the theme you like*

2. **打开设置**  
   Clash Verge Rev → 设置 → 主题设置 → CSS 注入  
   *Clash Verge Rev → Settings → Theme Settings → CSS Injection*

3. **粘贴并保存**  
   将 CSS 粘贴到“CSS 注入”，点击保存  
   *Paste the CSS into “CSS Injection” and save*

---

<h2>可自定义效果 / Customizable effects.</h2>
<details>
  
<summary><h3> 🌈 自定义流光效果 / How to Add Flowing Effect
</summary></h3>

1. **粘贴流光 CSS**  
   将 main 分支中的自定义流光效果 CSS 文件内容复制，并粘贴到你现有主题 CSS 的末尾  
   *Copy the flowing effect CSS from the main branch and paste it at the end of your existing theme CSS*

2. **打开设置**  
   Clash Verge Rev → 设置 → 主题设置 → CSS 注入  
   *Clash Verge Rev → Settings → Theme Settings → CSS Injection*

3. **粘贴并保存**  
   将完整 CSS 粘贴到“CSS 注入”，点击保存即可启用流光效果  
   *Paste the full CSS into “CSS Injection” and click save to enable the flowing effect*

4. **自定义颜色与透明度（可选）**  
   修改 `--flow-color` 或 `--bg-flow-color` 的 RGB 数值以更换颜色；调整 `rgba(..., 透明度)` 中的透明度系数（如 0.2、0.35、0.5）以增强或减弱效果  
   *Customize the color by editing the RGB values in `--flow-color` or `--bg-flow-color`; adjust the alpha values in `rgba(..., alpha)` (e.g., 0.2, 0.35, 0.5) to strengthen or soften the effect*
</details>
<details>
<summary><h3> 🔧 移除悬停强调效果及边框 / Usage Guide for Removing Hover Highlight and Border
</summary></h3>

  - **用法 / How to Use**  
  将对应的「移除悬停强调效果及边框」CSS 代码复制到你现有的 CSS 文件末尾，即可生效  
  *Copy the CSS code for “Remove Hover Highlight and Border” and paste it at the end of your existing CSS file to activate it*
</details>
