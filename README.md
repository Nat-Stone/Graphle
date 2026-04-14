# Graphle
The goal of this wordle-like game is to guess the secret graph in six attempts. With each guess, you are given the points at which your guess and the correct answer intersect. There are four built in difficulties, but custom difficulties are also supported. A daily game for each difficulty is randomly generated, but infinite play is supported too.

Answers and guesses can only be from the lists of possibilities, with translations and dilation based on the difficulty.
Flip X: Reflection over the X axis. For example, ln(x) --> -ln(x).
Flip Y: Reflection over the Y axis. For example, ln(x) --> ln(-x).
Translate X: Horizontal translation by h. For example, ln(x) --> ln(x-h).
Translate Y: Vertical translation by k. For exampl_e, ln(x) --> ln(x)+k.
Dilate X: Horizontal dilation by a/b. For example, ln(x) --> ln(b/a x).
Dilate Y: Vertical dilation by a/b. For example, ln(x) --> a/b ln(x).
