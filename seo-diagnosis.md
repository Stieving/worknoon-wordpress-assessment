# SEO Technical Diagnosis: Website Not Indexing

## Scenario

A new Worknoon website is not being indexed by Google even after sitemap submission.

---

## 1. Crawlability Tests

The first step is verifying if Googlebot can access the website.

### Robots.txt Check

Ensure important pages are not blocked:

### URL Accessibility

Test URLs manually:
- Must return 200 status code
- Must not redirect incorrectly

### Tools

- Google Search Console URL Inspection
- Screaming Frog SEO Spider
- Sitebulb

---

## 2. Canonical Checks

Canonical tags must be correct to avoid indexing conflicts.

Correct example:

```html
<link rel="canonical" href="https://worknoon.com/page" />
