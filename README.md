# Magento 2 Composer Patches

Patches to be applied by https://github.com/cweagans/composer-patches

Full example:

```
{
    "extra": {
        "magento-force": "override",
        "patches": {
            "magento/framework-message-queue": {
                "Fix Consumer Transactions Callbacks": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Message-Queue-Consumer-Transaction.patch"
            },
            "amasty/module-improved-layered-navigation-root": {
                "Fix: Remove unnecessary configurable block": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty-ImprovedLayeredNavigationRoot-M2.1.4-block-configurable.patch"
            },
            "magento/framework": {
                "Pull request: https://github.com/magento/magento2/pull/13577": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-mview-changelog-increment.patch",
                "Fix: https://github.com/magento/magento2/issues/9020": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.1.x-Search-Adapter-Mysql-Mapper-fix-order.patch"
            },
            "magento/magento2-base": {
                "Fix MAGE_DIRS for CLI": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-cli.patch",
                "Fix FotoramaJS for single frame": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-FotoramaJS-M2.1.0-enable-single-frame.patch",
                "Fix: cache clean after di compile": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-setup-upgrade.patch",
                "Fix: https://github.com/magento/magento2/issues/4232": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.1.0-widgets-values-utf8-decode.patch",
                "Fix: https://github.com/magento/magento2/issues/5808": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.1.0-catalog-gallery-allowfullscreen-false.patch",
                "Fix: https://github.com/magento/magento2/issues/4305": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.1.0-errors-apply-skin-fix.patch"
            },
            "magento/module-catalog": {
                "Fix: https://github.com/magento/magento2/issues/8018": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.3-category-indexer-range.patch",
                "Fix: Product auto enable on REST API update": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-rest-api-auto-enable-product-fix.patch",
                "Fix: Set default website insteed of admin on REST API create product": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-rest-api-single-store-fix.patch",
                "Fix: https://github.com/magento/magento2/issues/5438": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.0-image-attribute-backend-model-hardcoded-attribute-code-removal.patch",
                "Fix: catalog_product_flat does not update column with empty value. Fix options linking.": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.4-product-flat-indexer-v2.patch",
                "Fix: https://github.com/magento/magento2/issues/4387": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1-fix-product-auto-startdates.patch",
                "Fix: https://github.com/magento/magento2/issues/7874": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.4-regeneration-without-changes-fix.patch"
            },
            "magento/module-catalog-inventory": {
                "Fix: https://github.com/magento/magento2/issues/8566": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogInventory_M2.1.3-hide-out-of-stock.patch"
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
            "magento/module-configurable-product": {
                "https://github.com/magento/magento2/issues/7441": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_ConfigurableProduct-M2.1.2-configurable-options-sort.patch",
                "Pull request: https://github.com/magento/magento2/pull/9796": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Configurable-M2.1.3-lowest-price-provider.patch",
                "Pull request: https://github.com/magento/magento2/pull/9796": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Configurable-M2.1.6-lowest-price-provider.patch"
            },
            "magento/module-cron": {
                "Fix: https://github.com/magento/magento2/issues/4173": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Cron-M2.1.4-cron-generate-schedule.patch"
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
            "magento/module-sales-rule": {
                "Fix: https://github.com/magento/magento2/issues/6762": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_SalesRule-M2.1.6-fix-to-date-parameter.patch"
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
                "Fix: https://github.com/magento/magento2/issues/11825": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Wishlist-M2.x.x-add-to-wishlist-login-register.patch"
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
                "Fix: Reset broken shipping address in quote": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Quote-M2.1.x-reset-broken-shipping-address.patch"
            }
        }
    }
}
```
