# simplecipher

# Usage:

## To encrypt a string

```
text := []byte("Hello world")
key := []byte("the-key-has-to-be-32-bytes-long!")
ciphertext, err := encrypt(text, key)
fmt.Printf("%s => %x\n", text, ciphertext)
```

## To decrypt a string

```
key := []byte("the-key-has-to-be-32-bytes-long!")
plaintext, err := decrypt(ciphertext, key)
fmt.Printf("%x => %s\n", ciphertext, plaintext)
```

to install the package
```
go get github.com/alpha-hex/simplecipher
```
