# Simple-Google-Img

This software is a simple perl module with Google REST API.

**WARNING:** this software is deprecated and no longer working due to REST Google module.

## Features
Searching for images through Google Images with a specified keyword.

## Dependencies
* REST Google 1.0.8 or similar
* JSON 2.90 or similar

## Usage
```
use GoImgMod;
...
@results = GoImgMod::getImgURL($keyword);
...
```
## Example
```
perl example.pl -s/tmp/test -n3 "pokemon"
```
