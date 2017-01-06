# Snippets

## Terminal

### Git

Delete commit and keep changes

```bash
git reset HEAD^
```

### Files

#### MIME-type

Get the MIME-type of a given file

```bash
file -b --mime-type image.png
```

### Encode/Decode

#### Base64

Encode from file to file

```bash
openssl base64 -in <infile> -out <outfile>
```

Encode from input to output

```bash
openssl base64 -e <<< ram
```

Encode from input to clipboard

```bash
openssl base64 -e <<< ram | pbcopy
```

Decode from input to output

```bash
openssl base64 -d <<< cmFtCg==
```
