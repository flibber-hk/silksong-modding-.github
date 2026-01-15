The following should be done before releasing a new core mod.

* Set Thunderstore icon
* Set Thunderstore description
* Set Nuget description - this should be done with a <Description> tag in the csproj, and is not in the template by default
* Check dependencies, tags etc in the thunderstore .toml file
* Check that the owner is listed as silksong-modding in:
  - Thunderstore namespace (`silksong_modding`)
  - Thunderstore website (`silksong-modding.org`)
  - Website in the csproj (`silksong-modding.org`)
  - ID in the BepInAutoPlugin attribute (`org.silksong-modding.*`)
  - Copy target in the csproj (`silksong_modding`)
