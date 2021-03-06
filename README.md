# TumblrToStaticExporter
This python script generates a single page, Ajax driven copy of a Tumblr blog.
It's a fork of the python script found at http://greymask.com/how-to-backup-a-html-copy-of-your-entire-tumblr-blog/

You can see a copy of http://dummy-content.tumblr.com/ at https://matteobrusa.github.io/TumblrToStaticExporter/

**The HTML part is now a project on its own, and supports posting and editing on Amazon S3:** https://github.com/matteobrusa/Tumbless/ 

# Supported post types
- Photo
- Photoset
- Video
- Text

# Features
- Local download of photos and videos
- Backup of Private blogs 
- Password protection
- Infinite scrolling

# Dependencies
This script depends on spynner (https://github.com/makinacorpus/spynner) to download videos.

# How does password protection on a static website works
The private content is stored in a subfolder whose name contains the password.
Make sure your web browser doesn't show folder listing!
