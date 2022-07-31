Objective Outline - lovethedeck.com.au
===

### Objective: **Migration of content from WordPress to Grav CMS**

| Hours | Tasks |
| ----- | ----- |
| 2h | Install & configure Grav CMS on server using Composer package manager via SSH |
| 1h | Export data from existing WordPress admin, import into Grav CMS |
| 8h | CSS/JS styling of Twig templates to meet existing theme visual and mobile responsivity standards |
| **11h** | *Total* |


### Objective: **Expand "What We Do" section so client can add/remove simple text and image combos (which resize appropriately for mobile). Either text right side / image left and vice versa**
#### - *Create modular home page using Grav's content modules to accommodate existing sections: "What We Do", "Testimonials", "Get In Touch"*
| Hours | Tasks |
| ----- | ----- |
| 30m | Admin module blueprint for "What We Do" section with content editor for text, custom fields for media assets to allow paired image uploads for Before/After carousel |
| 30m | Admin module blueprint for "Get in Touch" section with content editor for text and structure of contact form |
| 1h | Admin blueprint for handling user submitted contact form |
| 1h | Twig template partial for rendering module wrapper displaying text content and media assets |
| 1h | Twig template partial for rendering contact form |
| **4h** | *Total* |


### Objective: **Keep the carousel for the hero image (just below header)**
#### - *Add "Hero Gallery" module with asset rendering template to allow uploads of featured work to be displayed on a single slide full size hero module carousel at top of home page.*
| Hours | Tasks |
| ----- | ----- |
| 30m | Admin module blueprint with custom fields to handle media assets and metadata to organize display ordering |
| 1h | Twig template partial for module to render media from module on home page |
| **1.5h** | *Total* |


### Objective: **Keep the Before and After / Testimonials / Contact all as is (Including carousels)**
#### - *Add "Testimonials" content module that renders testimonial cards in a multi-item carousel; each card will display an avatar image, heading that cites name and location of testimonial submitted, and a blockquote of the testimonial's text.*
| Hours | Tasks |
| ----- | ----- |
| 30m | Admin module blueprint with fields to display testimonial citation (customer and location), a text editor field for testimonial content, and media asset for avatar image |
| 1h | Twig template partial for module wrapper containing carousel, plus nested template partial for rendering testimonial cards |
| **1.5h** | *Total* |


### Objective: **Add a blog/news section that just displays the latest blog article, along with a link to reveal more posts (ie a blog feed) on separate page, under menu item "News"**
#### - *Add "News / Updates" content module below "Testimonials" that renders a featured post from blog (most recent, unless otherwise tagged as featured or sticky by client) along with a link to reveal more posts on a separate page titled "News"*
| Hours | Tasks |
| ----- | ----- |
| 30m | Admin module blueprint for blog entry featured on home page, with fields for display options |
| 30m | Admin page blueprint for blog page |
| 1hr | Admin post blueprint for posts displayed on home/blog page(s), with fields for post title, date, taxonomy, SEO metadata, media assets associated with post, and Markdown editor for post content |
| 1hr | Twig template partial for blog section of home page to display featured post |
| 1hr | Twig template partial for rendering blog post preview |
| 1hr | Twig template page for rendering full post content |
| 1hr | Twig template page for rendering list of blog posts |
| **6h** | *Total* |

## 24 Hours Total
Completion Time: 1 - 2 weeks
