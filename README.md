![Use Extension](https://raw.githubusercontent.com/bastndev/Astro-Snippets/refs/heads/main/assets/images/banner.jpg)

<p align="center">
    <img src="https://vsmarketplacebadges.dev/version-short/bastndev.astro-js-snippets.jpg?style=for-the-badge&colorA=ff2b7a&colorB=EEEEEE&color=18191e&label=VERSION" alt="Version">&nbsp;
    <img src="https://vsmarketplacebadges.dev/rating-short/bastndev.astro-js-snippets.jpg?style=for-the-badge&colorA=ff2b7a&colorB=EEEEEE&color=18191e&label=Rating" alt="Rating">&nbsp;
    <img src="https://vsmarketplacebadges.dev/downloads-short/bastndev.astro-js-snippets.jpg?style=for-the-badge&colorA=ff2b7a&colorB=EEEEEE&color=18191e&label=Downloads" alt="Downloads">&nbsp;
    <a href="https://github.com/bastndev/Astro-Snippets.tsx"><img src="https://raw.githubusercontent.com/bastndev/Astro-Snippets/main/assets/images/star.png" width="26.6px" alt="Github Star ⭐️"></a>
</p>

</br>

## 🚀 Main Snippets

| 🧩 Snippet               | 🆎 Prefix                  | ⚡ Quick Shortcut |
| ------------------------ | -------------------------- | ----------------- |
| Main Page                | `a-main`                   | `amain`           |
| Layout Component         | `a-layout`                 | `al`              |
| Import Layout            | `a-import-layout`          | `ail`             |
| Import Layout Tailwind   | `a-import-layout-tailwind` | `ailt`            |
| Page with getStaticPaths | `a-page-gsp`               | `apgsp`           |
| Content Collections Page | `a-page-collection`        | `apc`             |

## 🚀 Basic Snippets

| 🧩 Snippet          | 🆎 Prefix         | ⚡ Quick Shortcut |
| ------------------- | ----------------- | ----------------- |
| Astro Component     | `a-component`     | `acomp`           |
| Get Static Paths    | `a-gsp`           | `agsp`            |
| Astro Glob          | `a-glob`          | `aglob`           |
| Get Collection      | `a-collection`    | `acoll`           |
| Astro Named Slot    | `a-slot-named`    | `asn`             |
| Astro Style         | `a-style`         | `astyle`          |
| Astro Script        | `a-script`        | `ascript`         |
| Style & Script      | `a-style-script`  | `ass`             |
| Fragment Named Slot | `a-fragment-slot` | `afs`             |

## 🔀 Expressions and Logic

| 🧩 Snippet         | 🆎 Prefix   | ⚡ Quick Shortcut |
| ------------------ | ----------- | ----------------- |
| Map Expression     | `a-map`     | `amap`            |
| Ternary Expression | `a-ternary` | `aternary`        |
| -                  | -           | -                 |
| Astro Image Import | `a-img`     | `aimg`            |
| Astro Image Tag    | `a-image`   | `aimage`          |

## 🎨 Styles

| 🧩 Snippet | 🆎 Prefix      | ⚡ Quick Shortcut |
| ---------- | -------------- | ----------------- |
| Global CSS | `a-global-css` | `agcss`           |

</br>

### 🚀 How to Use

1. Open a `.astro` or `.css` file.
2. Type any **Quick Shortcut** or **Prefix** (e.g., `al` for Layout or `agcss` for Global CSS).
3. Press `Tab` or `Enter` to expand the snippet.

<details>
<summary>📖 Usage Guide</summary>

### 🎯 **Basic Components**

- **`a-component`**: Component with TypeScript and prop interfaces
- **`a-gsp`**: Static route generation with `getStaticPaths`
- **`a-collection`**: Get content collection with Astro Content Collections

### 🏗️ **Layouts and Structures**

- **`a-layout`**: Full layout component with SEO and dark mode support
- **`a-import-layout`**: Import layout component with basic structure
- **`a-import-layout-tailwind`**: Import layout with Tailwind CSS classes
- **`a-main`**: Complete main page with layout, styles, and scripts

### 🎨 **Styles**

- **`a-global-css`**: Global CSS with CSS variables, dark mode, and Tailwind import
- **`a-style`**: Astro style tag
- **`a-style-script`**: Combined style and script tags with markers

### 🔄 **Dynamic Rendering**

- **`a-map`**: List rendering with `.map()`
- **`a-ternary`**: Conditional rendering with ternary operator

### 🖼️ **Images**

- **`a-img`**: Import Astro Image component
- **`a-image`**: Optimized image tag with width and height

### 📝 **Content Collections**

- **`a-page-collection`**: Dynamic page for content collections with rendering

---

## 🚀 **Quick Start**

1. **Basic Component**: Type `a-component` + Tab to create a component with props
2. **Full Layout**: Type `a-layout` + Tab for a complete layout with SEO
3. **Main Page**: Type `a-main` + Tab for a complete page structure
4. **Global Styles**: Type `a-global-css` + Tab for global CSS with dark mode

## 💡 **Pro Tips**

- **Always use TypeScript**: Snippets automatically include prop interfaces
- **Dark Mode Ready**: Use `a-global-css` for automatic dark mode support
- **Optimize Images**: Use `a-image` instead of simple `<img>` tags
- **Content Collections**: Use `a-collection` for type-safe content management

</details>

## 🧩 Extension Commands [ + ]

This extension includes several commands to help you manage your snippets efficiently. You can access these commands by pressing `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS).

### Main Commands:

- 🛠️ **Astrojs: `Manage Snippets`** - Central hub to edit, delete, refresh, reset, and create snippets
- ✍️ **Astrojs: `Create New Snippet`** - Create a new custom snippet file for any language
- 🔄 **Astrojs: `Refresh Snippets`** - Reload snippets to reflect recent changes

### Additional Commands:

- 📄 **Astrojs: `Open Snippet File`** - Open a snippet file for editing
- ♻️ **Astrojs: `Reset Snippet to Original`** - Restore default snippet from extension
- 🗑️ **Astrojs: `Delete Custom Snippet`** - Remove a custom snippet file

</br>

## Installation

Launch _Quick Open_

- <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> Linux `Ctrl+P`
- <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> macOS `⌘P`
- <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> Windows `Ctrl+P`

Paste the following command and press `Enter`:

```
ext install bastndev.astro-js-snippets
```

## About Me

| [![gohitx](https://github.com/gohitx.png?size=100)](https://gohit.xyz/me) |
| :--------------------------------------------------------------------: |
|                    **[Gohit X](https://gohit.xyz)**                    |
|                         _Creator & Maintainer_                         |

- [🐦 X](https://twitter.com/gohitx) - For questions and discussions.
- 🔴 [Youtube](https://www.youtube.com/@gohitx?sub_confirmation=1) - Code, Software and development insights.
- 💼 [Linkedin](https://www.linkedin.com/in/gohitx) - Professional networking and career updates.

<br>

| Icon                                                                                                                                                                                                                                     | Name                                                           | Description                                                                                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [![Lynx Theme Pro](https://bastndev.gallerycdn.vsassets.io/extensions/bastndev/lynx-theme/0.1.2/1744898058774/Microsoft.VisualStudio.Services.Icons.Default)](https://marketplace.visualstudio.com/items?itemName=bastndev.lynx-theme)   | [Lynx Theme Pro](https://github.com/bastndev/Lynx-Theme)       | A professional extension with six available themes: Dark, Light, Night, Ghibli, Coffee, and Kiro—with integrated icons. Each theme is optimized to offer a more pleasant visual experience.        |
| [![Bracket Lynx](https://bastndev.gallerycdn.vsassets.io/extensions/bastndev/bracket-lynx/0.2.0/1748219628473/Microsoft.VisualStudio.Services.Icons.Default)](https://marketplace.visualstudio.com/items?itemName=bastndev.bracket-lynx) | [Bracket Lynx](https://github.com/bastndev/Bracket-Lynx)       | Enhances the development experience by displaying a label next to each closing parenthesis, indicating the name of the corresponding block or function, along with the start and end line numbers. |
| [![Lynx Keymap Pro](https://raw.githubusercontent.com/bastndev/Lynx-Keymap-Pro/refs/heads/main/assets/images/logo.png)](https://marketplace.visualstudio.com/items?itemName=bastndev.lynx-keymap)                                        | [Lynx Keymap Pro](https://github.com/bastndev/Lynx-Keymap-Pro) | Standardizes keyboard shortcuts across all code editors, allowing you to use key combinations to access any functionality. It improves workflow and development experience.                        |

<div align="center">

**Ready! 🚀 Your (Snippets Astro) are configured.**  
 _If you find any bugs or have feedback, you can [open an issue](https://github.com/bastndev/Lynx-Snippets/issues)._

</div>
