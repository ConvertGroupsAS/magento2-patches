# New Document
# Magento 2 Composer Patches

Patches to be applied by https://github.com/cweagans/composer-patches

**Module**|**Name**|**Fixes**|**Affected versions**
:-----:|:-----:|:-----:|:-----:
magento/magento2-base|Patch-Magento\_Base-cli.patch Patch-Magento\_Base-M2.2.x-cli.patch| |< 2.2.0 >=2.2.0
magento/framework|Patch-Magento\_Framework-mview-changelog-increment.patch|pull 13577|2.1-2.3
magento/framework|Patch-Magento\_Framework-M2.1.x-Search-Adapter-Mysql-Mapper-fix-order.patch|#9020|<2.2.0
magento/framework|Patch-Magento\_Framework-customer-grid.patch|#10838|2.2 (probably all)
magento/framework|Patch-Magento\_Framework-M2.2-cron-prevent-already-running.patch (install all 3 patches *-prevent-already-running)|pull #12497|2.2
magento/framework|Patch-Magento\_Framework-M2.2.x-fix-sessions.patch|Pull #2226|>=2.2.0 (2.2.2, 2.2.3 n/a)
magento/framework|Patch-Magento\_Framework-M2.2.5-force-unset-translation.patch| |>=2.2.5
magento/framework|Patch-Magento\_Framework-M2.2.x-drop-session-fix.patch"|#12362| >= 2.2.0 < 2.2.6
magento/framework|Patch-Magento\_Framework-M2.1.x-Curl-Post-Json.patch|#8373|< 2.2.0
magento/framework-message-queue|Patch-Message-Queue-Consumer-Transaction.patch| |EE Only < 2.2.0
magento/magento2-base|Patch-Magento\_Base-M2.1.0-widgets-values-utf8-decode.patch|#4232|< 2.1.8 (2.1.4 n/a)
magento/magento2-base|Patch-Magento\_Base-M2.2-cron-prevent-already-running.patch (install all 3 patches *-prevent-already-running)|pull #12497|2.2
magento/module-cms-url-rewrite|Patch-M2.2-Magento\_CmsUrlRewrite-global-rewrite-delete.patch|pull 14751|>= 2.2.0
magento/module-cron|Patch-Magento\_Cron-M2.1.4-cron-generate-schedule.patch|#4173|all as of 2.1.7 < 2.2.0
magento/module-cron|Patch-Magento\_Cron-M2.2.0-2.2.3-prevent-already-running-v2.patch Patch-Magento\_Cron-M2.2.4-prevent-already-running-v2.patch (install all 3 patches *-prevent-already-running)|pull #12497|2.2.0-2.2.3  2.2.4+
magento/module-directory|Patch-Magento\_Directory\_M2.1-zip-codes.patch|#6694|2.0.11+ < 2.2.0
magento/module-email|Patch-Magento\_Email-M2.1.0-create-email-logo-1.patch| |< 2.1.8 (2.1.4 n/a)
magento/module-review|Patch-Magento\_Review-M2.2-review-renderer-module-namespace.patch| |all as of 2.2.5
magento/module-theme|Patch-Magento\_Email-M2.1.0-create-email-logo-2.patch| |< 2.1.8 (2.1.4 n/a)
magento/magento2-base|Patch-Magento-FotoramaJS-M2.1.0-enable-single-frame.patch| |>= 2.1.0 >= 2.2.0
magento/module-page-cache|Patch-Magento\_PageCache-M2.1.0-element-js-error-fix.patch|#6818|< 2.1.10 < 2.2.0
magento/module-ui|Patch-Magento\_Ui-M2.1.0-allow-backend-to-know-the-origin-input-of-the-upload-request.patch|#5438|< 2.1.8 (2.1.4 n/a)
magento/module-widget|Patch-Magento\_Widget-M2.1.0-widgets-restore-conditions.patch|#2913|< 2.1.9 (2.1.4 n/a)
magento/magento2-base|Patch-Magento\_Base-setup-upgrade.patch| |>= 2.1.0 >= 2.2.0
magento/module-cms|Patch-Magento\_Cms-page-layout-handles.patch|#9247|< 2.2.0
magento/module-tax|Patch-Magento-Tax-M2.1.0-free-shipping-availability-on-backend.patch|?|>=2.1.4 >=2.2.0
magento/module-tax|Patch-Magento\_Tax-M2.X.X-sequence-fix.patch| |< 2.2.0
magento/module-quote|Patch-Magento\_Quote-M2.2.0-2.2.3-totals-extension-attributes.patch|#12819|2.2.0-2.2.3
magento/magento2-base|Patch-Magento\_Base-M2.1.0-catalog-gallery-allowfullscreen-false.patch|#5808|< 2.2.0
magento/magento2-base|Patch-Magento\_Base-M2.1.0-errors-apply-skin-fix.patch|#4305|< 2.2.0
magento/magento2-base|Patch-Magento\_Base-2.2.x-fotorama-ios.patch|#13226|>=2.2.0 < 2.3.0
magento/module-sales-rule|Patch-Magento\_SalesRule-M2.1.6-fix-to-date-parameter.patch|#6762|< 2.2.0
magento/module-google-tag-manager|Patch\_Magento\_GoogleTagManager\_M2.1.0-fix-empty-product-list-block.patch| |EE Only
magento/module-customer|Patch-Magento\_Customer-M2.1.9-array-street-line.patch (Patch-Magento\_Customer-array-street-line.patch)Patch-Webshipr\_Shipping-get-shipping-address-fix.patch|pull #10582 2.1.9 - error saving shipping address in checkout|>= 2.1.9 < 2.2.2
magento/module-customer|Patch-Magento\_Customer-M2.1.9-generate-new-formkey-wishlist.patch|#11825|>=2.1.9 >=2.2.0 <2.2.4(maybe)
magento/module-wishlist|Patch-Magento\_Wishlist-M2.x.x-add-to-wishlist-login-register.patch|#11825|>=2.1.9 >=2.2.0 <2.2.4(maybe)
magento/module-wishlist|Patch-Magento\_Wishlist-M2.x.x-wishlist-keep-item-in-cart.patch| |\>=2.1.0
magento/module-ui|Patch-Magento\_Ui-M2.1.9-country-select-extra-empty-option.patch|2.1.9 buggy implementation link|>= 2.1.9 <2.2.0 ???
magento/module-ui|Patch-Magento\_Ui-M2.1.x-layout-cache-empty-menu.patch|#8554|< 2.2.0
magento/module-catalog|Patch-Magento\_Catalog-rest-api-auto-enable-product-fix.patch| |< 2.2.0 all as of 2.1.9
magento/module-catalog|Patch-Magento\_Catalog-rest-api-single-store-fix.patch| |>= 2.1.0 >= 2.2.0
magento/module-catalog|Patch-Magento\_Catalog-M2.1-fix-product-auto-startdates.patch|#4387|< 2.1.10 < 2.2.0
magento/module-catalog|Patch-Magento\_Catalog-M2.1.4-regeneration-without-changes-fix.patch (install 2 patches *-regeneration-without-changes-fix)|#7874|>=2.1.4 < 2.1.9
magento/module-catalog|Patch-Magento-Catalog-M2.1.x-toolbar-default-sorting.patch|fix toolbar default sorting|>=2.1.0 <2.2.0
magento/module-catalog|Patch-Magento\_Catalog-M2.1.4-product-flat-indexer.patch|?|>= 2.1.0
magento/module-catalog|Patch-Magento\_Catalog-M2.1.0-image-attribute-backend-model-hardcoded-attribute-code-removal.patch|#5438|< 2.1.8 (2.1.4 n/a)
magento/module-catalog|Patch-Magento\_Catalog-M2.1.3-category-indexer-range.patch|#8018|>= 2.1.0 >= 2.2.0
magento/module-catalog-inventory|Patch-Magento\_CatalogInventory\_M2.1.3-hide-out-of-stock.patch|#8566|>=2.1.0 < 2.2.0
magento/module-catalog-inventory|Patch-Magento\_CatalogInventory-M2.1.x-stock-item-events-fix.patch|#4857|<2.2.0
magento/module-catalog-inventory|Patch-Magento_CatalogInventory-M2.2.0-2.2.3-fix-update-stock-item-on-product-save.patch|Fix: Update stock item on product save|>=2.2.0 <2.2.4
magento/module-catalog-rule|Patch-Magento-Catalog-Rule-M2.1.X-cron-job.patch|Q-67970|>= 2.1.0 >= 2.2.0
magento/module-catalog-url-rewrite|Patch-Magento\_CatalogUrlRewrite-M2.1.4-regeneration-without-changes-fix.patch (install 2 patches *-regeneration-without-changes-fix)|#7874|>=2.1.4 < 2.1.9
magento/module-catalog-widget|Patch-Magento\_CatalogWidget-M2.1.0-widgets-restore-conditions.patch|#2913|< 2.1.8 (2.1.4 n/a)
magento/module-swatches|Patch-Magento\_Swatches-rest-api-visual-swatches-fix.patch| |>= 2.1.4
magento/module-swatches|Patch-Magento\_Swatches-M2.1.x-zero-value-attribute-options-fix.patch|#10266|<= 2.1.10
magento/module-sales|Patch-Magento\_Sales-creditmemo-partial-tax-refund.patch|#10982|2.1-2.3
magento/module-store|Patch-Magento\_Store-emulation.patch|MAGETWO-59649|2.1-2.3
magento/module-developer|Patch-Magento\_Developer-M2.1.x-disable-debug-loging.patch|#4362|< 2.2.3 < 2.2.0 ???
magento/module-checkout|Patch-Magento\_Checkout-cart-form-key.patch|disable form key validation|>= 2.1.0 >= 2.2.0
magento/module-checkout|Patch-Magento\_Framework-M2.2.x-drop-session-fix.patch|#12362| >= 2.2.0 < 2.2.6
magento/module-checkout|Patch-Magento\_Framework-M2.2.6-drop-session-fix.patch|#12362| 2.2.6
magento/module-configurable-product|Patch-Magento\_ConfigurableProduct-M2.1.2-configurable-options-sort.patch|#7441|2.1.x
magento/module-configurable-product|Patch-Magento\_Configurable-M2.1.3-lowest-price-provider.patch Patch-Magento\_Configurable-M2.1.6-lowest-price-provider.patch|#13933  #9796|<= 2.1.5  < 2.2.0
magento/module-configurable-product|Patch-Magento\_ConfigurableProduct-M2.2.x-fix-empty-price-in-category-page.patch|On development stage|>=2.2.1
magento/module-configurable-product|Patch-Magento_ConfigurableProduct-M2.2.x-fix-min-max-prices.patch|#15654|>=2.2.0 <2.3.0
magento/module-configurable-product|Patch-Magento_Configurable_M2.1.x-fix-get-price.patch|#5519|<2.1.10

