# How to Upload and Update Your Bayesian Spike-and-Slab Document

## Quick Start

Your document link is: **`https://deeptendra.github.io/documents/bayesian-spike-slab.pdf`**

This link is permanent and can be used in your CV. When you update the document, the link will remain the same.

## Step-by-Step Instructions

### Initial Upload

1. **Prepare your PDF document**
   - Make sure your document is in PDF format
   - Name it `bayesian-spike-slab.pdf` (or keep this exact name)

2. **Upload to GitHub**
   - Go to your repository: https://github.com/Deeptendra/Deeptendra.github.io
   - Navigate to the `documents` folder
   - Click "Add file" → "Upload files"
   - Drag and drop your `bayesian-spike-slab.pdf` file
   - Replace the placeholder file
   - Commit the changes

3. **Verify the link**
   - After a few moments, visit: https://deeptendra.github.io/documents/bayesian-spike-slab.pdf
   - Your document should be accessible
   - The "View Document" button on your portfolio will also work

### Updating the Document

When you need to update your document:

1. **Go to the documents folder**
   - Navigate to: https://github.com/Deeptendra/Deeptendra.github.io/tree/main/documents

2. **Replace the file**
   - Click on `bayesian-spike-slab.pdf`
   - Click the trash/delete icon to remove it
   - Then upload your new version with the **same filename**
   - Or use "Upload files" and select "Replace existing file"

3. **Important:** Keep the same filename (`bayesian-spike-slab.pdf`)
   - This ensures the link in your CV never breaks
   - GitHub Pages will automatically serve the updated file

## Adding Documents for Other Projects

If you want to add documents for other projects:

1. **Upload the document to the `documents` folder**
   - Use a descriptive, permanent filename (e.g., `diabetes-prediction-analysis.pdf`)

2. **Add a link in index.html**
   - Find the relevant project card in `index.html`
   - Add this code before the closing `</div>` tag:
   ```html
   <p class="project-links">
       <a href="documents/your-document-name.pdf" class="project-link" target="_blank">View Document</a>
   </p>
   ```

3. **The link will be:**
   - `https://deeptendra.github.io/documents/your-document-name.pdf`

## Tips

- **Use descriptive filenames:** Choose clear names that describe the project
- **Avoid spaces:** Use hyphens instead (e.g., `my-project.pdf` not `my project.pdf`)
- **PDF format recommended:** Most universally accessible format
- **File size:** Keep files under 100MB for best GitHub Pages performance
- **Update README:** Document new files in `documents/README.md` for reference

## Current Document Structure

```
Deeptendra.github.io/
├── documents/
│   ├── README.md
│   └── bayesian-spike-slab.pdf  ← Your document goes here
├── index.html
├── styles.css
└── script.js
```

## Support

If you encounter any issues:
1. Check that the file is named exactly as expected
2. Wait a few minutes for GitHub Pages to update
3. Clear your browser cache
4. Check the repository Actions tab for deployment status
