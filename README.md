# Web Data Connector 3.0

[![As-Is](https://img.shields.io/badge/Support%20Level-As--Is-e8762c.svg)](https://www.tableau.com/support-levels-it-and-developer-tools)

:warning: **Deprecated — This repository will be removed with the Tableau 26.3 release.** The Web Data Connector 3.0 framework is deprecated and will not receive further updates. Migrate to the [REST API Connector on Tableau Exchange](https://exchange.tableau.com/products/1111) — built by Tableau, supports JSON and CSV over HTTP GET, Basic/Bearer/OAuth authentication, and runs on Tableau 2023.3 and later. Note: this connector is extract-only and requires a JDBC driver installation.​​​​​​​​​​​​​​​​

***NOTE:** Web Data Connector 3.0 is the latest version of Tableau's web data connector framework. If you are looking for the prior version(s), which are set to be deprecated, you can find information here: [https://tableau.github.io/webdataconnector/](https://tableau.github.io/webdataconnector/)*

This project captures links to documentation, tools, and other resources to help you build web data connectors to connect to web application data from Tableau. Unlike prior versions of Web Data Connector, WDC 3.0 allows you to build packaged connectors (i.e. .taco files similar to the [Tableau Connector SDK](https://tableau.github.io/connector-plugin-sdk/) for ODBC/JDBC data sources) that do not require web hosting and appear as named connectors in Tableau products.

## Documentation

Official documentation for WDC 3.0 can be found [here](https://help.tableau.com/current/api/webdataconnector/en-us/index.html)

## Taco Toolkit

The TACO Toolkit is a set of tools that helps simplify Tableau web data connector development. It contains a command-line interface (CLI) to create and publish Tableau web data connectors and a SDK that enables you to develop your connectors efficiently. It can be installed from npm: [https://www.npmjs.com/package/@tableau/taco-toolkit](https://www.npmjs.com/package/@tableau/taco-toolkit)

## Versioning Considerations

There are some version constraints between TACO Toolkit, WDC 3.0 connectors built with TACO Toolkit, and Tableau Products that must be taken into consideration. For details, please see the documentation [here](https://help.tableau.com/current/api/webdataconnector/en-us/docs/wdc_versioning.html)

