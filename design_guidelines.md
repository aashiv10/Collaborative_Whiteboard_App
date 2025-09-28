# Collaborative Whiteboard App Design Guidelines

## Design Approach
**Reference-Based Approach**: Drawing inspiration from Miro's clean, productivity-focused interface with modern collaboration tools like Figma and Notion. This utility-focused application prioritizes efficiency and learnability for creative workflows.

## Core Design Elements

### A. Color Palette
**Light Mode:**
- Primary: 240 6% 10% (charcoal for text and borders)
- Background: 0 0% 98% (off-white canvas)
- Surface: 0 0% 100% (pure white for panels)
- Accent: 217 91% 60% (professional blue for interactive elements)

**Dark Mode:**
- Primary: 210 20% 98% (light text)
- Background: 222 84% 5% (deep dark canvas)
- Surface: 217 33% 17% (elevated panels)
- Accent: 217 91% 60% (consistent blue accent)

**Sticky Note Colors (Fixed):**
- Peach: #FFD6A5, Yellow: #FDFFB6, Green: #CAFFBF, Blue: #9BF6FF, Purple: #BDB2FF

### B. Typography
**Fonts:** Inter (primary), JetBrains Mono (code/technical)
- Headers: 600 weight, 24-32px
- Body: 400 weight, 14-16px  
- UI Labels: 500 weight, 12-14px
- Monospace: 400 weight for technical elements

### C. Layout System
**Spacing Units:** Consistent use of Tailwind's 2, 4, 6, 8, 12, 16 unit system
- Micro spacing: 2-4 units (buttons, form elements)
- Component spacing: 6-8 units (between related elements)
- Section spacing: 12-16 units (major layout divisions)

### D. Component Library

**Navigation:**
- Clean sidebar with icon + label navigation
- Collapsible panels for to-do lists and tools
- Floating toolbar for drawing tools with rounded corners

**Canvas Interface:**
- Infinite scroll canvas with subtle grid background
- Floating tool palette with categorized sections
- Non-intrusive zoom controls in corner

**Forms & Inputs:**
- Rounded input fields (8px border-radius)
- Consistent focus states with accent color outline
- Clear visual hierarchy with proper spacing

**Data Display:**
- Card-based layout for board thumbnails
- Clean list styling for to-do items
- Subtle shadows and borders for depth

**Interactive Elements:**
- Rounded buttons with 6px radius
- Hover states with subtle color shifts
- Loading states with skeleton patterns

### E. Collaboration Features
- Real-time cursors with user colors
- Online user avatars in top-right corner
- Subtle notification badges for activity
- Clean invite modal with copy-link functionality

## Key Design Principles
1. **Minimal Distraction**: Clean interface that doesn't compete with user content
2. **Tool Accessibility**: Essential tools always within 1-2 clicks
3. **Visual Hierarchy**: Clear distinction between canvas, tools, and panels  
4. **Responsive Collaboration**: Real-time feedback that feels natural
5. **Consistent Interactions**: Predictable behavior across all tools and features

## Layout Structure
- **Header**: Minimal with board title, collaboration indicators, and user menu
- **Sidebar**: Collapsible tool palette and to-do panel
- **Main Canvas**: Full-screen drawing area with infinite scroll
- **Floating Elements**: Export options, invite button, mode toggles positioned non-intrusively

This design emphasizes productivity and collaboration while maintaining the visual polish expected in modern creative tools.