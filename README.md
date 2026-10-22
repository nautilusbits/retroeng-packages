# RetroEng packages

Public NuGet feed for the RetroEng engine binaries (closed source,
non-commercial binary licence: see LICENSE-RetroEng.txt).

Add the feed to your `nuget.config`:

```xml
<configuration>
  <packageSources>
    <add key="nuget.org" value="https://api.nuget.org/v3/index.json" />
    <add key="retroeng" value="https://nautilusbits.github.io/retroeng-packages/index.json" />
  </packageSources>
</configuration>
```

Packages: RetroEng.Core, RetroEng.Platform, RetroEng.Render, RetroEng.Audio,
RetroEng.Physics, RetroEng.Net, RetroEng.Editor, RetroEng.Native.
