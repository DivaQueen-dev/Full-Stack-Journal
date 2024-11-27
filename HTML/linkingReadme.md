# Linking Tags in HTML

This file, `linking.html`, demonstrates the use of **Anchor (`<a>`)** and **Image (`<img>`)** tags in HTML, with a focus on clickable fruit images that open descriptive pages about each fruit.

## Overview

- **Anchor Tag (`<a>`)**:  
  Used to create clickable links, allowing navigation to other web pages or sections. This file includes examples of anchor tag attributes like `target` to control how the links open.

- **Image Tag (`<img>`)**:  
  Displays images of fruits, which are clickable links.

## Features Demonstrated

1. **Clickable Fruit Images**:  
   - Displays images of fruits.
   - Clicking on a fruit's image opens a descriptive page about the fruit.
   - Demonstrates how to combine anchor tags and image tags.

2. **Anchor Tag Targets**:  
   - Explains the different `target` attribute values:
     - `target="_self"`: Opens the link in the same tab (default behavior).
     - `target="_blank"`: Opens the link in a new tab or window.
     - `target="_parent"`: Opens the link in the parent frame (used in framed content).
     - `target="_top"`: Opens the link in the full body of the window, breaking out of frames.
     - `target="[name]"`: Opens the link in a named iframe or child frame.

## Example Code Snippets

### 1. Fruit Image as a Link:
```html
<a href="apple.html" target="_blank">
  <img src="apple.jpg" alt="Apple" width="150" height="150">
</a>
