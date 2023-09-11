# CU Boulder Drupal 9+ Custom Entities

All notable changes to this project will be documented in this file.

Repo : [GitHub Repository](https://github.com/CuBoulder/tiamat-profile)

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- ### metatag necessary fields
  Closes https://github.com/CuBoulder/tiamat-theme/issues/149.
  Adds social sharing custom entity to enable metatags.
---

- ### Update core.entity_view_display.node.basic_page.default.yml
  The page title being moved to layout builder mode
  
  Sister PR: https://github.com/CuBoulder/tiamat-theme/pull/473
---

- ### New: Adds 'People List Block'
  ### People List Block
  A configurable and placeable block that displays a list of People, similar to the Person List Page with simpler options. Block contains options for how your block will display to users (Teaser, Grid, Name & Thumbnail, Name Only) and selectable filters by taxonomies on a Person (Department, Job Type, Filter 1, 2, 3) to curate a specific list of People ordered by Last Name.
  
  Includes:
  - `tiamat-custom-entities` => `issue/tiamat-theme/466`
  - `tiamat-theme` => `issue/tiamat-theme/466`
  
  Resolves https://github.com/CuBoulder/tiamat-theme/issues/466
---

- ### Removes image requirement from Content Row "Teaser" layouts
  This update enables the creation of Content Row blocks with image-less content and displays it correctly in the "Teasers" and "Teasers Alternate" layouts.
  
  CuBoulder/tiamat-theme#453
  
  Sister PR in: [tiamat-theme](https://github.com/CuBoulder/tiamat-theme/pull/457)
---

- ### Removes "D9" from theme name and the theme, custom entities Composer package names
  CuBoulder/tiamat-theme#435
  
  Sister PR in: [tiamat-theme](https://github.com/CuBoulder/tiamat-theme/pull/452), [tiamat-profile](https://github.com/CuBoulder/tiamat-profile/pull/52), [tiamat10-profile](https://github.com/CuBoulder/tiamat10-profile/pull/13), [tiamat-project-template](https://github.com/CuBoulder/tiamat-project-template/pull/28), [tiamat10-project-template](https://github.com/CuBoulder/tiamat10-project-template/pull/8), [ucb_site_configuration](https://github.com/CuBoulder/ucb_site_configuration/pull/26)
---

- ### Updated Byline
  Byline now has Author Person Page entity ID targetting
---

- ### Adds Description to Form Page Node
  Resolves #18 
---

- ### Change: Adds 'White' background to card-styled Text Block
  Adds a White background option to card-style Text Block for the case where sections have a different colored background
  
  Includes:
  
  - `tiamat-theme` => `issue/tiamat-theme/413`
  - `tiamat-custom-entities` => `issue/tiamat-theme/413`
  
  Resolves https://github.com/CuBoulder/tiamat-theme/issues/413
---

- ### Adds Additional Events link to Event Calendar block
  Resolves https://github.com/CuBoulder/tiamat-theme/issues/381 - Adds a Link field to the Events Calendar Block to allow for links to additional events.
  
  Includes:
  [tiamat-theme](https://github.com/CuBoulder/tiamat-theme) => [issue/tiamat-theme/381 ](https://github.com/CuBoulder/tiamat-theme/pull/411)
  [tiamat-custom-entities](https://github.com/CuBoulder/tiamat-custom-entities) => [issue/tiamat-theme/381](https://github.com/CuBoulder/tiamat-custom-entities/pull/65)
  
---

- ### Changes labels of Hero Block 'Content' and 'Design' tabs
  Resolves https://github.com/CuBoulder/tiamat-theme/issues/399
---

- ### Issue 320: Adding primary link to person pages
  Closes Issue 320 in tiamat-theme. Adds the necessary files for a primary link field in the person page.
---

- ### Update field.storage.block_content.field_grid_column_count.yml
  Added options for 5 and 6 columns in grid content
  
  Sister PR: https://github.com/CuBoulder/tiamat-theme/pull/395
---

- ### Changes to Article content type, Text and Content Grid blocks
  - Changes Article category and tag fields to tag style. Resolves CuBoulder/tiamat-theme#349
  - Removes Article Hero from Article. CuBoulder/tiamat-theme#352
  - Renames and reorders tabs in the Content Grid form display. Resolves CuBoulder/tiamat-theme#375
  - Renames tabs in the Text block form display. Resolves CuBoulder/tiamat-theme#386
---

- ### Update field.field.paragraph.row_layout_content.field_row_layout_cont…
  Made the text option not required
  
  Sister PR: https://github.com/CuBoulder/tiamat-theme/pull/391
---

- ### New Block Type: Article Slider
  Adds the Article Slider block. Much like the Article List page and other Article blocks, this will display a maximum of 6 articles in an interactive slider using user-provided inclusion and exclusion filters.
  
  Resolves [#319 ](https://github.com/CuBoulder/tiamat-theme/issues/319)
  
  Includes:
  `tiamat-theme` => `issue/tiamat-theme/319`
  `tiamat-custom-entities` => `issue/tiamat-theme/319`
---

- ### New Block Type: Article Feature
  Adds a new block type: Article Feature. The Article Feature block displays the latest Articles, with Category & Tag filters set by the user much like the Article List page. The first Article displays a large image and summary and the remaining articles displays titles and thumbnails. 
  
  Resolves [#318 ](https://github.com/CuBoulder/tiamat-theme/issues/318)
  
  Includes:
  
  - `tiamat-theme` => `issue/tiamat-theme/318`
  - `tiamat-custom-entities` => `issue/tiamat-theme/318`
---

- ### New Block Type: Article Grid
  Adds a new block type - Article Grid. Allows for Articles with thumbnails to be displayed in an Article List-style grid display.
  
  Includes:
  
  - `tiamat-theme` => `issue/tiamat-theme/317`
  -  `tiamat-custom-entities` => `issue/tiamat-theme/317`
  
  Resolves [#317 ](https://github.com/CuBoulder/tiamat-theme/issues/317)
---

- ### Update field.field.block_content.events_calendar.field_calendar_code.yml
  Updated help text to contain link to the events calendar widget maker
  
  Sister PR: https://github.com/CuBoulder/tiamat-theme/pull/367
---

- ### Change: Related Articles set via Global Settings
  Resolves[ #246 ](https://github.com/CuBoulder/tiamat-theme/issues/246)-- Related Articles paragraph now uses the Global Settings (Admin => Configuration / CU Boulder site settings / Related Articles) for Taxonomy Exclusions
  
  Includes:
  
  - tiamat-theme `issue/246`
  - tiamat-custom-entities `issue/tiamat-theme/246`
---

- ### New Block Type: Article List Block
  Adds Article List Block - a block version of the Article List page with some added display style customizations.
  
  Resolves https://github.com/CuBoulder/tiamat-theme/issues/316
  
  Includes:
  -tiamat-theme (https://github.com/CuBoulder/tiamat-theme/pull/357) => `issue/tiamat-theme-316` 
  -custom-entities => `issue/tiamat-theme-316`
---

- ### Issue/tiamat theme/265
  Closes #265.
---

- ### Change: Newsletter Taxonomy Enhancements and Newsletter URL Path
  Resolves https://github.com/CuBoulder/tiamat-theme/issues/306
  
  Adds the following fields to the Newsletter Taxonomy type to eventually be used in styling the Newsletter email render:
  - Design
  - Email Footer
  - Image
  - Newsletter Path*
  
  Also changes pathauto for Newsletters to follow this pattern:
  _/newsletter/newsletter-path*/title_
---

- ### chg: bumping for D10 compatibility
  
---

- ### Adds pronouns field to the Person page
  A pronouns text field has been added to the Person page, allowing a person's pronouns to be displayed below their name.
  
  CuBoulder/tiamat-theme#315
  
  Sister PR in: [tiamat-theme](https://github.com/CuBoulder/tiamat-theme/pull/327)
---

- ### Update hero unit form display
  Added "Block Description" to the form display.
  This option is needed to add titles to the Block Layout list of options.
  
  Closes #45
  (Issue number changed in ticket repo transfer)
---

- ### Modifies person page form display
  - CuBoulder/tiamat-theme#308: adds descriptions for the _Job Type_ and _Phone_ fields
  - Resolves CuBoulder/tiamat-theme#310: renames "Other" tab to "Filters"
  - Resolves CuBoulder/tiamat-theme#311: renames "Description" tab and "Bio" field to "Body"
---

- ### Add new image styles to WYSIWYG and full html
  Closes #152 in Tiamat Theme.
  Adds the new image styles to the custom entities
---

## [20230323] - 2023-03-23

-   ### Changes "Order by" for Person List page

    The option "Has Job Type, Last Name" has become "Job Type, Last Name". Rather than simply checking for the existence of the _job type_, sorting is performed alphabetically by a person's first _job type_.

    CuBoulder/tiamat-theme#280; Author @TeddyBearX 
    Sister PR in: [tiamat-theme](https://github.com/CuBoulder/tiamat-theme/pull/287)

* * *

-   ### Removes the ability to turn off "Restrict choices to those selected" in People List

    The option is no longer present when creating or editing a People List page.

    CuBoulder/tiamat-theme#281

    Sister PR in: [tiamat-theme](https://github.com/CuBoulder/tiamat-theme/pull/285)

* * *

-   ### Newsletter Email View Modes

    Adds `Email HTML` View Modes for the Newsletter Node, allowing for dual render styles to satisfy Newsletter requirements
    Partially resolves <https://github.com/CuBoulder/tiamat-theme/issues/222>

    Includes:
    `tiamat-theme` => issue/222
    `tiamat-custom-entities` => issue/222

* * *

-   ### Removes the ability to add articles to menus
    Resolves CuBoulder/tiamat-theme#239

* * *

-   ### Hidden Terms: Category and Tag Taxonomy Display Option

    Hidden Terms: Category and Tag schemas receive form option to toggle display for admin-only taxonomies.

    Resolves [#217 ](https://github.com/CuBoulder/tiamat-theme/issues/217)

    Change Includes:

    -   `tiamat-theme` => `issue/217`
    -   `tiamat-custom-entities` => `issue/217`

* * *

## [20230209] - 2023-02-09

-   ### Adds Title Background Images to Articles
    Schemas for new Article fields for Header Image, Overlay, and Header Color
    Resolves <https://github.com/CuBoulder/tiamat-theme/issues/154>

* * *

-   ### Publication Bundle

    Includes the following additions included in the Publication Bundle, resolves <https://github.com/CuBoulder/tiamat-theme/issues/168>.

    New Content Types:

    -   Issue
    -   Issue Archive

    Updated Content Types:

    -   Article

    New Block Types (Basic Page):

    -   Current Issue block
    -   Latest Issue block
    -   Category Cloud block
    -   Tag Cloud block

    Notes for testing:
    Includes branches `issue/168` on `tiamat-theme`

* * *

-   ### Adds `CHANGELOG.md` and workflow to `tiamat-custom-entities`
    Resolves #32 

* * *

[Unreleased]: https://github.com/CuBoulder/tiamat-custom-entities/compare/20230323...HEAD

[20230323]: https://github.com/CuBoulder/tiamat-custom-entities/compare/20230209...20230323

[20230209]: https://github.com/CuBoulder/tiamat-custom-entities/compare/5194d160ddd0ecedec145abb78463eda2032d8a4...20230209
