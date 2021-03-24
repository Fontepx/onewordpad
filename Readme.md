The Fontepx - OneWordPad.

A spreadsheet no macros that does one/many time pad type encryptions.
A word or group of words upto a total of 24 characters and a twelve digit number 
are used to create 41 permutated character sets and the one time pad.
When created, upto 3936 characters can be uniquely encrypted.

Enter text upto twenty four characters in Sheet1 cell B2. Enter values 1 to 99 into cells E2 to J2, No zeroes and no same values. 
In the Multi_Encrypt_96 Sheet, Cell A2 contains the scrambled character set. Cell A3 contains the one time pad created with the word and values entered in Sheet one.

UPDATE: OWP now has a Multi_Encrypt_96 sheet. 96 Characters with each of the 41 lines having its own permutated character set. A total of 3936  encrypted characters. Entry of message lines starts at A110. Encrypted text at B110. The permutated character sets start at J10, the line number is changed with cell G1 (red background). Cell C3 switches between message lines starting at A110 if cell C3 is an ‘a’ or A’ and encryption of lines starting at B110 if cell C3 is ‘b’ or ‘B’. Cell D3 is the line number. Change C3 to an ‘A’ or ‘B’ and the line number in D3 (C3, D3 and G1 have a red background). The generated character set used for each line of encryption and decryption is changed by changing the value in G1 (background color red).  Example: to encrypt a line of text in cell A110 set cell C3 to A and D3 to 110. Set G1 to 10 that is the character set. Cell F3 shows the encryption, cell F4 the decryption if decrypting. Right click and copy these cells then select were to paste by a right click and Copy then select a cell and- Paste Special – Unformatted text - text into B110 cell.

Each time a new word is entered into  Sheet1 cell B2 or a new X value is entered into Sheet1 cells E1 to J1, OWP will update and the character sets generated are automatically placed into J10 down to J51 in the Multi_Encrypt_96 sheet. Line J52 is the original start character set.

![image](https://user-images.githubusercontent.com/6797961/111641671-4805a980-87f5-11eb-9a9a-c4da38016817.png)
