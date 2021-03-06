## .NET Prolog implementations

*   [Prolog.NET by R. Todd](http://prolog.codeplex.com/) ([GitHub repo](https://github.com/Slesa/Prolog.NET))

*   [Prolog.NET by Ali Hodroj][1]
 
*   [P#][2]
 
*   [C# Prolog][3] by John Pool
 
*   [Yield Prolog][4]: This is probably the closest match to what I want. Cons: no unit tests (but can be added), lots of public static methods  not thread-safe.
 

## Other Prolog implementations and parser generators

*   Lex+yacc and MS MPLex+MPPG rely on ‘actions’ that are language specific (C or C#). I want my DCG code to be portable.
 
*   Antlr
 
*   [XSB][5]. Some people have called it ‘the best…’ (find quote) Cons: not thread-safe ([quote][7]):
 
    > “Currently, only one query can be active at a time. I.e., one must completely finish processing one query (either by retrieving all the answers for it, or by issuing a call to xsb\_close\_query(), before trying to evaluate another.”

*   SWI-Prolog: lazy lists
 
*   [tuProlog][6] 
 

*   [AGFL][8]   

 Has grammars for a few languages, including English and Russian.
 

*   [Backtracking yacc][9]

 [1]: http://hodroj.net/prolog/
 [2]: http://homepages.inf.ed.ac.uk/stg/research/Psharp/
 [3]: http://sourceforge.net/projects/cs-prolog/
 [4]: http://yieldprolog.sourceforge.net/
 [5]: http://www.cs.sunysb.edu/~sbprolog/xsb-page.html
 [6]: http://sourceforge.net/projects/tuprolog/
 [7]: http://www.cs.sunysb.edu/~sbprolog/manual2/node37.html
 [8]: http://www.agfl.cs.ru.nl
 [9]: http://www.siber.com/btyacc/  
