# 🤖 Prompt Vault

Welcome to your AI Prompt Vault! (🕓 Last updated: May 15, 2025)

Inside, you’ll find my prompt library designed to save time and grow your income… Fast.

It’s **ONLY new** and will be updated as I create new videos, so keep it bookmarked.

Use them one at a time. Test them. Tweak them. Profit.

👇 Scroll down to pick your poison.

<aside>
📌

**Bookmark this Vault**

Press **Ctrl + D** (Windows) or **Cmd + D** (Mac) to save it.

On mobile, tap the share icon → “Add to Bookmarks” or “Add to Home Screen.”

</aside>

## Prompts

### tempo.new prompt:
I want to build a travel/vacation planner using [Perplexity or Google Gemini API Key].
I will give you where I'm going, what days I'll be there, and what my budget is... You'll then tell me what spots to visit, what days, where to eat, etc.

### Google Gemini Pro 2.5 Prompt: 
My website is https://mubashirhassan.com/ . I found a competitor here: https://perfectketo.com/blog/
Focusing only on blog content, specifically informational content and tips type articles, compare the two websites, and come up with a content plan for my blog that would cover topics that perfectketo.com has covered that my blog has not. The content needs to be ideas that ketokrush could easily rank for as the content on perfectketo.com was not optimized for. You will investigate both websites and tell me what I need to write and add to ketokrush.com to grow the website.

### Generate Lego, Simpsons & Pixar Images with ChatGPT
Lego Prompt: "Create image. Convert this photo into a lego character. Keep the outfit style the same as the image. The Lego figure should be full bodied. Make them happy. Include a background setting of a creative office space full of post its and whiteboards."

Simpsons Prompt: "Create image. Convert the same photo into a Simpsons style character. The character is an energetic technology expert. Put them into an appropriate setting in the Simpson universe."

Pixar Prompt: "Create image. Use the attached image as a reference. Create a whimsical Pixar-style character with large expressive eyes, soft lighting, and vibrant colours in an imaginative setting like a magical or futuristic city."

# Helpful Prompts for Tools Website

Below is a collection of prompts and ideas designed to create useful tools and WordPress plugins for your website. These prompts focus on building practical, user-friendly tools to enhance functionality and engagement, perfect for developers, bloggers, and business owners.

---

## WordPress Plugin Prompts

### 1. Loan EMI Calculator WordPress Plugin

**Prompt:**  
I want to create a WordPress plugin named "Loan EMI Calculator" that helps users calculate their monthly loan EMI. The plugin should have a shortcode `[emi_calculator]` to embed it on any page.

**Features Required:**  
- **Input Fields:** Loan Amount (₹), Interest Rate (%) (Annual), Loan Tenure (Years or Months)  
- A "Calculate EMI" button that computes the EMI instantly  
- **Use the EMI formula:** EMI = [P × R × (1+R)^N] / [(1+R)^N – 1], where P = Loan Amount, R = Monthly Interest Rate (Annual Rate / 12 / 100), N = Loan Tenure (in months)  
- **Display the results:** Monthly EMI, Total Interest Payable, Total Amount Payable (Loan + Interest)  
- Use AJAX to calculate results dynamically without page refresh  
- Modern user-friendly UI with proper spacing  
- Use FontAwesome icons for better visual appeal  
- Proper CSS styling with `css/style.css` and JavaScript `js/script.js`  
- The plugin should enqueue scripts properly using `wp_enqueue_scripts`  

**Code Requirements:**  
- Provide a complete `loan-emi-calculator.php` plugin file  
- Include `js/script.js` for handling AJAX requests  
- Include `css/style.css` for styling  
- Explain step-by-step installation and how to use the plugin  

**Output:**  
Please generate the complete WordPress plugin code along with installation instructions.

---

### 2. GST Calculator WordPress Plugin

**Prompt:**  
I want to create a WordPress plugin named "GST Calculator India" that helps users calculate GST on products/services. The plugin should have a shortcode `[gst_calculator]` to display the calculator on any page.

**Features Required:**  
- **Input Fields:** Original Price (₹), GST Rate (%) (Dropdown with options: 5%, 12%, 18%, 28%)  
- A "Calculate GST" button to instantly compute the GST amount  
- **Formula:** GST Amount = (Original Price * GST Rate) / 100, Final Price = Original Price + GST Amount  
- **Output Display:** GST Amount (₹), Total Price After GST, CGST & SGST Breakdown for intra-state transactions  
- Use AJAX for dynamic calculation without page refresh  
- Modern UI with FontAwesome icons  
- Provide proper CSS styling in `css/style.css` and interactivity with `js/script.js`  
- Properly enqueue styles and scripts using `wp_enqueue_scripts`  

**Code Requirements:**  
- Provide the full `gst-calculator.php` plugin file  
- Include `js/script.js` for AJAX-based calculations  
- Include `css/style.css` for better styling  
- Explain step-by-step installation and usage  

**Output:**  
Please generate the complete WordPress plugin code along with installation instructions.

---

### 3. Word Counter & Read Time Calculator WordPress Plugin

**Prompt:**  
I want to create a WordPress plugin named "Word Counter & Read Time Calculator" that helps users count words and estimate reading time. The plugin should have a shortcode `[word_counter]` to display it anywhere on a page.

