# Local Business Schema

Copy-ready JSON-LD templates for local service businesses, maintained by [Smart Local](https://smart-local.com.au/).

Structured data helps Google and AI search tools read a business's name, address, phone, hours and services correctly. These templates follow schema.org and Google's structured data guidelines.

## Templates
- [`professional-service.json`](professional-service.json): ProfessionalService markup with address, geo, phone, hours and profiles (Smart Local's own live markup, as a worked example)
- [`service.json`](service.json): a single Service linked to its provider
- [`faq.json`](faq.json): FAQPage for a service page

## How to use
1. Copy the template and replace every value with the business's real details.
2. Keep name, address and phone identical to the Google Business Profile.
3. Add it to the page inside `<script type="application/ld+json">`.
4. Only mark up FAQs and services that are visible on the page.
5. Test with Google's [Rich Results Test](https://search.google.com/test/rich-results) and the [Schema Markup Validator](https://validator.schema.org/).

## About
Smart Local is a local digital marketing and AI search agency in Glasshouse Mountains, QLD. Website: [smart-local.com.au](https://smart-local.com.au/)
