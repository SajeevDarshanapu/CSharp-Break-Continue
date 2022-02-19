# CSharp-Break-Continue

# break

-------------The break statement can also be used to jump out of a loop.


# Example on break statement

for (int i = 0; i < 10; i++) 
{
  if (i == 4) 
  {
    break;                            //output: 0 1 2 3
  }
  Console.WriteLine(i);
}

# continue
-------------breaks one iteration (in the loop), if a specified condition occurs, and continues with the next iteration in the loop

# Example on continue statement

 for (int i = 0; i < 10; i++) 
{
  if (i == 4) 
  {
    continue;                              //skips 4 and prints remaining 
    
  }
  Console.WriteLine(i);                    // 0 1 2 3 5 6 7 8 9
}

--------------You can also use break and continue in while loops:
