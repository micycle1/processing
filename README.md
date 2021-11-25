[![](https://jitpack.io/v/micycle1/processing.svg)](https://jitpack.io/#micycle1/processing)

Processing 3
==========

This is the mirror of the [Processing 3](https://github.com/processing/processing) repository, with the addition of a *pom.xml*, turning the _processing-core_ library into a standalone *Maven* artifact.

It is hosted as a *Maven* dependency via [JitPack](https://jitpack.io/#micycle1/processing-core-4) (from this Github repository) so it can be referenced in your own *Maven* project (for when you want to use the Processing library outside of the Processing IDE).

---

## How to use in your Maven project

### Step 1. Add the *JitPack* repository to your pom.xml

```
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
     </repository>
</repositories>
  ```
  ### Step 2. Add the processing-core dependency

  ```
<dependency>
	  <groupId>com.github.micycle1</groupId>
	  <artifactId>processing</artifactId>
	  <version>3.5.4</version>
</dependency>
  ```

### **That's it!**
