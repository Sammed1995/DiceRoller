# DiceRoller
Java code

In this post, I will be sharing a simple Dice Roll Program in Java. Dice is a cube that has between one and six numbers or spots on its sides to provide random numbers. In other words, a dice can produce the integer numbers in the range 1(inclusive) and 6(inclusive).

the Random class nextInt(int) method returns a pseudorandom, uniformly distributed int value between 0 (inclusive) and the specified value (exclusive).

 
randomNumber.nextInt(6)+1

In the above code, nextInt(6) will return a random integer number between 0 and 5, but we need it from 1 to 6. That's why

