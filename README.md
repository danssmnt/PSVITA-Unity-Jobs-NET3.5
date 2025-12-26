# Unity Jobs Packages for .NET 3.5 (useful for PSVita development)

Some useful packages for Unity Jobs (works on PSVita) made compatible with .NET 3.5 (C# 4.0).

Included are:
 - Unity.Collections (0.0.9-preview.10)
 - Unity.Jobs (0.0.7-preview.5)
 - Unity.Mathematics (0.0.12-preview.20)

Confirmed working on *Unity 2018.2.19f1* with PSVita (PSP2) Tools.

## For what?

These packages overwrite unity math functions with custom native ones which run way faster with IL2CPP, so it's useful for game ports and development in general. (Tested on PSVita)

## Installing (Windows)
Simply add the 3 package folders to ``C:/Users/{Username}/AppData/Local/Unity/cache/packages/packages.unity.com/`` and write the following to ``{Your Project Path}/Packages/manifest.json`` inside ``dependencies``:
```
    "com.unity.collections": "0.0.9-preview.10",
    "com.unity.jobs": "0.0.7-preview.5",
    "com.unity.mathematics": "0.0.12-preview.20",
```
