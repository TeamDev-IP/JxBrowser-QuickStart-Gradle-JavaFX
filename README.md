# JxBrowser in a Gradle-based JavaFX desktop application

This example demonstrates how to configure a Gradle project with JxBrowser to embed a `BrowserView` widget into a JavaFX desktop application to display web pages.

## Prerequisites

* Java 17 or newer.
* Your JxBrowser license key, or a [free 30-day evaluation key][web-form].

## Run the JavaFX application

Use the following command to start the application:

```bash
./gradlew run -Djxbrowser.license.key=<your_license_key>
```

Once launched, the app loads the [HTML5 test page][html5-test-page]:

![JavaFX BrowserView][javafx-browser-view]

[web-form]: https://www.teamdev.com/jxbrowser#evaluate
[html5-test-page]: https://html5test.teamdev.com
[javafx-browser-view]: https://jxbrowser-support.teamdev.com/img/articles/javafx-view.webp
