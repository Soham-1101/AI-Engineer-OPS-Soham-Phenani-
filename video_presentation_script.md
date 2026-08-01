# QuickMove Assignment: Video Presentation Script

**Tip:** Have the `QuickMove_Vendor_Dispatcher.html` tool open in your browser before you start recording. Speak confidently and at a measured pace. 

---

### [0:00] Intro & The System Map
*(Visual: Start with your camera on, or showing the Submission_1_The_Map.docx on screen)*

**You:** "Hi, my name is Soham, and this is my submission for the QuickMove AI Ops Engineer assignment. 

To start, I mapped out the entire QuickMove lifecycle—from lead generation and requirement gathering to property matching, vendor negotiation, packing, moving, and utility setup. While mapping this out, I discovered several hidden bottlenecks. While customer anxiety is a loud problem, the highest leverage area for automation is actually in the middle of the funnel: **Workflow 04, Property Partner Outreach.**"

### [0:30] The Problem
*(Visual: Still on the Map document, or looking at the camera)*

**You:** "Currently, ops agents have to manually figure out which local property partners serve a specific city, manually check if they allow pets or have specific configurations, and then type out individual WhatsApp messages to request listings. This is highly error-prone, doesn't utilize performance data, and causes massive delays."

### [0:50] The Solution (The Build)
*(Visual: Switch your screen share to the QuickMove_Vendor_Dispatcher.html tool in your browser. Show the empty state first.)*

**You:** "To solve this, I built the **Dispatcher Intelligence Tool**. This is a zero-friction, standalone web application designed for the Operations team. 

As you can see, I've designed it with a premium, high-end 'dark mode' aesthetic that is both visually striking and highly functional for daily ops work."

### [1:10] Demonstration
*(Visual: Start clicking through the tool on screen)*

**You:** "Let’s run a live scenario. Let's say we have a client moving to **Bengaluru**. 
*(Action: Select 'Bengaluru' from the dropdown)*

They are looking for a **2BHK**. 
*(Action: Click the '2BHK' chip)*

Their budget is **₹45,000**, and they want to live in **Indiranagar**.
*(Action: Type '45,000' and 'Indiranagar' into the inputs)*

Crucially, they have a dog, so we must select **Pet Friendly**.
*(Action: Click the 'Pet Friendly' chip)*"

### [1:40] The Magic
*(Visual: Hover over the "Synthesize Match" button, then click it)*

**You:** "When I click 'Synthesize Match', the tool instantly queries our internal partner database. It strictly filters out any vendors that don't operate in Bengaluru, don't handle 2BHKs, or refuse pets. 

Then, it ranks the remaining eligible partners by their historical performance score and average response time."

*(Visual: Point to the generated cards on the screen)*

**You:** "Here are our top three matches. As you can see, it automatically generates a perfectly formatted WhatsApp outreach template for each partner. It includes the city, configuration, budget, and a unique tracking link for them to upload properties."

### [2:15] One-Click Action
*(Visual: Click the 'Copy Transmission' button to show the toast notification)*

**You:** "The ops agent simply clicks 'Copy Transmission'—which copies the text straight to their clipboard—and drops it into WhatsApp. What used to take 10 minutes of manual checking and typing now takes 15 seconds. This guarantees zero errors, ensures we only use high-performing partners, and drastically cuts down our SLAs."

### [2:35] Conclusion
*(Visual: Switch back to camera or show the Submission 3 document)*

**You:** "All of my architectural thinking, the iterative prompts, and the code generation process have been documented in the Submission 3 Build Log. Thank you for your time, and I look forward to discussing how this tool can scale operations at QuickMove."
