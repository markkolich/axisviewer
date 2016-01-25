# axisviewer

Java app to watch/stream a motion JPEG feed from an Axis network camera.

## Building

This app is built using Maven.

To package the application into a runnable JAR, run:

```
mvn clean package
```

The resulting runnable JAR will be dropped into the `dist` directory.

## Running

Invoke the `*-runnable.jar` JAR to start the application.  Pass the URL to the camera feed using the `--url` argument:

```
cd dist
java -jar axisviewer-0.1-runnable.jar --url "http://10.0.1.6/axis-cgi/jpg/image.cgi?resolution=640x480"
```

## Licensing

Copyright (c) 2016 <a href="http://mark.koli.ch">Mark S. Kolich</a>

All code in this project is freely available for use and redistribution under the <a href="http://opensource.org/comment/991">MIT License</a>.

See <a href="https://github.com/markkolich/axisviewer/blob/master/LICENSE">LICENSE</a> for details.