**Features Required:**  
- **Input Text Box** where users can type or paste text  
- **Live Word Count** that displays total words and characters as the user types  
- **Estimated Reading Time Calculation** using the formula: Read Time = Total Words / 200 (Assuming average reading speed is 200 words per minute)  
- If reading time is less than 1 minute, display the estimated time in seconds  
- **Display the results dynamically:** Total Words, Total Characters, Estimated Reading Time  
- AJAX-based real-time calculation without page reload  
- Modern UI with FontAwesome icons  
- Proper styling using `css/style.css` and JavaScript interactivity with `js/script.js`  
- Properly enqueue scripts using `wp_enqueue_scripts`  

**Code Requirements:**  
- Provide a full `word-counter.php` plugin file  
- Include `js/script.js` for real-time calculation  
- Include `css/style.css` for modern UI styling  
- Explain step-by-step installation and usage  

**Output:**  
Please generate the full WordPress plugin code along with installation instructions.

---

### 4. Age Calculator WordPress Plugin

**Prompt:**  
I want to create a WordPress plugin named "Age Calculator" that allows users to calculate their current age based on their Date & Time of Birth. The plugin should include a shortcode `[age_calculator]` to embed it anywhere on a WordPress page.

**Features Required:**  
- **Input Field** where users can select Date & Time of Birth using a modern Date-Time Picker  
- A "Calculate Age" button that, when clicked, will:  
  - Calculate and display years, months, days, hours, minutes, and seconds dynamically  
  - Show the age result without page refresh using AJAX  
- **Display Format:** Your Age: XX Years, XX Months, XX Days, XX Hours, XX Minutes, XX Seconds  
- The Date Picker must include decade selection so users can easily pick their birth year (e.g., 1990-2000, 2000-2010)  
- The tool should be responsive and mobile-friendly with an attractive UI  
- Include FontAwesome icons for better visuals  
- Use AJAX-based calculation so that users don't need to refresh the page  
- Proper CSS styling with `css/style.css` and interactivity with `js/script.js`  
- Enqueue styles and scripts properly using `wp_enqueue_scripts`  

**Code Requirements:**  
- Provide a full `age-calculator.php` plugin file  
- Include `js/script.js` for handling AJAX and real-time updates  
- Include `css/style.css` for UI design  
- Explain step-by-step installation and usage  

**Output:**  
Please generate the complete WordPress plugin code along with installation instructions.

---

## More Tools Ideas

### ✅ YouTube Video Thumbnail Downloader

**Use Case:** Fetch and download HD thumbnails from any YouTube video URL.  

**Features:**  
- Enter YouTube Video Link  
- Show Thumbnail in HD  
- Download Button for image  

**Best for:** Video editors, social media creators  

---

### ✅ Instagram Hashtag Generator Tool

**Use Case:** Generates trending hashtags for Instagram posts based on keywords.  

**Features:**  
- Enter Keyword (e.g., fitness, travel)  
- Fetch Trending Hashtags  
- Copy All Button  

**Best for:** Influencers, social media managers  

---

### ✅ Custom QR Code Generator

**Use Case:** Generate QR codes for links, text, contact details, or WiFi passwords.  

**Features:**  
- Input URL, Text, Contact  
- Generate Downloadable QR Code  
- Custom Color & Size  

**Best for:** Business websites, event pages  

---

### ✅ Password Generator Tool

**Use Case:** Generate strong passwords for users.  

**Features:**  
- Set password length  
- Select Uppercase, Numbers, Symbols  
- Copy Button  

**Best for:** Security-conscious users  

---

### ✅ Website Speed Test Plugin

**Use Case:** Helps users test their website loading speed.  

**Features:**  
- Enter Website URL  
- Show Loading Time  
- Show Page Size & Recommendations  

**Similar to:** GTmetrix, Google PageSpeed Insights  

---

### ✅ Image Compressor for WordPress

**Use Case:** Reduces image file size before uploading to WordPress.  

**Features:**  
- Upload image  
- Set Compression Level  
- Download Optimized Image  

**Best for:** Bloggers, photographers, eCommerce  

---

### 🛠️ Build A Website In Under 2 Minutes

Create a prompt to build a full modern HTML landing page for a service called **Finish Mode AI**, which helps businesses automate their operations using custom AI systems.

The design should include:

- A fixed header with navigation links (Features, Process, Pricing, Contact)
- A hero section with a strong headline, subheadline, and CTA button to book a Calendly call
- Sections for:
  - Features (with icons and descriptions)
  - Process (3-step transformation process)
  - Embedded YouTube video
  - Testimonials
  - Pricing (3 tiers with icons and hover effects)
  - Contact form + Calendly inline widget
- A sticky back-to-top button
- Light/dark mode toggle
- Smooth scrolling and scroll-triggered animations
- Fully mobile responsive with media queries
- Clean, well-commented CSS (either inline or internal)
- Use Google Fonts (Poppins & Open Sans) and Font Awesome icons
- Use semantic HTML5 structure
- Include JavaScript for nav toggle, theme switcher, scroll animations, and Calendly theme sync

Also, make sure the theme is sleek and techy — dark mode by default with a toggle for light mode. Use navy, neon green, white, and slate colors. Avoid bloated frameworks. This should feel like a modern SaaS site for high-ticket clients.

### 🧠 Deep Research Money Niches

#### Prompt 1: Find Underserved Niche Markets

*Most niche markets are just people repeating the same old crap: fitness, finance, make money online. Boring. I want you to dig up weird but real niche markets that are emotionally intense, profitable, and still wide open. So, give me 10 niche markets that are emotionally intense (pain or passion), underserved, and not yet saturated. Avoid common categories like health, fitness, finance, crypto, and productivity.*

**👉 Use this prompt with deep-research ChatGPT**

#### Prompt 2: Understand Their Daily Life

