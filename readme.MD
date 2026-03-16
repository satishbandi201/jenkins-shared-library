Branching strategy



dev -feature- main

enable multi branch pipeline

1 Set Rules for Main branch

cata logue folder - settings - braches - rules- rule sets - rule name (main ) - enable
Target branches- add target - include by pattern (main)-  
Rules - Branch rules - Restrict deletion,, Block force push,, Require a pull request befor merge(1 or 2),, 

Create

2 create multi branch pipeline in jenkins UI for catalogue

** Build once run anywhere - promoting that bulid to all other env with diff conf

ROBOSHO-New item - multi branch - Branch sources - Git - Repository URL(httpa://) - save



create catalogue feature branch
1 git checkout -b feature-1
2 git add .;git commit -m "catalogue feature";git push origin feature-1




