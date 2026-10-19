# The New Start Project Ltd — website rebuild

## Status
Rebuilt and locally tested static website files. NOT published to Cloudflare.
This package does not change the existing website or account.

## Public positioning
Supported accommodation management and administration, available to providers generally.
No public references or links to another organisation. No invented client list,
testimonials, accreditations or track record. Volunteer coordination is presented
as a requirement to discuss, not an established recruitment service.

## Files
- public/index.html — homepage, inline CSS and minimal navigation JavaScript
- public/privacy.html — privacy information scoped to this website and initial enquiries
- public/404.html — not-found page
- public/favicon.svg — favicon
- public/robots.txt — crawler instructions
- wrangler.jsonc.example — optional Cloudflare static-assets configuration

No build step, frameworks, external fonts, analytics, forms or third-party media.
Telephone and email are direct links to the current public contact details.

## Integrate into the EXISTING website project
1. Back up the current repository/project and note the existing deployment version.
2. Copy the contents of public/ into the existing project's published/static-assets
   directory. Preserve the existing deployment workflow and account settings.
3. Use the existing deploy command or connected GitHub workflow.
4. Do not replace bindings, routes, domains, databases or other existing settings.
5. Check the homepage, mobile menu, contact links, FAQs, privacy page and 404 after deployment.

If using Wrangler without an existing project configuration, review the example,
verify the Worker name/account, then copy it to wrangler.jsonc. Run the installed
Wrangler deploy command from this folder. This file is deliberately an example
so it cannot overwrite an existing project's live configuration accidentally.

## Content checks before publishing
Company number: 16195860 (from workspace company records).
Registered office: retained from the previous public website.
Updated contact details supplied by Paul: 01803 446114; contact@thenewstartprojectltd.co.uk.
Confirm the public service scope, service area and contact address remain current.
The privacy notice must match actual company practices and the chosen hosting/email
providers. Update it before adding forms, analytics, third-party embeds or tracking.
The current workers.dev address is not hard-coded as a canonical URL because the
preferred custom domain must be confirmed in the existing deployment setup.

This website describes services offered to the market. It does not establish
independent trading, external clients, regulatory status or a separate legal purpose.