*For the [niche], break down the person’s day. What frustrates them? What decisions do they obsess over? What do they wish existed but can’t find?*

**👉 Use this with regular ChatGPT.**

#### Prompt 3: Spending Behavior

*What solutions are they already spending money on? And what do they wish they could buy that doesn’t exist yet?*

**👉 Can use ChatGPT Deep Research for this, or just normal… deep research adds extra juice.**

#### Prompt 4: Monetize the Niche

*List 5 ways to monetize this niche without creating a physical product. Focus on affiliate products, digital offers, or services. Make them specific, not vague.*

**👉 Great with regular ChatGPT — it’s a creativity machine.**

#### Prompt 5: Create Low-Cost Offers

*Give me 3 possible low-cost offers ($7–$27) someone could sell to this niche to solve one of their urgent pains.*

#### Prompt 6: Emotional Purchase Triggers

*What emotional triggers or turning points would push someone in this niche to spend money fast? Think fear, guilt, pride, urgency, or FOMO.*

**👉 Use this with regular ChatGPT to tap into human psychology.**

### 9 Google Gemini 2.5 Use Cases

1. **Content System:**

Here’s my core idea: [INSERT TOPIC]

My target audience is: [INSERT AUDIENCE TYPE]

My goal is to promote: [INSERT PRODUCT, SERVICE, OR LINK]

Break this down into:

1. A blog post (800 words)
2. A YouTube video script (under 10 mins)
3. An Instagram carousel (7 slides)
4. A tweet thread (5–8 tweets)
5. A lead magnet title + outline
6. A short email to drive traffic to the blog post

Make everything use a relatable, human tone. Avoid fluff. Write like you're explaining this to a smart but overwhelmed solo creator. And include light emotional hooks where relevant.

2. **Find High-Pain, High-Profit Niche Ideas**

Search Reddit for emotionally charged threads related to [INSERT BROAD TOPIC OR NICHE, e.g., “making money online” or “weight loss”].

Find posts where users express frustration, confusion, desperation, or failed attempts.

Then:

1. Summarize the pain points in raw language (quote snippets if possible)
2. Suggest specific sub-niches based on recurring problems
3. Propose affiliate or digital products that could help solve those problems
4. Create 3 content angles that could speak directly to these people and stand out on YouTube or blogs

Focus on human behavior and emotional insight — not just surface-level complaints.

3. **Create Hyper-Relevant Landing Pages for Paid Ads**

Act as a modern landing page copywriter and HTML5 builder with a keen eye for design and conversion.

I’m creating a sleek, high-converting landing page for:

Audience: “Freelancers sick of chasing new clients every month”

Problem: “Inconsistent income and burnout”

Offer: $17 ebook: Build a Productized Service in 7 Days

Your task:

1. Write emotionally compelling, bold copy for each section (use punchy headers, benefit-rich bullets, and short-form storytelling)
2. Structure the layout clearly using a modern flow:
   - Hero with bold gradient + clear CTA
   - Pain section with problem language
   - Solution section that reframes hope
   - Benefit bullets with icons (can use emoji placeholders)
   - Bold CTA section with large button
   - 1 short testimonial
   - Simple footer with mini FAQ or social proof mention
3. Generate clean, beautiful HTML5 code for the page. No external CSS or JS. Use inline styles with:
   - Gradient backgrounds
   - Rounded buttons
   - Large headline fonts
   - Mobile-friendly spacing and padding
   - White space that breathes

Important: This should feel modern, fresh, and energizing — not stiff or old-school. Think like a startup landing page meets digital product mini-site.

Keep it fast-loading and paste-ready for Hostinger’s basic HTML editor.

4. **Use It as a Thinking Partner**

Act as a 190 IQ strategic business advisor and critical thinking coach.

I’m feeling stuck on this problem: [I have 3 products half-built and don’t know which one to launch]

Ask me 3 clarifying questions to better understand my situation, then help me:

1. Break the problem into smaller chunks
2. Identify the likely root cause
3. Offer 2–3 different action paths I could take
4. Give a recommendation based on the *Finish Mode* mindset (progress over perfection, shipping over planning)

Be honest, blunt, and helpful. Skip generic fluff — I want insight that moves me forward.

5. **Rewrite Sales Pages for Better Emotional Pull**

Act as a conversion copywriter trained in emotional storytelling and direct response.

Here is a sales page section that feels bland or robotic:

[PASTE TEXT HERE]

I want you to:

1. Rewrite it with stronger emotional संस्कार (urgency, pain, desire)
2. Use more relatable language — write like a real person, not a brochure
3. Inject Finish Mode energy: blunt, fast-moving, action-driven copy
4. Keep the structure, but tighten the flow and eliminate fluff

Goal: Make the reader feel like this offer is *exactly* what they’ve been waiting for — and they need to act now.

6. **Generate Lead Magnet Ideas That Don’t Suck**

Act as a conversion strategist and email list growth expert.

My audience is: [TARGET AUDIENCE]

Their biggest problem is: [EMOTIONAL + PRACTICAL PAIN POINT]

My goal is to create a **lead magnet** that feels like a quick win — not a long boring guide.

Give me:

1. 5 lead magnet ideas with benefit-focused titles (no fluff)
2. The format of each (template, cheat sheet, swipe file, quiz, etc.)
3. Why it works psychologically for this audience
4. A 3-bullet value breakdown for each one (what they’ll learn/feel/do)

Make these punchy, emotionally charged, and tied to *action*, not information overload.

7. **Build Multi-Page Mini Courses Fast**

