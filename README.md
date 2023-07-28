# tackle2-addon-windup

[![Windup Addon Repository on Quay](https://quay.io/repository/konveyor/tackle2-addon-windup/status "Windup Addon Repository on Quay")](https://quay.io/repository/konveyor/tackle2-addon-windup) [![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/konveyor/tackle2-addon-windup/pulls) [![Test Windup Addon](https://github.com/konveyor/tackle2-addon-windup/actions/workflows/test-windup.yml/badge.svg?branch=main)](https://github.com/konveyor/tackle2-addon-windup/actions/workflows/test-windup.yml)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fkonveyor%2Ftackle2-addon-windup.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fkonveyor%2Ftackle2-addon-windup?ref=badge_shield)

Tackle (2nd generation) addon for Windup.


Task data.

*=_optional_

```
{
  output: string,
  mode: {
    binary: bool,
    withDeps: bool,
    artifact: string,
  },
  sources: [str,],
  targets: [str,],
  scope: {
    withKnown: bool,
    packages: {
      included: [str,],
      excluded: [str,]
    }
  },
  rules*: {
    path: str, 
    tags: {
      included: [str,],
      excluded: [str,]
    }
  }
}
```


## Code of Conduct
Refer to Konveyor's Code of Conduct [here](https://github.com/konveyor/community/blob/main/CODE_OF_CONDUCT.md).


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fkonveyor%2Ftackle2-addon-windup.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fkonveyor%2Ftackle2-addon-windup?ref=badge_large)