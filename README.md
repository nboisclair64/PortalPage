# Portal

A clean portal application that displays cards with links to all your built applications.

## Getting Started

1. Open `index.html` in your browser or serve it with a local server
2. Add your application cards by editing the `card-grid` section in `index.html`

## Adding Applications

Add a card for each application by inserting a link with the `card` class:

```html
<a href="https://your-app-url.com" class="card">
    <div class="card-content">
        <h2>Application Name</h2>
        <p>Brief description of what this application does</p>
    </div>
</a>
```

## Customization

- Edit `styles.css` to customize colors, fonts, and layout
- The gradient background can be modified in the `body` CSS
- Cards automatically adjust to different screen sizes
