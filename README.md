# Improved Version of JadxFindJNI

**English** | [`Español`](README-es.md)

The repo is an updated version of JadxFindJNI to adapt to the latest IDAPro and JADX.  
Search for Java Native Interface (JNI) functions from an APK and export them to a JavaScript Object Notation (JSON) file.

## Build

```sh
$ make all
```

## Usage

```
$ java -jar JadxFindJNI.jar
Usage: JadxFindJNI.jar <file.apk> <output.json>
```

## Credits

- [skylot/jadx][jadx]
- [evilpan/jni_helper][evilpan]

[jadx]: https://github.com/skylot/jadx  
[evilpan]: https://github.com/evilpan/jni_helper