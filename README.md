Android Device Compatibility Package
======
[![Build Status](https://travis-ci.org/mixi-inc/Android-Device-Compatibility.svg?branch=master)](https://travis-ci.org/mixi-inc/Android-Device-Compatibility)

Yet another compatibility package of android. This project aims to make the app compatible with various devices all over the world.
The project will take care about lots of issues caused by device differences, so you don't need to write a weird compatibility code on your own.

![](https://farm5.staticflickr.com/4032/4302079406_aab8748987_o_d.jpg)
[Photo license](https://creativecommons.org/licenses/by/2.0/)

Features
-------

* Workarounds for device-specific problems
* OS version compatibility
* OS framework bugfixes

Requirements
-------

* Supports Android 2.1 or greater.

Download
-------

Via Gradle

```
repositories {
    mavenCentral()
    maven { url 'https://raw.github.com/mixi-inc/Android-Device-Compatibility/master/repository/' }
}
android {
    dependencies {
        compile 'jp.mixi.compatibility:AndroidDeviceCompatibility:0.1.0'
    }
}
```

Contributing
-------

Any contributions, bug fixes, unit/integration tests are welcomed and appreciated.
Please fork this repository and send pull requests to contribute.

License
-------

```
Copyright (C) 2012 mixi, Inc. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
