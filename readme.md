## Suggested Changes

### Update your email div to make the link clickable

```css
.footer {
            position: fixed;
            bottom: 0;
            /* Locks the footer at the bottom */
            width: 100%;
            /* Ensures it spans the full width of the viewport */
            background-color: #333;
            /* Background color for the footer */
            color: white;
            /* Text color */
            text-align: center;
            /* Centers the text within the footer */
            padding: 10px 0;
            /* Adds padding above and below the text */
            z-index: 1000;
            /* Ensures it stays above other content */
            font-family: Arial, Verdana, sans-serif;
            font-size: 1.5vw;
        }

```


```html
<div class="footer">
        <p>For further contact email
            <a href="mailto:sean@roge.me?subject=Game%20Design%20Inquiry">
                sean@roge.me
            </a> to contact me about this bio.
        </p>
    </div>
```

### Preview

Would look like this, and would always be locked to the bottom of the window, if you don't want it locked to the bottom of the window you can remove "position: fixed" and "bottom: 0"

![image](https://github.com/chrisroge/portfolio-assistance/assets/782671/7f328e01-ba43-4a78-a4a9-c92ffaa39e72)


  
