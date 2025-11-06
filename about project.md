# Mealify - Restaurant Landing Page Template

## Project Overview
Mealify is a modern, responsive restaurant landing page template built with pure HTML and CSS. The application provides a complete showcase for restaurants to display their menu, chefs, gallery, and contact information. The template features a beautiful design with dark/light mode toggle, responsive navigation, and a clean, professional layout suitable for restaurant businesses.

## Project Description
This is a fully responsive, single-page restaurant website template that demonstrates proficiency in frontend development, UI/UX design, and modern CSS techniques. The application features smooth scrolling navigation, dark/light theme toggle, interactive gallery, chef profiles, contact form with Google Maps integration, and a comprehensive footer with newsletter subscription.

## Key Features
- **Restaurant Landing Page**: Complete restaurant website with multiple sections
- **Dark/Light Mode Toggle**: CSS-based theme switching with `:has()` selector
- **Responsive Navigation**: Fixed-top navbar with mobile menu toggle
- **Hero Section**: Eye-catching hero section with call-to-action buttons
- **Chefs Section**: Display professional chefs with social media links
- **Gallery Section**: Interactive meal gallery with hover effects and overlay
- **Contact Section**: Contact form with Google Maps integration
- **Footer**: Comprehensive footer with newsletter subscription
- **Smooth Scrolling**: Seamless navigation between sections
- **Responsive Design**: Fully responsive layout for all devices
- **Google Maps Integration**: Embedded Google Maps for location display
- **Social Media Integration**: Social media links throughout the site
- **Newsletter Subscription**: Email subscription form in footer

## Technical Stack & Technologies Used

### Core Technologies
- **HTML5**: Semantic markup with modern HTML5 features
- **CSS3**: Advanced styling with CSS variables, Flexbox, and responsive design
- **CSS Advanced Features**: 
  - CSS Variables (Custom Properties)
  - `:has()` selector for dark mode
  - `::selection` pseudo-element
  - Custom scrollbar styling
  - Media queries for responsive design

### CSS Frameworks & Libraries
- **Font Awesome**: Comprehensive icon library
  - Solid icons
  - Brand icons
  - Regular icons
  - Custom webfonts included

### Typography
- **Google Fonts**: 
  - **Amatic SC**: Primary font for headings (weights: 400, 700)
  - **Inter**: Secondary font for headings (weights: 100-900)
  - **Open Sans**: Default font for body text (weights: 300-800)

### External Integrations
- **Google Maps**: Embedded iframe for location display
- **YouTube**: External link for video content

## Project Structure
```
Assignment-05 [Mealify Template]/
├── index.html              # Main HTML file
├── css/
│   ├── style.css           # Main stylesheet
│   ├── flexStyle.css       # Flexbox utilities
│   ├── mediaStyle.css      # Media queries
│   └── all.min.css         # Font Awesome CSS
├── images/
│   ├── chefs/              # Chef profile images
│   ├── meals/               # Meal gallery images
│   ├── favicon.png          # Site favicon
│   └── hero-img.png         # Hero section image
└── webfonts/                # Font Awesome webfonts
```

## Key Sections & Components

### 1. Navigation Bar
- **Fixed-top Navigation**: Stays visible on scroll
- **Logo**: Custom logo with dot accent
- **Responsive Menu**: Collapsible menu for mobile
- **Dark/Light Mode Toggle**: 
  - Moon icon for dark mode
  - Sun icon for light mode
  - CSS checkbox-based toggle
  - Uses `:has()` selector for theme switching
- **Mobile Toggle**: Hamburger menu with close icon

### 2. Hero Section (Home)
- **Background Image**: Hero image with overlay
- **Headline**: "Enjoy Your Healthy Delicious Food"
- **Description**: Restaurant description text
- **Call-to-Action Buttons**:
  - "Book a Table" button (links to contact section)
  - "Watch a Video" button (links to YouTube)
- **Hero Image**: Large hero image on the right

### 3. Chefs Section
- **Section Header**: "chefs" title and "Our Professional Chefs" description
- **Chef Cards**: 3 chef cards with:
  - Chef profile image
  - Chef name
  - Chef title (Master Chef, Patissier, Cook)
  - Chef description
  - Social media links (Twitter, Facebook, Instagram, LinkedIn)
- **Chefs Include**:
  - Walter White (Master Chef)
  - Sarah Jhonson (Patissier)
  - William Anderson (Cook)

### 4. Gallery Section
- **Section Header**: "GALLERY" title and "Check Our Gallery" description
- **Meal Grid**: 7 meal images in responsive grid layout
- **Meal Cards**: Each meal includes:
  - Meal image
  - Overlay with meal name and description
  - Hover effects
- **Meals Include**:
  - Pizza (Hawaiian pizza with ham and pineapple)
  - Levitation pizza
  - Beef steaks
  - Frittata
  - Burger
  - Crispy Fried Chicken
  - Lyulya kebab

### 5. Contact Section
- **Section Header**: "contact" title and "Need Help? Contact Us" description
- **Google Maps**: Embedded Google Maps iframe
- **Contact Details Cards**: 4 contact cards with:
  - Address card (location icon)
  - Email card (envelope icon)
  - Phone card (phone icon)
  - Opening Hours card (share icon)
- **Contact Form**: 
  - Name and Email inputs (side by side)
  - Subject input
  - Message textarea
  - Submit button

