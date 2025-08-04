
## 🌟 Features

- 🧮 Performs basic & scientific calculations
- 🎨 Uses a clean *pastel color theme* (no black or blue)
- 📱 Fully *responsive layout* for mobile devices
- 🧠 Includes scientific functions like sin, cos, tan, log, ln, √, π, e
- 🔢 Separates *numeric and operator buttons* for better UX
- ❌ Includes a *Cancel button* to clear current input

---

## 🛠 Mobile Layout Issue Fixed

Previously on small screens, the calculator showed *interleaved buttons* — where operator and number keys were mixed together, making it confusing for users.

✅ This issue has now been fixed by:
- Grouping *operator/function buttons* at the top
- Placing *number buttons* at the bottom
- Using *CSS media queries* targeting max-width: 480px
- Maintaining the original desktop layout

---

## 🧠 AI Prompt Used (Styled with Emoji)

"👋 Hello AI,

📄 1. I have an HTML file that displays a *Scientific Calculator* and includes the necessary JavaScript code.

💻 2. The calculator renders correctly on *desktop, but it has layout issues on **mobile devices*.

📱 3. Currently, *operator buttons* and *number buttons* are interleaved, creating a confusing layout.

📐 4. I want to group:
   - All *operator/function buttons* (e.g., sin, cos, log, √, etc.) at the *top*
   - All *numeric buttons* (0–9, ., =) at the *bottom*
   - Only for *mobile view (max-width: 480px)*

🎨 5. The calculator should use a *pastel color theme only* — ❌ avoid *black* or *blue. Use light, calming colors like **mint green, **peach, **lavender, or **beige*.

❌ 6. Please include a *Cancel button* that allows users to clear or exit their current input. Place it in a user-friendly position in the layout.

🛠 7. Please suggest only the required:
   - ✅ HTML structure changes (if needed)
   - ✅ CSS media queries for mobile
   - ✅ Minor layout adjustments to support this UI/UX
