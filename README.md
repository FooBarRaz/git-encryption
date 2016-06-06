# git-encryption
This project was created to experiment with encryption on files in a git repository. 

The idea is to share a password with authorized users/machines, so that when they view files in the repo, they see the decrypted contents, and when they commit changes, those changes are encrypted before being pushed to the remote. 

The implementation is mostly derived from the instructions provided in this gist, with a few changes. https://gist.github.com/shadowhand/873637

