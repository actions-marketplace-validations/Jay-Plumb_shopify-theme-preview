# shopify-theme-preview

Creates/Updates a Shopify theme to the respective tore and adds the preview link within the PR description and also as a comment.

The workflow is triggered when a Pull Request is both opened and any additional commits are made to the branch.

## Setup

| Secret                  | Description                                          |
| ----------------------- | ---------------------------------------------------- |
| SHOPIFY_FLAG_STORE      | The Shopify store URL e.g. store-name.myshopify.com  |
| SHOPIFY_CLI_THEME_TOKEN | The Shopify CLI theme token created via a custom app |

## Existing Functionality Callouts

> Currently, there is no support if you have a build step locally prior to shopify theme creation. If this would be of interest, open up a feature request.
