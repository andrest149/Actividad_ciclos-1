# Actividad_ciclos
Actividad del segundo corte
clc 
clear all
%exercise 8.2 
%There are many formulae for computing ? (the ratio of a circle’s
%circumference to its diameter). The simplest is:pi/4 = 1 - 1/3 + 1/5 - 1/7+
%1/9..(8.4)
%which comes from putting x = 1 in the series: arctan x = x - x^3/3 +
%x^5/5 - x^7/7 + x^9/9..(8.5)
%a)Write a program to compute pi using Equation (8.4). Use as many terms in the
%series as your computer will reasonably allow (start modestly, with 100 terms,
%say,and rerun your program with more and more each time).You should find that
%the series converges very slowly—it takes a lot of terms to get fairly close to pi.
nt=10000;
for n=1:nt
  FINDINGP(n)=(1/((2*n-1)));
    if sum(n==[1:2:nt])==1
        FINDINGP(n)=FINDINGP(n);
    1
    else
        2
        FINDINGP(n)=-FINDINGP(n);
    end 
end
Value=sum(FINDINGP)*4
