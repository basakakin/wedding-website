# Başak & Ahmet's Wedding Website 💍

A beautiful, responsive wedding website for our destination wedding in Rimini, Italy - September 10-13, 2026.

## 🌸 Features

- **Elegant Design**: Romantic/Vintage aesthetic with lilac, sage green, and white color scheme
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Multiple Pages**:
  - Home/Landing page with couple's story
  - RSVP page with Google Forms integration
  - Wedding Program with interactive timeline
  - Venue & Accommodations information
  - Travel & Directions guide
  - Photo Gallery with modal viewer
  - Comprehensive FAQ section
  - Room Matching service for guests
  
- **Interactive Elements**:
  - Expandable FAQ accordion
  - Photo gallery with lightbox
  - Beautiful timeline for wedding schedule
  - Google Forms integration for RSVP and room matching

## 📂 Project Structure

```
wedding_website/
├── index.html           # Home page
├── rsvp.html           # RSVP form with Google Forms
├── program.html        # Wedding program & timeline
├── venue.html          # Venue & accommodation info
├── travel.html         # Travel & directions
├── gallery.html        # Photo gallery
├── faq.html            # Frequently asked questions
├── room-matching.html  # Room matching form
├── styles.css          # Main stylesheet
├── assets/
│   └── images/         # Placeholder for photos
└── README.md           # This file
```

## 🎨 Color Scheme

- **Primary (Lilac)**: #B19CD9
- **Secondary (Sage Green)**: #9DC183
- **Accent (Off-white)**: #F5F5F5
- **Gold accent**: #D4AF92

## 🚀 Getting Started

### Local Development

1. Clone this repository
2. Open `index.html` in your web browser
3. Customize content as needed (see "Customization" below)

No build tools or dependencies required - this is a static HTML/CSS website!

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## ✏️ Customization

### Important: Update These Areas

1. **Couple Names & Email**: Update "Başak & Ahmet" and email addresses throughout all pages
2. **Google Forms**: 
   - Create forms for RSVP and Room Matching
   - Replace `YOUR_GOOGLE_FORM_ID` in `rsvp.html` and `room-matching.html`
   - Get the form ID from the form's embed code
3. **Venue Information**:
   - Update venue names and addresses in:
     - `program.html` (ceremony and reception times)
     - `venue.html` (hotel names, rates, contact info)
     - `travel.html` (venue directions)
4. **Wedding Details**:
   - Add photos to `assets/images/`
   - Update accommodation hotel information
   - Add real Google Maps links in travel.html
5. **Social Media**: Update social media links in footer
6. **Content**: Add your love story, specific wedding timeline, etc.

## 📋 Google Forms Setup

### RSVP Form

Required fields:
- Name
- Email
- Attendance (Yes/No/Maybe)
- Number of Guests
- Dietary Restrictions

Get the form embed code and replace the URL in `rsvp.html`:
```html
<iframe src="https://docs.google.com/forms/d/e/YOUR_FORM_ID/viewform?embedded=true" ...>
```

### Room Matching Form

Same process - create a Google Form with the fields in `room-matching.html` and embed it.

## 📸 Adding Photos

1. Add your photos to the `assets/images/` folder
2. Update the gallery in `gallery.html` with your image paths
3. The gallery supports any image format (jpg, png, webp)

## 🌐 Hosting on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com)
2. Click "New" to create a new repository
3. Name it `wedding-website` (or your preferred name)
4. Make it **Public** (required for free GitHub Pages)
5. Do NOT initialize with README, .gitignore, or license
6. Click "Create repository"

### Step 2: Push Your Code

In your terminal, from the `wedding_website` directory:

```bash
# Initialize git
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: Wedding website"

# Add remote repository (replace with your username and repo name)
git remote add origin https://github.com/YOUR_USERNAME/wedding-website.git

# Push to GitHub (use 'main' or 'master' depending on your git config)
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" (top right)
3. Click "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"
7. Your site will be published at: `https://YOUR_USERNAME.github.io/wedding-website/`

### Step 4: Share Your URL

Your website is now live! Share the URL with guests:
- Full URL: `https://YOUR_USERNAME.github.io/wedding-website/`
- Or set up a custom domain (see GitHub Pages docs)

## 🔄 Making Updates

After you've pushed to GitHub, you can make updates:

```bash
# Make your changes to HTML/CSS files

# Stage changes
git add .

# Commit with a message
git commit -m "Update venue information"

# Push to GitHub
git push
```

Changes will appear on your live website within seconds!

## 📱 Mobile Optimization

This website is fully responsive and tested on:
- iPhone (all sizes)
- Android devices
- Tablets
- Desktops

The CSS includes media queries for screens as small as 480px.

## ♿ Accessibility

The website includes:
- Semantic HTML structure
- Proper heading hierarchy
- Alt text support for images
- Keyboard navigation support
- Sufficient color contrast

## 📧 Google Forms Integration Tips

- Test your forms before sharing the link
- Check that responses go to the right email
- Consider setting form to "Accept only one response per user" if desired
- Enable "Shuffle question order" for unbiased responses

## 🎯 Pre-Launch Checklist

- [ ] Update all couple names and contact emails
- [ ] Add wedding date and location
- [ ] Create and embed Google Forms
- [ ] Add venue details
- [ ] Update accommodation information
- [ ] Add photos to gallery
- [ ] Test all links and forms
- [ ] Test on mobile devices
- [ ] Set up GitHub repository
- [ ] Enable GitHub Pages
- [ ] Share link with guests!

## 📞 Tech Support

If you need help updating the website:
1. Check the "Customization" section above
2. Refer to HTML/CSS files for specific sections
3. Google Fonts embedding information in styles.css

## 📄 License

This website template is created for your wedding. Feel free to use and modify as needed.

---

Made with ❤️ for Başak & Ahmet's Wedding - September 10-13, 2026, Rimini, Italy
