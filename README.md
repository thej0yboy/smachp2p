# smachp2p v2.0
smachp2p is a python chat room using end-to-end Encryption to encrypt messages

this is just a symlink to the real TheRoom chat,

This chat room use AES encryption with CBC mode

This server using the creds to encrypt chat key and iv before sending them in the air

# How its works:
1. server generate keys for chat session
2. server encrypt keys with a key and iv already known by the client
3. server send encrypted keys to the client
4. client decrypt keys with the known key and iv
5. start chating with the decrypted keys
