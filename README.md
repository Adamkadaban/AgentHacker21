# Agent Hacker
## Inspiration
We were inspired by the Spy vs. Spy, a favorite cartoon of both our hackers, as well as a passion for learning cryptography. Just like the two spies in the show, we can combat each other by making and breaking secret messages.

We made SpyTrainer a way to learn about encoding, decoding, encrypting, and decrypting because cybersecurity is all about the protection of computer systems and networks, which includes the data they contain. Encoding is used for maintaining data usability while encryption is essential for maintaining data confidentiality. We wanted users to be able to be “trained” in becoming a spy by learning about the different encryptions and being able to test it out for themselves. .

## What it does
Our home screen starts having the user select between encoding and encryption. If encoding is selected, the next screen shows six different encoding methods. The encoding techniques are Caesar’s Cipher, Rot13, UTF-8, Base 64, Hex, and Big Int. After making the selection of the encoding process they would like to use, they can read a short description teaching them about how the process works before typing in phrases to test it for themselves. After, they can also decode the message they just typed in to see that the encoding and decoding process successfully work.

## The encryption aspect of the platform works similarly with the user having the choice between RSA, Advanced Encryption Standard Electronic Code Block(AES ECB), and Advanced Encryption Standard Cipher-Block Chaining(AES CBC). In addition, the program also has 3 attacks: the Chinese Remainder Theorem, Coppersmith attack, and the dachshund attack that will be selected based on the user's input that is given.

## How we built it
We used the kivy module to create a graphical user interface that can not only be used on the computer, but also exported onto a phone as an mobile app. For the cryptography aspect, we utilized the python cryptodome module as well as our implementations of attacks on known vulnerabilities.

## Challenges we ran into
Learning and utilizing the kivy module for the graphical user interface was challenging for us because we had never used it in the past. Implementing the math behind some of the algorithms was also a challenge.

## Accomplishments that we're proud of
While most of the encoding methods were rather simple, we are proud of the automated Caesar Cipher that can break a Caesar cipher with any shift using an encoded word dictionary. Also, we are proud of understanding the math behind RSA AES because the decryption process was complicated with the attacks implemented.

## What we learned
To make this platform, we had to learn a lot about cryptography since we did not have much previous experience with this. We also had to study the complicated number theory behind many of the algorithms and theorems, such as the ones involving RSA, the public key cryptosystem. We also had to teach ourself the entirety of the kivy and kivymd modules, which was quite a challenge, as we don't have much front-end experience.

## What's next for SpyTrainer
In the future, we want to add more RSA attacks, in addition to the Chinese Remainder Theorem, Coppersmith attack, and the dachshund attack. We would also like to add a page where users can work on creating their own encoding techniques that are not already on there. Lastly, we would expand the length of the text that can be imputed and generate a frequency analysis tool to test for simple substitution ciphers.
