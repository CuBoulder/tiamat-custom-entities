# CU Boulder Drupal 9+ Custom Entities

All notable changes to this project will be documented in this file.

Repo : [GitHub Repository](https://github.com/CuBoulder/tiamat-profile)

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

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
