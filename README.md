# Free Shopify Sections

A growing collection of free, ready-to-use Shopify Liquid sections and snippets — no paid app required. Copy a section into your theme, add it in the theme customizer, and configure it with your own content.

Each section lives in its own folder with the `.liquid` file and a `README.md` explaining what it does and how to install it.

## How to use a section

1. Open the folder for the section you want (e.g. [`animated-banner/`](animated-banner)).
2. Copy the `.liquid` file into your theme's `sections/` directory (in Shopify Admin: **Online Store → Themes → Edit Code → Sections**).
3. Go to **Online Store → Themes → Customize**, add the section to a template, and configure its settings.
4. A few entries (marked *snippet* below) modify an existing template/snippet instead of adding a new section — see their individual README for exact steps.

## Sections

| Section | Description |
| --- | --- |
| [3D Image Gallery](3d-image-gallery) | Interactive 3D image gallery for showcasing products or photos. |
| [3D Product & Collection Slider](3d-product-and-collection-slider) | 3D carousel for displaying products or collections. |
| [Add Custom Input Fields](add-custom-field) *(snippet)* | Add personalization fields (engraving, gift notes, etc.) to the product page. |
| [Double Scrolling Text](add-double-scrolling-text) | Marquee-style scrolling text banner. |
| [Pricing Plan](add-pricing-plan) | Pricing/plan comparison section. |
| [Animated Banner](animated-banner) | Hero/promo banner with CSS entrance and loop animations. |
| [Animated Circle Products & Collections](animated-circle-products-and-collections) | Circular animated product/collection display. |
| [Animated Image Slider](animated-image-slider) | Slider with animated image transitions. |
| [Animated Team Section](animated-team-section) | Expandable animated image grid for team/staff pages. |
| [Autoplay Video Section](autoplay-video-section) | Section with an autoplaying background/inline video. |
| [Before and After Slider](before-and-after-slider) | Drag comparison slider for before/after images. |
| [Breadcrumbs](breadcrumbs) | Breadcrumb navigation trail. |
| [Circle Menu](circle-menu) | Circular navigation menu layout. |
| [Collection Carousel Slider](collection-carousel-slider-section) | Carousel slider for collections. |
| [Coming Soon / Password Page](coming-soon-or-password-page) | Custom coming-soon or password-page layout. |
| [Custom Animated Slider](custom-animated-slider) | Image + content slider with custom animations. |
| [Custom Contact Form](custom-contact-form) | Standalone contact form section. |
| [Custom Font](custom-font) *(snippet)* | Add and apply a custom web font across your theme. |
| [Event Calendar](event-calendar) | Calendar section for listing events. |
| [FAQ Section](faq) | Expandable FAQ / accordion section. |
| [Icons Slider](icons-slider-in-shopify) | Sliding row of icons/logos. |
| [Lookbook Section](lookbook-section) | Editorial lookbook-style image layout. |
| [Metafields for Size Charts](metafields-for-size-charts) | Product size chart driven by metafields. |
| [Real-Time Delivery Dates](real-time-delivery-dates) *(snippet)* | Show estimated delivery dates on the product page. |
| [Sales Popup](sales-popup) | Recent sales/purchase notification popup. |
| [Scrolling Images Slider](scrolling-images-slider) | Continuously scrolling image strip. |
| [Shape Divider](shape-divider-section) | Decorative SVG shape dividers between sections. |
| [Shining Hover Effect](shining-hover-effect) *(snippet)* | Shine/sheen hover animation on the buy button. |
| [Show Drop Down on Hover](show-drop-down-on-hover) *(snippet)* | Open header dropdown menus on hover instead of click. |
| [Show Sale Discount Percentage](show-sale-discount-percentage) *(snippet)* | Display the discount percentage on sale items. |
| [Show Selected Variant Images](show-selected-variant-images) *(snippet)* | Filter product images by the selected variant. |
| [Side Tabbed Section](side-tabbed-section) | Tabbed content layout with side navigation. |
| [Simple Testimonial Section](simple-testimonial-section) | Basic customer testimonial layout. |
| [Story Timeline](story-timeline) | Vertical timeline section for brand story/milestones. |
| [Stylish Product Grid](stylish-product-grid-section) | Styled product showcase grid. |
| [Vertical Card Slider](vertical-card-slider) | GSAP-powered vertical scrolling card slider. |
| [Video Carousel](video-carousel) | Carousel for multiple embedded videos. |
| [Video Carousel Section](video-carousel-section) | Carousel for multiple embedded videos. |
| [WhatsApp Chat Icon](whatsapp-chat-icon) | Floating WhatsApp chat button. |

> **Note:** [`video-carousel`](video-carousel) and [`video-carousel-section`](video-carousel-section) currently contain the same section under two different names/folders. Keeping both for now — see [Known Issues](#known-issues).

## Requirements

- A Shopify theme you can edit (Online Store 2.0 recommended for full settings support).
- No paid apps or build step needed — sections are plain Liquid/CSS/JS.

## Known Issues

- `video-carousel` and `video-carousel-section` are duplicates of the same section (identical Liquid, different README wording). One should eventually be removed or the two merged.
- Folder naming is inconsistent (e.g. `video-carousel-section` vs. `collection-carousel-slider-section` vs. plain `video-carousel`) — a cleanup pass would make the collection easier to browse.

## Contributing

Found a bug or want to add a new section? Open an issue or pull request. When adding a new section, please include:
- The `.liquid` file in its own folder.
- A `README.md` describing what it does, its features, and install steps (use an existing section as a template).

## License

Released under the [MIT License](LICENSE) — free to use, modify, and distribute in personal and commercial Shopify themes.
