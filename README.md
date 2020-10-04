# EvaSysWs

EvaSysWs is a Java Spring ... used to ...

## Installing & running

To get this project to work in its current state, following steps must be taken prior to building/running it:

- Eclipse Photon or lower must be used (if newer versions are also found to work, please update this readme file)
- Alongside JDK 1.8, 1.6 must also be installed and configured when building (see below)
- Maven version 3.2.5 or lower must be used because of an incompatibility between it and the version of schemagen that we are using


## Building with Maven

Before deploying, the project must be run with the "generate-schemas" profile.
The Run Configuration when generating the schemas should look like this.
![Build config for generation](https://github.com/IgorMilanovic23/IgorMilanovic23.github.io/blob/master/images/pic01.jpg)

After running with the above config and checking if the schemas have been generated correctly, following Run Configuration should be used for deployment:
![Build config for deployment](https://github.com/IgorMilanovic23/IgorMilanovic23.github.io/blob/master/images/pic02.jpg)


## License
\-
