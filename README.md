### Software rendered SDLQuake

Source: https://www.libsdl.org/projects/quake/

This repo has all the unused files removed. `extern` keyword is added to some of the files to support gcc10+. Tested under gcc11.

To compile, run:

```
> linux32 ./configure
> linux32 make
```

Note: You must have libsdl1.2-dev:i386 installed