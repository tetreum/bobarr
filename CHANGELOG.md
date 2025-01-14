# Changelog

## Master (pre-release)

### Added

- display downloaded torrent informations in movie details card (https://github.com/iam4x/bobarr/pull/146)
- choose the origanize file strategy between symlink, move or copy (https://github.com/iam4x/bobarr/issues/130)
- upload own .torrent or paste magnet link (https://github.com/iam4x/bobarr/issues/123)
- env variable to change movies/tvshows folder name (https://github.com/iam4x/bobarr/issues/116)
- calendar based on your actual library (https://github.com/iam4x/bobarr/issues/75)
- clear redis cache action in settings

### Fixes

- sort movies and tvshows by recently added
- handle multiple files with same extensions, like a sample of the movie downloaded
- cache requests to tmdb api (perf)
- fix discover download tvshow fails (https://github.com/iam4x/bobarr/issues/104)
- enable firewall in vpn container, this will prevent download starts before vpn is connected (https://github.com/iam4x/bobarr/issues/132)
- disable ipv6 in vpn container (https://github.com/iam4x/bobarr/issues/133)

## [v1.0.0-beta.1] - 2020-05-20

### Added

- download movies / tv shows
- search movies / tv shows with keywords
- search movies / tv shows with filters (year, genre, score...)
- recommendations based on what you have in your library
- scan your library to automatically track what you manually download
- auto-download missing movies / tv shows periodically
- auto-download new tv shows episodes
- support multi languages torrent trackers
