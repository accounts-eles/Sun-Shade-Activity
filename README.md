🌅 Sun-Shade Activity Template

An interactive "pull-down" reveal interface designed for comparative learning and progressive disclosure. This template features a unique "shade" mechanism that allows users to physically drag a cover down to reveal hidden content, simulating a tactile interaction.

🚀 Live Demo

Explore the Sun-Shade Interface Here

✨ Project Overview

The Sun-Shade template is built for activities where learners benefit from seeing two topics side-by-side or uncovering information at their own pace. By using a vertical slider, it adds a layer of gamification to standard text-heavy modules.

Key Features

Tactile Reveal Mechanism: A draggable "shade" (blind) with a handle that users must pull down to reveal content.

Multi-Page Navigation: Integrated pagination system allows for large datasets to be broken down into digestible steps (e.g., Page 1, Page 2, Page 3).

Comparative Layout: Side-by-side "Topic" sections perfect for comparing concepts, guidance vs. application, or problem vs. solution.

Branded Visual Identity: Uses the ecosystem's professional design language:

Midnight Blue (#1f2a52): Headers, navigation buttons, and structural borders.

Accent Teal (#00bec7): Interactive handles and hover states.

Light Aqua (#d2f0f0): The "shade" cover color and subtle background accents.

Mobile-First Interactivity: Support for both mouse and touch events, ensuring the "pull-down" motion works seamlessly on smartphones and tablets.

🛠️ Technical Implementation

Dynamic Slider Logic: Vanilla JavaScript calculates vertical deltas to update the height of the cover and the position of the handle in real-time.

Pagination State: Manages active classes across multiple content sections while re-initializing slider listeners for each specific page.

Responsive CSS Grid: Uses Tailwind's flexbox and grid utilities to stack content vertically on mobile and horizontally on larger displays.

Event Listener Management: Includes cleanup and re-initialization logic to prevent memory leaks and ensure interactivity persists across page changes.

📂 Project Structure

Sun-Shade-Activity/
├── index.html          # Core template, drag logic, and branded styles
├── previews/           # Automated UI capture assets
└── .github/workflows/  # CI/CD for catalog and preview synchronization


🤖 Catalog Integration

This repository is part of the Catalog of Repos ecosystem. Automated workflows capture the "shade" in various positions to demonstrate the reveal mechanic in the global project gallery.

📄 License

MIT License - Created for the accounts-eles ecosystem.
