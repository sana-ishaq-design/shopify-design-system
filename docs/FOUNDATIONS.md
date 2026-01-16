# Design Foundations

Core design tokens that define the visual language of the Shopify Design System.

---

## Color System

A Figma-based Shopify storefront design system inspired by Dawn

### Overview

Colors are grouped by purpose with semantic naming to help with developer handoff.

---

### Primary (Blue-ish / CTA)

| Token | Usage |
|-------|-------|
| `color/primary-900` | Hover states, strong accent backgrounds |
| `color/primary-700` | Hover states, emphasized actions |
| `color/primary-500` | **Primary CTA, primary action buttons, links in hero** |
| `color/primary-300` | Light backgrounds, subtle accents |
| `color/primary-100` | Very light backgrounds |

---

### Secondary (Warm Accent)

| Token | Usage |
|-------|-------|
| `color/secondary-700` | Strong secondary accents |
| `color/secondary-500` | **Secondary CTAs, badges, micro-interactions** |
| `color/secondary-300` | Light secondary accents |

---

### Neutral / Grays (UI & Surfaces)

| Token | Usage |
|-------|-------|
| `color/neutral-900` | **Main copy/paragraph text** |
| `color/neutral-800` | Strong text emphasis |
| `color/neutral-700` | Medium emphasis text |
| `color/neutral-600` | **Secondary text, meta, labels** |
| `color/neutral-500` | Placeholder text |
| `color/neutral-400` | Disabled text |
| `color/neutral-300` | Borders, dividers |
| `color/neutral-200` | **Borders, dividers, subtle backgrounds** |
| `color/neutral-100` | **Card backgrounds or surface** |
| `color/neutral-0` | Pure white, main background |

---

### Feedback Colors

| Token | Usage |
|-------|-------|
| `color/success-500` | **Inline messages, validation, toasts, badges** |
| `color/error-500` | **Inline messages, validation, toasts, badges** |
| `color/warning-500` | **Inline messages, validation, toasts, badges** |
| `color/info-500` | **Inline messages, validation, toasts, badges** |

---

### Functional / UI

| Token | Usage |
|-------|-------|
| `color/surface` | Base surface color for cards and containers |
| `color/overlay` | **Modal backdrops and image overlays** |
| `color/disabled` | **Disabled buttons/inputs, hint text** |
| `color/text-on-accent` | Text that sits on colored backgrounds (usually white) |

---

## When to Use Each Token

### Practical Color Mapping

| Token | Use Case |
|-------|----------|
| `color/primary-500` | Primary CTA, primary action buttons, links in hero |
| `color/primary-700` or `900` | Hover states, strong accent backgrounds |
| `color/secondary-500` | Secondary CTAs, badges, micro-interactions |
| `color/neutral-900` | Main copy/paragraph text |
| `color/neutral-600` | Secondary text, meta, labels |
| `color/neutral-300/200` | Borders, dividers, subtle backgrounds |
| `color/neutral-100` | Card backgrounds or surface |
| `color/success/error/warning` | Inline messages, validation, toasts, badges |
| `color/overlay` | Modal backdrops and image overlays |
| `color/disabled` | Disabled buttons/inputs, hint text |

---

## Accessibility Rules & Quick Checks

✅ **For body text:** Use at least **4.5:1 contrast** against background (WCAG AA)

✅ **For large text** (≥18pt bold or ≥24pt regular): Use at least **3:1 contrast**

✅ **Buttons with colored backgrounds** (like `primary-500`): Must use `color/text-on-accent` with sufficient contrast (white usually works; check it)

✅ **Hover states:** Always check CTA hover states too (`primary-700` on hover should still have readable text)

✅ **Disabled states:** Ensure color contrast is still understandable by visual grouping (not necessarily readable text)

### Practical Accessibility Check Approach

In Figma, use the **Contrast plugin** (or Figma's built-in accessibility tools) to verify each text color against its background.

If a combo fails, darken the text or lighten/darken the background until it passes.

---

## Typography

### Heading Scales

*[To be documented - include H1-H6 specifications with font sizes, weights, line heights]*

### Body Text

*[To be documented - paragraph styles, font sizes, weights]*

### Caption Styles

*[To be documented - small text, labels, metadata]*

---

## Spacing Scale

### 4px Base System

*[To be documented - spacing increments: 4, 8, 12, 16, 24, 32, 48, 64px]*

**Tokens:**
- `space/xs` - 4px
- `space/sm` - 8px
- `space/md` - 16px
- `space/lg` - 24px
- `space/xl` - 32px
- `space/2xl` - 48px

---

## Grid System

### Responsive Grid Structure

| Breakpoint | Columns | Gutter | Margin | Max Width |
|------------|---------|--------|--------|-----------|
| Desktop (≥1200px) | 12 | 24px | 80px | 1200px |
| Tablet (≥768px) | 8 | 20px | 48px | 768px |
| Mobile (<768px) | 4 | 16px | 16px | 375–414px |

---

## Elevation & Effects

### Shadows

*[To be documented - shadow tokens for depth and hierarchy]*

**Tokens:**
- `effect/elevation/1` - Subtle elevation
- `effect/elevation/2` - Medium elevation
- `effect/elevation/3` - High elevation

### Border Radius

**Tokens:**
- `radius/sm` - Small radius (4px)
- `radius/md` - Medium radius (8px)
- `radius/lg` - Large radius (16px)
- `radius/full` - Fully rounded (999px)

---

**[← Back to Documentation](../README.md)**
