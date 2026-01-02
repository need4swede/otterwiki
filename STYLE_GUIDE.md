# OtterWiki Color Style Guide

## Primary Color Palette

| Color   | Value     | Usage                          |
|---------|-----------|--------------------------------|
| Blue    | `#1890ff` | Primary actions, links         |
| Green   | `#0be881` | Success states, additions      |
| Yellow  | `#ffcf00` | Warnings, highlights           |
| Red     | `#ff4d4f` | Danger, errors, deletions      |
| Orange  | `#ed8936` | Secondary warnings             |
| Teal    | `#38b2ac` | Info, accents                  |
| Indigo  | `#6563ff` | Special accents                |
| Pink    | `#ed64a6` | Decorative accents             |

## Semantic Colors

| Purpose   | Light Mode | Dark Mode  |
|-----------|------------|------------|
| Primary   | `#1890ff`  | `#58a6ff`  |
| Success   | `#0be881`  | `#3fb950`  |
| Warning   | `#ffcf00`  | `#d29922`  |
| Danger    | `#ff4d4f`  | `#f85149`  |

## Light Mode

### Backgrounds
- **Page**: `#ffffff`
- **Navbar**: `#d2d2d2`
- **Sidebar**: `#e2e2e2`
- **Code blocks**: `rgba(0, 0, 0, 0.09)`

### Text
- **Primary**: `rgba(0, 0, 0, 0.85)`
- **Secondary**: `rgba(0, 0, 0, 0.7)`
- **Muted**: `rgba(0, 0, 0, 0.6)`

### Borders
- **Default**: `rgba(0, 0, 0, 0.2)`

## Dark Mode

### Backgrounds (Layered Depth)
- **Canvas**: `#060a10` — Deepest layer
- **Default**: `#090f18` — Primary background
- **Subtle**: `#0e1520` — Slight elevation
- **Muted**: `#131c2a` — Cards, panels
- **Emphasis**: `#1a2536` — Highlighted areas

### Text
- **Primary**: `#e2e8f0`
- **Secondary**: `#94a3b8`
- **Muted**: `#64748b`
- **Placeholder**: `#475569`

### Borders
- **Default**: `#1e2d3d`
- **Muted**: `#162232`
- **Subtle**: `#0f1824`

### Accents
- **Primary**: `#58a6ff`
- **Link hover**: `#79c0ff`

## Diff Colors

| State   | Light Background | Dark Background |
|---------|------------------|-----------------|
| Added   | `#d5f9e5`        | `#17312a`       |
| Removed | `#f8d0d9`        | `#301923`       |

## Shadows (Dark Mode)

```css
--dm-shadow-sm: 0 1px 2px rgba(0, 0, 0, 0.3);
--dm-shadow-md: 0 3px 6px rgba(0, 0, 0, 0.4);
--dm-shadow-lg: 0 8px 24px rgba(0, 0, 0, 0.5);
```

## Usage Guidelines

1. **Contrast**: Dark mode uses softer accent colors (`#58a6ff` vs `#1890ff`) for better readability
2. **Depth**: Dark backgrounds use a layered system from `#060a10` to `#1a2536`
3. **Highlights**: Use `#ffb100` (light) or `#DB9A00` (dark) for marked text
4. **Semantic consistency**: Always use green for success, red for danger, yellow for warnings