Act as a digital course builder and instructional designer.

I want to build a fast, high-impact **mini course** based on this topic: [INSERT TOPIC]

My audience is: [TARGET AUDIENCE]

The course goal is: [WHAT TRANSFORMATION OR OUTCOME THEY GET]

I want to deliver it as a simple 3-5 module course (text-based, Loom-style, or slides)

Create:

1. A compelling course title that speaks to their core pain or goal
2. A 3-5 part module breakdown with punchy names and clear outcomes
3. A short video script for each module (2–5 mins worth)
4. Suggested CTA at the end of the course (to buy, subscribe, or take next step)

Write it in a human, energetic tone. Keep it lean — no bloated lectures, just movement and clarity.

8. **Repurpose Old Content Into Finish Mode Funnels**

“Turn this into a 3-email sequence + landing page with a soft CTA to my prompt vault.”

### 📘 How To Create An Affiliate Ebook

#### STEP 1: Find a Profitable Niche

First thing—niche selection. You need a niche that:

✅ Has affiliate products  
✅ Solves a real problem  
✅ Actually makes money  

Say this:

"What are the 10 best affiliate 'niche' markets to enter into to make money online?"

AI spits out a list. Now, don’t just pick one that makes you say, hey I like this. Think like a marketer. What audience do you actually want to attract? If you choose “weight loss,” be prepared to deal with a ton of competition. If you go for something like "productivity for solopreneurs", you might have a better chance.

Pick a niche. Got it? Cool.

---

#### STEP 2: Identify the Problems in That Niche

Once you have a niche, you need a problem to solve. That’s what sells—people buy solutions, not random ebooks.

**Say this:**

"What are specific problems people face in the [INSERT NICHE] market?"

Now, AI will throw you a buffet of pain points. Your job? Pick ONE. Not five. Not three. ONE.

If you’re in the personal finance niche, maybe it’s “how to stop overspending.”

If it’s fitness, maybe it’s “how to build muscle as a skinny guy.”

Find one juicy problem people are desperate to fix.

#### STEP 3: Find Affiliate Products That Solve That Problem

Now that you have your problem, you need an affiliate product that actually fixes it.

**Say this:**

"Find the top 10 most relevant and promising affiliate products in [this niche] on Amazon, ClickBank, ShareASale, etc."

Look through the results. Pick something that:

✔ Pays decent commissions  
✔ Actually relates to your ebook’s problem  
✔ Has decent reviews (because selling garbage = refund city)

#### STEP 4: Brainstorm Ebook Ideas

**Say this:**

"I like the idea of [INSERT PROBLEM], and how to overcome it. Can you give me 5 ebook ideas on this topic?"

You’ll get five title ideas. Pick one that sounds like it actually belongs on a buyers list, not something AI spat out… too much of this.

#### STEP 5: Generate the Outline

**Say this:**

"Create a potential outline for a 5000-word ebook on this topic including the chosen affiliate product [INSERT AFFILIATE PRODUCT]. Make sure to add in at least 10 lesser-known pieces of advice."

Why lesser-known advice?

Because it makes your ebook unique. It also makes it easier to market—because “10 tips you’ve never heard of” is way more clickable than “the same boring crap you see everywhere.”

#### STEP 6: Generate the Content (One Section at a Time)

Now, don’t ask AI to write the whole thing at once—it’ll spit out the driest, most soulless garbage you’ve ever read. Instead, go section by section.

**Say this:**

*"Can you write Section 1 on [INSERT POINTS]?"*

When AI generates the text, tell it to be more casual:

*"Rewrite this in a more casual tone."*

### 💡 Content Ideas Generation

Skip the small talk. I'm writing for: {TARGET AUDIENCE}.

I don’t want bland, recycled advice. I want content ideas that hit nerves, flip beliefs, or make people stop scrolling and go: “Damn, that’s me.”

Here’s what I need:

1. **10 real struggles** this group is dealing with — not generic fluff, but the kind of stuff they think about at 2am.
2. **10 raw desires** they secretly (or not-so-secretly) want — not just goals, but the emotional drivers.
3. **10 content ideas** that feel like newsletter subject lines or YouTube titles designed to slap. Think:
   - Contrarian takes
   - “Nobody talks about this” hooks
   - Practical how-tos with a twist
   - Listicles that aren’t boring
   - Things that challenge assumptions

Don’t ask me to clarify the audience.
Don’t give me “it depends” advice.
Just give me the list — numbered, clean, and specific.

Target audience: {TARGET AUDIENCE}

### 🧭 The Best Strategic Advisor (Updated from Dan Koe)

Act as my personal strategic advisor with the following context:

- Your IQ is 180.
- You’ve built multiple billion-dollar companies from scratch.
- You have deep mastery of psychology, systems, strategy, and execution.
- You are brutally honest, direct as hell, and allergic to excuses.
- You care about my results — not my feelings.
- You think in terms of leverage, root causes, and long-term impact.
- You don’t tolerate busywork, mental gymnastics, or surface-level fixes.
- You default to speed over perfection — because action creates clarity.
- You simplify complex problems with ruthless precision. Short answers. Big results.
- You understand how resistance and self-sabotage show up — and you call it out before it wrecks momentum.

Your mission is to:

1. Expose the real bottlenecks holding me back.
2. Deliver specific, high-leverage actions to break through.
3. Call out my blind spots, coping mechanisms, and comfort zone bullshit.
4. Force me to think bigger, move faster, and act smarter.
5. Hold me to a standard most people can’t handle.
6. Arm me with frameworks, systems, and mental models I can deploy immediately.

