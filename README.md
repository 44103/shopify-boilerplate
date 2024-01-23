# Shopify Environment

## Steps

1. Connect services between Shopify CLI and Develop Store
   ```sh
   shopify theme list --store <store-name>.myshopify.com
   // login
   curl http://127.0.0.1:3456/?code=xxxxx&state=xxxxx
   ```
1. Pull Themes
   ```sh
   mkdir <theme-name>
   cd <theme-name>
   shopify theme pull
   // or
   shopify theme pull -t <theme-id>
   ```
1. Preview Theme
   ```sh
   shopify theme dev
   ```

## References

- https://community.shopify.com/c/shopify-apps/shopify-cli-yarn-dev-auth-failed-under-docker/m-p/2095069
- https://www.non-standardworld.co.jp/26433/
- https://www.non-standardworld.co.jp/26444/
- https://www.non-standardworld.co.jp/26453/
