# Replication of a Predictive Smartphone Keyboard for French Language

<img alt="Java" src="https://img.shields.io/badge/Java-%23ED8B00.svg?&style=flat-square&logo=java&logoColor=white"/><img alt="JavaFX" src="https://img.shields.io/badge/JavaFX-50EAFF.svg?&style=flat-square&logo=java&logoColor=black"/>

Academic group project in Java as part of a introduction course to Natural Language Processing (2020).

**Group : [Ninoh](https://github.com/ninohdasilva) , [Arno](https://github.com/awatiez/) , Ahmed**

Replication of a smartphone keyboard GUI with JavaFX. Word completion is handled with a Trie structure, and next words are predicted with n-grams.

The Trie and n-grams are updated with the content in the text area every time the green button is clicked, and users can create custom profiles with independant data that can be saved as long as the contents in `Liste_Utilisateurs.ser` are preserved.

<img src="https://github.com/ninohdasilva/PredictiveSmartphoneKeyboard/blob/main/Screenshot.png" width="50%">

## How to run 

### Linux

After cloning or donwloading the repository:

1) If you are not running Java 8 or a more recent version of Java with JavaFX support, extract the `jre.tar.xz` archive in the main folder.

2) Run the following command:
```
jre/bin/java -jar Smartphone.jar
```
or 

```
java -jar Smartphone.jar
```
if you have a Java version with JavaFX support

---
**NOTES**

The `jre.tar.xz` archive includes the Runtime Environment for Java 8, in order for JavaFX to run, as this package stopped to be included in JDKs and JREs after version 9.
There are other solutions for running this package but this is the one we went for at the time of the project. We might came up with a better solution.
We do not take credit for any licensed software in this archive.

---
