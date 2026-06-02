# Skill: Neon Conservatory Design System

## Overview
This skill defines the technical implementation of the Factus API "Neon Conservatory" design system. It prioritize visual excellence, editorial authority, and modern web aesthetics.

## Design Tokens

### Colors
- **Primary**: `#006e2a` (Brand Anchor)
- **Primary Container**: `#00c853` (Vibrant Green)
- **Secondary**: `#675688` (Violet Counterpoint)
- **Surface**: `#fef7ff` (Canvas)
- **Neutral 1**: `#f9f1ff` (Surface Container Low)
- **Neutral 2**: `#ffffff` (Surface Container Lowest)
- **Text**: `#221140` (Rich Violet-Black)

### Typography
- **Headings**: `Plus Jakarta Sans`
- **Body**: `Inter`
- **Labels/Mono**: `Space Grotesk`

## Technical Rules (MANDATORY)

1. **The "No-Line" Rule**: 
   - NEVER use `1px solid` borders for sectioning. 
   - Use background shifts (e.g., `surface` vs `surface-container-low`) for definition.
   - Use `outline-variant` at 20% opacity ONLY for form fields.

2. **Gradients & Soul**:
   - Use 135-degree linear gradients: `primary` to `primary-container`.
   - Apply subtle micro-animations on interactive elements (`hover:scale-105`, `duration-300`).

3. **Glassmorphism**:
   - Floating elements (Navbar, Snippets): `backdrop-filter: blur(20px)` + `background: rgba(var(--surface-rgb), 0.7)`.

4. **Tonal Layering**:
   - Stack `surface-container-lowest` cards on `surface-container-low` backgrounds for soft ambient lift.

## Component Structures (Astro)

### Layout
- Use a `BaseLayout.astro` for SEO and shared fonts.
- Implement responsive containers with `max-w-7xl mx-auto`.

### Atomic Components
- **Button**: Full rounded (`rounded-full`), gradient background.
- **Card**: Large rounded (`rounded-3xl`), no borders, tonal background.
- **Section**: Use `spacing-24` (6rem) vertical margin between sections.
