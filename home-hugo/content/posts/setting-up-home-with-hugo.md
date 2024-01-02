+++
title = 'Setting Up Home With Hugo'
date = 2024-01-02T12:12:18-06:00
+++

# Captain's Log

## Cleared the path for moving to Hugo

1. Basically just wiped out all the files in a new branch, `draft`.

## Followed the getting started tutorial

1. Instructions as seen at http://web.archive.org/web/20231230084934/https://gohugo.io/getting-started/quick-start/
  1. With some modifications:
    1. `hugo new site home-hugo`
    1. `hugo new content posts/setting-up-home-with-hugo.md` (This doc)

## Publishing

1. Configured `publishDir = '..'` to publish static content to the root directory
1. ran `hugo` and pushed.
1. From the project root you can do something like `(cd home-hugo/; hugo)`
