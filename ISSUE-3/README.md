ISSUE#3 - Unique substring
===

Problem:

Let�s have N different strings/words for each word print the minimum part of it which makes it unique toward others, for example:

input:
A13-OLinuXino
iMX233-OLinuXino
MOD-PULSE
MOD-IO
<end>

result:
A13-OLinuXino -> a
iMX233-OLinuXino -> 2
MOD-PULSE -> p
MOD-IO -> -i

i.e. if you search for �a� in all words you will find it only in �A13-OLinuXino�, if you search for �2� in all words you will find it only in �iMX233-OLinuXino� and so on.


Solutions:
==

1. Dylan, Python - works, received 26 minutes after the problem post, and one of smallest too just 10 rows solve the problem

2. Zokier, Python - works, very small and compact code

3. Davide Silvestri, Python - works, clean and commented code

4. Mateusz Klatecki, C - works, I admire everyone who works with strings in C ;-)

5. Hanspeter Portner, Lua 

6. Mikhail Soloviev, C++ 

7. Antal Koos, Python - works in both case sensetive and case insensetive

8. Piotr Gapinski, AWK - "$ gawk -f olimex.awk input" most exotic solution

9. Francesco Frassinelli, Python - another small and clean solution

10. Lukasz Pulka, Python - mix python/c

11. Diego Roversi, Python 

12. Miller Wang, C 

13. Johannes Lummel, PureBasic 

14. Petr Konecny, Python - another small and clean solutiion

15. Emilio Lopez, Python 

16. Bogdan Marinescu, Lua - interesting approach to work with numbers instead strings at start