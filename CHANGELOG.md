# Changelog

All notable changes to HolyFin will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.0] - 2026-01-03

### 🎨 Initial Release - Complete ElegantFin to HolyFin Transformation

#### Added

**Branding & Identity:**
- Complete HolyFin branding throughout the theme
- Custom "HolyFin" text logo with indigo gradient
- Version footer showing "HolyFin v1.0.0 | Based on ElegantFin by lscambo13"

**Indigo Color System:**
- Deep indigo color palette (#5E35B1 primary)
- Comprehensive color variable system with 10 indigo shades
- 5 deep purple accent colors for variety
- Consistent indigo-themed UI elements

**Visual Enhancements:**
- Glassmorphism effects on cards with indigo tint
- Enhanced button hover states with elevation and indigo glow
- Indigo gradient progress bars with soft glow effect
- Custom indigo-themed scrollbars
- Smooth transitions (0.2s cubic-bezier) on all elements
- Ripple effect on button clicks

**UI Improvements:**
- Enhanced focus states with indigo outline
- Indigo loading spinners
- Gradient badges and chips
- Improved dialog shadows with indigo tint
- Card hover effects with scale and shadow

**Typography & Layout:**
- Inter font family integration
- Professional gradient text logo
- Responsive logo sizing (desktop/mobile/TV)

#### Changed

**Complete Rebranding:**
- All "ElegantFin" references → "HolyFin"
- All "elegantfin" → "holyfin" (lowercase)
- All "Elegant Fin" → "Holy Fin" (spaced)
- Repository URLs: lscambo13/ElegantFin → HeiligerG/HolyFin
- File names: ElegantFin-* → HolyFin-*

**Color Scheme Overhaul:**
- Primary color: Blue/Purple → Deep Indigo (#5E35B1)
- Accent colors: Various → Consistent indigo palette
- Borders: Gray → Indigo tinted (rgba(94, 53, 177, 0.25))
- Backgrounds: Dark gray → Deep dark with indigo tint
- Hover states: Generic → Lighter indigo (#7E57C2)
- Active states: Generic → Darker indigo (#303F9F)

**Component Updates:**
- Submit buttons: Blue → Indigo (#5E35B1)
- Checkboxes: Blue → Indigo
- Highlight outlines: Blue → Deep Purple (#673AB7)
- UI accents: Generic → Indigo
- Progress bars: Standard → Indigo gradient with glow
- Scrollbars: Default → Custom indigo gradient

#### Technical

**File Structure:**
- 15 CSS files renamed (ElegantFin → HolyFin)
- Main file: HolyFin-theme-v25.12.31.css (102KB)
- Latest readable: HolyFin-jellyfin-theme-build-latest.css
- Latest minified: HolyFin-jellyfin-theme-build-latest-minified.css (93KB)
- Nightly version: HolyFin-theme-nightly.css

**Build & Distribution:**
- Pure CSS implementation (no build process needed)
- Minified version created via sed/tr
- Distributed via jsDelivr CDN
- GitHub repository: HeiligerG/HolyFin

**Documentation:**
- Comprehensive README.md with installation guide
- CONTRIBUTING.md with color guidelines
- CHANGELOG.md (this file)
- Updated .gitignore for project cleanup

#### Credits

This release is a complete customization of [ElegantFin](https://github.com/lscambo13/ElegantFin) v25.12.31 by lscambo13.

**Customizations by HolyG:**
- Indigo color scheme design
- Text logo implementation
- Glassmorphism and modern effects
- All branding and documentation

**Original ElegantFin Features (Inherited):**
- Core layout and structure
- Responsive design patterns
- Animation framework
- Component styling foundation
- TV/Mobile compatibility

#### Breaking Changes

⚠️ **This is not compatible with ElegantFin:**
- Different color scheme
- Different branding
- Cannot be used simultaneously

#### Migration from ElegantFin

If switching from ElegantFin:

1. Remove old import:
   ```css
   /* Remove this */
   @import url("https://cdn.jsdelivr.net/gh/lscambo13/ElegantFin@main/...");
   ```

2. Add HolyFin import:
   ```css
   /* Add this */
   @import url("https://cdn.jsdelivr.net/gh/HeiligerG/HolyFin@main/Theme/HolyFin-jellyfin-theme-build-latest-minified.css");
   ```

3. Hard refresh browser (CTRL + F5)

#### Known Issues

- Screenshots show ElegantFin colors (will be updated)
- Banner image still shows ElegantFin branding (will be replaced)
- No standalone HolyFin logo SVG yet (using text gradient)

---

## Future Versions

Template for future releases:

### [X.X.X] - YYYY-MM-DD

#### Added
- New features

#### Changed
- Modified features

#### Fixed
- Bug fixes

#### Removed
- Deprecated features

---

## Version History

- **v1.0.0** (2026-01-03) - Initial HolyFin release
- **v25.12.31** - Last ElegantFin version before fork

---

<div align="center">

**[⬆ Back to Top](#changelog)**

*HolyFin is based on [ElegantFin](https://github.com/lscambo13/ElegantFin) by lscambo13*

</div>
