# New Document
# Magento 2 Composer Patches

Patches to be applied by https://github.com/cweagans/composer-patches

**Module**|**Name**|**Fixes**|**Affected versions**
:-----:|:-----:|:-----:|:-----:
magento/magento2-base|Patch-Magento\_Base-cli.patch Patch-Magento\_Base-M2.2.x-cli.patch| |< 2.2.0 >=2.2.0
magento/magento2-base|Patch-Magento\_Base-M2.1.0-widgets-values-utf8-decode.patch|[#4232](https://github.com/magento/magento2/issues/4232)|< 2.1.8 (2.1.4 n/a)
magento/magento2-base|Patch-Magento\_Base-M2.2-cron-prevent-already-running.patch (install all 3 patches *-prevent-already-running)|[PR  #12497](https://github.com/magento/magento2/pull/12497)|2.2 < 2.2.6
magento/magento2-base|Patch-Magento\_Base-M2.x.x-zoomed-photo-product.patch |MAGETWO-94989| < 2.1-2.3
magento/magento2-base|Patch-Magento\_Base-M2.2.5-mangnifier-zoom-distortion.patch | | > 2.2.5
magento/magento2-base|Path-Magento\_Base-tests-cookie-and-session-add-to-return-null-value.patch| | >= 2.3.0
magento/magento2-base|Patch-Magento-FotoramaJS-M2.1.0-enable-single-frame.patch| |>= 2.1.0 >= 2.2.0
magento/magento2-base|Patch-Magento-FotoramaJS-M2.1.0-enable-single-frame_M2.2.6.patch| |>= 2.1.0 >= 2.2.6
magento/magento2-base|Patch-Magento\_Base-setup-upgrade.patch| |>= 2.1.0 >= 2.2.0
magento/magento2-base|Patch-Magento\_Base-M2.1.0-catalog-gallery-allowfullscreen-false.patch|[#5808](https://github.com/magento/magento2/issues/5808)|< 2.2.0
magento/magento2-base|Patch-Magento\_Base-M2.1.0-errors-apply-skin-fix.patch|[#4305](https://github.com/magento/magento2/issues/4305)|< 2.2.0
magento/magento2-base|Patch-Magento\_Base-2.2.x-fotorama-ios.patch|[#13226](https://github.com/magento/magento2/issues/13226)|>=2.2.0 < 2.3.0
magento/magento2-base|Patch-Magento_Base-M2.3-remove-php-memory-limit.patch| |>=2.3.0
magento/magento2-base|Patch-Magento_Base-test-graphql-application.patch|Running GraphQl API functional tests|
magento/magento2-base|Patch-Magento_Base-deploy-test-modules.patch|Deploy test modules - Convert|
magento/magento2-base|Patch-Magento_Base_2.4.5_jquery_cookies_issue.patch|Fix magento theme jquery cookie issue|
magento/framework|Patch-Magento\_Framework-mview-changelog-increment.patch|[PR #13577](https://github.com/magento/magento2/pull/13577)|2.1-2.3
magento/framework|Patch-Magento\_Framework-M2.1.x-Search-Adapter-Mysql-Mapper-fix-order.patch|[#9020](https://github.com/magento/magento2/issues/9020)|<2.2.0
magento/framework|Patch-Magento\_Framework-customer-grid.patch|[#10838](https://github.com/magento/magento2/issues/10838)|2.2 (probably all)
magento/framework|Patch-Magento\_Framework-M2.2-cron-prevent-already-running.patch (install all 3 patches *-prevent-already-running)|[PR  #12497](https://github.com/magento/magento2/pull/12497)|2.2
magento/framework|Patch-Magento\_Framework-M2.2.x-fix-sessions.patch|[PR #2226](https://github.com/magento/magento2/pull/2226)|>=2.2.0 (2.2.2, 2.2.3 n/a)
magento/framework|Patch-Magento\_Framework-M2.2.5-force-unset-translation.patch| |>=2.2.5
magento/framework|Patch-Magento\_Framework-M2.2.x-drop-session-fix.patch"|[#12362](https://github.com/magento/magento2/issues/12362)| >= 2.2.0 < 2.2.6
magento/framework|Patch-Magento\_Framework-M2.1.x-Curl-Post-Json.patch|[PR #8373](https://github.com/magento/magento2/pull/8373)|< 2.2.0
magento/framework|Patch-Magento\_Framework-M2.2.x-PRODSECBUG-2198.patch| |< 2.2.8
magento/framework|Patch-Magento\_Framework-M2.3.1-fix-elasticsearch-generation.patch| |>= 2.3.1 < 2.3.2
magento/framework|Patch-Magento\_Framework-M2.2.6-Fix-session-from-2.2.7.patch|[#12362](https://github.com/magento/magento2/issues/12362)| 2.2.6
magento/framework|Patch-Magento\_Framework-result-page.patch|Allow to add body class while block render|
magento/framework|Patch-Magento\_Framework-M2.4.x-performance-graphql-schema-parsing-fix.patch|[PR #31879](https://github.com/magento/magento2/pull/31879)|
magento/framework|Patch-Magento\_Patch-Magento_framework-M2.3.3-M2.4.3-security|(https://helpx.adobe.com/security/products/magento/apsb22-12.html)|>= 2.2.8 <=2.3.2
magento/framework|Patch-Magento\_Patch-Magento_framework-M2.3.4-p1-M2.4.2-p1-security|(https://helpx.adobe.com/security/products/magento/apsb22-12.html)|>= 2.3.4-p1 <=2.4.2-p1
magento/framework|Patch-Magento\_Patch-Magento_framework-M2.4.3-p1-security|(https://helpx.adobe.com/security/products/magento/apsb22-12.html)|>= 2.4.3-p1
magento/framework|Magento_Framework-verbose-logs.patch|Remove verbose logs|
magento/framework-message-queue|Patch-Message-Queue-Consumer-Transaction.patch| |EE Only < 2.2.0
magento/module-cms-url-rewrite|Patch-M2.2-Magento\_CmsUrlRewrite-global-rewrite-delete.patch|[PR #14751](https://github.com/magento/magento2/pull/14751)|>= 2.2.0 < 2.2.5
magento/module-cron|Patch-Magento\_Cron-M2.1.4-cron-generate-schedule.patch|[#4173](https://github.com/magento/magento2/issues/4173)|all as of 2.1.7 < 2.2.0
magento/module-cron|Patch-Magento\_Cron-M2.2.0-2.2.3-prevent-already-running-v2.patch Patch-Magento\_Cron-M2.2.4-prevent-already-running-v2.patch (install all 3 patches *-prevent-already-running)|[PR #12497](https://github.com/magento/magento2/pull/12497)|2.2.0-2.2.4 < 2.2.6
magento/module-cron|Magento_Cron-verbose-logs.patch|Remove verbose logs|
magento/module-directory|Patch-Magento\_Directory\_M2.1-zip-codes.patch|[#6694](https://github.com/magento/magento2/issues/6694)|2.0.11+ < 2.2.0
magento/module-eav|Patch-Magento\_Eav-M2.3-api-product-multiselect.patch|[PR #21901](https://github.com/magento/magento2/pull/21901)|>= 2.3.0
magento/module-email|Patch-Magento\_Email-M2.1.0-create-email-logo-1.patch| |< 2.1.8 (2.1.4 n/a)
magento/module-email|Patch-Magento\_Email-M2.2.x-cant-update-logo.patch|[PR #15137](https://github.com/magento/magento2/pull/15137) |< 2.2.6 (2.2.4 n/a)
magento/module-email|Patch-Magento\_Email-M2.2.8-2.3.2-No-Sid-In-Messages.patch| |>= 2.2.8 <=2.3.2
magento/module-email|Patch-Magento\_Patch-Magento_email-M2.3.3-M2.4.3-security| (https://helpx.adobe.com/security/products/magento/apsb22-12.html) |>= 2.3.3 <=2.4.3
magento/module-email|Patch-Magento\_Patch-Magento_email-M2.3.3-p1-M2.3.4-p1-security| (https://helpx.adobe.com/security/products/magento/apsb22-12.html) |>= 2.3.3-p1 <= 2.3.4-p1
magento/module-email|Patch-Magento\_Patch-Magento_email-M2.3.4-p2-M2.4.2-p1-security| (https://helpx.adobe.com/security/products/magento/apsb22-12.html) |>= 2.3.4-p2 <= 2.4.2-p1
magento/module-email|Patch-Magento\_Patch-Magento_email-M2.4.3-p1-M2.4.3-security| (https://helpx.adobe.com/security/products/magento/apsb22-12.html) |>= 2.4.3-p1
magento/module-elasticsearch|Patch-Magento_Elasticsearch-M2.2-total-fields-limit-10000.patch|Increase default fields limit|>= 2.2.0
magento/module-elasticsearch|Patch-Magento\_Elasticsearch-M2.3.x-Send-Error-Message.patch| |>= 2.3.0
magento/module-elasticsearch|Patch-Magento\_Elasticsearch-M2.3.0-M2.3.1-prices-pass-website-id.patch| |>= 2.3.0 <= 2.3.1
magento/module-elasticsearch|Patch-Magento_Elasticsearch-M2.3-attribute-options-optimization.patch|Attribute Options Optimization|>= 2.3.0
magento/module-elasticsearch-7|Patch-Magento_Elasticsearch7-disable-full-page-cache-show-error.patch|Elasticsearch error returns 503 code and message|\>= 2.3.5
magento/module-elasticsearch|Patch-Magento_Elasticsearch-2.4.5-adjust.patch|Adjust to PHP8.1 and Magento2.4.5|
magento/module-indexer|Patch-Magento_Indexer-M2.3.1-indexer-reindex-optional-dependencies.patch|indexer:reindex command - Optional dependencies|\>= 2.3.1
magento/module-review|Patch-Magento\_Review-M2.2-review-renderer-module-namespace.patch| |all as of 2.2.5
magento/module-review|Patch-Magento_Review-M2.3-observer-catalog-check-is-active.patch|Fix: Product Collection Observer - Check module status|
magento/module-theme|Patch-Magento\_Email-M2.1.0-create-email-logo-2.patch| |< 2.1.8 (2.1.4 n/a)
magento/module-theme|Patch-Magento_Theme_jquery_cookies_issue.patch|Fix magento theme jquery cookie issue|
magento/module-page-cache|Patch-Magento\_PageCache-M2.1.0-element-js-error-fix.patch|[#6818](https://github.com/magento/magento2/issues/6818)|< 2.1.10 < 2.2.0
magento/module-widget|Patch-Magento\_Widget-M2.1.0-widgets-restore-conditions.patch|[#2913](https://github.com/magento/magento2/issues/2913)|< 2.1.9 (2.1.4 n/a)
magento/module-cms|Patch-Magento\_Cms-page-layout-handles.patch|[PR #9247](https://github.com/magento/magento2/pull/9247)|< 2.2.0
magento/module-tax|Patch-Magento-Tax-M2.1.0-free-shipping-availability-on-backend.patch|?|>=2.1.4 >=2.2.0
magento/module-tax|Patch-Magento\_Tax-M2.X.X-sequence-fix.patch| |< 2.2.0
magento/module-quote|Patch-Magento\_Quote-M2.2.0-2.2.3-totals-extension-attributes.patch|[#12819](https://github.com/magento/magento2/issues/12819)|2.2.0-2.2.3
magento/module-sales-rule|Patch-Magento\_SalesRule-M2.1.6-fix-to-date-parameter.patch|[#6762](https://github.com/magento/magento2/issues/6762)|< 2.2.0
magento/module-sales-rule|Patch-Magento\_SalesRule-M2.4.3-fix-discount-amount.patch|[#30719](https://github.com/magento/magento2/issues/30719)| 2.4.3
magento/module-google-tag-manager|Patch\_Magento\_GoogleTagManager\_M2.1.0-fix-empty-product-list-block.patch| |EE Only
magento/module-customer|Patch-Magento\_Customer-M2.1.9-array-street-line.patch (Patch-Magento\_Customer-array-street-line.patch)Patch-Webshipr\_Shipping-get-shipping-address-fix.patch|[PR #10582](https://github.com/magento/magento2/pull/10582)|>= 2.1.9 < 2.2.2
magento/module-customer|Patch-Magento\_Customer-M2.1.9-generate-new-formkey-wishlist.patch|[#11825](https://github.com/magento/magento2/issues/11825)|>=2.1.9 >=2.2.0 <2.2.4(maybe)
magento/module-customer|Patch-Magento\_Customer-M2.4.1-context-customer-group-id-fix.patch||>=2.4.1 <2.4.3(maybe)
magento/module-customer|Patch-Magento\_Customer-M2.4.x-errors-in-customer-data-component-not-initialized-fix.patch|[PR #31940](https://github.com/magento/magento2/pull/31940)|>=2.4.0 <=2.4.3
magento/module-customer-graph-ql|Patch-Magento\_CustomerGraphQl-M2.4.1-context-customer-group-id-fix.patch||>=2.4.1 <2.4.3(maybe)
magento/module-customer-graph-ql|Patch-Magento-CustomerGraphQl-exception-category.patch|Return GraphQl exception category|
magento/module-wishlist|Patch-Magento\_Wishlist-M2.x.x-add-to-wishlist-login-register.patch|[#11825](https://github.com/magento/magento2/issues/11825)|>=2.1.9 >=2.2.0 <2.2.4(maybe)
magento/module-wishlist|Patch-Magento\_Wishlist-M2.x.x-wishlist-keep-item-in-cart.patch| |\>=2.1.0
magento/module-wishlist|Patch-Magento\_Wishlist_M2.x.x-failed-login-attempts.patch| |\>=2.2.* 2.3.*
magento/module-multiple-wishlist|Patch-Magento-multiple-wishlist-Not-existing-products.patch|Fix Magento wishlist bug in Admin reports|
magento/module-ui|Patch-Magento\_Ui-M2.1.0-allow-backend-to-know-the-origin-input-of-the-upload-request.patch|[#5438](https://github.com/magento/magento2/issues/5438)|< 2.1.8 (2.1.4 n/a)
magento/module-ui|Patch-Magento\_Ui-M2.1.9-country-select-extra-empty-option.patch|2.1.9 buggy implementation link|>= 2.1.9 <2.2.0 ???
magento/module-ui|Patch-Magento\_Ui-M2.1.x-layout-cache-empty-menu.patch|[#8554](https://github.com/magento/magento2/issues/8554)|< 2.2.0
magento/module-ui|Patch-Magento\_Ui-M2.2.x-invalid-date-range-fix.patch|[#16119](https://github.com/magento/magento2/issues/16119)|< 2.3.0
magento/module-ui|Patch-Magento-Ui_fix-reset-disabled-attributes.patch| |< 2.2.5
magento/module-catalog|Patch-Magento\_Catalog-rest-api-auto-enable-product-fix.patch| |< 2.2.0 all as of 2.1.9
magento/module-catalog|Patch-Magento\_Catalog-rest-api-single-store-fix.patch| |>= 2.1.0 >= 2.2.0 < 2.2.6
magento/module-catalog|Patch-Magento\_Catalog-M2.1-fix-product-auto-startdates.patch|[#4387](https://github.com/magento/magento2/issues/4387)|< 2.1.10 < 2.2.0
magento/module-catalog|Patch-Magento\_Catalog-M2.1.4-regeneration-without-changes-fix.patch (install 2 patches *-regeneration-without-changes-fix)|[#7874](https://github.com/magento/magento2/issues/7874)|>=2.1.4 < 2.1.9
magento/module-catalog|Patch-Magento-Catalog-M2.1.x-toolbar-default-sorting.patch|fix toolbar default sorting|>=2.1.0 <2.2.0
magento/module-catalog|Patch-Magento\_Catalog-M2.1.4-product-flat-indexer.patch|?|>= 2.1.0
magento/module-catalog|Patch-Magento\_Catalog-M2.1.0-image-attribute-backend-model-hardcoded-attribute-code-removal.patch|[#5438](https://github.com/magento/magento2/issues/5438)|< 2.1.8 (2.1.4 n/a)
magento/module-catalog|Patch-Magento\_Catalog-M2.1.3-category-indexer-range.patch|[#8018](https://github.com/magento/magento2/issues/8018)|>= 2.1.0 >= 2.2.0
magento/module-catalog|Patch-Magento\_Catalog-M2.2.x-related-products-visibility-in-admin.patch|[#13720](https://github.com/magento/magento2/issues/13720)|>= 2.2.1 >= 2.3.0
magento/module-catalog|Patch-Magento\_Catalog-M2.2.x-PRODSECBUG-2198.patch| |< 2.2.8
magento/module-catalog|Patch-Magento\_Catalog-improve-root-category-indexer-2.2.8.patch| | > 2.2.8
magento/module-catalog|Patch-Magento\_Catalog-M2.2.x-skip-empty-custom-options-skus.patch| | 2.2.5
magento/module-catalog|Patch-Magento-Catalog-M2.1.x-2.2.7-fix-save-customizable-options.patch|[PR #16838](https://github.com/magento/magento2/pull/16838)| >= 2.1.* <=2.3.1
magento/module-catalog|Patch-Magento_Catalog-M2.1-flat-availability.patch|Allow to use invalid Flat Indexer| \>= 2.1
magento/module-catalog|Patch-Magento_Catalog-M2.3-category-flat-chunk-limit.patch|Catalog Category Flat chunk limit|
magento/module-catalog|Patch-Magento_Catalog-M2.3-fix-category-image-upload.patch|Fix: Category Image Upload|
magento/module-catalog|Patch-Magento_Catalog-M2.4.2-website-select-processor-fix.patch|Fix: Use Indentifer field for Website processor|>2.1.0
magento/module-catalog|Patch-Magento-Catalog-M2.4.5-fix-for-price-indexer-getting-stuck.patch|Fix: https://github.com/magento/magento2/issues/36471| 2.4.5
magento/module-catalog-graph-ql|Patch-Magento\_CatalogGraphQl-aggregations-sorting-fix.patch|[#30775](https://github.com/magento/magento2/issues/30775)|>=2.3.5 < 2.4.3 (maybe)
magento/module-catalog-graph-ql|Patch-Magento\_CatalogGraphQl-aggregations-category-place-first.patch|Move Category filter on first place||
magento/module-catalog-graph-ql|Patch-Magento\_CatalogGraphQl-aggregations-price-category-translate-lables.patch|Translate Labels for Price and Category Filters||
magento/module-catalog-graph-ql|Patch-Magento_CatalogGraphQl-M2.4.x-special-price-from-to-dates.patch|[#29631](https://github.com/magento/magento2/issues/29631)|>2.3.5-p2 < 2.4.3
magento/module-catalog-graph-ql|Patch-Magento_CatalogGraphQl_sort_attributes_reader_fix.patch|Fix sorting attribute reader||>2.3.x
magento/module-catalog-inventory|Patch-Magento\_CatalogInventory\_M2.1.3-hide-out-of-stock.patch|[#8566](https://github.com/magento/magento2/issues/8566)|>=2.1.0 < 2.2.0
magento/module-catalog-inventory|Patch-Magento\_CatalogInventory-M2.1.x-stock-item-events-fix.patch|[#4857](https://github.com/magento/magento2/issues/4857)|<2.2.0
magento/module-catalog-inventory|Patch-Magento_CatalogInventory-M2.2.0-2.2.3-fix-update-stock-item-on-product-save.patch|Fix: Update stock item on product save|>=2.2.0 <2.2.4
magento/module-catalog-inventory|Patch-Magento_CatalogInventory-M2.2.0-2.2.4-stock-index.patch|[#12205](https://github.com/magento/magento2/issues/12205)|>=2.2.0 <2.2.5
magento/module-catalog-inventory|Patch-Magento_CatalogInventory-M2.3.3-2.3.4-fix-stock-indexer-deleting-new-records.patch|[#15984](https://github.com/magento/magento2/issues/15984)|2.3.3-2.3.4
magento/module-catalog-inventory|Patch-Magento_CatalogInventory-M2.2-new-item-use-config-manage-stock.patch|Fix: Use Config Manage Stock in new Stock Item|
magento/module-catalog-inventory|Patch-Magento_CatalogInventory-M2.4.x-invalidate-cache-parent-product-on-stock-update.patch|Fix: Invalidate parent product cache on stock update|
magento/module-inventory-cache|Patch-Magento_InventoryCache-M2.4.5-fix-cache-invalidation.patch|Fix inventory indexer is cleaning all caches in scheduled mode|2.4.5-2.4.6
magento/module-catalog-rule|Patch-Magento-Catalog-Rule-M2.1.X-cron-job.patch|Q-67970|>= 2.1.0 >= 2.2.0
magento/module-catalog-staging|Patch-Magento_Catalog_Staging-timestam.patch| | ?
magento/module-catalog-url-rewrite|Patch-Magento\_CatalogUrlRewrite-M2.1.4-regeneration-without-changes-fix.patch (install 2 patches *-regeneration-without-changes-fix)|[#7874](https://github.com/magento/magento2/issues/7874)|>=2.1.4 < 2.1.9
magento/module-catalog-url-rewrite|Patch-Magento\_CatalogUrlRewrite-update-url-key-for-products.patch|Fix Url rewrite generation in Magento CE||
magento/module-graph-ql|Patch-Magento\_GraphQl-load-translations-for-store-scope-fix.patch|[#31351](https://github.com/magento/magento2/issues/31351)| |
magento/module-webapi|Patch-Magento\_Webapi-M2.3.x-log-exceptions.patch||2.3.*
magento/module-catalog-widget|Patch-Magento\_CatalogWidget-M2.1.0-widgets-restore-conditions.patch|[#2913](https://github.com/magento/magento2/issues/2913)|< 2.1.8 (2.1.4 n/a)
magento/module-swatches|Patch-Magento\_Swatches-rest-api-visual-swatches-fix.patch| |>= 2.1.4
magento/module-swatches|Patch-Magento_Swatches-rest-api-visual-swatches-fix_2.2.6.patch| |>= 2.2.6
magento/module-swatches|Patch-Magento\_Swatches-M2.1.x-zero-value-attribute-options-fix.patch|[#10266](https://github.com/magento/magento2/issues/10266)|<= 2.1.10
magento/module-sales|Patch-Magento\_Sales-creditmemo-partial-tax-refund.patch|[#10982](https://github.com/magento/magento2/issues/10982)|2.1-2.3
magento/module-sales|Patch-Magento_Sales-M2.2-invoice-subtotal-canceled.patch|Canceled amount in Invoice Subtotal|
magento/module-sales|Patch-Magento_Sales-M2.3-invoice-tax-canceled.patch|Canceled amount in Invoice Tax|
magento/module-sales|Patch_Magento_Refund_Invoice_Without_0_Quantities.patch|Refund with 0 qty|< 2.4.2
magento/module-sales|Patch-Magento_Sales-M2.4.2-discount-cart-rule-results-in-tax-invoiced.patch|[#30853](https://github.com/magento/magento2/issues/30853)| >=2.4.0 <2.4.3
magento/module-staging|Patch-Magento_Staging-M2.2-fix-duplicated-rollback.patch||2.2
magento/module-store|Patch-Magento\_Store-emulation.patch|MAGETWO-59649|2.1-2.3
magento/module-developer|Patch-Magento\_Developer-M2.1.x-disable-debug-loging.patch|[#4362](https://github.com/magento/magento2/issues/4362)|< 2.2.3 < 2.2.0 ???
magento/module-checkout|Patch-Magento\_Checkout-cart-form-key.patch|disable form key validation|>= 2.1.0 >= 2.2.0
magento/module-checkout|Patch-Magento\_Checkout-M2.3.x-cart-form-key.patch|disable form key validation|>= 2.3.0
magento/module-checkout|Patch-Magento\_Framework-M2.2.x-drop-session-fix.patch|[#12362](https://github.com/magento/magento2/issues/12362)| >= 2.2.0 < 2.2.6
magento/module-checkout|Patch-Magento\_Checkout-M2.3.3-replace-ES6-code.patch|[#22119](https://github.com/magento/magento2/issues/22119)| >=2.3.0 <2.3.4
magento/module-checkout|Patch-Magento_Checkout-M2.3-billing-same-as-shipping-manually-v2.patch|Don't change checkbox billing-same-as-shipping automatically|
magento/module-checkout|Patch-Magento_Checkout-M2.3.3-place-order-allow-empty-billing.patch|Allow placing order with empty billing address|
magento/module-checkout|Patch-Magento_Checkout-M2.3.3-save-shipping-method-not-found.patch|Don't throw carrier not found error|
magento/module-checkout|Patch-Magento_Checkout-M2.3.x-checkout-login-form.patch|Login form of the checkout page is shown without any associating user account|
magento/module-checkout-staging|Patch-Magento-Checkout-Staging-2.4.4-extension-attributes.patch|Fix fail checking shipping vs billing_address in 2.4.4 when exension attributes are added https://github.com/magento/magento2/issues/34202|2.4.4
magento/module-configurable-product|Patch-Magento\_ConfigurableProduct-M2.1.2-configurable-options-sort.patch|[#7441](https://github.com/magento/magento2/issues/7441)|2.1.x
magento/module-configurable-product|Patch-Magento\_ConfigurableProduct-M2.2.x-priceBox-prior-to-initialization.patch|[#8018](https://github.com/magento/magento2/issues/8018)|2.2.x
magento/module-configurable-product|Patch-Magento\_Configurable-M2.1.3-lowest-price-provider.patch Patch-Magento\_Configurable-M2.1.6-lowest-price-provider.patch|[#13933](https://github.com/magento/magento2/issues/13933) [#9796](https://github.com/magento/magento2/issues/9796)|<= 2.1.5  < 2.2.0
magento/module-configurable-product|Patch-Magento\_ConfigurableProduct-M2.2.x-fix-empty-price-in-category-page.patch|On development stage|>=2.2.1
magento/module-configurable-product|Patch-Magento_ConfigurableProduct-M2.2.x-fix-min-max-prices.patch|[#15654](https://github.com/magento/magento2/issues/9796)|>=2.2.0 <2.3.0
magento/module-configurable-product|Patch-Magento_ConfigurableProduct-M2.2.x-fix-min-max-prices_M2.2.6.patch|[#15654](https://github.com/magento/magento2/issues/9796)|>=2.2.6
magento/module-configurable-product|Patch-Magento_ConfigurableProduct-M2.2.8-fix-min-max-prices.patch|[#15654](https://github.com/magento/magento2/issues/9796)| =2.2.8
magento/module-configurable-product|Patch-Magento_Configurable_M2.1.x-fix-get-price.patch|[#5519](https://github.com/magento/magento2/issues/5519)|<2.1.10
magento/module-configurable-product|Patch-Magento_ConfigurableProduct-quote-item-qty-doubling-fix.patch||>2.3.x
magento/module-configurable-product|Patch-Magento_BundleProduct-quote-item-qty-doubling-fix.patch||>2.3.x
magento/module-configurable-product-graph-ql|Patch-Magento_ConfigurableProductGraphQL-fix-breaking-response-if-no-variant.patch||>2.3.0
magento/module-cache-invalidate|Patch-Magento_CacheInvalidate-M2.1.x-purge-cache.patch|[#7614](https://github.com/magento/magento2/issues/7614)|<2.2
magento/module-cache-invalidate|Patch-Magento_CacheInvalidate.patch|Log Varnish purge errors|
magento/module-config|Patch-Magento_Config-Fix-of-Saving-clone-field-M2.2.6.patch|[#19070](https://github.com/magento/magento2/issues/https://github.com/magento/magento2/issues/7614)| 2.2.5 2.2.6
magento/module-company|Patch-Magento_Company-M2.3.3-company-double-save-error.patch|Fix: double save company error|
magento/module-page-builder|Patch-Magento_PageBuilder-M2.3.4-fix-preview-mode.patch|Fix: Preview Mode|\>=2.3.4
magento/module-persistent-history|Patch-Magento_PersistentHistory-no-such-entity-with-address-id-fix.patch|[#15115](https://github.com/magento/magento2/issues/https://github.com/magento/magento2/issues/https://github.com/magento/magento2/issues/https://github.com/magento/magento2/issues/7614)|2.2.x-2.3.0
magento/module-sitemap|Patch-Magento_Sitemap-M2.2.x-fix-sitemap-links.patch|[#19565](https://github.com/magento/magento2/issues/19565)|2.2.x
magento/module-backend|Patch-Magento_Backend-M2.4.3-authentication|"Invalid security or form key. Please refresh the page." message|2.4.3
magento/module-backend|Patch-Magento_Backend-M2.3-menu-log-level.patch|Menu Log Level - Debug|
magento/module-backend|Magento_Backend-verbose-logs.patch|Menu Log Level - Debug|
magento/module-related-product-graph-ql|Patch-Magento_RelatedProductGraphQl-M2.4.x-missed-sorting-by-position-fix.patch|[#33010](https://github.com/magento/magento2/issues/33010)|>2.4.0
magento/module-price-permissions|Patch-Magento_Price_Permissions_2.4.5.patch|Fix Price Permissions module requires Tabs in adminhtml|
magento/module-quote|Patch-Magento_Quote-M2.4.x-invalid-customer-address-id-fix.patch|[#1123](https://github.com/magento/magento2/issues/23618)|>2.4.0
elasticsearch/elasticsearch|Patch-Elasticsearch-bulk-errors.patch|[#23618](https://github.com/elastic/elasticsearch-php/issues/1123)|
paypal/module-braintree-core|Patch-Paypal-braintree-2.4.5-admin-report.patch|Fix Braintree bug in Admin reports|
magento/module-rule|Patch-Magento_Rule-product-load-performance-issue.patch|Fix performance issue with tens product loads for each item in the cart|


**3th party modules:**

**Module**|**Name**|                                                            **Fixes**                                                            |**Affected versions**
:-----:|:-----:|:-------------------------------------------------------------------------------------------------------------------------------:|:-----:
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-1.8.0-configurable-price.patch|                                                 Fix configurable product price                                                  |\>=1.8.0
algolia/algoliasearch-magento-2|Patch-Algolia_Algoliasearch-1.12.1-Amasty-conflict-resolve.patch|                       Resolve conflict with Amasty modules (due searchFilterList virtualType Overriding)                        |1.12.1
algolia/algoliasearch-magento-2|Patch-Algolia-AlgoliaSearch-1.12.1-out_of_stock_configurable.patch|                                        Fix configurable product checking for indexation                                         |1.12.1
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-1.11.0-configurable-product-special-price-fix.patch|                                           Special price with configurable product fix                                           | >=1.11.0
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-1.7-catalogrule-index-mview.patch|                              Subscribe to price index to reindex catalog rule changes on schedule                               |1.7.0-1.9.1
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-1.9-fix-queue-jobs.patch|                                                                                                                                 |1.9
algolia/algoliasearch-magento-2|Patch-Algolia-AlgoliaSearch-1.10.0-out_of_stock_configurable.patch|                                                                                                                                 |1.10.0
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-1.10.0-configurable-price.patch|                                     Fixed issue with wrong prices for configurable products                                     |1.10.0
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-1.10.0-1.12.0-unsubscribe-price-index.patch|                             [PR #870](https://github.com/algolia/algoliasearch-magento-2/pull/870)                              |1.10.0-1.12.0
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-add-store-to-facets.patch|                                                                                                                                 |
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-customer-group-catalogrule-price-website-id.patch|                             [PR #853](https://github.com/algolia/algoliasearch-magento-2/pull/853)                              |
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-emulation-clean-scope.patch|                             [PR #857](https://github.com/algolia/algoliasearch-magento-2/pull/857)                              |
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-pages-trigger-index.patch|                                                 Page indexer listeners on mview                                                 |
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-remove-show-all-products.patch|                                                    Remove show all products                                                     |
algolia/algoliasearch-magento-2|Patch-Algolia_AlgoliaSearch-check-request-path-to-empty.patch|                            [PR #1149](https://github.com/algolia/algoliasearch-magento-2/pull/1149)                             |
amasty/shopby|Patch-Amasty_Shopby-2.10.5-remove-price-indexer.patch|                                              Remove auto price indexer for v2.10.5                                              |2.10.5
amasty/shopby|Patch-Amasty_Shopby-2.12.5-remove-price-indexer.patch|                                              Remove auto price indexer for v2.12.5                                              |2.12.5
amasty/shopby|Patch-Amasty_Shopby-2.13.7-remove-price-indexer.patch|                                              Remove auto price indexer for v2.13.7                                              |2.13.7
amasty/shopby|Patch-Amasty_Shopby-category-es-performance2.patch|                                            ES performance fixes for category filter                                             |
amasty/module-improved-layered-navigation-root|Patch-Amasty-ImprovedLayeredNavigationRoot-M2.1.4-block-configurable.patch|                                                                                                                                 |all as of 1.15.1
amasty/module-shop-by-brand|Patch-Amasty_ShopbyBrand-2.6.x-missing-option-error-fix.patch|                                                                                                                                 | \>=2.6.0 < 2.6.5
amasty/module-shop-by-brand|Patch-Amasty_ShopbyBrand-2.6.x-fix-empty-title-for-brand-page.patch|                                                                                                                                 | \>=2.6.5
amasty/shopby-root|Patch-Amasty_ShopbyRoot-2.5.3-fix-broken-filters.patch|                                                                                                                                 | 2.5.3
amasty/shopby-seo|Patch-Amasty-ShopbySeo-2.4.6-set-category-sort.patch|                                               Add sorting from category settings                                                | \>=2.4.6 (didn't check older versions) <2.5.0
amasty/label|Patch-Amasty_Label-compatibility-with-M2.3.patch|                                                   Fix: require jQuery widget                                                    |
anowave/ec|Patch-Anowave-ec-102-fix-bug-in-admin.patch|                                               Fix Anowave/ec bug in Admin reports                                               |
bsscommerce/ajaxcart|Patch-Bss_AjaxCart-1.1.4-improvements.patch|                                                                                                                                 | \=1.1.4
bsscommerce/ajaxcart|Patch-Bss_AjaxCart-add-productIds-to-response.patch|                                                      Fix GTM compatibility                                                      |
colinmollenhour/cache-backend-redis|Patch-Cm_Cache_Backend_Redis-1.10.6-remove-by-chunks.patch|                                   Fixed removal of large amount of keys by dividing to chunks                                   | 1.10.6
clerk/magento2|Patch-Clerk_Clerk-image-init-properly.patch|                                          Initialize image properly and add placeholder                                          |
clerk/magento2|Patch-Clerk-4.7.7-empty-body-params.patch|                                          Empty request body params causes wrong resolving store based on passed credentials and in effect wrong indexation                                           | 4.7.4-4.7.7
clerk/magento2|Patch-Clerk-4.8.x-empty-body-params.patch|                                          Empty request body params causes wrong resolving store based on passed credentials and in effect wrong indexation                                           | 4.8.1-4.8.5
klarna/module-base|Patch-Klarna_Base-fix-round-to-int-and-tax-calculation.patch|                                            Fix rounding and discount tax calculation                                            |
klarna/module-kco|Patch-Klarna_Kco-5.0.5-reload-summary-action-error-log.patch|                                               Fix wrong function parameters order                                               |>=5.0.5
klarna/module-kco|Patch-Klarna_Kco-Add-order-variable-to-event-in-success-controller.patch|                                               Add order variable to success event                                               |
klarna/module-kco|Patch-Klarna_Kco-8-fix-total-base-calculation-plugin.patch|                                    Fix: Total Base Calculation Plugin - Check is KCO enabled                                    |
klarna/module-kco|Patch-Klarna_Kco-fix-shipping-methods-reload-and-widget-update.patch|                                                   Fix shipping method reload                                                    |
klarna/module-core|Patch-Klarna_Core-fix-customer-address-no-such-exception.patch|                                   Fix no such entity with addressId error in Klarna checkout                                    |>=4.2.3 (didn't check older versions)
klarna/module-core|Patch-Klarna_Core-klarna-logs-column-size-cleanlogs.patch| Fix based on https://docs.klarna.com/platform-solutions/adobe-commerce/adobe-commerce-23x-243/notice-for-users-of-magento-v243/ | <= 6.2.4
klarna/module-kco-core|Patch-Klarna_Kco_Core-Block-Info-fix-constructor-m2_5_2.patch|                               Fix Incorrect dependency in class Klarna\KcoCore\Block\Info\Klarna                                |>=5.2 (didn't check older versions)
klarna/module-kco-core|Patch-Klarna-KcoCore-log-json-encode.patch|                                             Convert logs from array to json format                                              |>=5.2.1 (didn't check older versions)
mirasvit/module-sorting|Patch-Mirasvit_Sorting-indexer-spawns-events.patch|                                        Mirasvit Sorting making swell its changelog table                                        | 2.4.5
nosto/module-nostotagging|Patch-Nosto_Tagging-indexer-spawns-events.patch|                                             Nosto making swell its changelog table                                              | 2.4.5
dotmailer/dotmailer-magento2-extension|Patch-Dotdigitalgroup_email-subject-fix.patch|                                            Fix utf8 encoding in the subject of email                                            |?
trollweb/module-bring|Patch-Trollweb-Bring-2.3.2-Customer-number-argument-usage|                                     Fix wrong Customer Number param in request for carriers                                     | 2.3.2
trollweb/module-bring|Patch-Trollweb_Bring-3.3.8-missed-method-displayName.patch|                                           Fix missed displayName for delivery method                                            | 3.3.8
vconnect/module-allinone|Patch-Vconnect_Allinone-2.3.x-allowed-methods-fix.patch|                                             Fixed allowed methods in carrier model                                              | >=2.3.0
vconnect/module-allinone|Patch-Vconnect_Allinone-allowed-methods-fix.patch|                                             Fixed allowed methods in carrier model                                              | >=2.2.0 < 2.3.0
vconnect/module-allinone|Patch-Vconnect_Allinone-2.3.x-find-points-fix.patch|                                                 Address fix for findPoints call                                                 | >=2.3.0
vconnect/module-allinone|Patch-Vconnect_Allinone-fix-js-for-ie.patch|                                                         Fixed JS for IE                                                         | >=2.2.0
vipps/module-payment|Patch-Vipps_ModulePayment-2.4.6-fix-place-order-quote-mask.patch|                                   [PR #89](https://github.com/vippsas/vipps-magento/pull/89)                                    | >=2.3
vipps/module-payment|Patch-Vipps_ModulePayment-2.4.5-no-quote-found-exception.patch|                                   [PR #88](https://github.com/vippsas/vipps-magento/pull/88)                                    | >=2.4.5
vipps/module-payment|Patch-Vipps_Payment-2.4.x-fix-Klarna-payment-customer.patch|                                  [PR #133](https://github.com/vippsas/vipps-magento/pull/133)                                   | >=2.2
vipps/module-payment|Patch-Vipps_Payment-2.4.x-fix-Vipps-express-payment.patch|                                  [PR #133](https://github.com/vippsas/vipps-magento/pull/133)                                   | >=2.2
vpietri/adm-quickdevbar|Patch-ADM_QuickDevBar-jquery-ui.patch|                                                                                                                                 |
weltpixel/m2-weltpixel-backend|Patch-ADM_QuickDevBar-jquery-ui.patch|                                                                                                                                 |1.8.5-1.9.1
visma/module-fram|Patch-Visma_Fram-1.4.1-suppress-request-if-disabled-empty-fix.patch|                                            Check module enabled, empty responce fix                                             |\>=1.4.1

Full composer.json example:

```json
{
    "extra": {
        "magento-force": "override",
        "patches": {
            "algolia/algoliasearch-magento-2": {
                "Fixed processing of queue jobs": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_AlgoliaSearch-1.9-fix-queue-jobs.patch",
                "Unsubscribe Price Index - https://github.com/algolia/algoliasearch-magento-2/pull/870": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_AlgoliaSearch-1.10.0-1.12.0-unsubscribe-price-index.patch",
                "Special price with configurable product fix": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_AlgoliaSearch-1.11.0-configurable-product-special-price-fix.patch",
                "Resolve conflict with Amasty": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_Algoliasearch-1.12.1-Amasty-conflict-resolve.patch",
                "Configurable product out of stock": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia-AlgoliaSearch-1.12.1-out_of_stock_configurable.patch",
                "Configurable product price fix": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_Algoliasearch-1.12.1-Amasty-conflict-resolve.patch",
                "Configurable product price fix": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_AlgoliaSearch-1.8.0-configurable-price.patch",
                "Configurable product out of stock": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia-AlgoliaSearch-1.10.0-out_of_stock_configurable.patch",
                "Fixed issue with wrong prices for configurable products": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_AlgoliaSearch-1.10.0-configurable-price.patch",
                "Remove auto price indexer for v2.10.5": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_Shopby-2.10.5-remove-price-indexer.patch",
                "Remove auto price indexer for v2.12.5": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_Shopby-2.12.5-remove-price-indexer.patch",
                "Set storeId for get facets": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_AlgoliaSearch-add-store-to-facets.patch",
                "Catalogrule price for customer groups: https://github.com/algolia/algoliasearch-magento-2/pull/853": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_AlgoliaSearch-customer-group-catalogrule-price-website-id.patch",
                "Clean scope code resolver: https://github.com/algolia/algoliasearch-magento-2/pull/857": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_AlgoliaSearch-emulation-clean-scope.patch",
                "Page indexer listeners on mview": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_AlgoliaSearch-pages-trigger-index.patch",
                "Remove show all products": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_AlgoliaSearch-remove-show-all-products.patch",
                "Check request param to empty instead strict equal": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Algolia_AlgoliaSearch-check-request-path-to-empty.patch"
            },
            "amasty/shopby": {
                "ES performance fixes for category filter": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_Shopby-category-es-performance2.patch"
            },
            "amasty/module-improved-layered-navigation-root": {
                "Fix: Remove unnecessary configurable block": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty-ImprovedLayeredNavigationRoot-M2.1.4-block-configurable.patch"
            },
            "amasty/shopby-seo": {
                "Fix: Broken product links in cart on different stores": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_ShopbySeo-cart-broken-links-fix.patch",
                "Fix: Add sorting from category settings": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty-ShopbySeo-2.4.6-set-category-sort.patch",
                "Fix: Broken product links in cart on different stores and fix wishlist": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_ShopbySeo-cart-broken-links-fix-v2.patch"
            },
            "amasty/module-shop-by-brand": {
                 "Fix error when option was removed from attribute": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_ShopbyBrand-2.6.x-missing-option-error-fix.patch",
                 "Fix empty brand column on brand page": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_ShopbyBrand-2.6.x-fix-empty-title-for-brand-page.patch"
            },
            "amasty/shopby-root": {
                 "Fix filters exception on category page": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_ShopbyRoot-2.5.3-fix-broken-filters.patch"
            },
            "amasty/label": {
                "Fix: require jQuery widget": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Amasty_Label-compatibility-with-M2.3.patch"
            },
            "colinmollenhour/cache-backend-redis": {
                "Fix: Remove by Chunks - https://github.com/colinmollenhour/Cm_Cache_Backend_Redis/issues/153": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Cm_Cache_Backend_Redis-1.10.6-remove-by-chunks.patch"
            },
            "clerk/magento2": {
                "Initialize image properly and add placeholder": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Clerk_Clerk-image-init-properly.patch"
            },
            "elasticsearch/elasticsearch": {
                "Throw an exception on unsuccessful bulk operations https://github.com/elastic/elasticsearch-php/issues/1123": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Elasticsearch-bulk-errors.patch"
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
                "Fix: https://github.com/magento/magento2/issues/12362": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.2.x-drop-session-fix.patch",
                "Fix: https://github.com/magento/magento2/issues/12362": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.2.6-Fix-session-from-2.2.7.patch",
                "Fix: SQL injection vulnerability": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.2.x-PRODSECBUG-2198.patch",
                "Fix: https://github.com/magento/magento2/issues/21916": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.3.1-fix-elasticsearch-generation.patch",
                "Allow to add body class while block render": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-result-page.patch",
                "Pull: https://github.com/magento/magento2/pull/31879": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.4.x-performance-graphql-schema-parsing-fix.patch",
                "Security: APSB22-12": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_framework-M2.3.3-M2.4.3-security-not-actual.patch",
                "Security: APSB22-12": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_framework-M2.3.4-p1-M2.4.2-p1_APSB22-12-security.patch",
                "Security: APSB22-12": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_framework-M2.4.3-p1_APSB22-12-security.patch",
                "Remove verbose logs": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Magento_Framework-verbose-logs.patch",
            },
            "magento/magento2-base": {
                "Fix MAGE_DIRS for CLI": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-cli.patch",
                "Fix FotoramaJS for single frame": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-FotoramaJS-M2.1.0-enable-single-frame.patch",
                "Fix FotoramaJS for single frame": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-FotoramaJS-M2.1.0-enable-single-frame_M2.2.6.patch",
                "Fix: cache clean after di compile": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-setup-upgrade.patch",
                "Fix: cache clean after di compile": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-setup-upgrade_2.2.6.patch",
                "Fix: https://github.com/magento/magento2/issues/4232": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.1.0-widgets-values-utf8-decode.patch",
                "Fix: https://github.com/magento/magento2/issues/5808": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.1.0-catalog-gallery-allowfullscreen-false.patch",
                "Fix: https://github.com/magento/magento2/issues/4305": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.1.0-errors-apply-skin-fix.patch",
                "Fix: https://github.com/magento/magento2/issues/13226": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-2.2.x-fotorama-ios.patch",
                "Pull request: https://github.com/magento/magento2/pull/12497": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.2-cron-prevent-already-running.patch",
                "Fix zoom in profuct page (Todo check: MAGETWO-94989)": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.x.x-zoomed-photo-product.patch",
                "Fix magnifier zoom calculation": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.2.5-mangnifier-zoom-distortion.patch",
                "Add null to return value for session and cookies": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.3.x-tests-cookie-and-session-add-to-return-null-value.patch",
                "Remove PHP memory_limit": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-M2.3-remove-php-memory-limit.patch",
                "Running GraphQl API functional tests": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-test-graphql-application.patch",
                "Deploy test modules - Convert": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base-deploy-test-modules.patch",
                "Fix magento theme jquery cookie issue": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Base_2.4.5_jquery_cookies_issue.patch"
            },
            "magento/module-cache-invalidate": {
                "Log Varnish purge errors": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CacheInvalidate.patch"
            },
            "magento/module-developer": {
                "Fix: https://github.com/magento/magento2/issues/4362": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Developer-M2.1.x-disable-debug-loging.patch"
            },
            "magento/module-cache-invalidate": {
                "Fix: https://github.com/magento/magento2/issues/7614": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CacheInvalidate-M2.1.x-purge-cache.patch"
            },
            "magento/module-catalog": {
                "Fix: https://github.com/magento/magento2/issues/8018": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.3-category-indexer-range.patch",
                "Fix: Product auto enable on REST API update": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-rest-api-auto-enable-product-fix.patch",
                "Fix: Set default website insteed of admin on REST API create product": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-rest-api-single-store-fix.patch",
                "Fix: https://github.com/magento/magento2/issues/5438": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.0-image-attribute-backend-model-hardcoded-attribute-code-removal.patch",
                "Fix: catalog_product_flat does not update column with empty value. Fix options linking.": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.4-product-flat-indexer-v2.patch",
                "Fix: https://github.com/magento/magento2/issues/4387": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1-fix-product-auto-startdates.patch",
                "Fix: https://github.com/magento/magento2/issues/7874": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1.4-regeneration-without-changes-fix.patch",
                "Fix: Change toolbar default sorting": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-Catalog-M2.1.x-toolbar-default-sorting.patch",
                "Fix: https://github.com/magento/magento2/issues/13720": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.2.x-related-products-visibility-in-admin.patch",
                "Fix: SQL injection vulnerability": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.2.x-PRODSECBUG-2198.patch",
                "Fix: Brand page for multystore": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-improve-root-category-indexer-2.2.8.patch",
                "Fix: skip empty Custom Options SKUs to avoid adding extra delimiters to configurable product SKU": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.2.x-skip-empty-custom-options-skus.patch",
                "Fix: https://github.com/magento/magento2/pull/16838": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-Catalog-M2.1.x-2.2.7-fix-save-customizable-options.patch",
                "Allow to use invalid Flat Indexer": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.1-flat-availability.patch",
                "Catalog Category Flat chunk limit": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.3-category-flat-chunk-limit.patch",
                "Fix: Category Image Upload": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.3-fix-category-image-upload.patch",
                "Fix: Use Indentifer field for Website processor": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog-M2.4.2-website-select-processor-fix.patch"
            },
            "magento/module-catalog-graph-ql": {
               "Fix: https://github.com/magento/magento2/issues/30775": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogGraphQl-aggregations-sorting-fix.patch",
               "Fix: Move Category aggregation to first place": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogGraphQl-aggregations-category-place-first.patch",
               "Fix: Translate Price and Category filter label on backend": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogGraphQl-aggregations-price-category-translate-lables.patch",
               "Fix: https://github.com/magento/magento2/issues/29631": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogGraphQl-M2.4.x-special-price-from-to-dates.patch",
               "Fix: Sorting attributes reader": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogGraphQl_sort_attributes_reader_fix.patch"
            },
            "magento/module-catalog-inventory": {
                "Fix: https://github.com/magento/magento2/issues/8566": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogInventory_M2.1.3-hide-out-of-stock.patch",
                "Fix: https://github.com/magento/magento2/issues/4857": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogInventory-M2.1.x-stock-item-events-fix.patch",
                "Fix: Update stock item on product save": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogInventory-M2.2.0-2.2.3-fix-update-stock-item-on-product-save.patch",
                "Fix: https://github.com/magento/magento2/issues/12205": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogInventory-M2.2.0-2.2.4-stock-index.patch",
                "Fix: https://github.com/magento/magento2/issues/15984": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogInventory-M2.3.3-2.3.4-fix-stock-indexer-deleting-new-records.patch",
                "Fix: Use Config Manage Stock in new Stock Item": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogInventory-M2.2-new-item-use-config-manage-stock.patch",
                "Fix: Invalidate parent product cache on stock update V2": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogInventory-M2.4.x-invalidate-cache-parent-product-on-stock-update.patch"
            },
            "magento/module-inventory-cache": {
                "Fix inventory indexer is cleaning all caches in scheduled mode": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_InventoryCache-M2.4.5-fix-cache-invalidation.patch"
            },
            "magento/module-catalog-rule": {
                "Fix: https://magento.stackexchange.com/questions/67970/catalog-price-rules-disappear-after-mid-night": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-Catalog-Rule-M2.1.X-cron-job.patch"
            },
            "magento/module-catalog-staging": {
                "Fix: changing the date depending on the locale": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Catalog_Staging-timestam.patch"
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
                "Fix: https://github.com/magento/magento2/issues/15654": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_ConfigurableProduct-M2.2.x-fix-min-max-prices_M2.2.6.patch",
                "Fix: https://github.com/magento/magento2/issues/15654": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_ConfigurableProduct-M2.2.8-fix-min-max-prices.patch",
                "Fix: https://github.com/magento/magento2/issues/5519": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Configurable_M2.1.x-fix-get-price.patch",
                "Fix: https://github.com/magento/magento2/issues/8018": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_ConfigurableProduct-M2.2.x-priceBox-prior-to-initialization.patch",
                "Fix: Configurable product quantity is doubling in the Quote item": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_ConfigurableProduct-quote-item-qty-doubling-fix.patch"
            },
            "magento/module-configurable-product-graph-ql": {
                "Fix breaking response if no variants": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_ConfigurableProductGraphQL-fix-breaking-response-if-no-variant.patch"

            },
            "magento/module-bundle": {
                "Fix: Bundle product quantity is doubling in the Quote item": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_BundleProduct-quote-item-qty-doubling-fix.patch"
            },
            "magento/module-cron": {
                "Fix: https://github.com/magento/magento2/issues/4173": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Cron-M2.1.4-cron-generate-schedule.patch",
                "Pull request: https://github.com/magento/magento2/pull/12497": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Cron-M2.2.0-2.2.3-prevent-already-running-v2.patch",
                "Pull request: https://github.com/magento/magento2/pull/12497": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Cron-M2.2.4-prevent-already-running-v2.patch",
                "Remove verbose logs": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Magento_Cron-verbose-logs.patch"
            },
            "magento/module-customer": {
                "Fix: https://github.com/magento/magento2/pull/10582": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Customer-M2.1.9-array-street-line.patch",
                "Fix: https://github.com/magento/magento2/issues/11825": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Customer-M2.1.9-generate-new-formkey-wishlist.patch",
                "Fix: https://github.com/magento/magento2/pull/31940": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Customer-M2.4.x-errors-in-customer-data-component-not-initialized-fix.patch",
                "Fix: Disable cache for customer section data": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch_Magento_Customer-M2.1.4-customer-section-load-fix.patch",
                "Fix: Added Customer Group Id to GraphQl Context": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Customer-M2.4.1-context-customer-group-id-fix.patch" 
            },
            "magento/module-customer-graph-ql": {
               "Fix: Added Customer Group Id to GraphQl Context": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CustomerGraphQl-M2.4.1-context-customer-group-id-fix.patch",
               "Return GraphQl exception category": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-CustomerGraphQl-exception-category.patch" 
            },
            "magento/module-directory": {
                "Fix: https://github.com/magento/magento2/issues/6694": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Directory_M2.1-zip-codes.patch"
            },
            "magento/module-eav": {
                "Pull: https://github.com/magento/magento2/pull/21901": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Eav-M2.3-api-product-multiselect.patch"
            },
            "magento/module-email": {
                "https://github.com/magento/magento2/issues/5352": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Email-M2.1.0-create-email-logo-1.patch",
                "https://github.com/magento/magento2/issues/14968": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Email-M2.2.x-cant-update-logo.patch",
                "Disable adding ?SID in email message urls": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Email-M2.2.8-2.3.2-No-Sid-In-Messages.patch",
                "Security: APSB22-12": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_email-M2.3.3-M2.4.3-security-notactual.patch",
                "Security: APSB22-12": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Module-email-M2.3.3-p1-M2.3.4-p1_APSB22-12-security.patch",
                "Security: APSB22-12": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Module-email-M2.3.4-p2-M2.4.2-p1_APSB22-12-security.patch",
                "Security: APSB22-12": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Module-email-M2.4.3-p1_APSB22-12-security.patch"
            },
            "magento/module-elasticsearch": {
                "Ignore Elastic Search Error": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Elasticsearch-M2.3.x-Send-Error-Message.patch",
                "Website prices: https://github.com/magento/magento2/pull/21216": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Elasticsearch-M2.3.0-M2.3.1-prices-pass-website-id.patch",
                "Index settings - mapping.total_fields.limit = 10000": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Elasticsearch-M2.2-total-fields-limit-10000.patch",
                "Attribute Options Optimization": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Elasticsearch-M2.3-attribute-options-optimization.patch",
                "Don't inherit pimcore_id from child products": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Elasticsearch-pimcore_id.patch",
                "Adjust to PHP8.1 and Magento2.4.5": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Elasticsearch-2.4.5-adjust.patch"
            },
            "magento/module-elasticsearch-7": {
                "Elasticsearch error returns 503 code and message": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Elasticsearch7-disable-full-page-cache-show-error.patch"
            },
            "magento/module-google-tag-manager": {
                "Fix: Check block before get Product List": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch_Magento_GoogleTagManager_M2.1.0-fix-empty-product-list-block.patch"
            },
            "magento/module-graph-ql": {
                "Fix: https://github.com/magento/magento2/issues/31351": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_GraphQl-load-translations-for-store-scope-fix.patch"
            },
            "magento/module-indexer": {
                "indexer:reindex command - Optional dependencies": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Indexer-M2.3.1-indexer-reindex-optional-dependencies.patch"
            },
            "magento/module-page-builder": {
                "Fix: Preview Mode": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_PageBuilder-M2.3.4-fix-preview-mode.patch"
            },
            "magento/module-page-cache": {
                "Fix: https://github.com/magento/magento2/issues/6818": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_PageCache-M2.1.0-element-js-error-fix.patch"
            },
            "magento/module-review": {
                "Fix review namespace": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Review-M2.2-review-renderer-module-namespace.patch",
                "Fix: Product Collection Observer - Check module status": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Review-M2.3-observer-catalog-check-is-active.patch"
            },
            "magento/module-sales": {
                "Fix: Partial creditmemo tax amount": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Sales-creditmemo-partial-tax-refund.patch",
                "Canceled amount in Invoice Subtotal": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Sales-M2.2-invoice-subtotal-canceled.patch",
                "Canceled amount in Invoice Tax": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Sales-M2.3-invoice-tax-canceled.patch",
                "Fix: https://github.com/magento/magento2/issues/23069": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch_Magento_Refund_Invoice_Without_0_Quantities.patch",
                "Fix: https://github.com/magento/magento2/issues/30853": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Sales-M2.4.2-discount-cart-rule-results-in-tax-invoiced.patch"
            },
            "magento/module-sales-rule": {
                "Fix: https://github.com/magento/magento2/issues/6762": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_SalesRule-M2.1.6-fix-to-date-parameter.patch"
            },
            "magento/module-staging": {
                "Fix: Duplicated rollback": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Staging-M2.2-fix-duplicated-rollback.patch"
            },
            "magento/module-store": {
                "Fix emulation in admin store (Todo check: MAGETWO-59649)": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Store-emulation.patch"
            },
            "magento/module-swatches": {
                "Fix: Add ability to set visual swatch by store ID as well as textual one": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Swatches-rest-api-visual-swatches-fix.patch",
                "Fix: Add ability to set visual swatch by store ID as well as textual one": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Swatches-rest-api-visual-swatches-fix_2.2.6.patch",
                "Fix: https://github.com/magento/magento2/issues/10266": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Swatches-M2.1.x-zero-value-attribute-options-fix.patch"
            },
            "magento/module-related-product-graph-ql": {
                "Fix: https://github.com/magento/magento2/issues/33010": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_RelatedProductGraphQl-M2.4.x-missed-sorting-by-position-fix.patch"
            },
            "magento/module-tax": {
                "Fix: https://github.com/magento/magento2/issues/2939": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-Tax-M2.1.0-free-shipping-availability-on-backend.patch",
                "Fix: https://github.com/magento/magento2/issues/7801": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Tax-M2.X.X-sequence-fix.patch"
            },
            "magento/module-theme": {
                "https://github.com/magento/magento2/issues/5352": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Email-M2.1.0-create-email-logo-2.patch",
                "Fix magento theme jquery cookie issue": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Theme_jquery_cookies_issue.patch"
            },
            "magento/module-ui": {
                "Fix broken by: MAGETWO-57144": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Ui-M2.1.9-country-select-extra-empty-option.patch",
                "Fix: https://github.com/magento/magento2/issues/5438": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Ui-M2.1.0-allow-backend-to-know-the-origin-input-of-the-upload-request.patch",
                "Fix: https://github.com/magento/magento2/issues/6281": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Ui-M2.1.x-multiselect-empty-save.patch",
                "Fix: https://github.com/magento/magento2/issues/8554": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Ui-M2.1.x-layout-cache-empty-menu.patch",
                "Fix: https://github.com/magento/magento2/issues/16119": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Ui-M2.2.x-invalid-date-range-fix.patch",
                "Fix reset of disabled attributes": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-Ui_fix-reset-disabled-attributes.patch"
            },
            "magento/module-webapi": {
                "Log webapi exceptions": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Webapi-M2.3.x-log-exceptions.patch"
            },
            "magento/module-widget": {
                "Fix: https://github.com/magento/magento2/issues/2913": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Widget-M2.1.0-widgets-restore-conditions.patch"
            },
            "magento/module-wishlist": {
                "Fix: https://github.com/magento/magento2/issues/11825": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Wishlist-M2.x.x-add-to-wishlist-login-register.patch",
                "Add ability to keep item in cart after adding to wishlist": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Wishlist-M2.x.x-wishlist-keep-item-in-cart.patch",
                "Remove failed login attempts from the database patch CVE-2019-8118 PRODSECBUG-2452": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Wishlist_M2.x.x-failed-login-attempts.patch"
            },
            "magento/module-offline-shipping": {
                "Fix: https://github.com/magento/magento2/issues/10704": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_OfflineShipping-M2.X-free-shipping-cart-rule-fix.patch",
                "Add ability create freeshipping by cart rule for Flatrate": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_OfflineShipping_freeshipping_for_flatrate-M2.2.4.patch"
            },
            "magento/module-catalog-url-rewrite": {
                "Fix: https://github.com/magento/magento2/issues/7874 depended on module-catalog patch": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogUrlRewrite-M2.1.4-regeneration-without-changes-fix.patch",
                "Fix: Fixed functionality for updating url key for products": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_CatalogUrlRewrite-update-url-key-for-products.patch"
            },
            "mirasvit/module-feed": {
                "Fix: DI compile without DB v2": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Mirasvit_Feed-1.0.60-fix-di-compile-without-db.patch"
            },
            "magento/module-quote": {
                "Fix: Reset broken shipping address in quote": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Quote-M2.1.x-reset-broken-shipping-address.patch",
                "Fix: Broken product links in cart on different stores": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Quote-M2.1.x-cart-product-links-fix.patch",
                "Fix: https://github.com/magento/magento2/issues/12819": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Quote-M2.2.0-2.2.3-totals-extension-attributes.patch",
                "Fix: https://github.com/magento/magento2/issues/23618": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Quote-M2.4.x-invalid-customer-address-id-fix.patch",
            },
            "magento/module-checkout": {
                "Fix: addresses from other store on checkout": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-M2.1.x-filter-addresses.patch",
                "Fix: addresses from other store on checkout 2.2+": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-M2.2.x-filter-addresses.patch",
                "Fix: Add to cart form key": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-cart-form-key.patch",
                "Fix: Add to cart form key": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-M2.3.x-cart-form-key.patch",
                "Fix: https://github.com/magento/magento2/issues/12362": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Framework-M2.2.x-drop-session-fix.patch",
                "Fix: https://github.com/magento/magento2/pull/18503": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-M2.2.x-quote-data-of-undefined.patch",
                "Fix: https://github.com/magento/magento2/issues/22119": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-M2.3.3-replace-ES6-code.patch",
                "Fix: https://github.com/magento/magento2/issues/29364": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-M2.3.x-checkout-login-form.patch",
                "Don't change checkbox billing-same-as-shipping automatically": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-M2.3-billing-same-as-shipping-manually-v2.patch",
                "Allow placing order with empty billing address": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-M2.3.3-place-order-allow-empty-billing.patch",
                "Don't throw carrier not found error": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Checkout-M2.3.3-save-shipping-method-not-found.patch"
            },
            "magento/module-checkout-staging": {
                "Fix fail checking shipping vs billing_address in 2.4.4 when exension attributes are added https://github.com/magento/magento2/issues/34202": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-Checkout-Staging-2.4.4-extension-attributes.patch"
            },
            "magento/module-company": {
                "Fix: double save company error": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Company-M2.3.3-company-double-save-error.patch"
            },
            "magento/module-backend": {
                "Menu Log Level - Debug": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Backend-M2.3-menu-log-level.patch",
                "Fix: https://github.com/magento/magento2/issues/33749#issuecomment-908145941": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Backend-M2.4.3-authentication.patch",
                "Remove verbose logs": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Magento_Backend-verbose-logs.patch"
            },
            "magento/module-multiple-wishlist": {
                "Fix Magento wishlist bug in Admin reports": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento-multiple-wishlist-Not-existing-products.patch"
            },
            "magento/module-price-permissions": {
                "Fix Price Permissions module requires Tabs in adminhtml": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Price_Permissions_2.4.5.patch"
            },
            "anowave/ec": {
                "Fix Anowave/ec bug in Admin reports": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Anowave-ec-102-fix-bug-in-admin.patch"
            },
            "klarna/module-core": {
                "Fix no such entity with addressId error in Klarna checkout": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Klarna_Core-fix-customer-address-no-such-exception.patch",
                "Fix klarna_logs table. https://docs.klarna.com/platform-solutions/adobe-commerce/adobe-commerce-23x-243/notice-for-users-of-magento-v243/": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Klarna_Core-klarna-logs-column-size-cleanlogs.patch"
            },
            "klarna/module-base": {
                "Fix rounding and discount tax calculation": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Klarna_Base-fix-round-to-int-and-tax-calculation.patch"
            },
            "klarna/module-kco-core": {
                "Fix Incorrect dependency in class Klarna_KcoCore_Block_Info_Klarna": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Klarna_Kco_Core-Block-Info-fix-constructor-m2_5_2.patch",
                "Convert logs from array to json format": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Klarna-KcoCore-log-json-encode.patch"
            },
            "klarna/module-kco": {
                "ReloadSummary action wrong order of parameters": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Klarna_Kco-5.0.5-reload-summary-action-error-log.patch",
                "Fix: Total Base Calculation Plugin - Check is KCO enabled": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Klarna_Kco-8-fix-total-base-calculation-plugin.patch",
                "Fix: shipping method reload": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Klarna_Kco-fix-shipping-methods-reload-and-widget-update.patch",
                "Add order variable to success event": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Klarna_Kco-Add-order-variable-to-event-in-success-controller.patch"
            },
            "bsscommerce/ajaxcart": {
                "Add event + multiple add to cart (reorder) fix": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Bss_AjaxCart-1.1.4-improvements.patch",
                "Fix GTM compatibility": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Bss_AjaxCart-add-productIds-to-response.patch"
            },
            "dotmailer/dotmailer-magento2-extension": {
                "Fix utf8 encoding in the subject of email": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Dotdigitalgroup_email-subject-fix.patch"
            },
            "magento/module-config": {
                "Fix: https://github.com/magento/magento2/issues/19070": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Config-Fix-of-Saving-clone-field-M2.2.6.patch"
            },
            "magento/module-persistent-history": {
                "Fix: https://github.com/magento/magento2/issues/15115": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_PersistentHistory-no-such-entity-with-address-id-fix.patch"
            },
            "magento/module-sitemap": {
                "Fix: https://github.com/magento/magento2/issues/19565": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Magento_Sitemap-M2.2.x-fix-sitemap-links.patch"
            },
            "paypal/module-braintree-core": {
                "Fix Braintree bug in Admin reports": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Paypal-braintree-2.4.5-admin-report.patch"
            },
            "trollweb/module-bring": {
                "Fix Сustomer number argument name and usage": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Trollweb-Bring-2.3.2-Customer-number-argument-usage.patch"
            },
            "vconnect/module-allinone": {
                "Fixed allowed methods in carrier model": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Vconnect_Allinone-2.3.x-allowed-methods-fix.patch",
                "Address fix for findPoints call": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Vconnect_Allinone-2.3.x-find-points-fix.patch",
                "Fixed JS for IE": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Vconnect_Allinone-fix-js-for-ie.patch",
                "Fixed Postnord refreshing": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Vconnect_Allinone-prevent-postnord-refreshing-v2.patch"
            },
            "vipps/module-payment": {
              "Fix: Quote Mask on Place Order": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Vipps_ModulePayment-2.4.6-fix-place-order-quote-mask.patch",
              "Fix: No Quote exception on callback": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Vipps_ModulePayment-2.4.5-no-quote-found-exception.patch",
              "Fix: Klarna payment order creation for logged-in customer": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Vipps_Payment-2.4.x-fix-Klarna-payment-customer.patch",
              "Fix: Vipps express checkout order creation": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Vipps_Payment-2.4.x-fix-Vipps-express-payment.patch"
            },
            "vpietri/adm-quickdevbar": {
              "jQuery/ui": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-ADM_QuickDevBar-jquery-ui.patch"
            },
            "weltpixel/m2-weltpixel-backend": {
              "Remove shell_exec from code": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Weltpixel_Backend-1.8.5-1.9.1-remove-shell_exec.patch"
            },
            "visma/module-fram": {
                "Check module enabled, empty responce fix": "https://raw.githubusercontent.com/ConvertGroupsAS/magento2-patches/master/Patch-Visma_Fram-1.4.1-suppress-request-if-disabled-empty-fix.patch"
            },
            "mirasvit/module-sorting": {
              "Fix indexers spawn thousands event": "patches/Patch-Mirasvit_Sorting-indexer-spawns-events.patch"
            },
            "nosto/module-nostotagging": {
              "Fix indexers spawn thousands event": "patches/Patch-Nosto_Tagging-indexer-spawns-events.patch"
            }
        }
    }
}
```
