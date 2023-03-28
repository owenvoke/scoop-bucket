# Scoop / Shovel Bucket

[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-github-actions]][link-github-actions]
[![Repo Size][ico-github-repo-size]][link-github-repo-size]

A custom bucket for [Scoop][link-scoop] and [Shovel][link-shovel].

# Install

Via Scoop

```powershell
scoop bucket add "owenvoke" "https://github.com/owenvoke/scoop-bucket"

# For a single package (replacing `package` with the required package)
scoop install "https://raw.githubusercontent.com/owenvoke/scoop-bucket/main/bucket/{package}.json"
```

## Credits

- [Owen Voke][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-github-actions]: https://img.shields.io/github/actions/workflow/status/owenvoke/scoop-bucket/auto-update.yml?branch=main&style=flat-square
[ico-github-repo-size]: https://img.shields.io/github/repo-size/owenvoke/scoop-bucket?style=flat-square

[link-github-actions]: https://github.com/owenvoke/scoop-bucket/actions
[link-github-repo-size]: https://github.com/owenvoke/scoop-bucket/tree/main/bucket
[link-scoop]: https://scoop.sh
[link-shovel]: https://shovel.ash258.com
[link-author]: https://github.com/owenvoke
[link-contributors]: ../../contributors
