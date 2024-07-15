# Daniel's Website

The base setup is based on [duplone.github.io], see [BSD-3](/BSD-3.txt).
Further—less direct—inspirations include [gwern.net][gwern.net] and
[Practical Typography][practical-typography].

[duplone.github.io]: https://github.com/duplode/duplode.github.io/
[gwern.net]: https://gwern.net/
[practical-typography]: https://practicaltypography.com/

## Notable Features

## Requirements

- [parallel]: Needed during building.
- [node]: Needed for pre-rendering math.
- [pygmentize]: Great syntax highlighting.
- [nix]: Great tool for producing reproducible builds. Was already configured in [slotThe.github.io]. Really need to look into it someday!

[parallel]: https://www.gnu.org/software/parallel/parallel_tutorial.html
[node]: https://nodejs.org/en/download/package-manager
[pygmentize]: https://pygments.org/download/
[nix]: https://nixos.org/download/
[slotThe.github.io]: https://github.com/slotThe/slotThe.github.io

## Build

If the requirements are there, then a simple `$ ./build.sh` should enough to build! It will call `make`, which will call `nix`.