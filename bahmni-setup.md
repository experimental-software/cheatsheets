---
title: Bahmni setup
category: Bahmni
layout: 2017/sheet
---

## Snippets
```
BAHMNI_VERSION= # e.g. 0.89
BAHMNI_BUILD_NUMBER= # e.g. 208

curl https://github.com/ksch-workflows/infrastructure/blob/master/bahmni/install-bahmni.sh > install-bahmni.sh
bash install-bahmni.sh -v ${BAHMNI_VERSION} -b ${BAHMNI_BUILD_NUMBER}
```

## Documentation
- [Install Bahmni on CentOS](https://bahmni.atlassian.net/wiki/spaces/BAH/pages/33128505/Install+Bahmni+on+CentOS)
- [All Bahmni releases](https://bahmni.atlassian.net/wiki/spaces/BAH/pages/70221837/All+Bahmni+Releases)
- [Troubleshooting Installation Issues](https://bahmni.atlassian.net/wiki/spaces/BAH/pages/71860313/Troubleshooting+Installation+Issues)
