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

1) If you are not running Java 8 or a more recent version of Java with JavaFX support, extract the `fx_sdk_and_jdk_16.tar.xz` archive in the main folder.

2) Run the following command:
```
openjdk-16+36_linux-x64_bin/jdk-16/bin/java -jar --module-path javafx-sdk-16/lib --add-modules=javafx.controls,javafx.fxml Smartphone.jar
```
or, if you have a Java version with JavaFX support:

```
java -jar Smartphone.jar
```

