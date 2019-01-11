<p align="center">
<img src="https://avatars2.githubusercontent.com/u/46451214?s=400&u=5d5b9c58fe5ff1dffd63846df5f923e9dd838172&v=4" >
</p>

---------------------------------------------------------------------------------------
 Getting Started:
 ==============

To get started with Pearl-OS, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/PearlOS/platform_manifest.git -b pie

```

Then to sync up:

```
repo sync -c -f --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j8
```

---------------------------------------------------------------------------------------
 Compilation of PearlOS:
 ==================

From root directory of Project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch pearl_$device-userdebug
$ mka bacon pearl or brunch device
```
---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**DotOS**](https://github.com/DotOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**CypherOS**](https://github.com/CypherOS)
 * [**Xtended**](https://github.com/Xtended-Pie)

---------------------------------------------------------------------------------------
