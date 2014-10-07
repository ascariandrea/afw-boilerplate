# AFW BOILERPLATE
Initial configuration to work with Android Studio, gradle, android annotations e afw.

===========

### Installation
This library includes the facebook-android-sdk and the afw modules.

To install you can clone with `--recursive` flag:
```
$ git clone --recursive git@github.com:ascariandrea/afw-boilerplate.git 
```

or clone, init and update the submodules
```
$ git clone git@github.com:ascariandrea/afw-boilerplate.git my-app-folder
$ cd my-app-folder
$ git submodule init
$ git submodule update
```

#### Remove origin
Remeber to remove the `.git` folder before your start your own project.

```
$ cd my-app-folder
$ rm -rf .git
```

Then you can create your own `.git` repository with:
```
$ cd my-app-folder
$ git init .
```

### Android Studio Import

Open your Android Studio and click on *File -> Import Project ...*, the folder where you downloaded this repo.