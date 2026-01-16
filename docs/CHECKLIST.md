# Design System Checklist — Dawn-Aligned

Track the implementation status of all components in the Shopify Design System.

## How to Use

**Status Column:**
- ☐ Pending
- 🔄 In Progress
- ✅ Complete

**Notes / Tasks:** Record specific adjustments, variants, or responsive fixes.

---

## Foundations

| Component | Status | Notes | Component Link | Usage | Priority |
|-----------|--------|-------|----------------|-------|----------|
| Color Tokens (Primary, Secondary, Neutral, Success, Error) | ☐ | Add semantic naming + WCAG contrast check | [Link](./FOUNDATIONS.md#color-system) | e.g., home | High |
| Typography Tokens (Heading, Body, Caption) | ☐ | Create Figma text styles | [Link](./FOUNDATIONS.md#typography) | e.g., home | High |
| Spacing Scale (4px base) | ☐ | Document spacing increments | [Link](./FOUNDATIONS.md#spacing-scale) | e.g., home | High |
| Grid System (12/8/4 columns) | ☐ | Align with breakpoints | [Link](./FOUNDATIONS.md#grid-system) | e.g., home | High |
| Radius + Shadows + Elevation | ☐ | Add subtle hover states | [Link](./FOUNDATIONS.md#elevation--effects) | e.g., home | Medium |

---

## Atoms

| Component | Status | Notes | Component Link | Usage | Priority |
|-----------|--------|-------|----------------|-------|----------|
| Button (Primary, Secondary, Ghost, Disabled) | ☐ | Add hover + focus states | [Link](./components/atoms/button.md) | e.g., home | High |
| Input (Text, Search, Checkbox, Select, Radio) | ☐ | Ensure consistent padding | [Link](#) | e.g., home | High |
| Icons (Cart, Menu, Search, Account, Arrow) | ☐ | Use 24×24 vector set | [Link](#) | e.g., home | High |
| Badge (Sale, New, Sold Out) | ☐ | Match brand accent colors | [Link](#) | e.g., home | Medium |
| Price Label (Regular, Discounted) | ☐ | Include compare-at price | [Link](#) | e.g., home | High |
| Divider (Neutral/200) | ☐ | Add responsive margins | [Link](#) | e.g., home | Low |

---

## Molecules

| Component | Status | Notes | Component Link | Usage | Priority |
|-----------|--------|-------|----------------|-------|----------|
| Product Card | ☐ | Hover swap image + quick add | [Link](#) | e.g., home | High |
| Collection Card | ☐ | Overlay gradient variant | [Link](#) | e.g., home | Medium |
| Search Bar | ☐ | Mobile full-width variant | [Link](#) | e.g., home | High |
| Header Nav Item | ☐ | Hover/dropdown state | [Link](#) | e.g., home | High |
| Cart Item Row | ☐ | Includes quantity selector | [Link](#) | e.g., home | High |
| Quantity Selector | ☐ | Keyboard accessible | [Link](#) | e.g., home | Medium |
| Review Snippet | ☐ | 5-star + short review | [Link](#) | e.g., home | Low |
| Announcement Bar | ☐ | Optional close button | [Link](#) | e.g., home | Medium |
| Breadcrumb | ☐ | Add separator icon variant | [Link](#) | e.g., home | Low |

---

## Organisms

| Component | Status | Notes | Component Link | Usage | Priority |
|-----------|--------|-------|----------------|-------|----------|
| Header | ☐ | Sticky + responsive | [Link](#) | e.g., home | High |
| Footer | ☐ | Collapsible columns on mobile | [Link](#) | e.g., home | High |
| Product Grid | ☐ | Auto layout for 4/2/1 columns | [Link](#) | e.g., home | High |
| Product Detail | ☐ | Gallery + info layout | [Link](#) | e.g., home | High |
| Collection Filter | ☐ | Collapsible filter sidebar | [Link](#) | e.g., home | Medium |
| Cart Drawer | ☐ | Overlay transition variant | [Link](#) | e.g., home | High |
| Newsletter Section | ☐ | Connected to form molecule | [Link](#) | e.g., home | Medium |
| Banner/Hero | ☐ | Image/video background | [Link](#) | e.g., home | High |

---

## Templates

| Component | Status | Notes | Component Link | Usage | Priority |
|-----------|--------|-------|----------------|-------|----------|
| Home Page | ☐ | All major sections included | [Link](#) | home | High |
| Collection Page | ☐ | Filter + pagination | [Link](#) | collection | High |
| Product Page | ☐ | Product detail + related | [Link](#) | product | High |
| Cart Page | ☐ | Summary + checkout | [Link](#) | cart | High |
| Search Page | ☐ | Results + empty state | [Link](#) | search | Medium |
| Static Pages (About, Contact, 404, Password) | ☐ | Minimal layout + content | [Link](#) | various | Low |

---

## Add-Ons (for Future Team Scaling)

- **Component Link** → Hyperlink directly to the Figma master component
- **Usage column** → Specify where it appears (e.g., Home, Product, Cart)
- **Priority** → Focus on components used most often in Shopify stores (e.g., Product Card = High, Breadcrumb = Low)

---

**[← Back to Documentation](../README.md)**
