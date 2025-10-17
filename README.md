# FrameForge
Frame Forge™ is the first of the self-contained HTML file, open-source, offline-first tool that instantly converts HTML &amp; CSS into an interactive, navigable wireframe diagram. Visualize, analyze, and export your front-end structure.

## FrameForge Version History

All notable changes to this project will be documented in this file.

#[1.2.5] - 2025-10-17

This version focuses on user experience refinements and visual polish.

Changed

Improved Text Block Visibility: Increased the opacity of text block fills in the wireframe to 80% for better contrast and emphasis, making complex layouts easier to read.

Refined Update Alert Animation: The update notification icon's animation has been changed from a simple pulse to a more visually appealing radial wave effect, better drawing attention without being distracting.

[1.2.0]

This release introduces major new functionality for responsive testing and application maintenance.

Added

Device Preview Switcher: A new floating toggle has been added to the top-left of the canvas. Users can now instantly switch the wireframe preview between Desktop and Mobile (375x812px) resolutions to analyze how their code responds to different viewports.

Automatic Update Notification System: FrameForge now automatically checks the official GitHub repository for new versions upon startup. If a newer version is detected, a subtle, pulsating red alert icon appears next to the "FrameForge" title. Clicking this icon opens a modal with a direct link to the repository for easy updating.

Internal Version Tagging: The application now includes a TOOL_VERSION constant (1.2.0) to track releases and facilitate the new update check functionality.

[1.1.0]

This release focused on professional branding, user engagement, and creating a polished first impression.

Added

Professional Splash Screen: A new animated splash screen is displayed on startup, featuring the FrameForge logo, a tagline ("Visualize • Design • Code"), and a creator credit for a more professional feel.

Complete Rebranding: The tool has been officially branded as "FrameForge" throughout the user interface, including the page title and sidebar header.

PayPal Contribution Button: An internet-aware contribution button has been integrated into the sidebar. It uses the navigator.onLine API to only appear when an active internet connection is detected, allowing users to support the project.

[1.0.0]

Initial public release of FrameForge.

Added

Core functionality to convert raw HTML and CSS into a live, interactive wireframe diagram.

Interactive Canvas: Pan (click & drag) and Zoom (mouse wheel) capabilities.

Intelligent Element Filtering: Hides non-visual structural containers for a cleaner wireframe.

Accurate Shape & Text Tracing: Renders border-radius and individual lines of text.

High-Resolution Export: Download the current wireframe view as a high-quality 2K PNG.

Full offline functionality.
