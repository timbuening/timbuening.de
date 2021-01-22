---
hide_git_sync_repo_link: false
sitemap:
    changefreq: monthly
body_classes: 'header-dark header-transparent'
hero_classes: 'text-light title-h1h2 overlay-dark-gradient hero-large parallax'
blog_url: /blog
show_sidebar: true
show_breadcrumbs: false
show_pagination: true
modular_content:
    items: '@self.modular'
    order:
        by: folder
        dir: dsc
content:
    items:
        - '@self.children'
    limit: 6
    order:
        by: date
        dir: desc
        excl: self
    pagination: true
    url_taxonomy_filters: true
bricklayer_layout: true
display_post_summary:
    enabled: false
feed:
    limit: 10
    description: 'Mein Blog'
pagination: true
child_type: item
---

# Ich bin **Tim** Büning
### Ma(lo)cher, Humanist, Weltenbummler
