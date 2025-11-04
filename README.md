# Jar Explorer Documentation

This repository provides documentation on how to inspect, extract, and decompile Java JAR files.

---

## Table of Contents
- [Extracting a JAR File](#extracting-a-jar-file)
- [Decompiling a JAR File](#decompiling-a-jar-file)
- [Tools](#tools)
- [References](#references)

---

## Extracting a JAR File

You can extract the contents of a JAR file using the `unzip` command:

```bash
unzip myfile.jar -d output_folder
```

- `myfile.jar` – the JAR file you want to extract  
- `output_folder` – the directory where files will be extracted

After extraction, you will see the folder structure of the JAR, including any `.class` files, resources, and the `META-INF` directory.

---

## Decompiling a JAR File

To view the Java source code from compiled `.class` files, you can use [JD-GUI](https://java-decompiler.github.io/):

1. Download and install JD-GUI.
2. Open your JAR file:

```bash
jdgui classes.jar
```

3. Browse the packages and classes, and optionally export the source code.

---

## Tools

- `unzip` – standard utility to extract JAR/ZIP files  
- [JD-GUI](https://java-decompiler.github.io/) – Java decompiler GUI for `.class` files  

---

## References

- [JD-GUI Official Website](https://java-decompiler.github.io/)  
- [Java .jar file documentation](https://docs.oracle.com/javase/tutorial/deployment/jar/)  
