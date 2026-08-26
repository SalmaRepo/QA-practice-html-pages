# QA Practice HTML Pages

Small standalone HTML pages built for hands-on Playwright and automation
testing practice. Each page is deployed live via Vercel and used as a
target for tests written in the `qa-automation-rebuilding` repo.

This repo isn't tied to one topic — pages get added here as new concepts
come up throughout the learning roadmap (locators, forms, waits, iframes,
alerts, file uploads, API mocking, visual testing, accessibility, etc.).

## Pages

| Page | Topic |
|------|-------|
| `index.html` | Locators — getByRole, getByLabel, getByPlaceholder, getByText, getByAltText, getByTitle, getByTestId |

New rows get added here as new pages are added.

## Conventions

- Each page lives at the repo root as its own `.html` file, so Vercel
  serves it at `/filename.html`.
- Keep each page focused on one topic — don't mix unrelated concepts
  into a single page.
- Update the table above whenever a new page is added.

## Deployment

This repo is connected to Vercel for automatic deployment on every push
to `main` — no build step, pages are served as static HTML.

## Related repo

Tests against these pages live in [`qa-automation-rebuilding`](#),
as `assignment_<topic>.spec.ts` files with tasks described in comments.
