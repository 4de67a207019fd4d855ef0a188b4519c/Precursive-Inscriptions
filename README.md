# Precursive Inscriptions

Precursive Inscriptions provide a mechanism for surreptitiously inscribing a series of recursive inscriptions containing a single encrypted file broken into discrete chunks. The goal is to allow files, even if larger than the blocksize, to be written to the blockchain over time without revealing a connection between each individual inscription as they are being inscribed. After the completion of this process, a final publishing transaction can be used to inscribe the decryption key and information necessary to tie all the previous inscriptions together to reconstitute and decrypt the file.

In the event the inscriber wishes to not give the public access to the data immediately, they can delay the submission of the final transaction. They can also make use of a timelock encryption scheme to include the information necessary to reveal the decryption key after confirming the final transaction but be sure the key will not be immediately available. 