### 6. Footer Section
- **About Section**: 
  - Logo and description
  - Social media links
- **Get in Touch Section**: 
  - Address with icon
  - Email with icon
  - Phone with icon
- **Subscription Section**: 
  - Newsletter subscription form
  - Email input
  - Subscribe button
- **Quick Links Section**: 
  - Menu
  - Promo
  - About Us
  - Contact
  - Testimonial
  - Our Partners

## CSS Features

### Design System
- **CSS Variables**: 
  - Font families (primary, secondary, default)
  - Colors (light-grey, default, secondary, tertiary, primary)
  - Background colors
  - Opacity values
- **Dark Mode**: 
  - Uses `:has()` selector for theme switching
  - Dynamic color variables
  - Background color changes
  - Text color adjustments

### Color Palette
- **Light Mode**:
  - Primary: Red (#ce1212)
  - Background: Light grey (#eee)
  - Text: Dark (#212529)
  - Light: White (#fff)
  
- **Dark Mode**:
  - Primary: Gold/Orange (#c17e1f)
  - Background: Dark grey (#252525)
  - Text: White (#fff)
  - Light: Black (#000)

### Layout Features
- **Flexbox**: Extensive use of Flexbox for layouts
- **Responsive Grid**: CSS Grid for gallery layout
- **Fixed Backgrounds**: Parallax-style backgrounds
- **Overlay Effects**: Semi-transparent overlays on images

### Typography
- **Font Families**: 
  - Amatic SC for headings
  - Inter for headings
  - Open Sans for body text
- **Font Sizes**: Responsive font sizes
- **Font Weights**: Various weights (300-900)

### Interactive Elements
- **Hover Effects**: Transitions on interactive elements
- **Card Shadows**: Box shadows for depth
- **Icon Animations**: Transition effects on icons
- **Button Styles**: Custom button styling with hover effects
- **Custom Scrollbar**: Styled scrollbar with colors

### Responsive Design
- **Mobile-First**: Responsive breakpoints
- **Flexbox**: Flexible layouts
- **Media Queries**: Custom responsive styles in `mediaStyle.css`
- **Mobile Menu**: Collapsible navigation

## Advanced CSS Techniques

### CSS Variables & Dark Mode
- **Dynamic Variables**: CSS variables change based on theme
- **:has() Selector**: Modern CSS selector for theme switching
- **Selection Styling**: Custom text selection colors
- **Custom Scrollbar**: Styled webkit scrollbar

### Flexbox Utilities
- **Flexbox Classes**: Utility classes in `flexStyle.css`
- **Flex Center**: Centering utilities
- **Flex Direction**: Direction utilities
- **Flex Space**: Spacing utilities
- **Flex Align**: Alignment utilities

### Media Queries
- **Responsive Breakpoints**: Media queries in `mediaStyle.css`
- **Mobile Optimization**: Mobile-specific styles
- **Tablet Optimization**: Tablet-specific styles
- **Desktop Optimization**: Desktop-specific styles

## Development Skills Demonstrated
- ✅ Pure HTML5 & CSS3
- ✅ CSS Variables & Custom Properties
- ✅ Advanced CSS Selectors (:has(), ::selection)
- ✅ Flexbox Layout
- ✅ CSS Grid (for gallery)
- ✅ Responsive Web Design
- ✅ Dark/Light Mode Implementation
- ✅ Custom Scrollbar Styling
- ✅ Google Maps Integration
- ✅ Form Styling
- ✅ Image Overlay Effects
- ✅ Hover Effects & Transitions
- ✅ Mobile-First Design
- ✅ Semantic HTML
- ✅ Accessibility (alt text, semantic elements)
- ✅ Clean Code Architecture
- ✅ CSS Organization (separate files)

## Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS `:has()` selector support required for dark mode
- CSS Grid and Flexbox support
- Custom scrollbar (webkit browsers)

## Performance Features
- Optimized images with lazy loading
- Efficient CSS organization
- Minimal code (no JavaScript)
- Fast loading (static HTML/CSS)
- External resources (Google Fonts, Font Awesome)

## User Experience Features
- **Smooth Scrolling**: Seamless navigation between sections
- **Visual Feedback**: Hover effects and transitions
- **Mobile-Friendly**: Responsive design for all devices
- **Accessibility**: Semantic HTML and alt text
- **Dark Mode**: User preference for theme
- **Professional Design**: Clean, modern aesthetic
- **Easy Navigation**: Clear navigation structure

## Additional Notes
- Pure HTML/CSS implementation (no JavaScript)
- Ready for customization
- Well-structured code
- Comprehensive documentation in HTML comments
- Production-ready template
- Easy to extend with additional features
- SEO-friendly structure

---

## Technologies Summary for CV
**Frontend**: HTML5, CSS3 (Pure CSS - No JavaScript)
**Advanced CSS**: CSS Variables, :has() Selector, Flexbox, CSS Grid
**Libraries**: Font Awesome
**Typography**: Google Fonts (Amatic SC, Inter, Open Sans)
**Architecture**: Single-page Application
**Features**: Dark/Light Mode, Responsive Design, Google Maps Integration
**Programming Paradigms**: CSS-based Theme Switching
**UI/UX**: Modern Restaurant Template, Professional Design, Interactive Elements
**Skills**: Advanced CSS, Flexbox, CSS Grid, Responsive Design, Dark Mode Implementation

