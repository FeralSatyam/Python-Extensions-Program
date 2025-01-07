# Python-Extensions-Program
This Python script identifies the MIME type of a file based on its extension. It’s a simple utility that can help understand the file type, especially when working with file uploads, downloads, or content delivery.

Features:
1. Accepts file names as input.
2. Strips whitespace and normalizes the file name to lowercase for consistency.
3. Checks for common file types and returns the appropriate MIME type:
4. JPEG Images: image/jpeg
5. GIF Images: image/gif
6. PDF Documents: application/pdf
7. PNG Images: image/png
8. Plain Text Files: text/plain
9. ZIP Archives: application/zip

Returns a default MIME type (application/octet-stream) for unknown extensions.
