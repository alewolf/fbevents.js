# fbevents.js

An archive of historical versions of Facebook's pixel tracking script `fbevents.js`. Useful for diffing changes between releases, auditing behavior over time, or pinning a specific version.

## Versions

Each version below links to the file in this repo and the original source it was retrieved from. Versions are listed newest first.

| Version | Released | File | Source |
| --- | --- | --- | --- |
| 2.9.324 | (added 22.05.2026) | [versions/2.9.324.js](versions/2.9.324.js) | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.324) |
| 2.9.300 | (added 22.05.2026) | [versions/2.9.300.js](versions/2.9.300.js) | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.300) |
| 2.9.200 | (added 22.05.2026) | [versions/2.9.200.js](versions/2.9.200.js) | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.200) |
| 2.9.134 | 15.10.2023 | [versions/2.9.134.js](versions/2.9.134.js) | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.134) |
| 2.9.121 | 05.08.2023 | [versions/2.9.121.js](versions/2.9.121.js) | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.121) |
| 2.9.94  | 22.01.2023 | [versions/2.9.94.js](versions/2.9.94.js)   | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.94) |
| 2.9.93  | 22.01.2023 | [versions/2.9.93.js](versions/2.9.93.js)   | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.93) |
| 2.9.92  | 22.01.2023 | [versions/2.9.92.js](versions/2.9.92.js)   | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.92) |
| 2.9.91  | 22.01.2023 | [versions/2.9.91.js](versions/2.9.91.js)   | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.91) |
| 2.9.90  | 22.01.2023 | [versions/2.9.90.js](versions/2.9.90.js)   | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.90) |
| 2.9.89  | 22.01.2023 | [versions/2.9.89.js](versions/2.9.89.js)   | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.89) |
| 2.9.88  | 22.01.2023 | [versions/2.9.88.js](versions/2.9.88.js)   | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.88) |
| 2.9.87  | 22.01.2023 | [versions/2.9.87.js](versions/2.9.87.js)   | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.87) |
| 2.9.84  | 22.01.2023 | [versions/2.9.84.js](versions/2.9.84.js)   | [connect.facebook.net](https://connect.facebook.net/en_US/fbevents.js?v=2.9.84) |
| 2.9.15  | 18.12.2019 | [versions/2.9.15.js](versions/2.9.15.js)   | [gist.github.com](https://gist.github.com/annewanghy/14052a329e2694a4845b89b940b8759b) |
| 2.8.14  | 15.05.2018 | [versions/2.8.14.js](versions/2.8.14.js)   | [github.com/popoiopo](https://github.com/popoiopo/dataMining/blob/master/Using%20Python%20to%20place%20in%20the%20top%2015%20of%20the%20Kaggle%20Expedia%20competition_files/fbevents.js.download) |
| 2.8.0   | 23.08.2021 | [versions/2.8.0.js](versions/2.8.0.js)     | [3sdigital.com.br](https://3sdigital.com.br/imagem/Pagar%20por%20BoletoReceipt%20Payment_files/fbevents.js.download) |
| 2.5.1   | 06.01.2017 | [versions/2.5.1.js](versions/2.5.1.js)     | [gist.github.com](https://gist.github.com/sunderls/dfd5293a8b8f24a4ef37189a1d8c1b46) |

> The "Released" date is the date the version was first observed in the wild, not necessarily Facebook's internal release date. When possible, versions are pulled directly from `connect.facebook.net`.

## CDN

### From Facebook

Append a `v` query parameter to request a specific version:

```
https://connect.facebook.net/en_US/fbevents.js?v=2.9.324
```

Only versions Facebook has actually released are served this way. Requesting an unknown version silently returns the latest build.

The latest version is always available at:

```
https://connect.facebook.net/en_US/fbevents.js
```

### From this repo (jsDelivr)

To pin a specific historical version, link via jsDelivr:

```
https://cdn.jsdelivr.net/gh/alewolf/fbqevent.js/versions/2.9.324.js
```

Replace the version number in the path as needed.

## Contributing

If you have a version that isn't in the archive yet, please open a PR adding the file under [versions/](versions/) and a corresponding row in the table above. Including a working source URL is appreciated.
