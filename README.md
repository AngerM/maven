Maven
-----
ARCHIVED: NO LONGER IN USE
I finally got around to setting up publishing to maven central. Going forward this will no longer be maintained

repository for the dev.angerm packages
To use add the raw path to your repositories list. Example:
```
repositories {
    maven {
      url = "https://raw.githubusercontent.com/AngerM/maven/main/"
    }
}
```
