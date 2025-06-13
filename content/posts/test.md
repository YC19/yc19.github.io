+++
date = '2025-05-08T14:01:17-05:00'
draft = true
title = 'Test'
# Method 1: Add CSS class to the entire post
class = "text-center"
# Or Method 2: Add custom CSS
style = "text-align: center;"
+++

# Example Links

Here are different ways to add links in Hugo:

1. Basic link: [Visit Google](https://www.google.com)

2. Link with title: [Visit GitHub](https://github.com "GitHub Homepage")

3. Reference style link: [Visit Stack Overflow][so]

[so]: https://stackoverflow.com

4. Internal link to another post: [Link to Research](/research/)

5. Link with image: [![Hugo Logo](https://gohugo.io/images/hugo-logo.png)](https://gohugo.io)

# Text Formatting Examples

## Bold Text
There are two ways to make text **bold** in markdown:
1. Using double asterisks: **This is bold text**
2. Using double underscores: __This is also bold text__

## Centered Text
To center text, we can use HTML's `<div>` tag with `text-center` class:

<div class="text-center">
This paragraph will be centered on the page. You can put multiple lines here
and they will all be centered. This is useful for quotes, important notices,
or any content you want to emphasize in the middle of the page.
</div>

## Combining Bold and Center
<div class="text-center">
This is a **centered paragraph** with some __bold text__ in it.
You can mix and match different formatting styles.
</div>

## Regular Paragraph
This is a regular paragraph that will be left-aligned. You can use **bold text** within it to emphasize certain words or phrases.

## Another Centered Section
<div class="text-center">
### This is a centered heading
And this is a centered paragraph below it. You can use **bold** and *italic* text within centered paragraphs.
</div>

# Centering Multiple Paragraphs

## Method 1: Single div for multiple paragraphs
<div class="text-center">
This is the first paragraph. It will be centered on the page.

This is the second paragraph. It will also be centered.

And this is the third paragraph. All paragraphs within the same div will be centered together.

You can even add **bold text** or *italic text* within these centered paragraphs.
</div>

## Method 2: Separate divs for each paragraph
<div class="text-center">
This is the first paragraph in its own div.
</div>

<div class="text-center">
This is the second paragraph in a separate div.
</div>

<div class="text-center">
This is the third paragraph in another div.
</div>

## Method 3: Centered section with multiple elements
<div class="text-center">
### This is a centered heading

This is the first paragraph under the centered heading.

This is the second paragraph.

*This is an italic paragraph.*

**This is a bold paragraph.**

And this is the final paragraph in the centered section.
</div>

## Regular (non-centered) text
This paragraph is not centered and will appear as normal text on the left side of the page.

# Centering Many Paragraphs

## Method 1: Using Front Matter
This entire post will be centered because we added `class = "text-center"` in the front matter.
No need to add any div tags!

This is another paragraph that will be centered automatically.

And another one. All paragraphs in this post will be centered.

You can still use **bold** and *italic* text.

## Method 2: Using a Single Div Wrapper
<div class="text-center">
This is the first paragraph in a centered section.

This is the second paragraph.

This is the third paragraph.

And so on... All paragraphs between the opening and closing div tags will be centered.

You can have as many paragraphs as you want here.

They will all be centered automatically.

**Bold text** and *italic text* work normally.

### Even headings will be centered
And the paragraphs below them too.

More paragraphs...

And more...
</div>

## Regular (non-centered) text
This paragraph is outside the div, so it won't be centered.
