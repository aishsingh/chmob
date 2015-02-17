# chmob
Simple script to modify permissions easier

## Usage
```
Usage: chmob [option] [file]

Options:
  -h         Shows this help page
  -r         Read file permission as symbols
  -R         Read file permission as a number
  -p         Set file permission
```

## Sample
Read current file permissions
```
$ chmob -r myfile.txt
rw-rw-rw-
```
Change permissions
```
$ chmob -p myfile.txt
rw-r
```
Check if permissions have changed
```
$ chmob -r myfile.txt
rw-r-----
```
