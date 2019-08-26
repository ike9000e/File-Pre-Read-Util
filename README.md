FILE PRE-READ UTIL
------------------
Pre-reads specified files by loading their binary data into
memory. Then just exits. Typically, can be used to force
all DLL files, in specified dir, precached off-HDD.

Usage
-------
    program.exe [options]
    program.exe --idn DIR [--exts EXTS] [--nBufSize NUM]
    program.exe [--bShowReads] [--bHideFnames] [--bNoSubdirs]
    program.exe [--bKeepData] [--bFollowDirSymlinks]

    EXTS: Comma separated file extension names.
          If first ext is a '*' then it is a blacklist (otherwise whitelist).
          Don't add leading dot character on each ext.
          Matching is case insensitive.

