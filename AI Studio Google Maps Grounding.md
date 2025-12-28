# AI Prompt: LeadGenius Maps "Command Center"

**Objective:** Build a high-tech, dark-themed "AI Lead Generation" dashboard designed to scout for local businesses that need digital marketing help.

## 1. The Vibe & Aesthetic
*   **Theme:** "Tactical Command Center."
*   **Colors:** Deep slate/black backgrounds (`slate-950`) with glowing indigo and violet accents.
*   **Typography:** Clean, sans-serif, legible.
*   **Feel:** Professional, sleek, and data-driven.

## 2. Layout Structure
The app should be a single-screen dashboard split into two sections:
*   **Left Sidebar (The Control Panel):** Contains the search inputs and the scrollable list of results.
*   **Right Panel (The Map):** A full-screen, interactive Google Map styled in "Dark Mode" to match the app theme.

## 3. Core Logic (The "AI Scout")
When the user inputs an **Industry** (e.g., Dentist) and a **Location** (City/State), the app acts as an AI Scout:
1.  **Search Criteria:** Look for "Underserved Opportunities"—specifically businesses with ratings between **3.5 and 4.5 stars** (good, but not perfect).
2.  **The Analysis:** For each business found, generate a specific **"Market Gap"** or **"AI Pitch Angle."**
    *   *Examples:* "No AI Chatbot," "Manual Booking Only," "SEO Neglect," or "Unanswered Reviews."
3.  **Verification:** Ensure the business exists on Google Maps and try to verify the gap by "scanning" their digital presence.

## 4. Features & Interactivity
*   **Result Cards:** Display the Business Name, Address, Rating, and the generated "Market Gap" clearly.
*   **Smart Map:**
    *   Use color-coded markers based on rating (e.g., Green for high, Yellow for mid, Red for low).
    *   **Sync:** Clicking a card in the sidebar should automatically zoom the map in and "fly" to that location.
*   **Filtering:** Add a slider tool in the sidebar to filter results by Star Rating range (e.g., "Show me only 3.5 to 4.0").
*   **Empty State:** If no search has happened, show a clean "Ready to Scout" overlay on the map.

## 5. User Experience
*   The UI should feel "snappy" and responsive.
*   Show a loading state (e.g., "Scouting & Verifying...") while the AI is processing.
*   Include a "View on Map" button on the cards to trigger the map interaction.
