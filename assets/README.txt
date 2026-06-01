Live Demos — media assets
==========================

The portfolio's "Live Demos" section (nav: Demos) shows a gallery card per
piece of work. Clicking a card opens a lightbox that plays videos and shows
screenshots. Files are loaded from THIS folder.

MCP-Based AI Business Analytics Chatbot — expected files:

  mcp-chatbot-demo.mp4         — screen-recording walkthrough (video)
  mcp-chatbot-insights.png     — Page Insights / property charts view
  mcp-chatbot-financial.png    — Chat: financial data + KPI metrics + chart
  mcp-chatbot-contracts.png    — Chat history + contracts overview (Norwegian)

Notes
-----
- Use these EXACT filenames, or update the `demos` array in index.html to
  match your own names/paths.
- Video: an MP4 (H.264) plays inline with controls. Keep it reasonably sized
  (a 720p/1080p screen recording is fine).
- Until a file exists, the gallery shows a tidy "coming soon" placeholder
  instead of a broken image/video. Drop files in and refresh — no code edits.

Adding another work to the showcase
-----------------------------------
Add an object to the `demos` array in index.html:

  {
    name: "My Project",
    desc: "One-line description.",
    media: [
      { type:"video", src:"assets/myproj-demo.mp4", cap:"Walkthrough" },
      { type:"image", src:"assets/myproj-1.png",    cap:"Dashboard" }
    ]
  }
