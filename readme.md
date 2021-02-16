# Crypgo - Crypto GO
Some basic implementations for cryptography tools, contains several packages:  
1. `dh` - Diffie-Hellman asymmetric protocol  
1. `salsa20` - steam cipher, also known as ChaCha20
1. `mac256` - HMAC signature, based on SHA-256 hash algorithm
1. `poly1305` - MAC for AES

### How to import into your project
We recommend you to use go modules via go.mod file:  
`require github.com/Projector-Solutions/crypto v0.0.1`  

But you also can use `go get` tool:  
`go get -u guthub.com/Projector-Solutions/crypto`

___Note:__ this project uses Go 1.11, check your project supports this version._
- - -


