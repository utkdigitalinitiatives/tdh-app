# [T]ennessee [D]ocumentary [H]istory #

## About ##
This repository currently contains data assets for building and deploying the Tennessee Documentary History project in [exist-db](http://exist-db.org/exist/apps/homepage/index.html).

## Build Requirements ##
- [Ant](https://ant.apache.org/)

## eXist Requirements ##
- [eXist, v4.5.0](https://bintray.com/existdb/releases/exist/4.5.0)

## Building the .xar ##
To build the TDH app .xar:
1. git clone git@github.com/:utkdigitalinitiatives/tdh-app
2. cd tdh-app
3. ant -f build.xml

## Deploying the .xar ##
1. Visit your eXist dashboard; i.e. `localhost:8080/exist/apps/dashboard`.
2. Authenticate and select **Package Manager**.
3. Click the **+** icon to upload a package and select your .xar from the `build` directory.
