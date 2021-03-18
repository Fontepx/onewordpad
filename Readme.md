The Fontepx - One Word Pad.

A spreadsheet no macros that does one/many time pad type encryptions.
A word or group of words upto a total of 16 characters and an eight digit number 
are used to create permutated character sets and the one time pad.
When created, upto 1728 characters can be uniquely encrypted.

Enter text upto sixteen characters in Sheet1 cell B2. Use / character instead of a space. Enter values 1 to 99 into cells E2 to H2, No zeroes and no same values. Goto the Encrypt sheet and enter upto sixteen characters to encrypt into cell B2. Thats it :-)  Cell C2 contains the encryption. To decrypt text goto the Decrypt sheet and enter text to be decrypted in cell B2. Cell C2 displays the decryption. Cell D2 shows the original encryption. You can carry on entering text to encrypt in sixteen character batches. Also try changing the values to add further encryption.               Cell A2 contains the scrambled character set. Cell A3 contains the one time pad created with the word and values entered in Sheet one.

UPDATE: OWP now has Multi-Encrypt/Decrypt. 27 lines of 64 characters each line can have its own permutated character set. Total 1728 characters. Entry of line batches starts at A80. Encrypted at B80 and the permutated character sets start at J10. Cell C3 switches between message lines starting at A80  if C3 is an ‘a’ or A’ and encryption of lines starting at B80 if C3 is ‘b’ or ‘B’. Click these cells and change C3 to an ‘A’ or ‘B’ and the line number in D3 (background color red). The permuted character set used for each lines encryption and decryption is changed by changing the value in G1 (background color red).  Example: to encrypt a line of text in cell A85 set cell C3 to A and D3 to 85. Set G1 to 15 that is line 5 in the permutated character set list. Cell F3 shows the encryption, cell F4 the decryption if decrypting. Right click and copy these cells then select were to paste by 
right click - Paste Special – Unformatted text on a cell.

Each time a new word is entered into  Sheet1 cell B2 or a new X value is entered into Sheet1 cells E1 to H1, OWP will update and the character set permutations automatically placed into J10 down to J37 in the Multi Encrypt sheet.

![image](https://user-images.githubusercontent.com/6797961/111641671-4805a980-87f5-11eb-9a9a-c4da38016817.png)
