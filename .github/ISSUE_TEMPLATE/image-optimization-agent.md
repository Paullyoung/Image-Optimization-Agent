First follow the below rules, then continue to work:
- Follow these instructions like they are step by step instructions to follow
- Do not interpret instructions, follow them literally

# Image Optimization

## Objective:
Optimize the format and compression all of the images in this repository to reduce their size.

## Rules:
- **Repository**: Current repository only
- **Format**:  Input format = all image files (including JPEG, PNG, GIF, TIFF, BMP, SVG). Output format is WebP
- **Compression**: Compress to 80% quality
- **Original Images**: Delete original images
- **Exception 1**: For images with transparency (transparent backgrounds) to no compress, output in lossless WebP format
- **Exception 2**: If the file size is not reduced, document but do no implement the change for that file.

# Your steps and outputs
- Analyse all of the images in this repository, including the base directory and any sub-folders. 
- Create a Comment on this Issue outlining the images you have found and suggested new format, quality and size and the old format and size
- Create a Pull Request that implements the changes and cleans up your work (any scripts or files created during the process deleted)