**3th party modules:**

**Module**|**Name**|**Fixes**|**Affected versions**
:-----:|:-----:|:-----:|:-----:
amasty/module-improved-layered-navigation-root|Patch-Amasty-ImprovedLayeredNavigationRoot-M2.1.4-block-configurable.patch| |all as of 1.15.1
amasty/module-shop-by-brand|Patch-Amasty_ShopbyBrand-2.6.x-missing-option-error-fix.patch|  | \>=2.6.0 < 2.6.5
amasty/shopby-root|Patch-Amasty_ShopbyRoot-2.5.3-fix-broken-filters.patch| | 2.5.3
klarna/module-kco|Patch-Klarna_Kco-5.0.5-reload-summary-action-error-log.patch|Fix wrong function parameters order|>=5.0.5


Full composer.json example:

```
{
    "extra": {
        "magento-force": "override",
        "patches": {
            "amasty/module-improved-layered-navigation-root": {
                "Fix: Remove unnecessary configurable block": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty-ImprovedLayeredNavigationRoot-M2.1.4-block-configurable.patch"
            },
            "amasty/shopby-seo": {
                "Fix: Broken product links in cart on different stores": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_ShopbySeo-cart-broken-links-fix.patch"
            },
            "amasty/module-shop-by-brand": {
                 "Fix error when option was removed from attribute": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_ShopbyBrand-2.6.x-missing-option-error-fix.patch"
            },
            "amasty/shopby-root": {
                 "Fix filters exception on category page": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_ShopbyRoot-2.5.3-fix-broken-filters.patch"
            },
            "magento/framework-message-queue": {
                "Fix Consumer Transactions Callbacks": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Message-Queue-Consumer-Transaction.patch"
            },
            "magento/framework": {
                "Pull request: https://github.com/magento/magento2/pull/13577": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-mview-changelog-increment.patch",
                "Fix: https://github.com/magento/magento2/issues/9020": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.1.x-Search-Adapter-Mysql-Mapper-fix-order.patch",
                "Fix: https://github.com/magento/magento2/issues/10838": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-customer-grid.patch",
                "Pull request: https://github.com/magento/magento2/pull/2226": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.2.x-fix-sessions.patch",
                "Pull request: https://github.com/magento/magento2/pull/8373": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.1.x-Curl-Post-Json.patch",
                "Pull request: https://github.com/magento/magento2/pull/12497": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.2-cron-prevent-already-running.patch",
                "Fix: Unset translations for same key-value only if given force parameter": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.2.5-force-unset-translation.patch",
                "Fix: https://github.com/magento/magento2/issues/12362": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.2.x-drop-session-fix.patch"
            },
            "magento/magento2-base": {
                "Fix MAGE_DIRS for CLI": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-cli.patch",
                "Fix FotoramaJS for single frame": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-FotoramaJS-M2.1.0-enable-single-frame.patch",
                "Fix: cache clean after di compile": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-setup-upgrade.patch",
                "Fix: https://github.com/magento/magento2/issues/4232": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.1.0-widgets-values-utf8-decode.patch",
                "Fix: https://github.com/magento/magento2/issues/5808": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.1.0-catalog-gallery-allowfullscreen-false.patch",
                "Fix: https://github.com/magento/magento2/issues/4305": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.1.0-errors-apply-skin-fix.patch",
                "Fix: https://github.com/magento/magento2/issues/13226": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-2.2.x-fotorama-ios.patch",
                "Pull request: https://github.com/magento/magento2/pull/12497": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.2-cron-prevent-already-running.patch"
            },
            "magento/module-developer": {
                "Fix: https://github.com/magento/magento2/issues/4362": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Developer-M2.1.x-disable-debug-loging.patch"
            },
            "magento/module-catalog": {
                "Fix: https://github.com/magento/magento2/issues/8018": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.3-category-indexer-range.patch",
                "Fix: Product auto enable on REST API update": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-rest-api-auto-enable-product-fix.patch",
                "Fix: Set default website insteed of admin on REST API create product": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-rest-api-single-store-fix.patch",
                "Fix: https://github.com/magento/magento2/issues/5438": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.0-image-attribute-backend-model-hardcoded-attribute-code-removal.patch",
                "Fix: catalog_product_flat does not update column with empty value. Fix options linking.": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.4-product-flat-indexer-v2.patch",
                "Fix: https://github.com/magento/magento2/issues/4387": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1-fix-product-auto-startdates.patch",
                "Fix: https://github.com/magento/magento2/issues/7874": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.4-regeneration-without-changes-fix.patch",
                "Fix: Change toolbar default sorting": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-Catalog-M2.1.x-toolbar-default-sorting.patch"
            },
            "magento/module-catalog-inventory": {
                "Fix: https://github.com/magento/magento2/issues/8566": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogInventory_M2.1.3-hide-out-of-stock.patch",
                "Fix: https://github.com/magento/magento2/issues/4857": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogInventory-M2.1.x-stock-item-events-fix.patch",
                "Fix: Update stock item on product save": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogInventory-M2.2.0-2.2.3-fix-update-stock-item-on-product-save.patch"
            },
            "magento/module-catalog-rule": {
                "Fix: https://magento.stackexchange.com/questions/67970/catalog-price-rules-disappear-after-mid-night": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-Catalog-Rule-M2.1.X-cron-job.patch"
            },
            "magento/module-catalog-widget": {
                "Fix: https://github.com/magento/magento2/issues/2913": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogWidget-M2.1.0-widgets-restore-conditions.patch"
            },
            "magento/module-cms": {
                "Pull request: https://github.com/magento/magento2/pull/9247": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Cms-page-layout-handles.patch"
            },
            "magento/module-cms-url-rewrite": {
                "Pull request: https://github.com/magento/magento2/pull/14751": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-M2.2-Magento_CmsUrlRewrite-global-rewrite-delete.patch"
            },
            "magento/module-configurable-product": {
                "https://github.com/magento/magento2/issues/7441": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_ConfigurableProduct-M2.1.2-configurable-options-sort.patch",
                "Pull request: https://github.com/magento/magento2/pull/9796": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Configurable-M2.1.3-lowest-price-provider.patch",
                "Pull request: https://github.com/magento/magento2/pull/9796": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Configurable-M2.1.6-lowest-price-provider.patch",
                "Fix: https://github.com/magento/magento2/issues/15654": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_ConfigurableProduct-M2.2.x-fix-min-max-prices.patch",
                "Fix: https://github.com/magento/magento2/issues/5519": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Configurable_M2.1.x-fix-get-price.patch"
            },
            "magento/module-cron": {
                "Fix: https://github.com/magento/magento2/issues/4173": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Cron-M2.1.4-cron-generate-schedule.patch",
                "Pull request: https://github.com/magento/magento2/pull/12497": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Cron-M2.2.0-2.2.3-prevent-already-running-v2.patch",
                "Pull request: https://github.com/magento/magento2/pull/12497": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Cron-M2.2.4-prevent-already-running-v2.patch"
            },
            "magento/module-customer": {
                "Fix: https://github.com/magento/magento2/pull/10582": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Customer-M2.1.9-array-street-line.patch",
                "Fix: https://github.com/magento/magento2/issues/11825": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Customer-M2.1.9-generate-new-formkey-wishlist.patch",                
                "Fix: Disable cache for customer section data": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch_Magento_Customer-M2.1.4-customer-section-load-fix.patch"
            },
            "magento/module-directory": {
                "Fix: https://github.com/magento/magento2/issues/6694": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Directory_M2.1-zip-codes.patch"
            },
            "magento/module-email": {
                "https://github.com/magento/magento2/issues/5352": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Email-M2.1.0-create-email-logo-1.patch"
            },
            "magento/module-google-tag-manager": {
                "Fix: Check block before get Product List": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch_Magento_GoogleTagManager_M2.1.0-fix-empty-product-list-block.patch"
            },
            "magento/module-page-cache": {
                "Fix: https://github.com/magento/magento2/issues/6818": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_PageCache-M2.1.0-element-js-error-fix.patch"
            },
            "magento/module-review": {
                "Fix review namespace": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Review-M2.2-review-renderer-module-namespace.patch"
            },
            "magento/module-sales": {
                "Fix: Partial creditmemo tax amount": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Sales-creditmemo-partial-tax-refund.patch"
            },
            "magento/module-sales-rule": {
                "Fix: https://github.com/magento/magento2/issues/6762": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_SalesRule-M2.1.6-fix-to-date-parameter.patch"
            },
            "magento/module-store": {
                "Fix emulation in admin store (Todo check: MAGETWO-59649)": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Store-emulation.patch"
            },
            "magento/module-swatches": {
                "Fix: Add ability to set visual swatch by store ID as well as textual one": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Swatches-rest-api-visual-swatches-fix.patch",
                "Fix: https://github.com/magento/magento2/issues/10266": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Swatches-M2.1.x-zero-value-attribute-options-fix.patch"
            },
            "magento/module-tax": {
                "Fix: https://github.com/magento/magento2/issues/2939": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-Tax-M2.1.0-free-shipping-availability-on-backend.patch",
                "Fix: https://github.com/magento/magento2/issues/7801": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Tax-M2.X.X-sequence-fix.patch"
            },
            "magento/module-theme": {
                "https://github.com/magento/magento2/issues/5352": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Email-M2.1.0-create-email-logo-2.patch"
            },
            "magento/module-ui": {
                "Fix broken by: MAGETWO-57144": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Ui-M2.1.9-country-select-extra-empty-option.patch",
                "Fix: https://github.com/magento/magento2/issues/5438": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Ui-M2.1.0-allow-backend-to-know-the-origin-input-of-the-upload-request.patch",
                "Fix: https://github.com/magento/magento2/issues/6281": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Ui-M2.1.x-multiselect-empty-save.patch",
                "Fix: https://github.com/magento/magento2/issues/8554": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Ui-M2.1.x-layout-cache-empty-menu.patch"
            },
            "magento/module-widget": {
                "Fix: https://github.com/magento/magento2/issues/2913": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Widget-M2.1.0-widgets-restore-conditions.patch"
            },
            "magento/module-wishlist": {
                "Fix: https://github.com/magento/magento2/issues/11825": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Wishlist-M2.x.x-add-to-wishlist-login-register.patch",
                "Add ability to keep item in cart after adding to wishlist": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Wishlist-M2.x.x-wishlist-keep-item-in-cart.patch"
            },
            "magento/module-offline-shipping": {
                "Fix: https://github.com/magento/magento2/issues/10704": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_OfflineShipping-M2.X-free-shipping-cart-rule-fix.patch"
            },
            "magento/module-catalog-url-rewrite": {
                "Fix: https://github.com/magento/magento2/issues/7874 depended on module-catalog patch": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogUrlRewrite-M2.1.4-regeneration-without-changes-fix.patch"
            },
            "mirasvit/module-feed": {
                "Fix: DI compile without DB v2": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Mirasvit_Feed-1.0.60-fix-di-compile-without-db.patch"
            },
            "magento/module-quote": {
                "Fix: Reset broken shipping address in quote": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Quote-M2.1.x-reset-broken-shipping-address.patch",
                "Fix: Broken product links in cart on different stores": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Quote-M2.1.x-cart-product-links-fix.patch",
                "Fix: https://github.com/magento/magento2/issues/12819": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Quote-M2.2.0-2.2.3-totals-extension-attributes.patch"
            },
            "magento/module-checkout": {
                "Fix: addresses from other store on checkout": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-M2.1.x-filter-addresses.patch",
                "Fix: addresses from other store on checkout 2.2+": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-M2.2.x-filter-addresses.patch",
                "Fix: Add to cart form key": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-cart-form-key.patch",
                "Fix: https://github.com/magento/magento2/issues/12362": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.2.x-drop-session-fix.patch"
            },
            "klarna/module-kco": {
                "ReloadSummary action wrong order of parameters": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Klarna_Kco-5.0.5-reload-summary-action-error-log.patch"
            }
        }
    }
}
```
