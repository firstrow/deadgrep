# v0.4

When starting a search from another search buffer, remember the
original file that the original search buffer was opened from. This
ensures we can still offer useful globbing/file type defaults.

# v0.3

Added the ability to collapse results from a specific file!

Deadgrep now re-uses search settings from the last search, so if you
prefer regexp settings, you only need to set it once!

When choosing a file type to search, the default option matches the
file the search was started from.

Fixed an issue where active regions hang around after starting a
search.

# v0.2

Fixed Windows (PR by @iquiw).

Added the ability to show lines of context around search results.

# v0.1

Initial release.
