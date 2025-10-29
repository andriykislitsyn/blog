# My Blog

A simple, clean blog built with HTML and CSS, hosted on GitHub Pages.

## Features

- 📝 Clean and minimal design
- 📱 Responsive layout (works on mobile and desktop)
- 🚀 Fast loading times
- 🎨 Easy to customize
- 🆓 Free hosting with GitHub Pages

## Live Demo

Once deployed, your blog will be available at: `https://andriykislitsyn.github.io/blog/`

## Getting Started

### Enabling GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the branch you want to deploy (e.g., `main`)
4. Click "Save"
5. Wait a few minutes for GitHub to build and deploy your site
6. Your blog will be live at `https://yourusername.github.io/repository-name/`

### Customizing Your Blog

#### Update Site Information

1. Edit `index.html` to change the blog title and content
2. Update `_config.yml` with your name and blog description

#### Adding New Blog Posts

1. Create a new HTML file in the `posts/` directory
2. Use the existing post files as templates (`first-post.html`, `second-post.html`)
3. Add a link to your new post in `index.html`

#### Styling

- Modify `style.css` to change colors, fonts, and layout
- The CSS is well-organized and commented for easy customization

## Project Structure

```
blog/
├── index.html          # Homepage with blog post list
├── style.css           # Main stylesheet
├── posts/              # Directory for blog posts
│   ├── first-post.html
│   └── second-post.html
├── _config.yml         # GitHub Pages configuration
├── README.md           # This file
└── LICENSE             # License file
```

## Customization Tips

### Changing Colors

Edit the color values in `style.css`:
- Header/Footer background: `#2c3e50`
- Links and accents: `#3498db`
- Body background: `#f5f5f5`

### Adding More Pages

Create new HTML files in the root directory and add links to them in the navigation menu in `index.html`.

### Adding Images

1. Create an `images/` directory
2. Add your images to this directory
3. Reference them in your HTML: `<img src="images/your-image.jpg" alt="Description">`

## Technologies Used

- HTML5
- CSS3
- GitHub Pages for hosting

## License

This project is open source and available under the MIT License.