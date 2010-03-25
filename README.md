# Commonize

This is a RingoJS package that converts one or more RingoJS modules 
into pure CommonJS by replacing their use of `include()` and 
`export()` with other constructs.

### Warning

**This script will edit your files in-place without making backups.**

Never ever run this script on resources that are not under a version 
control system.

### Usage

    bin/commonize path/to/directory/or/file
