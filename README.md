# Lansing Sewer Line Pros
Astro source for Lansing sewer line information and service requests. Production domain: https://lansingsewerline.prosapp.site.

Contact, landing-page phone settings and request tracker are single-source in `src/data/siteConfig.ts`. No analytics code is installed. Normal pages, local guides, legal pages and three noindex ad landing pages use shared source layouts. Request success is shown only for a matching accepted tracker POST; this does not independently confirm CRM arrival.

Build with `npm install` then `npm run build`. Cloudflare Pages build command: `npm run build`; output directory: `dist`.

Local research includes the Westside Neighborhood Association, Moores Park Neighborhood Organization, Lansing historic-property account, and the city's sewer ordinance and backup guidance. See page-specific reference links in the local guide and neighborhood pages. No municipal affiliation is claimed.
