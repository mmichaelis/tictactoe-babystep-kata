# TicTacToe BabyStep Kata

This Kata was performed during a meetup of Softwerkskammer Hamburg (SoKaHH) in [September 2013][meetup-2013]. One
learning we got after performing this Kata was that it would have been good to have a prepared workspace to have
less overhead at the start. This is what this workspace is for.

The Kata is based on a Kata Tic-Tac-Toe described at [Clean Code Advisors][cca-katas].

## BabyStep Kata Rules

The Baby-Steps Rules got introduced by [Adrian Bolboaca][babysteps]. Here is a list of the
rules/process to apply (direct copy from Adrian):

1. Setup source control repository.
2. Setup a timer for 2 minutes interval when you start.
3. Write exactly one test
    1. If the **timer rings** and the **<span style="color:red;">test is red</span>**
       then **revert** and **start over**.
    2. If the **<span style="color:green;">test is green</span>** before timer rings then **commit**.
4. Restart timer (no discussions in between timers)
5. Refactor
    1. If the **timer rings** and the **<span style="color:red;">refactoring is not complete</span>**
       then **revert** and **start over**.
    2. If the **<span style="color:green;">refactoring is complete</span>** before the timer rings then **commit**.
6. Restart the timer (no discussions in between timers)
7. Go to 3.
8. When session time is up **delete the code**.

## Pairing

It is a good experience to do this Kata as pair and to hand over the keyboard to your pair every two minutes.
If you don't like that one does the development while the other always only the refactorings think of possible
other solutions.

## Required Git Commands

If doing the Kata with Git you might want to use these commands:

```
$ git commit -a -m "..."
$ get reset HEAD --hard
```

[babysteps]: <http://blog.adrianbolboaca.ro/2013/03/taking-baby-steps/> "Taking Baby Steps | Adrian Bolboaca"
[cca-katas]: <http://clean-code-advisors.com/ressourcen/application-katas> "Application Katas « Clean Code Advisors"
[meetup-2013]: <http://www.meetup.com/sokahh/events/134779132/> "Softwerkskammer Hamburg Meetup Sept. 2013"




