# Multicategory One - Standalone Template

This is a standalone version of the **Multicategory One** ecommerce template extracted from the Multimart theme.

## 📁 Folder Structure

```
multicategory-one/
├── index.html              # Main HTML file (open this in browser)
├── assets/
│   ├── css/               # All stylesheets (30 CSS files)
│   ├── js/                # All JavaScript files (35 JS files)
│   ├── images/            # All images used by this template
│   │   ├── fashion1/     # Fashion product images
│   │   ├── slider/        # Slider images
│   │   ├── multicategory/ # Multicategory specific images
│   │   ├── electronics2/  # Electronics images
│   │   ├── product-page/  # Product page images
│   │   ├── cart/          # Cart images
│   │   ├── favicon/       # Favicon files
│   │   ├── logo8.png      # Logo
│   │   └── payment_cart.png
│   └── fonts/             # Custom fonts (Flaticon, FontAwesome, etc.)
└── README.md              # This file
```

## 🚀 Quick Start

1. **Open the template**: Double-click `index.html` or open it in your web browser
2. **Edit the template**: Open `index.html` in any code editor (VS Code, Sublime Text, etc.)
3. **Customize**: See customization guide below

## ✨ Features

- ✅ Fully responsive design
- ✅ Multiple product categories on one page
- ✅ Shopping cart functionality
- ✅ Product sliders and carousels
- ✅ Modern UI with Bootstrap 5
- ✅ All assets included (no external dependencies except Google Fonts)

## 🎨 Customization Guide

### Change Logo
**File**: `index.html` (line ~118)  
**Find**: 
```html
<img src="assets/images/logo8.png" class="img-fluid" alt="">
```
**Replace**: Change `logo8.png` to your logo file

### Change Store Name
**File**: `index.html` (line 12)  
**Find**: 
```html
<title>Multimart | Multicategory Layout</title>
```
**Replace**: Change "Multimart" to your store name

### Change Colors
**File**: `index.html` (line 43)  
**Find**: 
```html
<link rel="stylesheet" type="text/css" href="assets/css/style13.css" id="color">
```
**Available**: Change `style13.css` to `style1.css` through `style30.css` for different color schemes

### Update Product Images
**Location**: `assets/images/multicategory/product/`  
Replace product images with your own products

### Modify Categories
**File**: `index.html` (around line 223)  
Update category names and links in the navigation menu

## 📝 Files Included

### CSS Files (30 files)
- `bootstrap.css` - Bootstrap framework
- `style13.css` - Current color scheme (change to style1-30 for different colors)
- `slick.css`, `slick-theme.css` - Slider styles
- `font-awesome.css` - Icon fonts
- `flaticon.css`, `themify.css` - Additional icons
- `animate.css` - Animations
- And more...

### JavaScript Files (35 files)
- `jquery-3.3.1.min.js` - jQuery library
- `bootstrap.js` - Bootstrap components
- `slick.js` - Slider functionality
- `menu.js` - Navigation menu
- `custom-scripts.js` - Custom functionality
- `timer-three.js`, `timer-three-one.js` - Countdown timers
- And more...

### Images
- Product images in `multicategory/product/`
- Banner images in `multicategory/banner/`
- Slider images in `slider/`
- Cart images in `cart/`
- Logo and favicon files

## 🔗 Links to Update

The template includes placeholder links (`javascript:void(0)`). Update these to point to:
- Product detail pages
- Category pages
- Cart page
- Checkout page
- Login/Register pages

## 💡 Tips

1. **Keep a backup**: Always backup before making changes
2. **Test locally**: Open `index.html` in browser to see changes
3. **Use browser DevTools**: Press F12 to inspect and debug
4. **Color schemes**: Try different `style*.css` files to find your favorite
5. **Responsive**: Test on mobile, tablet, and desktop

## 📚 Related Templates

If you need other pages, you can copy them from:
- `../theme/bs_5/html/product-page(3-column).html` - Product detail page
- `../theme/bs_5/html/cart.html` - Shopping cart
- `../theme/bs_5/html/checkout.html` - Checkout page
- `../theme/bs_5/html/category-page.html` - Category listing

## 🆘 Need Help?

- Check the original documentation: `../Documentation/index.html`
- Review other HTML files in `../theme/bs_5/html/` for reference
- All CSS and JS files are well-commented

---

**Ready to customize! Open `index.html` and start editing! 🎉**

