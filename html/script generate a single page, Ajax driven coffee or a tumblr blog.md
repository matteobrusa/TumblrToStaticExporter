# Mission
This script generates a single page, Ajax driven copy of a tumblr blog.

# Supported post types
 Photo
 Photoset
 Video

# Features
 Infinite scrolling
 Local download of photos and videos
 Backup of Private blogs 
 Password protection

# How does password protection on a static website works
The private content is stored in a subfolder whose name is the hash of the password.
The landing page computes the hash of the password, then try to retrieve the content from a folder named as the hash.
Make sure your web browser doesn't show folder listing!