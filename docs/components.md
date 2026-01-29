---
title: Components
description: Reusable design elements that keep your designs consistent. Update a component once and all instances (siblings) update automatically.
---

Components are reusable design elements that help you maintain consistency across your designs. When you update a component, all instances (called "component siblings") automatically update to match.

## What are Components?

Components are master design elements that serve as templates. They can be any design element or group of elements:

- Buttons, cards, or UI elements
- Icons or logos
- Complex nested structures with multiple layers
- Any design element you want to reuse

Components appear in the layers panel with a special component icon and are highlighted in a distinct color to make them easy to identify.

## Creating Components

To create a component from existing design elements:

1. Select one or more elements on the canvas
2. Press `Option + Cmd + K` (Mac) or `Alt + Ctrl + K` (Windows/Linux)
3. The selected elements are converted into a component

**Note:** Elements that are already components will be skipped. You cannot convert the root page node into a component.

## What are Component Siblings?

Component siblings (also called instances) are copies of a component that are linked to the original. They:

- Automatically sync when you edit the original component
- Maintain their own position and can be moved independently
- Are named with a "Sibling" suffix (e.g., "Button Sibling")
- Appear in the layers panel with a sibling icon

When you update a component's properties (colors, text, size, effects, etc.), all of its siblings automatically update to reflect those changes.

## Using Components

### Viewing Components

Open the left sidebar and click the "Components" tab to see all components in your design. Each component shows a preview thumbnail and its name.

### Creating Siblings

1. Open the Components tab in the left sidebar
2. Drag a component from the sidebar onto the canvas
3. A new sibling instance is created at the drop location

### Editing Components

When you edit a component (change colors, text, size, effects, etc.), all of its siblings automatically update to match. This includes changes to nested elements within the component.

### Identifying Components and Siblings

- Components show a component icon and are highlighted in a special color
- Siblings show a sibling icon and have "Sibling" in their name
- Both types are easy to spot in the layer hierarchy

## Best Practices

- **Create components for reusable elements:** Buttons, cards, icons, and other UI elements that appear multiple times
- **Use siblings for consistency:** When you need multiple copies of the same element, create siblings instead of duplicating
- **Edit the component, not siblings:** To update all instances at once, edit the original component
- **Organize with clear names:** Give components descriptive names to make them easy to find in the Components tab
