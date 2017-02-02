A fork of bypass library that allows to use different font for bold, italic and italicbold formatted texts. It uses a custom font span under the hood.

3 new methods were added:
```java
Bypass.setsetBoldTypeface(Typeface)
Bypass.setItalicTypeface(Typeface)
Bypass.setBoldItalicTypeface(Typeface)
```

# Gradle Dependency

```gradle
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```

```gradle
dependencies {
    compile 'com.github.mzgreen:bypasses:1.0.5'
}
```


# Usage
See http://uncodin.github.io/bypass/

# Robolectric
See [this issue](https://github.com/Commit451/bypasses/issues/2) for an explination for getting Robolectric to work.

# Proguard
This dependency also packages the Proguard rules [suggested](https://github.com/Uncodin/bypass/issues/195) for bypass to work properly with Proguard enabled

License
--------

    Copyright 2015 Commit 451
    Copyright 2015 Uncodin

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

