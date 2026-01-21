# Web Development Day‑09

## 1. Working with images in HTML

1) The `<img>` tag is used to display images; it is self‑closing and must have a `src` attribute pointing to the file and an `alt` attribute describing the image.  
2) Example: `<img src="images/profile.jpg" alt="Student profile photo">`. The `alt` text is shown to screen readers and when the image fails to load.  
3) Common optional attributes:
   - `width` and `height` to control the displayed size (usually set via CSS in real projects).  
   - `title` to show a small tooltip on hover.

## 2. Relative vs absolute paths for media

1) For images, audio, and video inside the project, use **relative paths** like `images/logo.png` or `media/song.mp3`.  
2) For content hosted elsewhere (CDN or external site), use a full URL like `https://example.com/assets/banner.png`.  
3) Keeping all media inside a `images/`, `audio/`, or `video/` folder makes paths easier to manage.

## 3. Embedding audio

1) The `<audio>` element is used to play sound files in the browser; it usually wraps one or more `<source>` tags.  

2) Basic pattern:
   <audio controls>
       <source src="audio/theme.mp3" type="audio/mpeg">
       <source src="audio/theme.ogg" type="audio/ogg">
       Your browser does not support the audio element.
   </audio>

## 4. Embedding video

1) The <video> element works similarly to <audio>, but for video files.

2) Basic pattern:
<video controls width="640">
    <source src="video/intro.mp4" type="video/mp4">
    <source src="video/intro.webm" type="video/webm">
    Your browser does not support the video tag.
</video>