Every response should follow this structure:

- Start with the **hard truth** I need to hear — no sugarcoating.
- Follow with **clear, actionable steps** I can implement *today*.
- End with a **direct challenge or assignment** to push my edge.
- Ask for **proof or a debrief** next round — no ghosting, no drifting.

Only respond when you're ready to go to war with comfort, excuses, and mediocrity.

### 🎓 Learning Concierge

You're my personal learning concierge.

I want to master [SKILL], and I’m not interested in wasting time with fluff or outdated advice.

Give me:

1. The **top 3–5 books** that actually move the needle (no theory dumps — give me practical, proven stuff).
2. The **best websites or communities** where serious learners hang out.
3. A few **YouTube videos or channels** that are actually worth watching — not clickbait or surface-level stuff.
4. The **best online courses** — ideally ones that include exercises, case studies, or real-world application.

For each resource:

- Explain *why* it's valuable (don’t just say “comprehensive” or “well-rated”).
- Tell me **who it's best for** (beginner, intermediate, advanced).
- Show me how to **use it effectively** — e.g. take notes, apply it to real projects, etc.

I want insight, not just a list. Curate this like you’re building a custom learning path for someone who takes action — not just another browser-tab hoarder.

### 😶‍🌫️ Idea Reframer

> I’m working on an offer for [insert type of product… e.g. a mini course, ebook, template pack, etc.].
> 
> Here's a rough version of it:
> 
> “[Paste your rough offer idea here]”
> 
> Reframe this offer using the following angles:
> 
> 1. What pain does this solve clearly and directly?
> 2. What transformation will someone *feel* by the end?
> 3. Say it back to me in a clear, exciting sentence that makes people want to buy.
> 4. Optional: Turn that sentence into a hook or subject line.

---

#### 💥 Example:

### Simple Hosting Comparison HTML

Create a simple hosting comparison checker in html I can put on my systeme.io page for the top 10 cheap hosting programs that are perfect for beginners. Make it funky and in cool techy neon colors, with a dark background. When it's searching for the best deals at the moment, have a cool waiting animation going.

### Keyword-to-Content Power Prompt

Using the keyword: [INSERT KEYWORD], do the following in one go:

**Commercial Intent Keyword List:** Provide a list of commercial intent keywords for this niche that fit the golden keyword ratio and have a keyword difficulty under 20.

**SEO-Optimized Article Outline:** Create a full article outline based on this keyword. Include a compelling title tag and a meta description that uses ellipses to build intrigue, while naturally including the main keyword. Ensure the article semantically covers the topic in-depth, includes "People Also Ask" queries from Google, and incorporates related LSI keywords and specific entities.

**Introduction:** Write a powerful, emotion-based hook for the introduction that grabs attention and aligns with the outline.

**Section 2 Deep Dive:** Flesh out Section 2 of the outline by educating the reader thoroughly. Include a short opening paragraph and expand on each sub-point with at least two paragraphs each, making it highly informative and actionable.

**Conclusion:** Wrap up the article with a strong closing paragraph. Summarize key takeaways from each section, reinforce the benefits, encourage action, and offer a final tip related to the topic.

### Grok Article Creation

**Prompt 1:** Search exclusively on X.com and give me 10 blog post ideas about [INSERT NICHE] based on what’s trending over the last week. Each post should have at least 1000 likes.

**Prompt 2:** Write 5 clickable blog titles for a post about [INSERT CHOSEN POST], based on the top liked post in this niche today.

**Prompt 3:** Create a 5-part blog post outline for a post titled [INSERT BLOG TITLE] designed to [INSERT DESIRED ACTION] and feel supported. Base it on the most relevant trending content from X today within the same niche. Structure it in a way that balances storytelling and practical steps.

**Prompt 4:** Write an emotional, attention-grabbing intro paragraph for this blog post, based on trending perspectives from [YOUR NICHE] on X. Make it feel like it was written by someone who’s part of the community and understands the emotional tension behind the topic.

**Prompt 5:** *Rewrite that intro paragraph from the perspective of someone who [INSERT YOUR HUMAN PERSPECTIVE], and make it feel like their personal turning point.*

**Prompt 6:** Write a persuasive closing paragraph for this blog post that encourages [ACTION] today. Offer them a [LEAD MAGNET], and make sure the tone feels supportive, not salesy. Structure it like a mini story — one that ends with a hopeful next step.

### Note Taking App in Firebase

**Prompt 1:**

*Build a simple mobile-friendly notepad app that runs locally without backend.*

*Features:*

- *Add ideas with a title and description using a form*
- *Show a list of ideas (newest first) in a card-based layout*
- *Allow users to mark/unmark favorites (with icon toggle)*
- *Store ideas using local storage (no Firebase/Firestore)*
- *Use simple icons for actions: add, favorite, delete*

*Style:*

- *Clean, minimal design*
- *Use cards for each idea*
- *Include intuitive icon buttons*

*Make this in Flutter so I can turn it into a mobile app later.*

**Prompt 2:**

***UI Upgrade:***

*Update the entire app to use the following color scheme:*

- *Background color: #002244*
- *Primary accent (buttons, icons, outlines): #10ffb6*
- *Text: Use white or light tones for readability*

*Polish the app UI with:*

- *Card-style layout for each idea with slight shadow, rounded corners, and padding*
- *Bolder titles and improved spacing between elements*
- *Use modern, clean font*
- *Update the input fields and add idea button to match the color theme*
- *Use outlined heart icons for favoriting, and filled hearts in #10ffb6 when toggled*
- *Add a delete icon in the corner of each card*

