---
name: blogpost-template
about: Describe this issue template's purpose here.
title: How to write a blogpost
labels: blog-post
assignees: ''

---

1. Create a new .md file with a proper and relevant filename
2. Add below settings to your .md file first.

```
---
title: "My Blog Post" # Title of the blog post.
date: dd-mm-yyyy # Date of post creation.
description: "Article description." # Description used for search engine.
featured: true # Sets if post is a featured post, making appear on the home page side bar.
draft: true # Sets whether to render this page. Draft of true will not be rendered.
toc: false # Controls if a table of contents should be generated for first-level links automatically.

usePageBundles: false # Set to true to group assets like images in the same folder as this post.
featureImage: "/images/path/file.jpg" # Sets featured image on blog post.
featureImageAlt: 'Description of image' # Alternative text for featured image.
featureImageCap: 'This is the featured image.' # Caption (optional).
thumbnail: "/images/path/thumbnail.png" # Sets thumbnail image appearing inside card on homepage.
shareImage: "/images/path/share.png" # Designate a separate image for social media sharing.
codeMaxLines: 10 # Override global value for how many lines within a code block before auto-collapsing.
codeLineNumbers: false # Override global value for showing of line numbers within code block.
figurePositionShow: true # Override global value for showing the figure label.
categories:
  - category1
  - category2
tags:
  - Tag_name1
  - Tag_name2
series:
  - series1
---
```

3. Then continue writing the content, adding images and links based on the topic. 
4. If you want to write a series, rename "series1" with the actual series name. Add relevant tags under tags like "Tag_name1, Tag_name2". 
5. To understand more Hugo features, look into the reference markdown file for the template used for this website
