# Konflux GitOps Onboarding Redesign - Slideshow

This is a markdown-driven slideshow that walks through the GitOps onboarding redesign concept from ADR #047.

## How to View

1. Open `index.html` in your web browser
2. Use arrow keys or click to navigate through slides
3. Press `ESC` to see slide overview
4. Press `F` for fullscreen mode

## What's Covered

The slideshow demonstrates how Konflux will transition from the current dual-path onboarding (UI vs GitOps) to a unified VS Code plugin-based experience that:

- Moves complex forms (like the "Create a Component" screen) into VS Code
- Provides local validation and schema checking
- Uses Git as the single source of truth
- Introduces a multi-repo GitOps model with ArgoCD
- Preserves the UI for monitoring and runtime operations

## Key Screens Referenced

The slideshow includes mockups based on the current Konflux UI, showing:
- Current "Create a Component" form (complex multi-field configuration)
- How this would look in VS Code plugin
- New Tenant Registration flow
- Simplified UI focused on operations

## Technical Details

Built with reveal.js for smooth presentation experience. The styling matches Konflux's current design patterns with the dark sidebar and blue accent colors. 