
PySceneDetect Changelog
==========================================================


## 0.4-beta-dev (features planned or in development)
 * [feature]  graphical user interface (GTK+)
 * [enhance]  added configuration file to support more options and cleanup/remove some command-line arguments
 * [feature]  user-selectable fade bias when using threshold-based detection
 * [internal] preperation for automated splitting via integration with supported tools (ffmpeg, avconv, mkvmerge)
 * [internal] framework for edge-detection and dissolve/fade based scene cut algorithms for future versions


----------------------------------------------------------------


### 0.3.1-beta (in development)

 * [feature] restored function of statistics generation mode (-s/--statsfile)


## 0.3-beta (January 8, 2016)

 * major release, includes improved detection algorithms and complete internal code refactor
 * [feature]  content-aware scene detection using HSV-colourspace based algorithm (use `-d content`)
 * [enhance]  added CLI flags to allow user changes to more algorithm properties
 * [internal] re-implemented threshold-based scene detection algorithm under new interface
 * [internal] major code refactor including standard detection algorithm interface and API
 * [internal] remove statistics mode until update to new detection mode interface


----------------------------------------------------------------


### 0.2.4-alpha (December 22, 2015)
 * [bugfix] updated OpenCV compatibility with self-reported version on some Linux distributions


### 0.2.3-alpha (August 7, 2015)
 * [bugfix]  updated PySceneDetect to work with latest OpenCV module (ver > 3.0)
 * [bugfix]  added compatibility/legacy code for older versions of OpenCV
 * [feature] statsfile generation includes expanded frame metrics


### 0.2.2-alpha (November 25, 2014)

 * [feature] added statistics mode for generating frame-by-frame analysis (-s / --statsfile flag)
 * [bugfix]  fixed improper timecode conversion


### 0.2.1-alpha (November 16, 2014)

 * [enhance] proper timecode format (HH:MM:SS.nnnnn)
 * [enhance] one-line of CSV timecodes added for easy splitting with external tool


## 0.2-alpha (June 9, 2014)

 * [enhance] now provides discrete scene list (in addition to fades)
 * [feature] ability to output to file (-o / --output flag)


----------------------------------------------------------------


## 0.1-alpha (June 8, 2014)

 * first public release
 * [feature] threshold-based fade in/out detection
