# Quantum-Cryptography-Compare-QKD_BB84-protocol-with-Classical-Computer

Quantum cryptography is one of the emerging topics in the field of computer industry. Quantum Cryptography is the future of the next generation.The best known example of quantum cryptography is quantum key distribution in which used BB84 protocol

<h1>Methodology</h1>

Alice <br>
&nbsp; &nbsp;Encodes her information randomly in one of the two bases…
   

For example,<br>
&nbsp; &nbsp;Basis A  &nbsp; &nbsp; &nbsp;  Basis B <br>
&nbsp; &nbsp;| 0> = 0 &nbsp; &nbsp; &nbsp;  | 0> = 0 <br>
&nbsp; &nbsp;| 0> = 0 &nbsp; &nbsp; &nbsp;  | 0> = 0<br>

Alice’s bits &nbsp; &nbsp; &nbsp; 0101100010101100 <br>
Alice’s bases &nbsp; &nbsp; &nbsp;BAABAABAAAABBBBA <br>
States sent  &nbsp; &nbsp; &nbsp; +10-10+0101+--+0 <br>

Bob receives the stream of qubits and measures each one in a random basis: <br>
&nbsp; &nbsp; &nbsp; ABAABAAABABBBBA <br>

Bob’s bases  &nbsp; &nbsp; &nbsp;ABAABAAABABBBBAB <br>
Bob’s results&nbsp; &nbsp; &nbsp;1-00-0+0+0-+--1+ <br>

Bob receives the stream of qubits and measures each one in a random basis:<br>
&nbsp; &nbsp; &nbsp;ABAABAAABABBBBAB <br>

So he gets, &nbsp;**0**0*0*0*+--** <br>

Then Alice and Bob compare their measurement bases, not the results, via a public channel.<br>
So Bob and Alice are left with 7 useable bits out of 16 <br>
	_ _ 0 _ _ 0 _ 0 _ 0_ 0 1 1 _ _ <br>
These bits will be the shared key they use for encryption <br>

Now enter Eve… Eve wants to spy on Alice and Bob.<br>
So Eve intercepts the bit stream from Alice, measures it, and prepares a new bit stream to Bob based on her measurements.....<br>

So how do we know when Eve is being nosy?<br>

Well… Eve doesn’t  know what bases to measure in, so Eve would have to measure randomly and 50% of the time Eve will be wrong ...<br>

<h1>implementation</h1>

Divide into 3 phase :<br>

phase:1 Deploy code in classical computer<br>
phase:2 Deploy code in IBM quantum <br>
phase:3 Compare result classical computer with IBM quantum experience<br>




		





	


