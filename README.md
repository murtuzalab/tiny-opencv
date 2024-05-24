## OpenCV: Open Source Computer Vision Library

This is a fork of the opencv/opencv:4.x. branch. 

To build a tiny version of opencv world ~8.2MB (for x64, original: 65.5 MB) with:
* core
* highgui
* imgcodecs
* imgproc
* world

Use the below cmake options:

```
BUILD_JPEG=ON
BUILD_OPENEXR=ON
BUILD_OPENEXR=ON
BUILD_OPENJPEG=ON
BUILD_PACKAGE=ON
BUILD_PNG=ON
BUILD_SHARED_LIBS=ON
BUILD_ZLIB=ON
BUILD_opencv_core=ON
BUILD_opencv_highgui=ON
BUILD_opencv_imgcodecs=ON
BUILD_opencv_imgproc=ON
BUILD_opencv_world=ON
ENABLE_SOLUTION_FOLDERS=ON
INSTALL_PDB=ON
INSTALL_PDB_COMPONENT_EXCLUDE_FROM_ALL=ON
OPENCV_ENABLE_ALLOCATOR_STATS=ON
OPENCV_ENABLE_ATOMIC_LONG_LONG=ON
OPENCV_ENABLE_MEMALIGN=ON
OPENCV_GENERATE_SETUPVARS=ON
OPJ_USE_THREAD=ON
WITH_JASPER=ON
WITH_JPEG=ON
WITH_OPENEXR=ON
WITH_OPENJPEG=ON
WITH_PNG=ON
WITH_PROTOBUF=ON
WITH_TIFF=ON
WITH_WEBP=ON
ccitt=ON
logluv=ON
lzw=ON
mdi=ON
next=ON
packbits=ON
thunder=ON
```



### Resources

* Homepage: <https://opencv.org>
  * Courses: <https://opencv.org/courses>
* Docs: <https://docs.opencv.org/4.x/>
* Q&A forum: <https://forum.opencv.org>
  * previous forum (read only): <http://answers.opencv.org>
* Issue tracking: <https://github.com/opencv/opencv/issues>
* Additional OpenCV functionality: <https://github.com/opencv/opencv_contrib>
* Donate to OpenCV: <https://opencv.org/support/>


### Contributing

Please read the [contribution guidelines](https://github.com/opencv/opencv/wiki/How_to_contribute) before starting work on a pull request.

#### Summary of the guidelines:

* One pull request per issue;
* Choose the right base branch;
* Include tests and documentation;
* Clean up "oops" commits before submitting;
* Follow the [coding style guide](https://github.com/opencv/opencv/wiki/Coding_Style_Guide).

### Additional Resources

* [Submit your OpenCV-based project](https://form.jotform.com/233105358823151) for inclusion in Community Friday on opencv.org
* [Subscribe to the OpenCV YouTube Channel](http://youtube.com/@opencvofficial) featuring OpenCV Live, an hour-long streaming show
* [Follow OpenCV on LinkedIn](http://linkedin.com/company/opencv/) for daily posts showing the state-of-the-art in computer vision & AI
* [Apply to be an OpenCV Volunteer](https://form.jotform.com/232745316792159) to help organize events and online campaigns as well as amplify them
* [Follow OpenCV on Mastodon](http://mastodon.social/@opencv) in the Fediverse
* [Follow OpenCV on Twitter](https://twitter.com/opencvlive)
* [OpenCV.ai](https://opencv.ai): Computer Vision and AI development services from the OpenCV team.
