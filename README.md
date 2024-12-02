java c
DEPARTMENT OF ELECTRONIC, ELECTRICAL AND   SYSTEMS ENGINEERING, SCHOOL OF ENGINEERING
LH POWER ELECTRONICS AND POWER SYSTEMS (30037)
Power Systems Assignment: Power Flow   Studies   using MATLABConsider a two-bus   system with the   single-line diagram   shown   in Figure   1.   In   the   two   bus system, Bus   1 is slack bus where voltage is given in Fig.   1. Bus 2 is a PQ bus where   load   power   is   given.   The   impedance   of the   transmission   between   bus   1   and   bus   2   is   Z12      =   0.0   +   j0.15 p.u.       Please    code    computer   programme    using   Newton-Raphson method   to   calculate   power   flow   solution,   using   (1)   a   voltage   convergence   tolerance   of εp      =   10   −6 :       max    |vik+1−vik |   <   εp       and    (2)   a   power   mismatch   tolerance    of εp      =   10   −6: max   (|∆p2 | ,   |∆Q2 |)   <   εp   ,   respectively,   and   comparing   the   results   with   Gauss-   Seidel method.
   
Fig.   1 Two-bus   system
Structure of   the Report:
Based   on   the   above   assignment, you   are   asked   to   prepare   a   report   of   around   10   -   15   pages including the following sections:
1.         Cover page
2.         Summary
3.       Table   of   contents
4.       Introduction
5.       Theory about Gauss-Seidel method, Newton-Raphson method and Fast   Decoupled   Load   Flow method (Show   necessary equations and diagrams. Don’t copy   the lecture   notes and   you   will need to   rewrite   the equations and   redraw the diagrams rather   than   use scanned equations and diagrams from lecture   notes   or   textbooks!)
6.       Power Flow   Study Results and Analysis
You will need to carry out the following THREE   studies:
(a)   Case   Study   1:   Comparing   the results using Newton-Raphson with   those   using   Gauss-Seidel    method    with    a    voltage    convergence    tolerance    of   εp       =    10−6    :   max      |vik+1−vik |   <   εp
(b)   Case Study 2: Showing the convergence characteristics of   the   Newton-Raphson   method   by   drawing   a   relationship   Log10   [Max(|ΔP2   |,   |ΔQ2   |)]   vs   iteration   count   k.
(c)   Case   Study   3:   Showing the   convergence   characteristics   of   the   Fast   Decoupled   Load    Flow   method   by    drawing    a    relationship    Log10       [Max(|ΔP2   |,    |ΔQ2   |)]    vs   iteration   count   k.
(d)   MATLAB   Code   for   Gauss-Seidel   method   including   necessary   comments   in   your   computer   code   to   explain   your   calculations,   should   be   submitted   in   a   separate .m   file.
(e)   MATLAB   Code   for   Newton-Raphson   method   including   necessary   comments   in   your   computer   code   to   explain   your   calculations,   should   be   submitted   in   a   separate   .m file.
(f)代 写Power Systems Assignment: Power Flow Studies using MATLABR
代做程序编程语言    MATLAB   Code   for   Fast   Decoupled   Load   Flow   method   including   necessary   comments    in    your    computer    code    to    explain    your      calculations,      should      be   submitted in a   separate   .m   file.
7.       Conclusions
8.       References   (IEEE   format   should   be   used)
IEEE reference format:
https://www.ieee-pes.org/part-4-preparation-of-a-formatted-technical-work-for-the-ieee-power-energy-   societyReport   Layout:   Page   numbers   should   be   inserted   at   the   bottom   centre   of each   page   except the cover page. Report should be typed on A4 paper, spaced   1.5 with margins as   follows: Top-2.54cm, bottom-2.54cm, left-2.54cm, right-2.54cm. Font size of 11 or   12   can be used.Report Writing: The style. of   writing should be formal and   precise with no more words   than needed to make the meaning clear. Every statement must be   justified, and   nothing   that    is    written    should    be      vague.      Tables      and      diagrams      should      be      used      wherever   appropriate. A   specific   point   that   must   be   made   is   that   the   report   should   be   written   in the third person.   For   example, ‘this was   carried   out’   should be   used   rather   than   ‘I   did   this’   .
MATLAB code:   MATLAB code should be put in a separate *.m   file where necessary   comments in your computer code to explain your calculations   should be   included.
Marking Criteria: The following is the marking criteria   for this   assignment:
(1) Introduction - a general description of   the problem to be   solved   (10%).
(2) Methodology – how the problems are solved (20%).
(3) Results and discussion  MATLAB code   (40%).
(4) Conclusions (10%).
(5) Use   of   references   (5%)
(6) Overall report quality and   structure   (15%)Plagiarism: Plagiarism will not be tolerated. It is the act of   a   Student   claiming   as their   own, intentionally or   by omission,   work   which   was   not done   by that Student. Plagiarism   also   includes   a   Student   deliberately   claiming   to   have   done   work   submitted   by   the   Student   for   assessment   which   was   never   undertaken   by   that   Student,   including   self-   plagiarism and the other breaches. Sanctions of   a plagiarism include the Student failing   the   Programme   of   study.
The report as well as the computer code will   need to be   submitted via   the   CANVAS   and the submission should include the following FOUR   separate   files:
(a)   Report ( word or PDF   format   );
(b)   MATLAB Code for Gauss-Seidel method (   .m   file )
(c)   MATLAB Code for Newton-Raphson method (   .m file )
(d)   MATLAB Code for Fast Decoupled Load Flow method (   .m   file   )







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
