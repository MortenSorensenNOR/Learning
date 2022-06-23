# Huffman-encoding
A simple - that is, probably neither an efficient nor a good - implementation of huffman encoding to encode strings of text.
In order to encode a string, call the generateTree() function and pass the return value from this into encodeStringHuffman() with it as the first parameter, 
an empty string as the second and the output object as the third. Then use this newly created array of assigned keys relating to each letter in your string in the 
encodeMessageHuffman function with regards to the original input string, and there you have it.. an encoded string. Use the decodeMessageHuffman function passing in
the previously created huffman tree and the encoded message to get the original message.
