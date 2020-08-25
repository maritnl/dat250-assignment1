# Software Technology Experiment 1

## Technical problems - Software

I experienced no technical problems during installation, as I already had all necessary software installed. I use iOS, and upgraded git using homebrew as I noticed I was using an older version.

## Validating the software development environment

I validated my git installation with

```
git --version

```
and thus discovered that I was using an old version as described above. Updated it from 2.15.0 to 2.28.0.

I similarly validated my java and maven installation with

```
java -version

```

and

```
mvn -version

```

I use IntelliJ as my main IDE.

## Heroku

The Heroku installation went fine with no problems. When following the guide I encountered a problem under the "Local changes" part, where my local changes were not applied to the project. This was easily fixed by adding the pom.xml file as a maven project. The deployed tutorial website can be found [here](https://morning-plateau-31910.herokuapp.com/).
