# VerdiFLX Pellets | Strategic Sales Intelligence Platform

An interactive B2B Sales Intelligence dashboard designed for high-stakes outreach in the circular economy, focusing on auto OEMs and appliance manufacturers. 

This platform showcases the target Ideal Customer Profile (ICP), prioritizes a targeted sales hit list, outlines an interactive 8-week launch playbook roadmap, and features a real-time Conversion Funnel Calculator.

---

## 🚀 Key Features

### 1. Modern Visual Hero Header
* **VerdiFLX Pellets Illustration**: Interactive floating card showing engineering-grade recycled polyolefin.
* **Micro-Animations**: Features CSS `@keyframes float` translation for a premium 3D feeling.
* **Hover Overlay Card**: Hovering over the image reveals a sleek, blurred glassmorphic description card explaining the pellets' material sourcing.

### 2. Tailored ICP Profile Card (Hero MotoCorp)
* **Design Customization**: Integrates the actual profile photo and name of **Ram Kuppuswamy (Head of Procurement — Hero MotoCorp)**.
* **Arrow-Only Expansion**: Cleaned up visual clutter (removed "Click to view details" helper text) and made the card static. Detail expansion is triggered exclusively by clicking the top-right chevron button, which transitions the card into a neumorphic-recessed active state.

### 3. Interactive 8-Week Playbook Roadmap
* **Progressive Timeline**: Clicking on W1-2, W3-4, W5-6, or W7-8 dynamically fills a custom progress bar to that specific point.
* **Step Styling Indicators**: Progressing along the timeline highlights completed steps by converting them from default neumorphic flat circles to vibrant blue active states (`bg-secondary text-white`) with drop shadows.

### 4. Dynamic Outbound Conversion Funnel Calculator
* **Interactive Counter Inputs**: Real-time counter fields for Email and LinkedIn conversion rates (Total Sent, Replies Received, Positive Replies).
* **Reactive Real-time Calculation**: Instant formulas display the computed Reply Rate and Positive Reply Rate dynamically upon input modification.

### 5. Multi-Priority Target Filter Table
* **Priority Toggling**: Instant tab-switching filters (All, High, Medium, Strategic) to isolate targeted manufacturers like Bajaj Auto, Motherson Sumi, Nilkamal, LG Electronics, and Ather Energy.

### 6. Scroll-Tracking Header Navigation
* **Dynamic Active States**: A customized `IntersectionObserver` tracks the visible sections during scrolling and automatically underlines the active menu link (e.g., Target, Hit List, Tech Stack, Routine, Dashboard).
* **Anti-Layout Shift**: All links feature transparent borders by default so activating the underline does not shift navigation heights.

---

## 🛠️ Technology Stack

* **Core Structure**: HTML5 with semantic layout tags.
* **Styling & Theme**: Tailwind CSS (integrated via CDN with Forms and Container Queries plugins).
* **Typography & Icons**: Google Web Fonts (Montserrat and Inter) & Google Material Symbols.
* **Functionality**: Pure Vanilla ES6+ Javascript for animation observers, conversion arithmetic, filters, and step progression.

---
