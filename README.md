Soflomo\Sitemap
===
Soflomo\Sitemap is a simple sitemap generation module for Zend Framework 2. It provides a html version and XML version of the sitemap using `Zend\Navigation`.

Installation
---
Soflomo\Sitemap can be loaded via composer. Require `soflomo/sitemap`. The current version is tagged as 0.1.0, so you can use the constraint `>=0.1.0,<0.2.0-dev`. After the module is loaded, do not forget to enable it in your application.config.php under the module name `Soflomo\Sitemap`.

Usage
---
Visit `/sitemap` for the html version. The `/sitemap/xml` is the XML version for the sitemap. Soflomo\Sitemap uses the default navigation container. If you want to set another container to be rendered, inject this container in the navigation view helper prior to the dispatch of the `Soflomo\Sitemap\Controller\SitemapController`.