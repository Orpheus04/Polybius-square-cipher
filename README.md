# Polybius-square-cipher
The Polybius square cipher is one of the **oldest encryption protocols** known to mankind. It was made by the historian Polybius and was used to encrypt military dispatches. This is a fun project that uses that same logic to encrypt and decrypt plaintext. 

The original Polybius cipher is neither very clever nor very secure. Pretty easy to break with frequency analysis. So, I used a polybius cipher that was one notch more harder to break by introducing a **keyword** logic. 

It's the same 5x5 grid except, you take a short keyword and replace the first few letters of the grid with the keyword. Then you fill the rest of the grid with the english alphabet in chronological order and skip letters that were already included with the letters of the keyword to avoid overlap. Now, you need the keyword to decrypt any message encrypted using that keyword. Pretty neat. 
