I have a React Native (Expo + Expo Router + NativeWind) dating app.
I will provide my swipe screen (index.tsx) and related UI files.
IMPORTANT RULES (VERY STRICT):
- DO NOT change business logic (API hooks, state, handlers)
- DO NOT break navigation (router, Link must remain)
- DO NOT change icons (Ionicons must remain same)
- DO NOT change font families
- DO NOT remove existing components unless necessary
- ONLY fix layout, UI, and UX behavior
----------------------------------
🎯 GOAL:
Fix layout issues and upgrade UI to a clean, premium dating app with proper structure and smooth UX.
----------------------------------
🔧 REQUIRED FIXES & FEATURES:
1️⃣ FIX LAYOUT ISSUES
- Remove all overlapping UI elements
- Ensure proper spacing using flex, padding, and margins
- Card should be centered and not overflow screen
- ScrollView should not conflict with swipe area
- Ensure SafeAreaView is respected
----------------------------------
2️⃣ PROFILE CARD (VERY IMPORTANT)
Modify ProfileView usage so card shows ONLY:
- Name + Age (bold, prominent)
- Distance from user (e.g., "2 km away")
- Online status (green dot if online)
REMOVE:
- extra clutter
- unnecessary text
- excessive details
Card must be:
- Full image background
- Bottom gradient overlay
- Text aligned at bottom-left
- Rounded corners (2xl)
- Clean and minimal
----------------------------------
3️⃣ FILTER BAR (ADD ABOVE CARD)
Create a horizontal filter bar above cards with:
- Online toggle (button)
- Age range slider (18–100, 18 fixed minimum)
- Location filter (map-based placeholder button)
- "Looking for" filter (text button)
UI:
- Horizontal scroll or flex row
- Clean pill-style buttons
- Subtle shadow
- Proper spacing (no overlap)
----------------------------------
4️⃣ ACTION BUTTONS (BELOW CARD)
Modify buttons:
- ❌ (skip)
- ❤️ (like)
- 💬 (message) ← replace star
Add:
- Press animation (scale 0.95 → 1)
- Shadow and elevation
- Equal spacing
----------------------------------
5️⃣ PRIVATE vs PUBLIC PROFILE LOGIC (UI ONLY)
Add UI distinction:
PRIVATE PROFILE:
- Blur or partially hide content
- Show "Request Access" button
- Disable full profile view
PUBLIC PROFILE:
- Fully clickable
- On click → navigate to full profile screen
----------------------------------
6️⃣ FULL PROFILE SCREEN (UI FLOW)
When clicking a PUBLIC profile:
Navigate to profile details screen showing:
- Name
- Age
- Location
- Gender
- Orientation
- About section
- Photos
Ensure layout is:
- Scrollable
- Clean sections
- Proper spacing
----------------------------------
7️⃣ ANIMATIONS (IMPORTANT)
- Swipe animation already exists → KEEP it
- Add fade-in for new cards
- Add press animation to ALL buttons (80–90%)
- Keep animations smooth and minimal (no lag)
----------------------------------
⚡ PERFORMANCE RULES:
- Do NOT introduce heavy re-renders
- Keep animations lightweight
- Maintain current functionality
----------------------------------
📦 OUTPUT FORMAT:
- Show ONLY modified sections
- Clearly indicate where to replace code
- Do NOT rewrite entire files unless necessary
----------------------------------
FINAL RESULT:
The app should feel like a premium dating app:
- clean
- minimal
- smooth
- no layout bugs
- clear UX
now you could able to see the entire projrct src code 
-> this is my entire project file i want you to completely analysis the structure of my app and include the above features which i have mentioned instead of filter in drop down use sliding. make the entire app more premium. add dark and light theme get refleacted on all pages. include top nav bar where we have logo, notiifcation setting. setup the profile page chat page,all page should be more perimum like instagram,whatsapp,grinder and foloow the color code entire app for the buttons animations etc : 692ce3 and c35de6.

* Matchmaking Algorithm – Smart and customizable matching system.
* Privacy First – No tracking, no data selling.
* Real-Time Chat – Secure messaging between matches.
* Open-Source – Transparent and community-driven.
* Cross-Platform – Available for Web, Android, and iOS. also should be there later i will give prompt to build backedn as of now i need premium ui production readyscreens
