# brms

<details>

* Version: 2.10.0
* Source code: https://github.com/cran/brms
* URL: https://github.com/paul-buerkner/brms, http://discourse.mc-stan.org
* BugReports: https://github.com/paul-buerkner/brms/issues
* Date/Publication: 2019-08-29 15:50:07 UTC
* Number of recursive dependencies: 168

Run `revdep_details(,"brms")` for more info

</details>

## Newly broken

*   R CMD check timed out
    

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.6Mb
      sub-directories of 1Mb or more:
        R     4.1Mb
        doc   2.6Mb
    ```

# dynr

<details>

* Version: 0.1.15-1
* Source code: https://github.com/cran/dynr
* Date/Publication: 2019-10-05 06:50:02 UTC
* Number of recursive dependencies: 120

Run `revdep_details(,"dynr")` for more info

</details>

## In both

*   checking whether package ‘dynr’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/dynr/new/dynr.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘dynr’ ...
** package ‘dynr’ successfully unpacked and MD5 sums checked
** using staged installation
checking for gsl-config... no
configure: error: gsl-config not found, is GSL installed?
ERROR: configuration failed for package ‘dynr’
* removing ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/dynr/new/dynr.Rcheck/dynr’

```
### CRAN

```
* installing *source* package ‘dynr’ ...
** package ‘dynr’ successfully unpacked and MD5 sums checked
** using staged installation
checking for gsl-config... no
configure: error: gsl-config not found, is GSL installed?
ERROR: configuration failed for package ‘dynr’
* removing ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/dynr/old/dynr.Rcheck/dynr’

```
# Hmisc

<details>

* Version: 4.3-0
* Source code: https://github.com/cran/Hmisc
* URL: http://biostat.mc.vanderbilt.edu/Hmisc, https://github.com/harrelfe/Hmisc
* Date/Publication: 2019-11-07 19:20:02 UTC
* Number of recursive dependencies: 121

Run `revdep_details(,"Hmisc")` for more info

</details>

## In both

*   checking whether package ‘Hmisc’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/Hmisc/new/Hmisc.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘Hmisc’ ...
** package ‘Hmisc’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
/usr/local/opt/llvm/bin/clang -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG   -isysroot /Library/Developer/CommandLineTools/SDKs/MacOSX.sdk -I/usr/local/include  -fPIC  -Wall -g -O2  -c Hmisc.c -o Hmisc.o
gfortran  -fPIC  -Wall -g -O2  -c cidxcn.f -o cidxcn.o
gfortran-4.2: error trying to exec '/usr/local/bin/i686-apple-darwin8-gfortran-4.2': execvp: Bad CPU type in executable
make: *** [cidxcn.o] Error 255
ERROR: compilation failed for package ‘Hmisc’
* removing ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/Hmisc/new/Hmisc.Rcheck/Hmisc’

```
### CRAN

```
* installing *source* package ‘Hmisc’ ...
** package ‘Hmisc’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
/usr/local/opt/llvm/bin/clang -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG   -isysroot /Library/Developer/CommandLineTools/SDKs/MacOSX.sdk -I/usr/local/include  -fPIC  -Wall -g -O2  -c Hmisc.c -o Hmisc.o
gfortran  -fPIC  -Wall -g -O2  -c cidxcn.f -o cidxcn.o
gfortran-4.2: error trying to exec '/usr/local/bin/i686-apple-darwin8-gfortran-4.2': execvp: Bad CPU type in executable
make: *** [cidxcn.o] Error 255
ERROR: compilation failed for package ‘Hmisc’
* removing ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/Hmisc/old/Hmisc.Rcheck/Hmisc’

```
# MissingDataGUI

<details>

* Version: 0.2-5
* Source code: https://github.com/cran/MissingDataGUI
* Date/Publication: 2016-04-25 08:58:53
* Number of recursive dependencies: 103

Run `revdep_details(,"MissingDataGUI")` for more info

</details>

## In both

*   checking whether package ‘MissingDataGUI’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/MissingDataGUI/new/MissingDataGUI.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘MissingDataGUI’ ...
** package ‘MissingDataGUI’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** data
*** moving datasets to lazyload DB
** inst
** byte-compile and prepare package for lazy loading
Error in dyn.load(file, DLLpath = DLLpath, ...) : 
  unable to load shared object '/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/RGtk2/libs/RGtk2.so':
  dlopen(/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/RGtk2/libs/RGtk2.so, 6): Library not loaded: /Library/Frameworks/GTK+.framework/Versions/2.24.X11/Resources/lib/libgtk-x11-2.0.0.dylib
  Referenced from: /Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/RGtk2/libs/RGtk2.so
  Reason: image not found
Please install GTK+ from http://r.research.att.com/libs/GTK_2.24.17-X11.pkg
If the package still does not load, please ensure that GTK+ is installed and that it is on your PATH environment variable
IN ANY CASE, RESTART R BEFORE TRYING TO LOAD THE PACKAGE AGAIN
Error in dyn.load(file, DLLpath = DLLpath, ...) : 
  unable to load shared object '/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so':
  dlopen(/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so, 6): Library not loaded: /Library/Frameworks/GTK+.framework/Versions/2.24.X11/Resources/lib/libgtk-x11-2.0.0.dylib
  Referenced from: /Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so
  Reason: image not found
In addition: Warning message:
Failed to load RGtk2 dynamic library, attempting to install it. 
Please install GTK+ from http://r.research.att.com/libs/GTK_2.18.5-X11.pkg
If the package still does not load, please ensure that GTK+ is installed and that it is on your PATH environment variable
IN ANY CASE, RESTART R BEFORE TRYING TO LOAD THE PACKAGE AGAIN
Error: package or namespace load failed for ‘gWidgetsRGtk2’:
 .onAttach failed in attachNamespace() for 'gWidgetsRGtk2', details:
  call: .Call(name, ..., PACKAGE = PACKAGE)
  error: "S_gtk_icon_factory_new" not available for .Call() for package "RGtk2"
Error: package ‘gWidgetsRGtk2’ could not be loaded
In addition: Warning message:
In fun(libname, pkgname) :
  Failed to load cairoDevice, attempting to install itError in dyn.load(file, DLLpath = DLLpath, ...) : 
  unable to load shared object '/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so':
  dlopen(/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so, 6): Library not loaded: /Library/Frameworks/GTK+.framework/Versions/2.24.X11/Resources/lib/libgtk-x11-2.0.0.dylib
  Referenced from: /Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so
  Reason: image not found

Execution halted
ERROR: lazy loading failed for package ‘MissingDataGUI’
* removing ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/MissingDataGUI/new/MissingDataGUI.Rcheck/MissingDataGUI’

```
### CRAN

