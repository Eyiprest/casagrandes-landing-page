# 🏠 The Casagrandes Landing Page

A vibrant, responsive landing page for The Casagrandes cartoon series.


---

## 👥 Team Members

| Name | Section | Branch | Status |
|------|---------|--------|--------|
| [Sandra] | Navigation & Hero | `hero-section` | 🟡 In Progress |
| [Prest] | About & Characters | `characters-section` | 🟡 In Progress |
| [Precious] | Episodes & Footer| `episodes-section` | 🟡 In Progress |

**Status Legend:**
- 🟡 In Progress
- ✅ Complete
- 🔴 Needs Review


---

## 🎨 Style Guide

> **IMPORTANT:** Follow this style guide exactly to ensure consistency across all sections!

### Color Palette

#### Primary Colors
```css
/* Main brand colors - use these most frequently */
--teal: #00B8D4;        /* Main brand color, primary buttons, accents */
--coral: #FF6B35;       /* Call-to-action buttons, highlights */
--purple: #9C27B0;      /* Secondary accents, gradients */
```

#### Supporting Colors
```css
/* Use for variety and depth */
--yellow: #FFC107;      /* Highlights, decorative elements */
--deep-blue: #1A237E;   /* Footer background, depth */
--cream: #FFF8E1;       /* Page background */
--white: #FFFFFF;       /* Cards, clean sections */
```

#### Text Colors
```css
/* For all text content */
--text-primary: #2D3748;    /* Main headings, body text */
--text-secondary: #718096;  /* Descriptions, captions */
```

### Typography

#### Font Families
```css
/* Headings - Bold and playful */
font-family: 'Fredoka One', cursive;

/* Body Text - Clean and readable */
font-family: 'Poppins', sans-serif;
```

**Import these fonts in your CSS:**
```css
@import url('https://fonts.googleapis.com/css2?family=Fredoka+One&family=Poppins:wght@400;600;700&display=swap');
```

#### Type Scale
| Element | Font | Size | Weight | Line Height | Use Case |
|---------|------|------|--------|-------------|----------|
| **H1** | Fredoka One | 56px | Bold | 1.2 | Hero headline |
| **H2** | Fredoka One | 42px | Bold | 1.3 | Section titles |
| **H3** | Fredoka One | 24px | Bold | 1.4 | Card titles |
| **Body** | Poppins | 18px | Regular | 1.6 | Paragraphs |
| **Small** | Poppins | 14px | Regular | 1.5 | Captions, labels |

### Spacing System

**Use consistent spacing with 8px base unit:**

```css
--space-xs: 4px;      /* Tight spacing, icon padding */
--space-sm: 8px;      /* Small gaps between elements */
--space-md: 16px;     /* Standard padding, button padding */
--space-lg: 24px;     /* Card padding, section spacing */
--space-xl: 32px;     /* Large gaps between cards */
--space-2xl: 48px;    /* Section margins */
--space-3xl: 64px;    /* Hero padding, major sections */
```

**Example Usage:**
```css
.card {
    padding: var(--space-lg);        /* 24px */
    margin-bottom: var(--space-xl);  /* 32px */
}
```



---

## 🚀 Getting Started

### Initial Setup (Do This Once)

1. **Accept the GitHub invitation** (check your email)

2. **Clone the repository:**
cd Desktop  # or wherever you want the project
git clone https://github.com/[PROJECT-TEAMMAIN-USERNAME]/casagrandes-landing-page.git
cd casagrandes-landing-page
```

3. **Open in VS Code:**
Press below in your prompt to open VS code
code .
```

4. **Switch to your branch:**
```bash
git checkout your-section-name
# Example: git checkout hero-section
```

5. **Verify you're on the right branch:**
```bash
git branch
# You should see a * next to your branch name
```

---

## 💻Workflow

### Starting Work any day

# 1. Navigate to project folder
cd casagrandes-landing-page

# 2. Get latest changes
git pull origin main

# 3. Switch to your branch
git checkout your-branch-name

# 4. Start coding!
code .
```

### Saving Your Work (Do This Frequently!)

# 1. Check what you changed
git status

# 2. Add your changes
git add .

# 3. Commit with a clear message
git commit -m "Added hero section gradient background"

# 4. Push to GitHub
git push origin your-branch-name
```


### Submitting Your Work (When Your Section is Complete)

1. **Push your latest changes:**
git push origin your-branch-name
```

2. **Go to GitHub in your browser**

3. **You'll see a yellow banner** - click "Compare & pull request"

4. **Fill in the Pull Request:**
   - **Title:** "Completed [Your Section Name]"
   - **Description:**
     ```
     ## What I did: Sanple
     - Added hero section gradient background
     - Created two call-to-action buttons
     - Made navigation sticky on scroll
     

     ```

5. **Click "Create pull request"**

6. **Wait for review** - The pteam together will review and merge

---

```

**IMPORTANT:** 
- Everyone works in the SAME `index.html` file (or can embed styles in HTML)
- Work only on YOUR assigned section (lines specified above)
- Don't change other people's sections
- Use the style guide variables for consistency
- **Commit your images to Git** - they're part of the project!


---

## 🧪 Testing

### Before Submitting Your Pull Request


**Test Responsive Design:**
- [ ] Mobile (320px - 767px)
- [ ] Tablet (768px - 1023px)
- [ ] Desktop (1024px+)

**How to test responsive in Chrome:**
1. Right-click on page → "Inspect"
2. Click device icon (top left) OR press Ctrl+Shift+M
3. Select different devices from dropdown
4. Test all features


---

## 📚 Resources

### For Learning
- **HTML/CSS:** [MDN Web Docs](https://developer.mozilla.org/en-US/)
- **Git/GitHub:** [GitHub Learning Lab](https://lab.github.com/)
- **Responsive Design:** [This is Responsive](https://bradfrost.github.io/this-is-responsive/)



---

## ❓ Getting Help

### If You're Stuck:

1. **Check this README** - The answer might be here!
2. **Ask in the team chat** - Someone might know
3. **Google the error** - Most coding problems have solutions online


### Creating an Issue

If you find a bug:

1. Go to **Issues** tab on GitHub
2. Click **New Issue**
3. Describe:
   - What you expected to happen
   - What actually happened and maybe,
   - Steps to reproduce


**Updated by: Prest**
