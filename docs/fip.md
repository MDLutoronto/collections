---
title: Fire Insurance Plans
layout: wide  # Layout type, usually 'page' for standard pages.
nav_order: 2  # Order in the navigation menu.

created_date:  # Date when the page was created. Should be in YYYY-MM-DD format.
has_children: true  # Set to True if the page has sub-pages.
staff:  # Optional: Nested list of staff members associated with the page.
  - name: Staff One  # PLACEHOLDER: Replace with actual staff member's name.
    link: https://library.utoronto.ca/staff/staff-one  # link is optional
maintainer:
  - name: Maintainer Name  # PLACEHOLDER: Replace with actual maintainer's name.
    link: https://example.com/maintainer  # link is optional

parent: Collections
---
{% include csv_table.html data_key="Fire_Insurance_Plans" %}