```
* installing *source* package ‘MissingDataGUI’ ...
** package ‘MissingDataGUI’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** data
*** moving datasets to lazyload DB
** inst
** byte-compile and prepare package for lazy loading
Error in dyn.load(file, DLLpath = DLLpath, ...) : 
  unable to load shared object '/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/RGtk2/libs/RGtk2.so':
  dlopen(/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/RGtk2/libs/RGtk2.so, 6): Library not loaded: /Library/Frameworks/GTK+.framework/Versions/2.24.X11/Resources/lib/libgtk-x11-2.0.0.dylib
  Referenced from: /Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/RGtk2/libs/RGtk2.so
  Reason: image not found
Please install GTK+ from http://r.research.att.com/libs/GTK_2.24.17-X11.pkg
If the package still does not load, please ensure that GTK+ is installed and that it is on your PATH environment variable
IN ANY CASE, RESTART R BEFORE TRYING TO LOAD THE PACKAGE AGAIN
Error in dyn.load(file, DLLpath = DLLpath, ...) : 
  unable to load shared object '/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so':
  dlopen(/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so, 6): Library not loaded: /Library/Frameworks/GTK+.framework/Versions/2.24.X11/Resources/lib/libgtk-x11-2.0.0.dylib
  Referenced from: /Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so
  Reason: image not found
In addition: Warning message:
Failed to load RGtk2 dynamic library, attempting to install it. 
Please install GTK+ from http://r.research.att.com/libs/GTK_2.18.5-X11.pkg
If the package still does not load, please ensure that GTK+ is installed and that it is on your PATH environment variable
IN ANY CASE, RESTART R BEFORE TRYING TO LOAD THE PACKAGE AGAIN
Error: package or namespace load failed for ‘gWidgetsRGtk2’:
 .onAttach failed in attachNamespace() for 'gWidgetsRGtk2', details:
  call: .Call(name, ..., PACKAGE = PACKAGE)
  error: "S_gtk_icon_factory_new" not available for .Call() for package "RGtk2"
Error: package ‘gWidgetsRGtk2’ could not be loaded
In addition: Warning message:
In fun(libname, pkgname) :
  Failed to load cairoDevice, attempting to install itError in dyn.load(file, DLLpath = DLLpath, ...) : 
  unable to load shared object '/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so':
  dlopen(/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so, 6): Library not loaded: /Library/Frameworks/GTK+.framework/Versions/2.24.X11/Resources/lib/libgtk-x11-2.0.0.dylib
  Referenced from: /Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/MissingDataGUI/cairoDevice/libs/cairoDevice.so
  Reason: image not found

Execution halted
ERROR: lazy loading failed for package ‘MissingDataGUI’
* removing ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/MissingDataGUI/old/MissingDataGUI.Rcheck/MissingDataGUI’

```
# Replication

<details>

* Version: 0.1.1
* Source code: https://github.com/cran/Replication
* Date/Publication: 2019-08-01 14:50:02 UTC
* Number of recursive dependencies: 107

Run `revdep_details(,"Replication")` for more info

</details>

## In both

*   checking whether package ‘Replication’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/Replication/new/Replication.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘Replication’ ...
** package ‘Replication’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** byte-compile and prepare package for lazy loading
Error: .onLoad failed in loadNamespace() for 'rjags', details:
  call: dyn.load(file, DLLpath = DLLpath, ...)
  error: unable to load shared object '/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/Replication/rjags/libs/rjags.so':
  dlopen(/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/Replication/rjags/libs/rjags.so, 10): Library not loaded: /usr/local/lib/libjags.4.dylib
  Referenced from: /Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/Replication/rjags/libs/rjags.so
  Reason: image not found
Execution halted
ERROR: lazy loading failed for package ‘Replication’
* removing ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/Replication/new/Replication.Rcheck/Replication’

```
### CRAN

```
* installing *source* package ‘Replication’ ...
** package ‘Replication’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** byte-compile and prepare package for lazy loading
Error: .onLoad failed in loadNamespace() for 'rjags', details:
  call: dyn.load(file, DLLpath = DLLpath, ...)
  error: unable to load shared object '/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/Replication/rjags/libs/rjags.so':
  dlopen(/Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/Replication/rjags/libs/rjags.so, 10): Library not loaded: /usr/local/lib/libjags.4.dylib
  Referenced from: /Users/buurensv/Dropbox/Package/mice/mice/revdep/library.noindex/Replication/rjags/libs/rjags.so
  Reason: image not found
Execution halted
ERROR: lazy loading failed for package ‘Replication’
* removing ‘/Users/buurensv/Dropbox/Package/mice/mice/revdep/checks.noindex/Replication/old/Replication.Rcheck/Replication’

```
