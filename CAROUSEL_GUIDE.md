# Auto-Scrolling Image Carousel

## What's New

A beautiful auto-scrolling carousel has been added under the "What We Do" blog section on the home page.

## Features

✅ **Continuous Scrolling** - Images scroll automatically at a smooth pace (30 seconds per loop)
✅ **Hover to Pause** - Animation pauses when user hovers over the carousel
✅ **10 Product Images** - Displays various products and accessories
✅ **Responsive Design** - Works on desktop, tablet, and mobile devices
✅ **Smooth Animations** - Uses CSS animations for optimal performance
✅ **Professional Styling** - Modern design with box shadow and rounded corners

## How It Works

1. **Auto-Scroll**: The carousel continuously scrolls from left to right
2. **Pause on Hover**: When users hover their mouse over it, scrolling pauses
3. **Resume on Leave**: Scrolling resumes when user moves mouse away
4. **Seamless Loop**: Images loop infinitely without visible jumps

## Location

The carousel appears:
- **Page**: Home page (index.html)
- **Section**: Between "What We Do" (blog section) and "Contact Us" section
- **Title**: "Our Products & Brands"

## Customization

### Change Images
Edit the carousel items in `index.html`:
```html
<div class="carousel_item"><img src="images/your-image.png" alt="Product Name"></div>
```

### Change Scroll Speed
In `css/style.css`, find:
```css
animation: scroll-carousel 30s linear infinite;
```
- `30s` = 30 seconds per complete loop
- Decrease for faster scrolling, increase for slower

### Change Item Size
Modify `.carousel_item` width and height in style.css:
```css
.carousel_item {
  width: 200px;  /* Change this */
  height: 200px; /* Change this */
}
```

### Change Title/Subtitle
Edit in `index.html`:
```html
<h1 class="carousel_title">Our Products & Brands</h1>
<p class="carousel_subtitle">Explore our wide range...</p>
```

## Responsive Breakpoints

The carousel automatically adjusts for:
- **Desktop (>768px)**: 200px × 200px items
- **Tablet (≤768px)**: 150px × 150px items  
- **Mobile (≤480px)**: 120px × 120px items

## Browser Support

✅ Chrome/Edge/Firefox - Full support
✅ Safari - Full support
✅ Mobile browsers - Full support
✅ IE11 - Works (but animation may be less smooth)

## Performance

- Uses CSS animations (GPU accelerated)
- No JavaScript required
- Lightweight and fast
- No impact on page load time

## Accessibility

- Images have alt text
- Works with keyboard navigation
- Pause on hover benefits users who need more time to view
- Text labels and descriptions included

## Files Modified

- **index.html** - Added carousel HTML structure
- **css/style.css** - Added carousel styling and animations

## Tips

1. **Image Quality**: Use optimized/compressed images for faster loading
2. **Image Consistency**: Keep images similar in size for best appearance
3. **Color Matching**: Images should work well against the light gray background
4. **Testing**: Test on multiple devices to ensure proper display

## Future Enhancements

Consider adding:
- Navigation arrows to manually scroll
- Dots/indicators showing position
- Touch swipe support for mobile
- Click to enlarge image modal
- Different scroll directions (vertical, diagonal)
