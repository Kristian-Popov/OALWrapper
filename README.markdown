OAL Wrapper Source Code
=======================

Build status, Ubuntu 20.04 x64 | [![Build Status](https://travis-ci.org/Kristian-Popov/OALWrapper.svg?branch=improvements)](https://travis-ci.org/Kristian-Popov/OALWrapper)
----------------- | ---------------

Yes, here is the OpenAL C++ Wrapper that was built and used for the Penumbra series as well as Amnesia: The Dark Descent.

Read through the TODO file for various known things that should be cleaned up / fixed.

Included are project files for Xcode, Cmake (for Linux).

Changes specific to this port:
* Does not use precompiled libraries from dependencies bundle, instead system libraries are used.
* Removed most unused code from CMake file, like support of macOS, Emscripten, iOS, SDL 1

Contributing Code
-----------------
We encourage everyone to contribute code to this project, so just sign up for a github account, create a fork and hack away at the codebase. We will start an Open Source forum on the Frictional Games forums as a place to talk about changes and to submit patches from your forks.

License Information
-------------------
All code is under the zlib license. Please read the LICENSE file for more information on terms of use.
