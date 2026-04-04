# News-outlet-site-
🗞️ AI-powered Indian news website with 12 categories, live article generation via Claude API, breaking news ticker, full article modal, and search — built in pure HTML/CSS/JS.

Learning Objectives

Through this project, I practiced:

Structuring webpages using semantic HTML

Styling layouts with CSS

Creating responsive website designs

Organizing content like a real news portal

Improving UI/UX design fundamentals

Future Improvements

Some features that can be added in the future include:

JavaScript for dynamic news updates

Search functionality

Dark mode support

API integration for real-time news

Mobile optimization improvements

----------------------------------------------------------------------------------------

✅ 🚀 WHAT I CHANGED / IMPROVED;-

🔧 Fixed Issues
Fixed broken CSS syntax
Simplified structure (clean & readable)
Removed overly complex nesting

🎨 UI Improvements ;-

Clean modern layout
Responsive grid system
Better typography hierarchy
Dark mode toggle 🌙

----------------------------------------------------------------------------

🚀 ✅ WHAT I ADDED (SIDE-BY-SIDE EXPLANATION)
🧠 1. REAL API INTEGRATION
Before:

❌ Fake / AI-generated news

Now:

✅ Uses NewsAPI

fetch(`https://newsapi.org/v2/top-headlines?...`)

👉 Gives real-world news (India + global)

🔍 2. SEARCH FUNCTION

https://newsapi.org/v2/everything?q=keyword

👉 User can search anything
👉 Dynamic results

⭐ 3. BOOKMARK SYSTEM (LocalStorage)

localStorage.setItem("bookmarks", JSON.stringify(data));
What it does:
Saves articles permanently
Works without backend
Acts like “Save for later”

📖 4. MODAL ARTICLE VIEW
openModal(title, desc, url)

👉 Shows:

Full title
Description
Link to full article

🌙 5. DARK MODE
document.body.classList.toggle("dark");

👉 Improves UX + modern UI

⚡ 6. CATEGORY FILTERING
loadNews("technology")

👉 Switch sections instantly:

Tech
Sports
Business

🎯 7. CLEAN UI SYSTEM
Grid layout
Responsive cards
Modern typography
🔥 BONUS FEATURES I NOW HAVE

✅ Real-time news
✅ Search engine
✅ Bookmark system
✅ Modal reader
✅ Dark mode
✅ Categories
✅ Responsive design
