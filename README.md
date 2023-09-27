[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12075654&assignment_repo_type=AssignmentRepo)
# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

  1. The smaller order variables are ignored.
  2. The program could be implimented poorly.
  3. The machine its running on could be slow.

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

  1. The machine the program is running on for it could be worse.
  2. The program does arbitrary things as it gets larger slowing down time.
  3. The thing its looking for could not be in the tree.

Add your answers to this markdown file.
