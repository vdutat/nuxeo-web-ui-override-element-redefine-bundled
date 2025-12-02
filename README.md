# nuxeo-web-ui-override-element-redefine-bundled
## About / Synopsis

This plugin contains the `redefine-bundled.js` that allows to overwrite Web UI elements.

It was generated with the following commands:
```
mkdir nuxeo-web-ui-override-element-redefine-bundled && cd $_
nuxeo bootstrap multi-module
nuxeo b single-module --type web
# Add redefine-bundled.js
# Add Nuxeo index.jsp and edit it to add NONCE
# Add deployment-fragment.xml
mvn clean package
nuxeo b package
mvn clean install
```

## Table of contents

> * [nuxeo-web-ui-override-element-redefine-bundled](#nuxeo-web-ui-override-element-redefine-bundled)
>   * [About / Synopsis](#about--synopsis)
>   * [Table of contents](#table-of-contents)
>   * [Installation](#installation)
>   * [Requirements](#requirements)
>   * [Build](#build)
>   * [License](#license)
>   * [About Hyland Nuxeo](#about-hyland-nuxeo)

## Requirements

Building requires the following software:

* git
* maven

## Build

```
git clone ...
cd nuxeo-web-ui-override-element-redefine-bundled

mvn clean install
```

## Installation

```
nuxeoctl mp-install nuxeo-web-ui-override-element-redefine-bundled/nuxeo-web-ui-override-element-redefine-bundled-package/target/nuxeo-web-ui-override-element-redefine-bundled-*.zip
```

## Support

**These features are not part of the Nuxeo Production platform, they are not supported**

These solutions are provided for inspiration and we encourage customers to use them as code samples and learning resources.

This is a moving project (no API maintenance, no deprecation process, etc.) If any of these solutions are found to be useful for the Nuxeo Platform in general, they will be integrated directly into platform, not maintained here.

## License

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

## About Hyland Nuxeo

Nuxeo Platform is an open source Content Services platform, written in Java. Data can be stored in both SQL & NoSQL databases.

The development of the Nuxeo Platform is mostly done by Nuxeo employees with an open development model.

The source code, documentation, roadmap, issue tracker, testing, benchmarks are all public.

Typically, Nuxeo users build different types of information management solutions for [document management](https://www.nuxeo.com/solutions/document-management/), [case management](https://www.nuxeo.com/solutions/case-management/), and [digital asset management](https://www.nuxeo.com/solutions/dam-digital-asset-management/), use cases. It uses schema-flexible metadata & content models that allows content to be repurposed to fulfill future use cases.

More information is available at [www.nuxeo.com](https://www.nuxeo.com).


