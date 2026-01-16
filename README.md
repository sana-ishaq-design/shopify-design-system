# Shopify Design System — Dawn-Aligned Framework

A production-ready Figma design system for building modern Shopify storefronts, inspired by the **Dawn theme** and structured with **Atomic Design principles**.

## 🎯 Purpose

This system bridges the gap between design and development for Shopify projects by providing:
- **Scalable component architecture** (Atoms → Molecules → Organisms → Templates)
- **Dawn theme alignment** for seamless developer handoff
- **Responsive-first design** with mobile, tablet, and desktop variants
- **Accessibility built-in** with WCAG-compliant color contrast
- **Auto Layout & Variants** for flexible, maintainable components

## 🏗️ Structure

### Foundations
Core design tokens that define the visual language:
- **Color System**: Semantic tokens (Primary, Secondary, Neutral, Success, Error) with WCAG AA compliance
- **Typography Scale**: Heading, Body, and Caption styles optimized for readability
- **Spacing System**: 4px base scale for consistent rhythm
- **Grid System**: Responsive 12/8/4 column layouts
- **Elevation**: Radius, shadows, and subtle depth

### Atoms
Smallest reusable components:
- Buttons (Primary, Secondary, Ghost, Disabled)
- Form inputs (Text, Search, Checkbox, Radio, Select)
- Icons (24×24 vector set: Cart, Menu, Search, Account)
- Badges (Sale, New, Sold Out)
- Price labels with compare-at pricing
- Dividers

### Molecules
Combined atoms forming functional units:
- Product Card with hover states and quick-add
- Collection Card with overlay gradients
- Search Bar with mobile optimization
- Navigation items with dropdown states
- Cart item rows with quantity selectors
- Review snippets with 5-star ratings
- Announcement bar
- Breadcrumbs

### Organisms
Complex, page-level components:
- Header (sticky, responsive)
- Footer (collapsible on mobile)
- Product Grid (auto-layout for 4/2/1 columns)
- Product Detail (gallery + info)
- Collection Filters (collapsible sidebar)
- Cart Drawer (overlay transition)
- Newsletter Section
- Hero/Banner (image/video backgrounds)

### Templates
Complete page layouts:
- Home Page
- Collection Page (with filters & pagination)
- Product Page (detail + related products)
- Cart Page (summary + checkout)
- Search Page (results + empty state)
- Static Pages (About, Contact, 404, Password)

## ✨ Key Features

- **Auto Layout Ready**: Every component uses Figma's Auto Layout for responsive behavior
- **Component Variants**: Comprehensive states (default, hover, focus, disabled, error)
- **Semantic Naming**: Clear, developer-friendly naming conventions
- **Theme-Ready**: Easily customizable color tokens for different brands
- **Mobile-First**: Responsive breakpoints built into every component
- **Accessibility**: WCAG contrast ratios and keyboard navigation considerations

## 📋 Component Coverage

View the complete [Component Checklist](./docs/CHECKLIST.md) to see:
- ✅ 40+ components across all atomic levels
- 📊 Implementation status
- 🔗 Direct Figma component links
- 📱 Usage contexts (Home, Product, Cart, etc.)
- ⚡ Priority levels for phased implementation

## 🎨 Figma File

**[View Design System in Figma →]((https://www.figma.com/design/RI8epkmOBGRdvyYbxlgDJH/Shopify-Figma-Design-System?node-id=12-487&t=9kRJjsre3iBJOAnE-1))**

*Note: Community file is view-only. Duplicate to your workspace to use.*

## 🚀 How to Use

1. **Duplicate the Figma file** to your workspace
2. **Enable component library** in your project
3. **Start with foundations** - apply color and typography tokens
4. **Build pages** using templates as starting points
5. **Customize** - swap colors and adjust spacing to match your brand

## 📐 Design Principles

1. **Scalability First**: Built for growth and team collaboration
2. **Developer-Friendly**: Clean naming and structure for smooth handoff
3. **Shopify-Optimized**: Components map directly to Dawn theme sections
4. **Performance-Minded**: Optimized for fast-loading storefronts
5. **Accessibility-Aware**: WCAG guidelines baked into design decisions

## 🛠️ Built With

- **Figma** (Auto Layout, Variants, Styles)
- **Atomic Design Methodology**
- **Shopify Dawn Theme** (as reference)
- **WCAG 2.1 AA Standards**

## 📖 Documentation

- [Component Checklist](./docs/CHECKLIST.md) - Track implementation status
- [Design Foundations](./docs/FOUNDATIONS.md) - Color, typography, spacing details
- [Design Tokens](./docs/DESIGN-TOKENS.md) - Token structure and usage
- [Component Library](./docs/COMPONENTS.md) - Detailed component specs

## 🎯 Ideal For

- Shopify merchants building custom themes
- Agencies working on multiple Shopify projects
- Designers learning design systems
- Teams needing faster design-to-development workflow

## 🔮 Roadmap

- [ ] Add animation guidelines
- [ ] Create Storybook integration examples
- [ ] Export design tokens to JSON
- [ ] Add more e-commerce patterns (wishlists, gift cards, etc.)
- [ ] Multi-language support documentation

## 👩‍💻 About

Created by **Sana Ishaq** — UI/UX Designer specializing in design systems and conversion optimization for eCommerce.

- Portfolio: [sanaishaq.framer.website](https://sanaishaq.framer.website/)
- GitHub: [@sana-ishaq-design](https://github.com/sana-ishaq-design)

## 📄 License

This design system is available for personal and commercial use. Attribution appreciated but not required.

---

**⭐ If you find this useful, consider starring this repo!**
