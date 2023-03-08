# Simple git push action
Commit & push your GitHub action's output into your repository

This action makes pushing to GitHub as simple as possible

## Usage:
    - uses: actions/checkout@v2

    ## Your action work here...

    - uses: jasineri/simple-push-action@v2
      with:
         # Optional, Repository name with owner. For example, actions/checkout, default: ${{ github.repository }}
         # repository: ${{ github.repository  }}

         # Optional, Personal access token (PAT) used to push the repository, default: github.token
         # token: ${{ github.token }}

         # Optional, Ralative path under $GITHUB_WORKSPACE to the repository, default: . (current dir)
         # path: .

         # Optional, Commit message, default: 'Update from Github Action at `date`'
         # message: 'Update from Github Action at `date`'

         # Optional, Files pattern to add, wildcards supported, default: ./*.*
         file_pattern: ./*.html