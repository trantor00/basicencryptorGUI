Basic encryptor-decryptor implementation with wxwidgets GUI Built by trantor00

This time I used exact RSA Algorithm to strengthen encryption. RSA_Algorithm class handles encryption and encrypted files only consist numbers anymore.
I'd add XOR as well for additional encryption security.

I also solved some memory leak problems..
Again program handles every character separately and applies RSA. Of course I couldn't quarantee succesful encryption of big files like mp4, zip, iso etc.
It's way too more suitable using with text files(I'd rather say don't use it with anything but text files).

Attention! You must have wxwidgets libs to compile source codes. I included a compiled executable file(windows) and will include for linux as well..