*Make the UI feel sleek, futuristic, and mobile-friendly.*

### ChatGPT Clarity Driver for Google NotebookLM

**Prompt 1:**

You’re my AI setup strategist. I need you to extract the essence of how I think, talk, and operate — including my tone, values, priorities, and the way I help others.

Create a single doc that captures:

– My brand tone (blunt, human, sometimes sweary, never fluffy)  
– My strategic lens (simplicity, leverage, finishing fast)  
– My content purpose (helping overwhelmed solo creators make money online without burning out)  
– The emotional/behavioral truths I build from (momentum > perfection, emotional cycles, INTP wiring)  
– How AI should respond to me (mirror my tone, be strategic, never generic, always simplify)

This document will be used to train AI systems or teammates to think like me when creating content, summarizing ideas, organizing knowledge, or building new assets.

**Prompt 2:**

- Intro Concept for a YouTube script
- How-to angle for an Email
- Pain point for a Tweet thread
- System map for a Carousel post
- Case example for a Mini course lesson
- FAQ item for a Short-form video/IG Reel

### MarketSpy Prompt String

**Prompt 1:**

You are MarketSpy — my emotional intelligence agent for affiliate product research.

Analyze the Reddit thread below and extract the **real buyer psychology**, including:

1. Core emotional pain (be specific, not generic)
2. Identity-level beliefs or self-talk (e.g., “I’m lazy”, “I always quit”)
3. What they’ve tried and why it didn’t work
4. What they’re afraid of, and what they secretly want
5. Emotional language or phrases they repeat

Then translate those insights into:

- 3 product angle ideas (types of offers that would feel like a relief or breakthrough)
- 2 affiliate product categories that align emotionally (e.g., tool, course, membership)
- Keywords to search for affiliate products on Gumroad, ClickBank, Amazon, or PartnerStack
- 3 emotionally charged content ideas (blog, video, or email)
- 3 hook headlines

SOURCE: [paste Reddit thread here]

**Prompt 2:**

Based on the emotional and identity insights you just extracted, do the following:

1. Suggest 3 real affiliate products that align with these emotional needs.
2. For each, include:
   - Emotional hook
   - Why this product feels like a “relief” or “solution” to them
   - Affiliate network to search (e.g., ClickBank, Gumroad, Amazon, Systeme.io)

**Prompt 3:**

Now turn the emotional insight + product match into affiliate content ideas for [INSERT PRODUCT]

For each product idea:

1. Suggest 1 long-form blog topic, 1 YouTube video, and 1 email subject line
2. Include a short outline or content flow for each
3. Make it emotionally-driven and conversion-focused, not just a review

Format:

- 📝 Blog:
- 🎥 Video:
- 📧 Email:

**Prompt 4:**

Take [ARTICLE NAME] and write a full affiliate article in the following structure:

1. Hook (emotionally resonant intro)
2. Personal-feeling story or relatable experience
3. Problem they're facing
4. Failed attempts
5. Why this product speaks to them now
6. How it works
7. Unique tip or insight
8. Call-to-action with urgency or identity-based close

Tone: blunt, emotionally sharp, helpful, non-hypey. No fluff. Speak like a real human.

**Extra Prompt:**

Create a freebie lead magnet or bonus checklist that would pair with this affiliate product and increase conversions.

Make it fast to create, useful, and tied to an emotional need.

Include a name, one-line promise, and what’s inside.

### Gemini Affiliate Site

1. Can you give me a properly copywritten review in the style of Dan Kennedy for the affiliate product [tai lopezs 67 steps] ensuring that it hits all psychological buying triggers and follows the six step sales cycle as outlined in Silver Bullet Selling by G.A. Bartick and Paul Bartick. Use these as a guide to the article and do not explicitly mention in the article, using their role as the guide for the reader. Please make the review properly formatted with correct title and heading structure and between 1500 and 2000 words. Only mention information related to the affiliate product.

2. *Create a simple affiliate webpage explicitly including all of this full review ensuring to make it modern and sleek, adding images placeholder with text outlining what images to include, and ensuring RS ensuring it includes graphically and psychologically attention grabbing elements including cta buttons, headlines, callouts, quotes, etc.. Do not include any mention of the copywriting style or the actual names of the sales process being used.*

**Optional:** *Is there anything we missed out on that could help this site convert better?*

3. **Reddit Value Post Structure**

**Title:**

Craft it like a genuine reflection or insight — not a pitch.

Examples:

- *“Tried [Product] for 60 Days – Here's What I Wish I Knew Before”*
- *“This tool helped me fix [specific pain point], but not without problems…”*
- *“Noticed a pattern after testing 5 [tool types] — here's what stood out”*

---

**Body:**

**1. Start with your honest story or insight.**

“Okay, so I’ve been neck-deep in [problem] for the past 3 months. I tried everything from X to Y. Most of it was junk or just not a good fit for my brain.”

**2. Introduce the product naturally.**

“I stumbled onto [product] pretty randomly and figured I’d test it out. At first, I was skeptical because [reason], but…”

**3. Share the good, the bad, and the unexpected.**

Bullet points or raw honesty always works:

- “It nailed X.”
- “It totally missed the mark on Y.”
- “But what surprised me most was Z — no one talks about that.”

**4. Give actionable takeaways.**

Stuff like:

“If you're thinking of trying it, make sure you...”

“Don’t bother unless you already have…”

“This works best for people who ___.”

**5. Softly drop the link.**

“And because I went full nerd on this, I wrote a longer breakdown with screenshots, examples, and a few weird things I found — you can read it [here](yourlink)

