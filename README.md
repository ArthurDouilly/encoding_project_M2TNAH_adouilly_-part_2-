# Encoding project (part 2)

### Stepping away from TEI with a custom DTD

For the first part of the assignment, I had adhered to the TEI lite scheme as closely as I could while making my own DTD. Following a conversation with Ms. Kapitan, the choice was made to alter the objective of part 2 accordingly and orient myself towards a custom DTD.  This allowed me to think about the specific structure of the documents which I was encoding.

### Structuring the DTD

##### What is to be encoded

The first step of the encoding was deciding what I wanted to encode in my documents. Testaments are archival documents and official acts which follow a specific structure that can be analyzed with diplomatics, from the protocol calling to religious figures and addressing the reader to the body text which contains the measures to be taken, and finally the eschatocol which contains the marks of validation of the document. Within that structure, it was also interesting to me to see which names and figures are called to by the testator.

##### How to encode it

The way I have chosen to encode my documents was to keep to that structure, with a 'docMetadata' element which was meant to define who wrote the document, its history, and where it is found, as well as a 'docText' element which contains the document. 'docEncoding' is structured by 'protocol', the protocol, 'main' containing the core of the text, and an optional 'eschatocol'. I have chosen to use empty elements and notes to give more details as needed.

### Encoding in TEI_all

Part of the assignment was also to encode in TEI_all and compare. Further notes will be detailed in **reflection_note.md**.

### AI statement

No generative AI was used in this project.
