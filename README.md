# Quantum Chatting
Quantum Chatting is a webapp that uses quantum key distribution (the BB84 Protocol + Huffman Coding) to send an encrypted message between people.
<p align="center">
  <img width="500" height="500" src="https://github.com/Innanov/2022_qutech_challenge/blob/main/Quantum%20Chatting/Quantum%20Chatting.png?raw=true">
</p>

## :pushpin: About
Quantum key distribution provides a way of distributing and sharing secret keys that are necessary for cryptographic protocols. The importance here is in ensuring that they remain private, i.e. between the communicating parties.
In the BB84 protocol, Alice can transmit a random secret key to Bob by sending a string of photons with the secret key encoded in their polarization. The no-cloning theorem guarantees that Eve cannot measure these photons and transmit them to Bob without disturbing the photon’s state in a detectable way. 

<p align="center">
  <img width="500" height="500" src="https://user-images.githubusercontent.com/64653897/151697661-49b42d9e-5c85-41d6-8f16-57e19c6daf48.png">
</p>

Visit our webapp ... for more details !

# Running the code:
Go through qkd.ipynb chronologically, you should run through the imports and authentication to verify its functionality, and then run the BB84 runner. After that, run the HuffmanEncoding code and finally run the code that combines these two tools into one set of cells. You should be able to input a string, have it be converted into a list for QKD, and then BB84 will be applied to it. After verifying the security of the code, we run the Huffman decoding algorithm and regain the original string input.


# :star: Our Team :  


<a href="https://github.com/abhamra">Arjun Bhamra</a>

<a href="https://github.com/jayashQ">Jayash Panigrahi</a>

<a href="https://github.com/Ray16">Ruijie Zhu</a>

<a href="https://github.com/Innanov">Nouhaila Innan</a>


## Our iQuHack 2022 Experience:
During the 1-day hackathon, we brainstormed ideas and made progress together. We explored the world of quantum computing with curiosity and joy. We are proud to present our final model to the world, which added lossless data compression functionality that allows for efficient data transfer.
 

:pushpin: _This project is upgraded under <a href="https://www.iquise.mit.edu/iQuHACK/2022-01-28">iQuHACK 2022</a>_ 
