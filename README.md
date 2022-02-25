# decode-jwt

Simple shell script (but invaluable) to decode JWTs.

The script will strip human header and footer (if present), i.e. ----- blah blah ----- stripped.

# Usage
```bash
cat <yourjwtfile> | decodejwt.sh
```
# Pre-requisites
* Linux
* bash
* jq
* base64

