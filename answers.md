# CMPS 2200 Recitation 6
## Answers

**Name:** Roberto Duran


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**
    - I see a few trends with the cost of Huffman vs Fixed length, first that huffman seems to cost more when there are more lines in the file, sencond that even though there are less lines, huffman also seems to cost more if there are more symbols/the file type is different such as in grammar.lsp with ($->), and lastly with fixed length where it seems to be cheaper with c files compared to huffman. Also all of the ratios seem to only be simplified to 7.

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
    - f1.txt    |    1340    |     68340     |     51 : 1
    - alice29.txt    |      1039367       |       10839113       |     73 : 7
    - asyoulik.txt    |       876253        |     17650239      |      141 : 7
    - grammar.lsp    |       26047       |     1220488     |      328 : 7
    - fields.c    |      78050      |    2564500      |        230 : 7




- **e.**
    - Since the greek alphabet has 24 letters, a document in which every character had the same frequency the cost would be 4585 bits times the length of the document and as long as the characters keep the same frequency the cost would be consistent accross documents


