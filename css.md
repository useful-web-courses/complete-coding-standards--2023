# CSS

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