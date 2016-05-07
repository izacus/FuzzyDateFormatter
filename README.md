Fuzzy Date Formatter
========================

A simple formatter library which formats dates in a fuzzy form for display in apps. E.g.

```
Calendar -> "6 minutes ago"
```

Contributions and translations welcome.

Usage
-------

```groovy
repositories {
    jcenter()
}

dependencies {
    compile 'si.virag:fuzzydateformatter:1.1.0'
}
```

```java
Date date = new Date();
String text = FuzzyDateTimeFormatter.getTimeAgo(context, date);
```

License
-------

    Copyright 2015 Jernej Virag

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.