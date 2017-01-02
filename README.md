# Snippets

## Terminal

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

Decode from input to output

```bash
openssl base64 -d <<< cmFtCg==
```
