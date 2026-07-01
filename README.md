# Tinybit.ca

A clean, simple blog about health, menopause, and food reclamation. Deployed on Netlify.

## What you have

- **index.html** - Homepage with hero, stats, latest posts preview
- **blog.html** - Blog archive with posts organized by category
- **style.css** - All the styling (cool-light palette, ocean teal accents)
- **README.md** - This file

## How to add a new blog post

### Step 1: Go to blog.html
Open blog.html in GitHub's editor (click the pencil icon when viewing the file).

### Step 2: Find the template
Look for this comment near the bottom:
```html
<!-- TEMPLATE FOR NEW POSTS -->
```

### Step 3: Copy and paste the template
Copy the template block and paste it BEFORE the closing `</section>` tag.

### Step 4: Fill in your content
Replace the placeholders:
- `[POST-X]` = Give it a unique ID (post-4, post-5, etc.)
- `[CATEGORY]` = One of: `food`, `progress`, or `science`
- `[CATEGORY NAME]` = One of: "Food & Fasting", "Progress Notes", or "Menopause & Science"
- `[DATE]` = When you wrote it or a reference point
- `[POST TITLE]` = Your post title
- `[YOUR CONTENT HERE]` = Your actual post content (just text, HTML handles the formatting)

### Step 5: Save
Click "Commit changes" and Netlify will auto-deploy in ~1 minute.

## Example of a filled-in post

```html
<article class="blog-post food" id="post-4" data-category="food">
  <div class="post-header">
    <div class="post-meta-blog">
      <span class="post-date-blog">Day 14</span>
      <span class="post-category-badge food">Food & Fasting</span>
    </div>
    <h2>Two weeks: the pattern emerges</h2>
  </div>
  <div class="post-content">
    <p>By week two, a pattern was clear. The energy dips happen when I skip protein at breakfast.</p>
    <p>Here's what that looks like...</p>
  </div>
  <div class="post-footer">
    <a href="index.html" class="back-link">← Back to home</a>
  </div>
</article>
```

## How to update the homepage stats

1. Open **index.html** in the GitHub editor
2. Find the `.stats` section (around line 20)
3. Update the numbers and labels
4. Save with "Commit changes"

Example:
```html
<div class="stat">
  <div class="stat-number">14</div>
  <div class="stat-label">Days consistent</div>
</div>
```

## How to update the research section

1. Open **index.html**
2. Find the "What the research shows" section
3. Edit the source, paragraph, and highlight text
4. Save

## Categories

Use one of these three when adding posts:
- **food** - Food & Fasting (orange accent)
- **progress** - Progress Notes (blue accent)
- **science** - Menopause & Science (green accent)

## The color scheme

- Pale background: `#F8F9FA`
- Ocean teal: `#0A6B7E` (main accent)
- Seafoam: `#5FD4D8` (light accent)
- Text: `#1A1A1A` (dark)
- Text secondary: `#666666` (medium gray)
- Borders: `#E8EAED` (light gray)

## Deploying to Netlify

1. **First time only:**
   - Go to netlify.com and sign up (free)
   - Click "New site from Git"
   - Connect your GitHub account
   - Select your `tinybit-ca` repository
   - Click deploy
   - Netlify will give you a live URL

2. **After that:**
   - Every time you commit to GitHub, Netlify auto-deploys
   - You'll see a little badge showing deployment status

## Editing in GitHub

You don't need to use the terminal or VS Code. You can edit files directly in GitHub:
1. Go to github.com/vjohnston044-eng/tinybit-ca
2. Click on any file (index.html, blog.html, style.css)
3. Click the pencil icon to edit
4. Make changes
5. Click "Commit changes"

That's it. Netlify will deploy automatically.

## If something breaks

- Check that you have matching opening and closing tags
- Make sure you didn't accidentally delete part of the HTML
- Roll back by viewing the file history in GitHub (click "History")
- Reach out and we'll fix it together

## Future improvements

Want to add:
- More categories (just ask)
- Different colors (edit style.css)
- Different fonts (change `var(--font-sans)` in style.css)
- An about page (create about.html)

## Questions?

Everything is here. But if you get stuck, ask.