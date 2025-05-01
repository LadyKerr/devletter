# UTM Link Tracker App

## Overview
The **UTM Link Tracker App** is a practical tool for marketers and developers to generate, manage, and track UTM parameters for their campaigns. Built with **Astro**, it provides a sleek and user-friendly interface for creating and organizing trackable links, all in one place.

## Features
- **UTM Link Generator:**
  - Input fields for URL, source, medium, campaign, term, and content.
  - Automatically generate trackable UTM links with a copy-to-clipboard button.

- **Link Management:**
  - Save and organize UTM links in a dashboard.
  - Search and filter links by campaign, source, or date.

- **Basic Analytics:**
  - Integrate with Google Analytics or use mock data to display basic performance stats.
  - Visualize clicks by source, medium, or campaign using charts (e.g., bar or pie charts).

- **Export Options:**
  - Export saved UTM links as a CSV file.

- **Responsive UI:**
  - Mobile-friendly design for easy access on the go.

## Tech Stack
- **Frontend:** Astro for static site generation with modern UI components.
- **Database:** LocalStorage for quick prototyping
- **Backend (Optional):** A lightweight server (e.g., Node.js, Express) for interacting with analytics APIs.
- **Styling:** TailwindCSS for a sleek, responsive design.

## File Structure
Here’s the proposed file structure for the Astro project:
```plaintext
src/
├── components/
│   ├── UTMForm.astro         (Form for generating UTM links)
│   ├── UTMList.astro         (Displays saved UTM links)
│   ├── AnalyticsChart.astro  (Charts for UTM performance tracking)
│   └── Footer.astro          (Footer with credits and links)
├── layouts/
│   └── BaseLayout.astro
├── pages/
│   ├── index.astro           (Landing page with UTM generator)
│   ├── dashboard.astro       (UTM link management dashboard)
│   └── about.astro           (Optional: About the project)
└── styles/
    └── global.css
```

## How It Works
1. **Generate UTM Links:**
   - Input a URL and UTM parameters (source, medium, campaign, etc.).
   - The app generates a formatted URL with the UTM parameters appended.

2. **Manage Links:**
   - Save the generated links in a dashboard for future reference.
   - Filter and search links by campaigns or sources.

3. **Track Performance:**
   - Visualize basic analytics (e.g., clicks per source) using integrated or mock data.

4. **Export Data:**
   - Download all saved UTM links as a CSV file for offline use.

## Live Stream Build Plan
Here’s the step-by-step plan for building the app live:

1. **Intro (10-15 min):**
   - Explain what UTM links are and why they’re essential for tracking marketing efforts.
   - Present the project plan and features.

2. **Astro Setup (10-15 min):**
   - Initialize the Astro project and create the basic file structure.
   - Set up TailwindCSS for styling.

3. **UTM Generator Form (20 min):**
   - Build the form for inputting URLs and UTM parameters.
   - Add logic to dynamically generate UTM links.

4. **Dashboard Setup (20 min):**
   - Create the dashboard page to display and manage saved UTM links.
   - Integrate Supabase/Firebase to store and retrieve link data.

5. **Optional: Analytics Integration (15+ min):**
   - Add Google Analytics integration or mock data for link performance tracking.

6. **Testing & Wrap-Up (15 min):**
   - Test the app live by generating and saving links.
   - Demonstrate the analytics and export functionality.

## Future Enhancements
- Add user authentication for personalized dashboards.
- Include advanced analytics (e.g., time-based trends or geolocation data).
- Build a browser extension for quick UTM link generation.
- Support bulk UTM link creation from CSV uploads.

---

💡 **Get ready to simplify your UTM tracking workflows with this handy app!**