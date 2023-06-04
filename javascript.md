# File naming

Rules:
- Only lower case letters
- If longer than one word add dash (-) wherever a space would be

Examples:
- main.js
- scroll-effects.js



# Code structure

Rules
- All code in the main.js file should be calls to modules in another folder, no functions, classes or module in the main.js file
- Should always use classes never just global normal functions


# Example (code)

```HTML
<script>
    import { scroll_animator } from "./modules/animations.js";
    
    scroll_animator();
</script>
```


# Example (graphic)
![Graphic explaining HTML structure](/media/images/html.jpg)
