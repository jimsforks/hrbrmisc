
<!-- README.md is generated from README.Rmd. Please edit that file -->
`hrbrmisc` is @hrbrmstr's personal R pkg and unlikely to ever make it to CRAN

Features
--------

### Predicate-y

-   `%!fmin%`: Shortcuts for 'fmatch' and 'match' operations
-   `%!in%`: Shortcuts for 'fmatch' and 'match' operations
-   `%fmin%`: Shortcuts for 'fmatch' and 'match' operations
-   `%||0%`: Is an object 'NULL' or length zero
-   `%||0NA%`: Is an object 'NULL' or length zero or 'NA'
-   `is_empty_string`: Is a string equivalent to '""'
-   `is_zero_length`: Is length 0

### dplyr-ish

-   `count_pct`: Shortcut for adding percentages to 'dplyr::count' summaries

### grep-py

-   `ggrep`: Shorthand helpers for base 'grep' and 'grepl'
-   `igrep`: Shorthand helpers for base 'grep' and 'grepl'
-   `igrepl`: Shorthand helpers for base 'grep' and 'grepl'
-   `lgrep`: Shorthand helpers for base 'grep' and 'grepl'
-   `vgrep`: Shorthand helpers for base 'grep' and 'grepl'
-   `vigrep`: Shorthand helpers for base 'grep' and 'grepl'

### Utility

-   `as_date`: Shortcut to avoid specifying origin
-   `has_env`: Does the environment variable exist?
-   `last_el`: get last element
-   `make_numeric`: Clean up a character vector to make it numeric
-   `make_percent`: Clean up a character vector to make it a percent
-   `qp_decode`: Decode a quoted printable string

### Da-BOM

-   `has_bom`: Tests whether a raw httr response or character vector has a byte order mark (BOM)
-   `sans_bom`: Remove byte order mark (BOM) from 'httr::response' object or character vector

### httr-ish

-   `sDELETE`: "Safe" versions of 'httr' functions
-   `sGET`: "Safe" versions of 'httr' functions
-   `sHEAD`: "Safe" versions of 'httr' functions
-   `sPATCH`: "Safe" versions of 'httr' functions
-   `sPOST`: "Safe" versions of 'httr' functions
-   `sPUT`: "Safe" versions of 'httr' functions
-   `sVERB`: "Safe" versions of 'httr' functions

### ggplot2-y

-   `gbarplot`: Quick way to replace the handy 'barplot'
-   `quick_map`: Plot a fortified map using coord\_quickmap
-   `theme_hrbrmstr`: My ggplot2 go-to theme
-   `title_left`: Completely flush-left-align ggplot2 title

### "Cyber"

-   `hhs_breaches`: Retrieve current public list of U.S. Health & Human Services Breaches
-   `host_up`: Is a host listening on a port (TCP)?
-   `get_public_dns_servers`: Get public DNS servers list
-   `get_dotgov`: Get `.gov` domains

### JSON-ish

-   `json_view`: JSON & R list (virtually any object, really) viewer
-   `json_tree_view`: JSON & R list (virtually any object, really) tree viewer

Code of Conduct
---------------

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.
