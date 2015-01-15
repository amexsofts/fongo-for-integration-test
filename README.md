
# Fongo Integration Test Plugin for grails

[Fongo](https://github.com/fakemongo/fongo) is an in-memory java implementation of MongoDB. It intercepts calls to the standard mongo-java-driver for 
finds, updates, inserts, removes and other methods. The primary use is for lightweight unit testing where you
don't want to spin up a `mongod` process.

And this project aims to create a plugin to that will make fongo available for integration tests. In some cituations Access to the real mongo proccess is required, but in most cases a fast in memory mock of mono is a great thing because it makes tests super fast. ![License Apache2](https://go-shields.herokuapp.com/license-apache2-blue.png)

## Reporting Bugs and submitting patches

If you discover a bug with fongo you can file an issue in github. At the very least, please include a complete description of the problem with steps to reproduce.
If there were exceptions thrown, please include the complete stack traces. If it's not easy to explain the problem, failing test code would be helpful.
You can fork the project and add a new failing test case. 

It's even better if you can both add the test case and fix the bug. I will merge pull requests with test cases and add 
your name to the patch contributors below. Please maintain the same code formatting and style as the rest of the project.

## Original Author of Fongo Plugin
* [Jon Hoffman](https://github.com/hoffrocket)

## Patch Contributers of Fongo
* [Guido García](https://github.com/palmerabollo)
* [rid9](https://github.com/rid9)
* [aakhmerov](https://github.com/aakhmerov)
* [Eduardo Franceschi](https://github.com/efranceschi)
* [Tobias Clemson](https://github.com/tobyclemson)
* [Philipp Knobel](https://github.com/philnate)
* [Roger Lindsjö](https://github.com/rlindsjo)
* [Vadim Platono](https://github.com/dm3)
* [grahamar](https://github.com/grahamar)
* [Boris Granveaud](https://github.com/bgranvea)
* [Philipp Jardas](https://github.com/phjardas)
* [Sergey Passichenko](https://github.com/serj-de-sudden)
* [William Delanoue](https://github.com/twillouer)
* [Juan F. Codagnone](https://github.com/jcodagnone)
* Anton Bobukh
* [Matthew Reid](https://github.com/drei01)
* [jasondemorrow](https://github.com/jasondemorrow)
* [lldata](https://github.com/lldata)
* [renej-github](https://github.com/renej-github)
* [mathieubodin](https://github.com/mathieubodin)
* [Alex Art](https://github.com/elennaro)
* [htmldoug](https://github.com/htmldoug)
* [antonbobukh](https://github.com/antonbobukh)
* [Alban Dericbourg](https://github.com/adericbourg)
* [louisnerys](https://github.com/louisnerys)
* [Changgeng Li](https://github.com/changgengli)
* [Nils Meder](https://github.com/nilstgmd)
* [Liran Moysi](https://github.com/liranms)
* [Kong TO](https://github.com/newlight77)
* [tomdearman](https://github.com/tomdearman)
* [James Jory](https://github.com/james-jory)
* [Riaz Ahmed](https://github.com/riyyaz)
* [Martin W. Kirst](https://github.com/nitram509)
* [LiBe](https://github.com/libetl)
* [Vladimir Shakhov](https://github.com/bogdad)
