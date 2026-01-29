# Copilot Instructions for FigClank Studio

## Overview
This document provides essential guidelines for AI coding agents working within the FigClank Studio codebase. Understanding the architecture, workflows, and conventions will enable agents to be productive immediately.

## Architecture
- **Components**: The application is structured around reusable components that maintain design consistency. Components can be buttons, cards, or complex nested structures. When a component is updated, all instances (siblings) automatically reflect the changes.
- **Frames**: Frames are container elements that organize content. They can be created using the Frame tool (`F`), which opens a modal for selecting templates based on device types (e.g., Mini Apps, Phones, Tablets).
- **3D Tool**: The 3D Extrusion tool transforms 2D shapes into 3D objects, allowing for depth and rotation adjustments.

## Developer Workflows
- **Building**: Use the standard build commands defined in the project setup. Ensure all dependencies are installed before building.
- **Testing**: Follow the testing conventions outlined in the documentation. Use the provided shortcuts for quick access to testing tools.
- **Debugging**: Utilize the built-in debugging tools and follow the established patterns for error handling and logging.

## Project-Specific Conventions
- **Keyboard Shortcuts**: Familiarize yourself with the keyboard shortcuts for tool selection and actions. For example, `V` for Cursor/Select, `F` for Frame, and `T` for Text.
- **Auto Layout**: Use Auto Layout to create responsive designs. Control the flow direction and resizing options to ensure elements adjust as content changes.

## Integration Points
- **AI Design Generator**: This feature allows users to generate mini app screens from text descriptions. Agents should understand how to interact with this tool to facilitate design generation.
- **External Dependencies**: Be aware of any external libraries or APIs used within the project. Ensure that all integrations are functioning as expected.

## Communication Patterns
- **Cross-Component Communication**: Components communicate through props and events. Ensure that data flows correctly between parent and child components.
- **State Management**: Understand the state management approach used in the application, whether it’s local state, context API, or a state management library.

## Key Files/Directories
- **docs/**: Contains all documentation files, including guides for tools and components.
- **docs.json**: Configuration file for the documentation structure and navigation.
- **README.md**: Overview of the project, setup instructions, and contribution guidelines.

## Conclusion
By following these guidelines, AI coding agents can effectively navigate and contribute to the FigClank Studio codebase. For any unclear sections or additional information, please refer to the relevant documentation files or reach out for clarification.