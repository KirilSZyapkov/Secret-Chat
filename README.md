# Secret-Chat

You have plenty of free time, so you decide to write a program that conceals and reveals your received messages. Go ahead and type it in!  

On the first line of the input you will receive the concealed message. After that, until the "Reveal" command is given, you will be receiving strings with instructions for different operations that need to be performed upon the concealed message in order to interpret it and reveal its true content. There are several types of instructions, split by ":|:" 

InsertSpace:|:{index} 

Inserts a single empty space at the given index. The given index will always be valid. 

Reverse:|:{substring} 

If the message contains the given substring, cut it out, reverse it and add it at the end of the message.  

If not, print "error".  

This operation should replace only the first occurrence of the given substring if there are more than one such occurrences. 

ChangeAll:|:{substring}:|:{replacement}  

Changes all occurrences of the given substring with the replacement text.
