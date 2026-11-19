# Catalog MFE WBA translations

The catalog JSON files cannot contain comments. The WBA-owned entries are the final block in `translations/frontend-app-catalog/src/i18n/transifex_input.json` and in the active locale files `bo.json`, `es_419.json`, `fr.json`, `id.json`, `vi.json`, and `zh_CN.json`. Four blank lines separate that block from the Open edX entries copied from `release/verawood`.

Six of these IDs also exist in the upstream catalog. They are removed from the upstream section and kept only in the WBA block, so each key appears once. On a later Tutor upgrade, copy the new upstream catalog folder, delete these six keys from the refreshed files if they return, and restore the WBA block:

- `catalog.home-page.search-placeholder`
- `catalog.home-page.title`
- `category.catalog.no-results-found`
- `category.header.dashboard.label`
- `category.header.discoverNew`
- `category.header.explore-courses`

## WBA message IDs

- `catalog.home-page.eyebrow-signed-in`
- `catalog.home-page.eyebrow-signed-out`
- `catalog.home-page.hero-courses`
- `catalog.home-page.new-course`
- `catalog.home-page.provider-logo-alt`
- `catalog.home-page.welcome-back`
- `catalog.home-page.search-placeholder`
- `catalog.home-page.title`
- `catalog.course-about.about-this-course.heading`
- `catalog.course-about.course-overview.heading`
- `catalog.course-about.course-requirements.heading`
- `catalog.course-about.course-short-description.heading`
- `catalog.course-about.instructors.heading`
- `catalog.course-about.instructors.image-alt`
- `catalog.course-about.learning-outcomes.heading`
- `catalog.course-about.sidebar-details.archive-date`
- `catalog.course-about.sidebar-details.course-duration`
- `catalog.course-about.sidebar-details.estimated-effort-hours`
- `catalog.course-about.sidebar-details.release-date`
- `catalog.course-about.sidebar-details.students-enrolled`
- `category.catalog.filter.clear-all`
- `category.catalog.filter.remove-chip`
- `category.catalog.filter.title`
- `category.catalog.no-results-found-message`
- `category.catalog.no-results-found`
- `category.catalog.page-eyebrow`
- `category.catalog.page-heading`
- `category.catalog.pagination-label`
- `category.catalog.row-status`
- `category.course-about.course-intro.buy-course-btn`
- `category.course-about.course-intro.checking-enrollment-options-btn`
- `category.course-about.course-intro.close-modal-btn`
- `category.course-about.course-intro.course-media.watch-intro-btn`
- `category.course-about.course-intro.how-to-get-invite-btn`
- `category.course-about.course-intro.invite-instructions-modal.body`
- `category.course-about.course-intro.invite-instructions-modal.title`
- `category.course-about.course-intro.status-message.purchased`
- `category.course-about.course-intro.wishlist.wishlist-btn`
- `category.course-about.course-intro.wishlist.wishlisted-btn`
- `category.header.wishlist`
- `category.header.dashboard.label`
- `category.header.discoverNew`
- `category.header.explore-courses`
