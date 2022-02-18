# Simple git push action
Push your GitHub action's output into your repository

This action makes pushing to GitHub as simple as possible

## Usage:
    - uses: jasineri/simple-push-action@v1
      with:
        # Files pattern to add, wildcards supported
        # Optional, default: ./*.*
        file_pattern: *.html