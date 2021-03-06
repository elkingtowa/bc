CRYPTODEGREE
=============
CryptoDegree is just a small program that allows you to encrypt the contents of a file.
The operation is very simple: the program reads character by character the source file, performs an XOR between the ascii value of each character and the private key and saves the result to another file.
The program is, therefore, an implementation of a simple symmetric encryption algorithm.

DISCLAIMER
=============
The program requires that users agree on the use of a single numerical key that will be used for encryption and decryption of the message.
The program has a use for purely educational: it works, but it's just a bunch of bad code.

COMPILING
=============
gcc cryptodegree.c -o cryptodegree

HOW TO USE?
=============
The program accept 3 parameters: 
- The path of the origin file
- The path of the destination file
- The numerical key

./cryptodegree /Users/Mark/file.txt /Users/Mark/crypto.txt 28932

MIT LICENSE
=============
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.