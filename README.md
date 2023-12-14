[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12075654&assignment_repo_type=AssignmentRepo)
# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

  1. The smaller order variables are ignored.
  2. Coefficents are ignored.
  3. Asymptotic analysis considers worst, average, and best times which can be misleading by overestimating or underestimating the time of the program.

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

  i would guess that it would take around 6.66 seconds, because we know searching 
  through a binary tree takes log(n) time so we therefore know that 5 = C*log(1000).
  so we just have to solve for c which gets us 0.501, then we use that in the equation
  and solve it 0.501*log(10000) which gets us 6.66 seconds or so.

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

  1. When the program was initialy run it could have been run on a nasa super computer and gotten lucky when finding the number. Then it could have been run again on a computer from 1991 leading to much slower results.
  2. The program does arbitrary things as it gets larger slowing down time.
  3. The program for the larger set could have been given a linked list, and the program for the smaller set could have been given a binary tree. this could lead to the large descrepency.

Add your answers to this markdown file.