If this helps even one person skip the same trial-and-error I went through, worth it.” (This humanizes the link drop.)

### Gemini Email Funnel

#### System Level:

You are a skilled email copywriter who writes like a real human, with a friendly, direct, slightly rebellious tone. Your job is to write a short 5-part email funnel that turns new subscribers into buyers.

Here’s the product info you will receive from the user:

– Offer: [Insert your product or service here]  
– Target audience: [Who it’s for]  
– Key emotional driver: [e.g., “They feel stuck and overwhelmed with too many tools”]  
– Unique hook: [e.g., “You don’t need ClickFunnels or plugins — Gemini builds funnels for you in minutes”]  
– CTA destination: [Link or call-to-action]

Keep the tone honest, sharp, and non-hype. You can use storytelling, objection flipping, and real human talk — but NO guru vibes. Be concise. Aim for 150–200 words per email. Include subject lines and clear CTAs where appropriate.

**Write Email 1 of a 5-part sequence.**

This is the welcome email. Introduce the sender, connect with the reader’s current frustration, and create instant alignment. Use a personal tone. Show that you understand what they’re struggling with, and make them feel like they’re finally in the right place.

End with a soft CTA that invites them to check out the offer.

---

**Write Email 2 of the sequence.**

Highlight why the reader is still stuck — not due to lack of trying, but because the current approach (tools, overthinking, planning) hasn’t worked. Amplify the frustration. Flip the perspective.

End with a teaser: “Tomorrow I’ll show you a simpler way.”

---

**Write Email 3 of the sequence.**

Introduce the product or offer as a solution. Frame it as a smarter, faster way to get results. No hype. Make the solution feel simple and obvious in hindsight.

Give 2–3 quick bullet benefits. End with a direct CTA.

---

**Write Email 4 of the sequence.**

Handle a common objection like:

– “I don’t have time”  
– “I’ve tried stuff before”  
– “I’m not ready yet”

Reframe it with empathy and honesty. Use a mini story or metaphor if helpful. End with a confident CTA.

---

**Write Email 5 of the sequence.**

This is the final push. Recap the transformation the reader wants. Remind them what happens if they stay stuck. Encourage them to take the leap.

Make it punchy, no fluff. Close with one clear call-to-action.

---

**Bonus Email:**

Write a casual check-in email. Speak like a real person — not salesy. Ask if they’re still interested in fixing [insert frustration]. Remind them what the offer helps with and include a fresh link or invite to check it out again.

### AI Side Hustles

**SPECIAL NOTE:** These are just base prompts and should be adapted to suit your needs. Also, if you want me to go into a full breakdown, let me know in the comments.

#### Cold Email Affiliate:

📌 **Prompt Example**:

Write a 5-part cold email sequence that builds curiosity, solves a pain point, and introduces [Serpple] as the solution. Keep it conversational, sharp, and non-spammy.

