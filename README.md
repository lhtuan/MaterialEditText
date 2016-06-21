MaterialEditText
================

# Setup
Add as a dependency to your ``build.gradle``:

```groovy
repositories {
    maven {
        url 'https://dl.bintray.com/baole/maven'
    }
}
dependencies {
    compile 'org.baole.org.baole.materialedittext:1.41@aar'
}
```
# Usages

Add Foregroundxxx to your layout.xml

```

            <org.baole.MaterialEditText
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:hint="Library Name"
                android:text="MaterialEditText"
                android:textCursorDrawable="@drawable/text_cursor_cyan"
                android:textSize="34sp"
                app:met_baseColor="@android:color/white"
                app:met_floatingLabel="highlight"
                app:met_maxCharacters="20"
                app:met_primaryColor="?colorAccent"
                app:met_singleLineEllipsis="true"
                app:met_underlineFocusHeight="1dp" />
```

## Thanks to

[NineOldAndroids](https://github.com/JakeWharton/NineOldAndroids/)

## License

    Copyright 2016 baole
    Copyright 2014 rengwuxian

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
