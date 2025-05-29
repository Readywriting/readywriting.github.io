# Book Cover Images

This directory is intended for book cover images for the Published Books section of the portfolio website.

## Current Status
The website currently uses attractive gradient-based placeholder covers with book titles. These placeholders are professionally designed and provide a good visual representation until actual book covers can be added.

## Adding Real Book Covers

To replace the placeholders with actual book cover images:

1. **Obtain proper permissions** from publishers or use copyright-free sources
2. **Save images** in this directory with the following naming convention:
   - `of-many-minds.jpg` - Of Many Minds: Neurodiversity and Mental Health
   - `affective-labor.jpg` - Affective Labor and Alt-Ac Careers  
   - `journey-translation.jpg` - A Journey in Translation: Anne Hébert's Poetry
   - `twist-weave-untangle.jpg` - Twist, Weave, Untangle: Critical Pedagogue
   - `learning-breathe.jpg` - Learning to Breathe: A Mental Health Journey
   - `dany-laferriere.jpg` - Dany Laferrière: Essays On His Works
   - `anne-hebert.jpg` - Anne Hébert: Essays on Her Works

3. **Update HTML** by replacing the placeholder content in each book-image div:
   ```html
   <!-- Replace this: -->
   <div class="book-image [class-name]">
       <div class="book-placeholder">...</div>
   </div>
   
   <!-- With this: -->
   <div class="book-image [class-name]">
       <img src="images/book-covers/[filename].jpg" alt="[Book Title] cover">
   </div>
   ```

## Image Specifications
- **Format**: JPG or PNG
- **Size**: Recommended 300-400px width, maintaining book proportions (approximately 2:3 ratio)
- **Quality**: High resolution for crisp display on all devices

## Copyright Notice
Ensure all book cover images are used with proper permissions from copyright holders (publishers, authors, etc.) or are in the public domain.
