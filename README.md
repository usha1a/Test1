What is Zing? ![Zulu Duke in a Box][1]
======================================

Azul Zing is a runtime platform that uses the Zing Virtual Machine to run Java™ technology-based applications for Linux operating systems. The Zing Virtual Machine (ZVM) allows existing Java applications to elastically scale to dozens of CPU cores and hundreds of gigabytes of memory, meaning resources can also scale up and down based on real-time demands, and without garbage collection pauses present in other Java runtimes.

Azul Zing is compliant with the Java SE standard. 

Zing is built, tested, supported, and delivered by [Azul Systems][2].

Check out [Zing Overview][3] for more information.

Ubuntu and Debian Docker images of Zing are available in the following repositories:

  * [smetsys1uza/zing][7]
  * [smetsys1uza/zing-debian][6]

Usage
=====

This Zing repository supports numerous versions of OpenJDK-based Java SE JDKs. Versions 11 and 8 of Zing are compliant with Java SE 11 and 8 respectively.

To run a container of your choice, use commands below as an example.

For a Zing 11 container, enter:

    docker run -it --rm smetsys1uza/zing-centos:11 java -version

For a Zing 8 container, enter:

    docker run -it --rm smetsys1uza/zing-centos:8 java -version


  [1]: https://www.azul.com/files/ZuluDocker60.gif
  [2]: http://www.azul.com/zing
  [3]: https://www.azul.com/products/zing/
  [6]: https://hub.docker.com/r/smetsys1uza/zing-debian
  [7]: https://hub.docker.com/r/smetsys1uza/zing
  [53]: https://github.com/alex01t/zing/blob/master/centos/8-19.07.0.0-4/Dockerfile
  [84]: https://github.com/alex01t/zing/blob/master/centos/11-19.07.0.0-4/Dockerfile
