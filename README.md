# Text-Encryption-in-Image

Image Processing - Project  Report


Project Topic:Hiding text in image(Text to image encryption)

Faculty Name: Dr. Devanjali Relan

Project Title: Hiding the Text in Image file- Image encryption

Summary :

The project introduces a program which can hide any text / numbers into a given image. This technique can be used for passing on secret messages among different agencies.

Here a given image is taken and a desired text converted to ascii Code is stored in that image array and accordingly the gray values of image changes , since the array of image is very large in comparison to the array of ascii codes of the text.



Problems that project solves:

Majorly the agencies sending secret messages does by morse code , but it has become too common and any one after learning the codes for alphabets and symbols can decode it, hence it is no more secretive, nut imagine same message is being send to the decoders in form of basic image files than the chances of someone recognizing lessens, also if someone is aware about such thing , he won’t be able to decode it in ages since our methods uses a human made function we cannot be configured in ages. So relax!!

This kind of problem motivated us to move forward.


List of problems solved by the project:

Problem solved by us is security and encrypting secret messages and it's a very safe method for secret communication.

Provide a detailed explanation of how this project solves the problem(s).

Explanation of our project:

Firstly we read an image and then we store an array of gray scale values of image and then we’ll define two functions which need to be known in order to decode the encryption, also for this infinite functions can be made to hide the text,that will denote row and column numbers of array that will be manipulated as function varies and then we’ll take input of secret message and then convert it into ascii code and store in array of image and then we’ll save the image and it will be sent to receiver .

Receiver can now apply decryption process and it’s fairly easy to encrypt and decrypt by this methods to apply and it’s pretty secure as well as it can be extracted only if person knows the function used for encryption and we’ll retrieve value using function and it will give us ascii values as output and then we’ll covert it back to string and our message is retrieved.
One more thing that we are doing is that we are also storing the length of the secret message at the 1 element of the array of images.

Isn’t this way of encryption and decryption pretty easy as compared to others.  

Existing state-of-the-art:

Currently used technology is steganography, it’s a method of hiding secret data in any image/audio/video.

Encode the data : Every byte of data is converted to its 8-bit binary code using ASCII values. Now pixels are read from left to right in a group of 3 containing a total of 9 values. The first 8-values are used to store binary data. The value is made odd if 1 occurs and even if 0 occurs. 

Decode the data : To decode, three pixels are read at a time, till the last value is odd, which means the message is over. Every 3-pixels contain a binary data, which can be extracted by the same encoding logic. If the value is odd the binary bit is 1 else 0.
But this method is pretty lengthy and hard to implement in comparison to our method which is way more simpler to understand and implement.

List of known Ways:

S. No.
Existing state of art 
Drawbacks in existing state of art
Overcome
1.
Steganography
Complex method to implement and hide text in image

Use predefined libraries so there is no mathematical function used to encode , thus decoding is very easy just have to check the library.
To overcome this we are simply using string to ascii conversion and a simple process of storing by using functions and getting index of matrix and storing at that index.



List the Technical features and Elements used for the project:

We have used python as our programming language and used various libraries such as open-cv, numpy, pandas and others are just basic concepts used and in addition to twe have used an approach of using mathematical functions to get row and column numbers to store our code.


List all the components: 

We have used Jupyter notebook as our coding platform.
Some mathematical concepts to create a function and range,domains concepts  of that function inorder to get the info how much data we can store in a n*m dimensional image.

List out the features of your project which are believed to be new and distinguish them over the closest technology:

Features:

Easy implementation
Less usage of libraries
More Secure
As there can be an infinite number of functions so decoding it would be really hard.
Our closest technology is Steganography, but implementation is pretty hard and alot of libraries are used.
We have built it from scratch and just used some basic libraries like open-cv ,numpy,pandas and mathematical functions


Are there any Alternatives present ? Are they better than yours?

Yes there are some existing solutions which hide text in image but they are based on steganography, in which predefined libraries are used to hide the text into image
But our method is more secure and thus better, because we are not using any predefined method to encode and decode the text rather we are using our self defined mathematical functions to encode and decode text, which needs to be known in order to decode the encryption, also for this infinite functions can be made to hide the text.


Status Of project:
The current status: its working real good for the test cases done till yet, only thing is missing is the color conversion from gray scale, which shall be accomplished shortly.

Developed by : Harshit and Shivani Mittal , in a span of 3-4 days.

Further stages: another method to hide image within image in under process shall be deployed shortly in the current program.


Scope of project in terms of usages in products:
Can be used encoding telephonic conversations in a sequence of images.
Anywhere, where encryption required from text to image.


Additional Information:

Steganography is the technique of hiding secret data within an ordinary, non-secret, file or message in order to avoid detection; the secret data is then extracted at its destination. The use of steganography can be combined with encryption as an extra step for hiding or protecting data



References:
Image Steganography using Python. Understanding LSB Image Steganography… | by Rupali Roy | Towards Data Science
Image based Steganography using Python - GeeksforGeeks
Steganography - An Experiment in Python | Section

