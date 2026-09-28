# Setup Instructions

## Adding Dr. Maya Reynolds' Photo

The website is configured to use a local image for Dr. Maya Reynolds. To add her photo:

### Step 1: Extract Image from PDF

1. Open `Dr. Maya Reynolds, PsyD.pdf` from your Downloads folder
2. Right-click on her photo in the PDF
3. Select "Save Image As..." or "Copy Image"
4. Save the image as `dr-maya-reynolds.jpg`

### Step 2: Place the Image

Save the extracted photo to:
```
E:\assigment\images\dr-maya-reynolds.jpg
```

### Alternative Method:

If you can't extract from PDF:
1. Take a screenshot of her photo from the PDF
2. Crop it to just her headshot
3. Save as `dr-maya-reynolds.jpg` in the `images` folder

### Current Image Paths:

- **Hero Section**: `images/dr-maya-reynolds.jpg` (Dr. Maya's photo)
- **Services**: Using placeholder images from Unsplash (can be replaced)
- **About Section**: Using placeholder therapy image (can be replaced)

### Replacing Service Images:

To use custom images for the service cards, replace these URLs in `index.html`:

```html
Line ~40: Anxiety therapy image
Line ~46: Trauma therapy image  
Line ~52: Burnout therapy image
```

Save your images to the `images/` folder and update the `src` attributes.

## Testing

Once you've added the image:
1. Open `index.html` in your browser
2. Check that Dr. Maya's photo appears in the hero section
3. If it doesn't show, verify the file path and name match exactly

## Need Help?

- Make sure the image filename is exactly: `dr-maya-reynolds.jpg`
- Image should be in: `E:\assigment\images\`
- Recommended dimensions: 600x600px or higher
- Format: JPG or PNG
