# NZBGet repo for hosting build files (vcpkg cache, buildroot, etc)

Changelog:

v1.0
- initial release

v2.0
- lib/unpackers changes:
```
7-Zip	24.05   ->  24.08
UnRAR	7.0     ->  7.11
LibXML2	2.12.4  ->  2.13.5
ncurses	6.4     ->  6.5
OpenSSL	3.1.2   ->  3.4.1
```

v3.0
- added boost::filesystem
- update UnRAR to 7.13

v4.0
- update 7-Zip to 25.01

v5.0
- update OpenSSL 3.4.1 -> 3.5.4

v6.0
- update OpenSSL 3.5.4 -> 3.5.5 (Linux / FreeBSD / Android only)
- update 7-Zip to 26.00
- update UnRAR to 7.20

v7.0
- update 7-Zip to 26.01
- update UnRAR to 7.21

v8.0
- update buildroot to buildroot-2025.02.13
- update Android NDK to r27c
- update FreeBSD sysroot to 13.4
- rebuild all libs / unpackers with new toolchains

v9.0
- update UnRAR to 7.22 (Windows / macOS only)
