# Horiseon

![Horiseon website](./assets/images/screen-shot.PNG "Horiseon website")

Horison is challenge one of my fullstack flex boot camp. I had to refactor an existing HTML and CSS code repository to achive mulitiple goals.

- semantic code
- logical structure
- alt attributes for images
- sequential heading elements
- descriptive title 

## Semantic Code

I needed to update the html code from older outdated methodology to the modern one.

### For example: 

From this:

```html
<div class="header">
```

To this:

```html
<header>
```

## logical Structure

I needed to refactor the code to be in an orginised and understandable layout.

### For example:

From this:

```html
<div>
    <ul>
        <li>
            <a href="#search-engine-optimization">Search Engine Optimization</a>
        </li>
        <li>
            <a href="#online-reputation-management">Online Reputation Management</a>
        </li>
        <li>
            <a href="#social-media-marketing">Social Media Marketing</a>
        </li>
    </ul>
</div>
```

To this:

```html
<div>

    <nav>

        <li>
            <a href="#search-engine-optimization">Search Engine Optimization</a>
        </li>

        <li>
            <a href="#online-reputation-management">Online Reputation Management</a>
        </li>

        <li>
            <a href="#social-media-marketing">Social Media Marketing</a>
        </li>

    <nav>

</div>
```