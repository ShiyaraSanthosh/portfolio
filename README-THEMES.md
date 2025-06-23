# 🎨 Color Themes for Developer Portfolio

Your portfolio now includes **6 beautiful, modern color themes** that you can easily switch between!

## 🚀 Quick Theme Switch

To change themes, edit `app/css/color-themes.scss`:

1. **Comment out** the current active theme (wrap with `/* */`)
2. **Uncomment** your desired theme (remove `/* */`)
3. Save the file and refresh your browser

## 🎯 Available Themes

### 1. **Modern Professional** (Default)

- **Colors**: Cool blue with cyan accent (`#00d4ff`, `#7c3aed`)
- **Vibe**: Clean, professional, tech-focused
- **Best for**: Corporate, SaaS, fintech portfolios

### 2. **Cyberpunk Neon**

- **Colors**: Electric cyan and hot pink (`#00ffff`, `#ff0080`)
- **Vibe**: Futuristic, edgy, high-energy
- **Best for**: Gaming, creative, blockchain portfolios

### 3. **Warm Sunset**

- **Colors**: Amber and pink gradients (`#f59e0b`, `#ec4899`)
- **Vibe**: Warm, inviting, creative
- **Best for**: Design, marketing, lifestyle portfolios

### 4. **Emerald Forest**

- **Colors**: Deep greens with gold accents (`#10b981`, `#f59e0b`)
- **Vibe**: Natural, growth-focused, sustainable
- **Best for**: Environmental, health, education portfolios

### 5. **Royal Purple**

- **Colors**: Deep purples with gold highlights (`#a855f7`, `#fbbf24`)
- **Vibe**: Luxurious, premium, sophisticated
- **Best for**: Luxury brands, consulting, high-end services

### 6. **Ocean Depths**

- **Colors**: Deep blues with teal accents (`#06b6d4`, `#3b82f6`)
- **Vibe**: Calm, trustworthy, stable
- **Best for**: Healthcare, finance, legal portfolios

## 🛠️ Using Theme Classes

Replace your hardcoded colors with theme-aware classes:

### Old way:

```jsx
<div className="bg-[#0d1224] text-[#16f2b3]">
```

### New way:

```jsx
<div className="theme-bg-primary theme-text-accent-primary">
```

## 📚 Available CSS Classes

### Background Colors

- `theme-bg-primary` - Main background
- `theme-bg-secondary` - Secondary sections
- `theme-bg-tertiary` - Cards and components
- `theme-bg-card` - Individual cards

### Text Colors

- `theme-text-primary` - Main text (white)
- `theme-text-secondary` - Secondary text
- `theme-text-muted` - Muted/subtle text
- `theme-text-accent-primary` - Primary accent color
- `theme-text-accent-secondary` - Secondary accent color

### Special Effects

- `theme-gradient-text` - Gradient text effect
- `theme-gradient-bg` - Gradient background
- `theme-hover-accent` - Hover color change
- `theme-hover-glow` - Hover glow effect

## 🎨 Color Variables

You can also use CSS variables directly:

```css
.my-custom-element {
  background: var(--bg-primary);
  color: var(--accent-primary);
  border: 1px solid var(--border-primary);
}
```

## ✨ Pro Tips

1. **Test on different devices** - Colors may look different on various screens
2. **Consider your audience** - Choose themes that match your target industry
3. **Accessibility** - All themes maintain good contrast ratios
4. **Consistency** - Use theme classes instead of hardcoded colors for easy switching

## 🔧 Customization

Want to create your own theme? Copy any existing theme block in `color-themes.scss` and modify the color values. Make sure to:

- Keep the same CSS variable names
- Test contrast ratios for accessibility
- Include both light and dark color variants

---

**Current Active Theme**: Modern Professional
**Last Updated**: December 2024

Enjoy your new beautiful color themes! 🚀
