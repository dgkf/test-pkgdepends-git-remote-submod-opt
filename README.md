# Test Case for `pkgdepends`

This repo contains two `git` submodules, which are currently unsupported in 
`pkgdepends`. Neither is required for installation. 

- The first is outside the package sub-directory
- The second is ignored as specified in `.Rbuildignore`

As neither is required for installation, the remaining files from the repo
should be sufficient for installation, even if they fail to be fetched.

Further discussion in 
[`pkgdepends#354`](https://github.com/r-lib/pkgdepends/issues/354), 
[`pkgdepends#355`](https://github.com/r-lib/pkgdepends/pull/355).
