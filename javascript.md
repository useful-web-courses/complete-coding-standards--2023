# File naming

Rules:
- Only lower case letters
- If longer than one word add dash (-) wherever a space would be

Examples:
- index.js
- scroll-effects.js



# Code structure

Rules
- All code in the main.js file should be calls to modules in another folder, no functions, classes or module in the main.js file
- Should always use classes never just global normal functions

### section--*
can have these inside of it:
- container--*
- component--*
- part--*
- element

Examples:
- section--projects
- section--employees
- section--reviews

---

### container--*
Holds:
- component--*
- part--*
- element

Examples:
- container--projects
- container--employees
- container--reviews

---

### component--*
Holds:
- part--*
- element

Examples:
- component--project
- component--employee
- component--review

---

### part--*
Holds:
- element

Examples:
- part--name-and-technology
- part--name-and-position
- part--name-and-rating

---

### element
Holds:
- Raw text

Examples:
- h1, h2, h3, h4, h5, h6
- p, a, span
- img, video


# Example (code)

```HTML
<div class="section--projects">
    <h1>Projects</h1>
    
    <div class="container--projects">
        <div class="component--project-card">
            <img src="/media/images/projects/1.jpg" alt=""/>
            
            <div class="part--project-info">
                <h1>Project 1</h1>
            </div>
        </div>
        
        <div class="component--project-card">
            <img src="/media/images/projects/1.jpg" alt=""/>
            
            <div class="part--project-info">
                <h1>Project 2</h1>
            </div>
        </div>
    </div>
</div>
```


# Example (graphic)
![Graphic explaining HTML structure](/media/images/html.jpg)
