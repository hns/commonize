# Commonize

This is a RingoJS package that converts one or more RingoJS modules 
into pure CommonJS by replacing their use of `incclude()` and 
`export()` with other constructs.

# Warning: this script will edit your files in-place without making backups first

Do not run this script on resources that are not under a version 
control system.

### Usage

bin/commonize path/to/directory/or/file
