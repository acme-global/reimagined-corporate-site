---
title: Blog
slug: /blog
postFeed:
  showThumbnail: true
  showExcerpt: true
  showDate: true
  showAuthor: true
  variant: three-col-grid
  colors: bg-light-fg-dark
  styles:
    self: {}
  type: PagedPostsSection
numOfPostsPerPage: 12
enableSearch: true
topSections:
  - title:
      text: Featured Post
      color: text-dark
      type: TitleBlock
    subtitle: This is the subtitle
    posts:
      - content/pages/blog/top-ten-lessons-we-learned.md
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    variant: big-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-28
          - pb-0
          - pl-4
          - pr-4
        justifyContent: flex-start
    type: FeaturedPostsSection
styles:
  title:
    textAlign: center
seo:
  metaTitle: Blog - Demo site
  metaDescription: >-
    This is the blog of the demo site where we post about technology, product,
    and design.
  socialImage: /images/soc-blog.jpg
  type: Seo
type: PostFeedLayout
---
