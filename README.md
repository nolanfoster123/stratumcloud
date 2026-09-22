# Stratum Cloud website

Five HTML pages with shared CSS and vanilla JavaScript. No build tools required.

## Open locally
Open dist/index.html in a browser, or serve dist with any static web server. Keep the assets directory beside the HTML files. Google Fonts is optional; system font fallbacks work offline.

## Pages
- index.html: homepage, six product pillars and architecture diagram
- about.html: positioning, principles and migration approach
- blog.html: featured article and links to its technical sections
- blog-post.html: complete production AI infrastructure guide
- calculator.html: live monthly estimate with editable resource quantities and unit rates

## Customization before production
Stratum Cloud is an invented concept brand, not a verified operating provider. Replace the brand, company positioning and footer with approved information. No customer logos, certifications, performance guarantees or customer counts are asserted.
Replace illustrative USD rates with approved prices. The calculator GPU rate includes its host allocation; VM charges are additional application or worker nodes. Database rates are per instance. Storage quantities represent provisioned/billable GB. Compute hours affect GPUs and VMs only. The example uses 730 hours, not a promise of a fixed monthly billing period. The maximum is 744 hours.
Migration, taxes, backup capacity, storage API requests, load balancing, support and licensing are excluded and disclosed. The calculator is a planning model, not checkout or a quote.
The blog index contains one complete article plus clearly labeled links to sections of that article. Add real articles when available.
No backend, tracking, payment, signup or contact-submission integrations are included.

## Checks completed
JavaScript syntax passed. All five HTML pages have one H1 and page metadata. All local asset references, page links and fragment targets resolve. Calculation checks passed for the default estimate ($2,215.20), zero compute hours ($215.00 recurring costs) and zero resources ($0.00).
Responsive CSS includes desktop, tablet and mobile layouts; keyboard focus, skip links, reduced-motion handling and labeled inputs are included. Visual browser/device testing was not available in the static preview environment. Optional WebMCP registration is feature-detected; validation in a supported browser context was unavailable.

## Editing
Change palette and typography in dist/assets/style.css. Edit copy directly in each HTML page. Calculator defaults live in calculator.html; formulas and input behavior live in assets/app.js. Navigation and footers are static and should be updated consistently across all five pages.

## Design refinement
Rebuilt the homepage hero with a connected architecture diagram, improved hierarchy and six line icons. Refined all secondary pages. Added short entrance transitions, one-time scroll reveals, hover states, article reading progress and calculator change feedback. All motion respects reduced-motion preferences, and page content remains visible if JavaScript is disabled. Visual browser testing remains unavailable for this static preview environment.
