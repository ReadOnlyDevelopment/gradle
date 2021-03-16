# Galacticraft Dev Jars

**IMPORTANT** (This is only for Minecraft 1.12.2)

Two options are available.
* Get defined build version
* Get the latest version


## Defined Version
USE ONLY for builds 261 and below

In your `build.gradle` script. Add the following block and define the version you want
```gradle
project.ext {
	gcbuild = "###"
}

apply from: "https://raw.githubusercontent.com/ReadOnlyDevelopment/gradle/galacticraft/dev.gradle"
```
-> *`###` is the build number you want to use* 

**Note**
If your going to just put the latest build number simply use the `dev-latest` script. That script will always define the latest version


## Latest Version (Disabled Due To Error)
### Do Not Try to Compile against this script

In your `build.gradle` script. Add the following block and define the version you want

<details>
  <summary>Hidden Until Fixed</summary>
```gradle
apply from: "https://raw.githubusercontent.com/ReadOnlyDevelopment/gradle/galacticraft/dev-latest.gradle"
```
</details>

Special Thanks to [Marcus8448](https://github.com/marcus8448) for creating the ivy repository part of the script
