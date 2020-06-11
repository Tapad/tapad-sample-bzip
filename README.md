# tapad-sample-bzip2

The files contains 2 MiB of lorem ipsum. It has been compressed with Tapad's latest bzip2 compatible compression


## Uncompression tests

| Utiliity | Compatible | Note |
| -------- | :----------: | ---- |
| bzip2 1.0.5 | ✅ | Distributed in CentOS 6 package universe |
| bzip2 1.0.6 | ✅ | Distributed in CentOS 7 package universe |
| bzip2 1.0.6 | ✅ | Ships by default on Ubuntu 18.04 |
| bzip2 1.0.8 | ✅ | Ships by default on Ubuntu 20.04 |
| 7Zip 16.04 | ✅ |  |
| Java 8 | ✅ | OpenJDK 8, Apache Commons Compress |
| Java 11 | ✅ | OpenJDK 11, Apache Commons Compress |
| C# .NET 4.8| ✅ | [SharpZLib](https://github.com/icsharpcode/SharpZipLib) |
| Python 2.7.17 | ✅ | bz2 library |
| Python 3.8.1 | ✅ | bz2 library |
| Go | ✅ | [compress/bzip2](https://golang.org/pkg/compress/bzip2/) |
