---
title: 3D Tool
description: Transform 2D shapes into 3D objects with the 3D Extrusion tool. Adjust depth and rotation to create realistic 3D representations on the canvas.
---

The 3D Extrusion tool transforms 2D shapes into 3D objects by extruding them along a depth axis. This creates realistic 3D representations that can be rotated and viewed from different angles.

## Workflow

Input shape → 3D Extrude modal (depth & rotation) → 3D output on canvas.

![Input](https://raw.githubusercontent.com/Diskyeth/FigClank-Studio/d55f9112804375334214c3cbc9e967a07507aee3/docs/doc_resources/images/FAQ_3DExtrude_InputExample_.png) → ![3D Extrude Modal](https://raw.githubusercontent.com/Diskyeth/FigClank-Studio/d55f9112804375334214c3cbc9e967a07507aee3/docs/doc_resources/images/FAQ_3DExtrude_Modal_.png) → ![3D Output](https://raw.githubusercontent.com/Diskyeth/FigClank-Studio/d55f9112804375334214c3cbc9e967a07507aee3/docs/doc_resources/images/FAQ_3DExtrude_OutputExample_.png)

## Accessing the Tool

| Icon | Tool | Description |
|------|------|-------------|
| ![3D Extrude](https://raw.githubusercontent.com/Diskyeth/FigClank-Studio/d55f9112804375334214c3cbc9e967a07507aee3/docs/doc_resources/icons/toolbar-extrude-3d.svg) | **3D Extrude Button** | Located in the toolbar. Click to open the 3D extrusion modal. |

## Supported Shapes

The 3D tool works with the following shape types:

- **Rectangles:** Creates a rectangular prism with front, back, and four side faces
- **Circles/Ellipses:** Creates a cylindrical extrusion with front, back, and curved side faces
- **Vectors:** Basic vector path support (simplified extrusion)

## Controls

### Depth

Adjust the extrusion depth (1–500px). This determines how far the shape extends in the Z-axis, creating the 3D effect.

### Rotation

Set rotation angles for each axis:

- **X-axis:** Rotate around horizontal axis (pitch)
- **Y-axis:** Rotate around vertical axis (yaw)
- **Z-axis:** Rotate around depth axis (roll)

Values are in degrees (0–360°). You can also drag the preview to adjust rotation interactively.
