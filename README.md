# Aurora Nova — AI Training Infrastructure in Space

Aurora Nova is a futuristic landing page for a hardware company that offers AI training on orbital server clusters in space at competitive prices. The page is designed following the **AIDA** (Attention, Interest, Desire, Action) sequence and features a fixed video background playing on repeat with semi-transparent glassmorphic overlays.

## Tech Stack
- **Structure:** HTML5 (Semantic HTML, SEO optimized)
- **Styling:** Vanilla CSS3 (Custom design system based on `DESIGN.md` tokens, responsive grid/flexbox layouts, glassmorphism filters, scroll-triggered animations)
- **Interactions:** Vanilla JavaScript (Scroll animations, mobile navigation drawer)
- **Video:** GPU-accelerated video background with performance fallback

## Key Features
- **AIDA Structure:**
  - **Attention:** High-impact hero section with live stats and bold typography.
  - **Interest:** Outlining terrestrial data center bottlenecks vs. space computing solutions.
  - **Desire:** Showcasing specific space-grade features and competitive pricing tiers.
  - **Action:** Prominent call-to-action to book a call.
- **Glassmorphism Design:** All page elements sit on semi-transparent blurred backgrounds (`backdrop-filter`) to keep the orbital background video visible during scroll.
- **Electric Voltage Theme:** Built using a high-contrast theme featuring electric yellow (`#faff69`) accents on dark canvas.
- **Fully Responsive:** Adapts seamlessly across desktop, tablet, and mobile breakpoints.

## Running Locally
To run the project locally, serve the directory using any HTTP server:
```bash
# Using http-server
npx http-server .
```
Open `http://localhost:8080` in your browser.
