# Star Wars Theme written in BASIC on a Tandy Color Computer 2

Color Basic code (ran on vintage 1986 computers such as the Tandy Color Computer 2) that will play the Star Wars theme

[Video of running code (2min 17sec)](https://youtu.be/jp5BP-P2Drg)

The code can be used as an educational example of how compression works. For example, many note sequences are repeated in the song, so instead of coding out all the measures, the programmer identified the repeated sequences, stored them in a reference variable, and called those reference variables to play the song. This is similar to how a very basic compression algorithm works.

## Possible class project

Find a song or poem that repeats itself. Identify what pieces repeat, label the unique pieces as A, B, C, etc., then record the sequence (e.g., A C C D A B E) and have someone reconstruct the song or poem by matching the cut pieces with the sequence.

For example the following: "The Paris lights are bright. The Paris lights are white." can be chopped up into 3 pieces, A: "The Paris lights are", B: "bright.", and C: "white." The coded sequence would be A, B, A, C.

Additional questions: How many words were in the original phrase? How many need to be saved to reconstruct? (Answer 10 in original; only 6 need to be saved.) What is the space savings? Answer: 1 - (6/10) = .4, which means we saved 40% of space. Advanced question: What is the compression ratio? Answer: 0/6 = 1.67, so the compression ratio is 1.67, sometimes noted as 1.67 to 1, meaning for every 1.67 units of data, we got 1 out.

So, final question: What is the compression ratio of the song as coded in this program? For the solution, it might be helpful to reconstruct based on the variables and do the calculations. (Note: the code is not compressed, only the representation of the song. Do not account for the PLAY or other code—only the contents of the variables!)

Also, I'd like to point out that this is an exercise in understanding compression; zipping a text file with the Paris phrase will yield different results. I need to state this because there are sticklers out there on the internet who will say, "But actually..."
