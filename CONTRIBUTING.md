# Contributing to HolyFin

Thanks for your interest in improving HolyFin! This guide will help you contribute effectively.

## 🎯 Project Philosophy

HolyFin is a **CSS-only theme** with a focus on:
- Deep indigo aesthetics (#5E35B1 primary color)
- Clean, modern design inherited from ElegantFin
- Universal compatibility (desktop, mobile, TV)
- Maintainability and performance

## 🚀 Getting Started

### Prerequisites
- Basic CSS knowledge
- Jellyfin server for testing (recommended)
- Git installed

### Setup
1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/HolyFin.git
   cd HolyFin
   ```
3. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 📝 Making Changes

### CSS Modifications

All theme code is in the `Theme/` directory:
- `HolyFin-theme-v25.12.31.css` - Latest versioned release
- `HolyFin-jellyfin-theme-build-latest.css` - Main readable version
- `HolyFin-jellyfin-theme-build-latest-minified.css` - Production version

**When editing:**
1. Edit the readable `.css` file (not minified)
2. Test your changes in Jellyfin
3. Create a minified version if needed

### Color Scheme

**Maintain the indigo palette:**

```css
/* Primary HolyFin colors */
--holyfin-purple-600: #5E35B1;  /* Main brand color */
--holyfin-purple-500: #673AB7;  /* Hover states */
--holyfin-purple-400: #7E57C2;  /* Secondary accents */
--holyfin-indigo-700: #303F9F;  /* Active states */
```

**Do NOT:**
- ❌ Change primary color away from indigo
- ❌ Use colors outside the indigo/purple family
- ❌ Remove the "HolyFin" text logo

**You CAN:**
- ✅ Adjust opacity/transparency
- ✅ Add new indigo shade variables
- ✅ Improve animations and effects
- ✅ Fix bugs and layout issues

### Testing

1. **Load your CSS in Jellyfin:**
   - Dashboard → General → Custom CSS
   - Paste your modified CSS

2. **Test on multiple devices:**
   - Desktop browser (Chrome, Firefox, Edge)
   - Mobile app (if available)
   - TV interface (if possible)

3. **Check for:**
   - ✅ Visual consistency with indigo theme
   - ✅ Responsive behavior
   - ✅ No broken layouts
   - ✅ Smooth animations
   - ✅ Proper contrast/readability

## 🔀 Submitting Changes

### Pull Request Process

1. **Make your changes with clear commits:**
   ```bash
   git commit -m "feat: add indigo gradient to navigation menu"
   ```

2. **Push to your fork:**
   ```bash
   git push origin feature/your-feature-name
   ```

3. **Create a Pull Request** on GitHub

### PR Guidelines

Your PR should include:

- ✅ **Clear description** of what changed and why
- ✅ **Screenshots** for visual changes
- ✅ **Testing notes** (what you tested on)
- ✅ **Follows existing code style**
- ✅ **No unrelated changes**

### Commit Message Format

Use conventional commits:

```
type(scope): subject

Examples:
feat: add new indigo button style
fix: correct progress bar alignment on mobile
docs: update installation instructions
style: improve card hover animation
refactor: simplify color variable structure
```

**Types:**
- `feat` - New feature
- `fix` - Bug fix
- `docs` - Documentation only
- `style` - Formatting, visual improvements
- `refactor` - Code restructuring
- `test` - Testing related
- `chore` - Maintenance tasks

## 🐛 Reporting Bugs

Use the [Bug Report template](https://github.com/HeiligerG/HolyFin/issues/new?template=bug_report.md)

**Include:**
- Jellyfin version
- Device/browser
- Screenshots
- Steps to reproduce
- Expected vs actual behavior

## 💡 Feature Requests

Use the [Feature Request template](https://github.com/HeiligerG/HolyFin/issues/new?template=feature_request.md)

**Describe:**
- Use case (why is this needed?)
- Expected behavior
- Mockups or examples (if applicable)
- How it fits with the indigo theme

## 📜 Code of Conduct

- ✅ Be respectful and constructive
- ✅ Focus on the issue, not the person
- ✅ Welcome diverse perspectives
- ✅ Give credit where it's due
- ❌ No harassment or discrimination

## 🎨 Design Guidelines

### Indigo Theme Consistency

All new features should:
1. Use the existing indigo color variables
2. Maintain visual harmony with the theme
3. Support light text on dark backgrounds
4. Include hover/active states with indigo variations

### Animation Guidelines

```css
/* Good: Smooth, subtle animations */
transition: all 0.25s cubic-bezier(0.4, 0.0, 0.2, 1);

/* Avoid: Jarring or slow animations */
transition: all 1s linear; /* Too slow */
```

### Accessibility

- Maintain sufficient contrast (WCAG AA minimum)
- Don't rely solely on color to convey information
- Test with keyboard navigation
- Consider screen reader compatibility

## ❓ Questions?

- 💬 [Start a discussion](https://github.com/HeiligerG/HolyFin/discussions)
- 📧 Open an issue for specific questions
- 📖 Check the [README](README.md) for basic info

## 🙏 Credits

**Important:** HolyFin is based on [ElegantFin](https://github.com/lscambo13/ElegantFin) by lscambo13.

When contributing:
- Respect the original author's work
- Maintain attribution in code comments
- Keep the GPL-2.0 license intact

---

## 📋 Quick Checklist

Before submitting a PR:

- [ ] Code follows existing style
- [ ] Maintains indigo color scheme
- [ ] Tested on desktop browser
- [ ] Tested on mobile (if possible)
- [ ] No console errors
- [ ] Screenshots included (for visual changes)
- [ ] Commit messages are clear
- [ ] PR description is complete

---

**Thank you for contributing to HolyFin! 💜**

*Your contributions help make Jellyfin more beautiful for everyone.*
