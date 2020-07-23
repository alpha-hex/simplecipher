# simplecipher

Usage:

to encrypt a string

text := []byte("Hello world")
key := []byte("the-key-has-to-be-32-bytes-long!")
ciphertext, err := encrypt(text, key)
fmt.Printf("%s => %x\n", text, ciphertext)

to decrypt a string

key := []byte("the-key-has-to-be-32-bytes-long!")
plaintext, err := decrypt(ciphertext, key)
fmt.Printf("%x => %s\n", ciphertext, plaintext)
