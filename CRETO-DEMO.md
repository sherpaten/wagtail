# Creto Studio Demo Plan — Wagtail

This repository is the upstream Wagtail CMS. The Creto demo will be a separately built, Creto-branded editorial website powered by Wagtail; it is not a claim that the upstream project was authored by Creto Studio.

## Demo concept
**Creto Content Studio — CMS-powered website**

- Build a polished sample company/editorial website with a home page, services or articles, category pages, search, and contact page.
- Demonstrate the Wagtail editor experience and structured content management.
- Use fictional company and editorial content; do not publish copied client content.
- Keep the Wagtail admin separate from the public website and protect editor accounts.

## Implementation boundary
This repository is the CMS framework, not a finished website theme or a ready-made demo. Create a separate Django/Wagtail site project with Creto templates, page models, sample content, and a suitable public frontend.

## Deployment prerequisites
- Python and Django versions compatible with the selected Wagtail release.
- PostgreSQL (or another officially supported database configuration) and persistent media storage.
- Separate production settings, secret key, allowed hosts, static/media handling, and protected admin access.
- A read-only public demo experience; no real user submissions or personal data without a secure backend.

## Licensing and attribution
The root LICENSE is BSD 3-Clause. Preserve the copyright notice, conditions, and disclaimer in source and required binary notices. Do not imply Wagtail or Torchbox endorses Creto Studio.

## Status
- [x] Demo scope documented.
- [ ] Select compatible Wagtail/Django versions and verify template/dependency licences.
- [ ] Scaffold the Creto-branded sample site and CMS page models.
- [ ] Configure content, media, security, and deployment.
- [ ] Add the verified demo URL to Creto Studio Projects.
