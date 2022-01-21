---
layout: post
title:  "How to make a Post"
summary: "Learn how to add a Post to the QAP Knowledgebase"
author: elsnoman
date: '2022-01-20 15:48:00 +0000'
category: ['get started', 'guides', 'testing']
tags: QAP
thumbnail: /assets/img/posts/code.jpg
keywords: get started, guides, how to, post, make a post
usemathjax: false
permalink: /blog/how-to-make-a-post/
---

# How to make a Post

One of the many ways you can contribute to the QAP community is by creating Posts (aka Articles) for our [QAP Open Source Knowledgebase](https://base.qap.dev). You can either add the post directly to the [GitHub Repo](https://github.com/qa-at-the-point/base) or send the post to Carlos Kidman.

This post is a guide to help you create one yourself, but please reach out if you have questions or need help!

## Anatomy of a Post

In a nutshell, posts are just markdown files. They also need a "metadata" section at the top and a specific file name format, but knowing how to write with markdown is 95% of it.

> 💡 Post files go in the `_posts` folder of the project

### File Names

> 💡 The format is `YYYY-MM-DD-[post-name].md`

1. The filename starts with the date in `YYYY-MM-DD` format. Use the date you'd like this to be posted by.
2. Next you have the name of the file and the file extension

For example, the file name for this post was `2022-01-20-how-to-make-a-post.md`

### Metadata

With the file created, you start by adding a metadata section (aka frontmatter). This is information about the article that Jekyll will use when generating the website.

> 💡 This section starts with three dashes and ends with three dashes.

For example, this is the frontmatter I used for this post:

```yml
---
layout: post
title:  "How to make a Post"
summary: "Learn how to make a Post for the QAP Knowledgebase"
author: elsnoman
date: '2022-01-20 15:48:00 +0000'
category: ['guides', 'testing']
tags: QAP
thumbnail: /assets/img/posts/code.jpg
keywords: guides, how to, post, make a post
usemathjax: false
permalink: /blog/how-to-make-a-post/
---
```

> 💡 Posts _must_ start with the frontmatter or the post won't get rendered 🥲

### Markdown

From there, the rest of the file is pure markdown.

If you are new to markdown, I recommend starting with this [Syntax Cheatsheet](https://www.markdownguide.org/basic-syntax/) and searching other resources.

> 💡 I also recommend looking over our [Styleguide](https://base.qap.dev/styleguide) so you can see what the syntax will look like on the QAP knowledgebase website!

## Ready to submit

Now add all of your wonderful markdown content! Once you're ready, we need some remaining pieces before you submit.

### Credit the Author

If you are a new author, then you need to provide some info about you.

* Author image - This is a small pic of you or an avatar. Branding matters, so do something you'd be proud of.
* Author metadata - This is info about you (see below).

> 💡 The name of your image and metadata files should match the `username` field of the post metadata

1. Add your image to the `assets/img/authors` folder (ex. `johndoe.png`)
2. Add your metadata file to the `_authors` folder (ex. `johndoe.md`)

This is an example of a Author Metadata file called `johndoe.md` (you don't need all the social links):

```yml
---
name: John Doe
username: johndoe
bio: "Hi I a John, a Web Developer and Designer."
site: http://johndoe.com
avatar: johndoe.png
email: mail@johndoe.com
social:
    - title: "github"
      url: "https://github.com/johndoe"
    - title: "linkedin"
      url: "https://www.linkedin.com/in/johndoe"
    - title: "youtube"
      url: "https://www.youtube.com/channel/UCSfLBFFfNU9r6ihfei6VeJw"
    - title: "facebook"
      url: "https://www.facebook.com/johndoe"
    - title: "twitter"
      url: "https://www.twitter.com/johndoe"
    - title: "behance"
      url: "https://behance.com/johndoe"
    - title: "instagram"
      url: "https://instagram.com/johndoe"
    - title: "medium"
      url: "https://medium.com/johndoe"
    - title: "telegram"
      url: "https://telegram.com/johndoe"
    - title: "dribbble"
      url: "https://dribbble.com/johndoe"
    - title: "flickr"
      url: "https://flickr.com/johndoe"
---
```

### Send it!

If you are working on the post locally or in gitpod, you can run the web server locally to see what everything will look like before you submit anything. I recommend having the web server running while you're writing 😎

```sh
bundle exec jekyll serve --livereload
```

* If you are in the project, make sure you've added the post, your author image, and author info. Then submit a pull request.
* If not, send the markdown file and the author info to Carlos Kidman (via Slack, carlos@qap.dev, etc).

> 🎉 We will review it, ask for revisions (if needed), and eventually approve and publish it!

## Tips & Tricks

There are some other bits and pieces you may need depending on your situation. I will add them to this section, but this isn't an exhaustive list. Some are just good ideas like listing sources and adding alt text!

### Add a Category

> 💡 Available categories are located in the `categories` folder

If you're making a new category all we need to do is,

1. Create a new file with [your_category_name].md inside the categories folder.

2. Copy categories/testing.md file and replace the content in [your_category_name].md in that. (Please don't copy the code below its just sample, since it renders the jekyll syntax dynamically)

```jsx
---
layout: page
title: Guides
permalink: /blog/categories/your_category_name/
---

<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.your_category_name %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>
```

Using the category, all the posts associated with the category will be listed on
`http://localhost:4000/blog/categories/your_category_name`

### Thumbnail

I recommend adding a thumbnail to every post since they're not just visual, but also set the tone for the post.

The frontmatter has a `thumbnail` field that points to a specific folder `/assets/img/posts/`. For example, this post uses the `code.jpg` image so the frontmatter field looks like this:

```yml
thumbnail: /assets/img/posts/code.jpg
```

### References

🙏🏽 Please source any images or data (if necessary), and add alt text to images.

> 💡 This is a great [blog post by code-comments](https://code-comments.com/markdown-images-alt-text-and-title/) on how to do exactly this!

## You ready to contribute?

That's everything you need to create a post for the **QAP Open Source Knowledgebase**. Check out our other posts, including this one, under the [_posts folder](https://github.com/qa-at-the-point/base/tree/main/_posts) for more examples and inspiration.

✏️ Happy writing and have a quality day ✏️
