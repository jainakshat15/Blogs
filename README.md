# Blog Repository Guidelines

## Purpose

This repository stores all blog content for the website.

Each blog must live inside the posts directory.

## Directory Structure

posts/
  blog-slug/
    meta.json
    blog.md

## Blog Requirements

Every blog should contain:

- Clear title
- Long-form content
- Multiple sections
- Relevant external links
- Code snippets where applicable
- Key takeaways section
- FAQ / Q&A section
- Conclusion section
- Cover image

## Metadata Requirements

Each post must include:

- id
- title
- slug
- date
- category
- tags
- coverImage
- excerpt

## Categories And Tags

Before creating a new post:

1. Check categories.json
2. Check tags.json
3. Reuse existing categories and tags whenever possible
4. If a new category or tag is required, update the corresponding file before publishing the article

## Content Quality Standards

- Prefer detailed content over short content
- Use markdown formatting
- Include practical examples
- Include code snippets when relevant
- Include useful resource links
- Avoid duplicate topics
- Focus on evergreen and searchable content

## SEO Guidelines

- Use descriptive titles
- Use keyword-rich headings
- Add meaningful excerpts
- Use readable URLs
- Include FAQ sections
- Include outbound links when relevant

## Example Workflow

1. Create post folder
2. Create meta.json
3. Create blog.md
4. Verify category exists
5. Verify tags exist
6. Add new category/tag if needed
7. Publish