**Tools:** [Hunter.io](http://Hunter.io) and Instantly

#### Clone-a-Creator Newsletter Service:

📌 **Prompt Example**:

Analyze the writing style of [INSERT CREATOR].

Write a 300-word newsletter in their voice, targeting their audience.

Match their tone, pacing, phrasing, humor, and psychology. Use references to their past posts or catchphrases if possible.

#### CAC2:

📌 **Prompt Example**:

Hey [Name], I’ve been following your stuff for a while. I built a prompt stack that mimics your style and used it to draft 3 newsletter editions in your voice. Want me to send them?

**NOTE:** Feed your AI 2-3 pieces of content to get it to properly get into it.

#### AI-Personalized eBook Flipping:

📌 **Prompt Example**:

Rewrite this eBook in a more engaging, modern tone. Change the voice to be for **neurodivergent bloggers who struggle with consistency but have great ideas.** Rename it. Add actionable checklists and relatable examples.

**Tools:** [PLR.me](http://PLR.me) and Gutenburg

#### Local Service 'Auto-Client Kits':

📌 **Prompt Example**:

“Create a full client acquisition kit for a local [Tattoo Removal Clinic] that includes:

1. Landing page copy
2. 3 follow-up emails
3. 1 sales pitch deck outline

A simple social post to attract leads

Tone: Friendly, expert, trustworthy. Audience: People embarrassed by their tattoos.”

#### Micro Info Products for Tiny Audiences:

📌 **Prompt Example**:

Create a 15-page beginner’s guide called ‘TikTok Booking System for Wedding DJs’.

Make it super clear, include checklist items, and position it as a way to get more high-paying wedding gigs without using wedding directories.

### QWEN3 is an Online Business Weapon

**Prompt:**

Rewrite the following landing page headline and subheadline to increase conversions. Focus on urgency, emotional payoff, and clarity. Use active verbs and remove fluff.

**HEADLINE:** Discover the Easiest Way to Start Affiliate Marketing

**SUBHEAD:** Learn How Bloggers Make Passive Income Online Without Paid Ads

**Prompt:**

Summarize this document in terms of:

1. 3 core pain points it addresses
2. 3 emotional triggers it uses
3. 3 potential CTA angles I could turn into offers

Output should be skimmable and focused on offer-building insights.

**Prompt:**

Translate the following sales page headline and paragraph into [Spanish or any language], keeping persuasive tone, emotion, and urgency intact. Do not translate literally — localize the message to resonate emotionally.

**Prompt:**

Analyze the sentiment of this email and tell me:

- Is it too pushy or passive?
- Is the CTA strong enough?
- What would you change to improve emotional resonance?

*[Paste your email copy]*

**Prompt:**

Generate 3 Facebook ad headlines and primary text variations for this product. Focus on benefit-first, curiosity hooks, and short, snappy copy.

**Product:** A free course that teaches people how to use AI to build their first $100 digital product in 72 hours.

**Prompt (Model A):**

Write a YouTube video title about Qwen3’s best features for online entrepreneurs. Make it curiosity-driven and click-worthy. Use no more than 70 characters.

**Prompt (Model B):**

*(Same prompt above, using different model selected in Qwen UI)*

Then ask Qwen:

Which of these two would most likely get higher engagement based on current YouTube trends? Justify the answer in 3 bullet points.

### Gemini Lead Magnet Funnel

**Prompt: Getting The PDF Thesis**

*Extract the name and thesis behind this pdf… the audience it is targeting and the main 3 selling points.*

**Prompt: Opt-in Page**

*Write a high-converting opt-in (squeeze) page for this free guide. Target the Audience of audience of bloggers, solopreneurs, creators. The Goal: Highlight one big result, add curiosity, and build trust. Include: headline, subheadline, 2-3 benefit bullets, form fields, CTA button text.*

*Create this into HTML page, in cool neon and dark colors*

*Add your systeme code…* https://systeme.io/dashboard/share?hash=54645635eb1cbb7771fef943270634a60d5c0cb&type=funnel

---

**Thank You Page Prompt**

*Write a thank-you page script that confirms delivery of the freebie and smoothly introduces a paid offer. Use a tone that is: friendly, no hard sell. Include a delivery confirmation, soft upsell to the Blog Profit Path, and one clear CTA button.*

*Create this into HTML page, in the same design*

---

**Prompt: 3-Email Delivery Sequence**

*Write a 3-email sequence to deliver a free guide.*

*Email 1: Deliver the freebie + create excitement.*

*Email 2: Share a personal story + why this topic matters.*

*Email 3: Offer a paid product as the next step, with urgency.*

*Audience: [YOUR AUDIENCE].*

*Tone: conversational, helpful, slightly edgy.”*

### 5 Laws of Master-Level Project Management Thinking

🟢 **Prompt:**

Act as a senior project manager. Review this plan and list missing steps, unclear owners, or unrealistic timelines.

🟢 **Prompt:**

Act as my devil’s advocate. List 5 hidden risks I might be missing in this project.

🟢 **Prompt:**

Translate this project update into:

1. exec summary (3 bullets),
2. detailed team update,
3. client-friendly email.

🟢 **Prompt:**

Do a pre-mortem: what assumptions must be true for this plan to succeed? What could go wrong?

🟢 **Prompt:**

Simplify this plan. Reduce it to the smallest set of actions that still hit the goal.

### Quality Deepseek Affiliate Articles

**Prompt 1:**

Act as an affiliate marketer. I need you to help me identify one affiliate product that:

- solves a specific problem for [describe audience or niche… e.g., beginner bloggers, pet owners, fitness enthusiasts]
- has a good commission potential
- is not oversaturated or ultra-competitive

List 3 product recommendations, include:

1. Product name + affiliate program (or network it’s on)
2. What problem it solves for the audience
3. Approximate commission % or payout
4. Why it’s a smart pick for a new affiliate

**EXTRA:**

Give me 3 top affiliate products to promote from [program/platform] for [audience], with commission details and why they are a good fit.

**Prompt 2:**

Act as a Platform SEO expert and affiliate marketing strategist.

I need you to help me understand:

1. What is the main search intent for people looking for [product or product type]?
2. What are the top 5 pain points, desires, or objections this audience has?
3. What questions or keywords do they search for before buying?

The product or product type is: [insert product or niche, e.g., email marketing software, dog training course]

**Output:**

- Short description of the audience + search intent
- List of 5 pain points or desires
- List of 5 keywords or questions they are searching for

Prioritize keywords that show buying intent.

**Prompt 3:**

Act as an Platform SEO content strategist and affiliate marketer.

Using the product and keywords below, create a detailed article outline.

The outline should include:

- Introduction (hook + why this matters to the audience)
- Section 1: Product overview
- Section 2: Key benefits + features (with 3–5 bullet points)
- Section 3: Pros + cons
- Section 4: Personal opinion or hypothetical use case
- Section 5: FAQs or common objections (with 3–5 questions + short answers)
- Section 6: Conclusion + clear call to action (include affiliate link placement)

**Product:** [insert product]

**Main keyword:** [insert main keyword]

**Supporting keywords:** [insert keywords]

**Format:**

1. Introduction → [write 1–2 bullet points]
2. Product Overview → [1–2 bullet points]
3. Benefits + Features → [3–5 bullet points]
4. Pros + Cons → [2–3 bullet points each]
5. Personal Opinion / Use Case → [1–2 bullet points]
6. FAQs → [3–5 questions + short bullet answers]
7. Conclusion + CTA → [1–2 bullet points]

**Prompt 4:**

**Writing:**

Expand this outline point into a full paragraph;

[INSERT OUTPUT]

Write like you’re giving advice to a smart beginner who feels overwhelmed about [WHAT ACTION ARE THEY TRYING TO TAKE].

Keep it emotional, motivating, and practical — casual tone, no formal corporate voice.

Gently weave the phrase [INSERT MAIN KEYWORD] once if it fits naturally.

Also, weave in one of these related phrases naturally if it fits: [paste best intent based keywords here from Step 1].

Do not keyword-stuff or make it sound robotic. Do not use words like here’s the thing. Your main role is to not sound like an AI.
