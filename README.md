# hashids.as
Generate short unique ids from integers

### Build Instructions

To build the JW Player, you will need the following software:

 * Flex SDK 4.1: http://sourceforge.net/adobe/flexsdk/wiki/Downloads/
 * Ant 1.7.0: http://ant.apache.org/bindownload.cgi

To compile with Flex and Ant, you'll first need to modify the `build.properties` file found in the `src` folder:

* Set `FLEX_HOME` to the install location of the Flex SDK (e.g. `/usr/local/bin/flex/`)

You can now compile the player using Ant:

```sh
ant -buildfile hashids\src\build.xml
```

If the build is successful, the hashids.swf will appear in the `bin` folder.
