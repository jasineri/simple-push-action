# Simple git push action
Commit & push your GitHub action's output into your repository

This action makes pushing to GitHub as simple as possible

## Usage:
    - uses: actions/checkout@v2

    ## Your action work here...

    - uses: jasineri/simple-push-action@v1
      with:
        # Files pattern to add, wildcards supported
        # Optional, default: ./*.*
        file_pattern: ./*.html