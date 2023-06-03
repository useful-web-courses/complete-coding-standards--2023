# File naming
Rules:
- Primary css file where variables among other things are specified is called main.css
- Only lower case letters
- If longer than one word add dash (-) wherever a space would be

Examples:
- main.css
- about-me.html


# Code structure

## Logical sizing
Examples:
- thin, thicker, thickest
- small, medium, large
- narrow, regular, wide

---

## Alphabetical
Look at first letter, if same, look at 2nd, third and so on
If one word is identical in the beginning like padding and padding-left, then padding should be on top.

Example:
```HTML
<style>
    html {
        --color--background: #FFFFFF;
        --color--faint: rgba(0, 0, 0, 0.3);
        --color--text-primary: #000000;
    }
</style>
```

---

## Order of stylesheet

### elements

### part--*

### component--*

### container--*

### section--*

### media queries

Example:
```HTML
<style>
    :root {
        
    }
    
    /***************/
    
    h1 {
        
    }
    
    h2 {
        
    }
    
    p {
        
    }
    
    a {
        
    }
    
    /***************/
    
    .part--product-info {
        
    }
    
    .component--product-card {
        
    }
    
    .container--product-cards {
        
    }
    
    .section--products {
        
    }
    
    @media only screen and (max-width: 512px) {
        
    }
    
    /***************/
    
    .part--contact-info {
        
    }
    
    .component--contact-card {
        
    }
    
    .container--contact-info {
        
    }
    
    .section--contact-info {
        
    }
    
    @media only screen and (max-width: 512px) {
        
    }
    
    /***************/
</style>
```

# Example (code)

```HTML
<style>
    html {
        --border--radius: 8px;
        --border--width: 2px;

        --color--accent: #ed6941;
        --color--on-accent: #f9f9f9;
    
        --color--background: #121212;
        --color--on-background: #121212;
        --color--on-background-faint: rgba(255, 255, 255, 0.5);
    
        --color--link: #7c98f9;
        --color--on-link: #f9f9f9;
    
        --color--surface: #080808;
        --color--on-surface: #121212;
        --color--on-surface-faint: #121212;
    
        --font--family: "Arial";

        --font--size--small: 1rem;
        --font--size--medium: 1.8rem;
        --font--size--large: 2.4rem;

        --font--weight--thin: 300;
        --font--weight--regular: 500;
        --font--weight--bold: 800;

        --space--tiny: 8px;
        --space--small: 16px;
        --space--medium: 32px;
        --space--large: 64px;
    }

    html[data-theme="light"] {
        --color--background: #f9f9f9;
        --color--faint: rgba(0, 0, 0, 0.5);
        --color--surface: #e7e7e7;
        --color--text-primary: #000000;
        --color--text-secondary: rgba(0, 0, 0, 0.65);
        --color--link: #385cdd;
    }
</style>
```