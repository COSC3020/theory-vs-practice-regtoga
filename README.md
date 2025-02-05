# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

1. At low values of n asymptoticly worse functions may outpreform an otherwise asymptoticly superior version
2. asymptotic complexity does not factor in external factors such as cashe misses, the temperature of the air, hardware accelarators and so on.
3. asymptotic complecity only shows you the worst case, but most of the time that wont happen.

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

i would say that the worse case would take:
![6.66](calculator.png)
6.6666 secconds

reasoning: i set it up like ratio and solved for the missing variable.

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

1. asymptotic complexity does not measure external circumstances such as the computer does not "efficently",
work with numbers above a certain size, so if all were doing is adding expoentially larger numbers while addition at small input size has hardware-
accelarators we may have to fall back to a software solution at larger inputs. the specifics were just an example of my thought process but i think you get what im thinking
2. does this count as another one or is it part of the first? what if we ran out of cashe or even worse we ran out of ram entirly-
and had to use the swap file, this could lead to horrible run times.
3. There was another program running on the system that bogged down the preformance.

Add your answers to this markdown file.
