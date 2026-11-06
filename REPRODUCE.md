# Reproducing this repository

```
python tools/fetch_cap.py <cache> us f f2d f3d f-appx
python tools/build.py ca7 <cache>/<reporter>,... <empty folder> --today 2026-11-06
```

Input: static.case.law reporter volume zips (CC0). Gives 49,221 decision commits and one documentation commit.
