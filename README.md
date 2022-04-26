# Horiseon

![Horiseon website](./assets/images/screen-shot.PNG "Horiseon website")

Horison is challenge one of my fullstack flex boot camp. I had to refactor an existing HTML and CSS code repository to achive mulitiple goals.

I have also deployed it as a [GitHub Page](https://nabhahnk.github.io/Horiseon/).


- [Horiseon](#horiseon)
  - [Semantic Code](#semantic-code)
    - [For example:](#for-example)
  - [Logical Structure](#logical-structure)
    - [For example:](#for-example-1)
  - [Alt Attributes for Images](#alt-attributes-for-images)
  - [Sequential Heading Elements](#sequential-heading-elements)
  - [Descriptive Title](#descriptive-title)
  - [CSS Refactor](#css-refactor)
    - [For example:](#for-example-2)

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

## Logical Structure

I needed to refactor the code to be in an organised and understandable layout.

### For example:

From this:

```html
<div class="content">
        <div class="search-engine-optimization">
            ...
        </div>
        <div id="online-reputation-management" class="online-reputation-management">
            ...
        </div>
        <div id="social-media-marketing" class="social-media-marketing">
            ...
        </div>
    </div>
    <div class="benefits">
        <div class="benefit-lead">
            ...
        </div>
        <div class="benefit-brand">
            ...
        </div>
        <div class="benefit-cost">
            ...
        </div>
    </div>
```

To this:

```html
<div class="content">

        <section id="search-engine-optimization">

            ...

        </section>

        <section id="online-reputation-management">

            ...

        </section>

        <section id="social-media-marketing">

            ...

    </div>

    <aside class="benefits">

        <section class="benefit-section">

            ...

        </section>

        <section class="benefit-section">

            ...

        </section>

        <section class="benefit-section">

            ...

        </section>

    </aside>
```

## Alt Attributes for Images

One of the criteria is to add alt attributes to images.

```html
<img src="./assets/images/cost-management.png" alt="image of a gear and money icons"/>
```

![alt image example](./assets/images/cost-management.png "alt image example")

## Sequential Heading Elements

I had to search and verify that the heading tags were used in am acceptable manner.

Such as, h1, before h2, before h3, and so on.

## Descriptive Title 

I had to change to title to one that matched the content appropriately.

From this:

```html
<title>website</title>
```

To this:

```html
<title>Horiseon</title>
```

## CSS Refactor

I also had to comment and consolidate the style.css file.

### For example:

From this:

```css
.search-engine-optimization h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.online-reputation-management h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
```

To this:

```css
/*sets the bottom margin to 20px and the font-size to 36px*/

#search-engine-optimization h2, #online-reputation-management h2, #social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
```