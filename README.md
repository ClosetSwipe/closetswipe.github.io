# ClosetSwipe Landing Page

A beautiful, editorial-style pre-launch landing page for the ClosetSwipe fashion app. Features typography-led design with no images, clean animations, and a two-page flow.

## 🎨 Design Features

### Page 1: Hero Landing
- **Gradient Background**: Soft blend of brand colors (#469DF8, #4FA9CC, #E8A7BF, #C66E9E)
- **Layered Typography**: 
  - 3 stacked "Closet" text elements (2 outlined, 1 filled) using bold Inter font
  - "Swipe" in decorative Shrikhand font
- **Editorial Layout**: Off-center, large text with strong whitespace usage
- **Floating Animation**: Gentle floating circles for dynamic feel
- **Social Links**: Instagram, TikTok, YouTube (bottom-right corner)
- **Smooth Transitions**: Fade-in animations and hover effects

### Page 2: Email Collection
- **Clean Design**: Soft pink gradient background
- **Large Input Field**: Stylish email input with elegant styling
- **Working Integration**: Connected to existing Google Sheets backend
- **Success/Error States**: Clean feedback without popups
- **Responsive**: Mobile-first design

## 🛠 Technical Stack

- **Pure HTML/CSS/JavaScript** - No external frameworks
- **Google Fonts**: Inter, Playfair Display, Shrikhand
- **Responsive Design**: Mobile-first approach
- **Cross-browser Compatible**: Modern browser support
- **GitHub Pages Ready**: Optimized for easy deployment

## 🚀 Deployment Instructions

### Current Setup
Your site is already configured with:
- Domain: `closetswipe.co.uk` (via CNAME file)
- Google Sheets integration for email collection
- GitHub Pages deployment

### To Update Live Site
1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "New editorial landing page design"
   git push origin main
   ```

2. **GitHub Pages**: Your site will automatically deploy to `https://closetswipe.co.uk`

### Domain Connection (Already Set Up)
Your `CNAME` file is already configured for `closetswipe.co.uk`. If you need to change domains:

1. Update the `CNAME` file with your new domain
2. Configure DNS settings with your domain provider:
   ```
   Type: CNAME
   Name: @ (or www)
   Value: [your-username].github.io
   ```

## 📱 Features

### Landing Page
- ✅ Layered "Closet" typography with outline effects
- ✅ Decorative "Swipe" text
- ✅ "Keeping fashion circular" tagline
- ✅ "be the first to know" CTA button
- ✅ Social media links (IG, TikTok, YouTube)
- ✅ Floating animation elements
- ✅ Gradient background using brand colors

### Email Collection Page
- ✅ Clean, minimal design
- ✅ Large email input field
- ✅ "get exclusive discounts. no spam ever." message
- ✅ Working Google Sheets integration
- ✅ Success/error feedback
- ✅ Smooth page transitions

### Animations & Interactions
- ✅ Fade-in on scroll animations
- ✅ Gentle hover effects
- ✅ Floating background elements
- ✅ Smooth page transitions
- ✅ Luxury feel with subtle animations

### Responsive Design
- ✅ Mobile-first approach
- ✅ Optimized for all screen sizes
- ✅ Touch-friendly interface
- ✅ Scalable typography

## 🎯 Brand Colors Used

- `#469DF8` - Primary Blue
- `#4FA9CC` - Light Blue  
- `#E8A7BF` - Light Pink
- `#C66E9E` - Rose Pink

## 📧 Email Collection

The email form integrates with your existing Google Sheets setup:
- **Endpoint**: Already configured
- **Validation**: Client-side email validation
- **Feedback**: Clean success/error messages
- **No Spam**: Privacy-focused messaging

## 🔧 Customization

### Typography
- **Headlines**: Inter (bold, sans-serif)
- **Decorative**: Shrikhand (curvy)
- **Body**: Playfair Display (serif, italic)

### Colors
Update the CSS custom properties to change the color scheme:
```css
/* In the gradient background */
background: linear-gradient(135deg, #YOUR_COLOR1, #YOUR_COLOR2, #YOUR_COLOR3, #YOUR_COLOR4);
```

### Social Links
Update the social media URLs in the HTML:
```html
<a href="https://www.instagram.com/your_handle">
<a href="https://www.tiktok.com/your_handle">
<a href="https://www.youtube.com/your_channel">
```

## 📊 Performance

- **Lightweight**: No external frameworks or heavy dependencies
- **Fast Loading**: Optimized CSS and minimal JavaScript
- **SEO Friendly**: Proper HTML structure and meta tags
- **Accessibility**: ARIA labels and keyboard navigation support

## 🔄 Future Enhancements

- Add more sophisticated animations
- Implement A/B testing for CTAs
- Add analytics tracking
- Create additional landing page variants
- Integrate with email marketing platforms

---

**Ready to launch!** 🚀 Your editorial, fashion-forward landing page is now live and collecting emails for ClosetSwipe's launch.