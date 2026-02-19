IMAGES FOLDER

• Original full-size photos stay here (for backup/print).
• The carousel uses optimized copies in the carousel/ subfolder (resized to 800px max, JPEG ~85%) so the site loads fast on phones.

To add new photos: put them here, then create a carousel version:
  sips -s format jpeg -s formatOptions 85 -Z 800 YOURFILE.jpg --out carousel/YOURFILE.jpg
Then add the path (images/carousel/YOURFILE.jpg) to MEMORY_IMAGES in index.html.
