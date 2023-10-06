## Software Design Principles

1. Divide & Conquer

Take a big problem, chop them into smaller chunks, until you solve the problem.

Eg. if you have a e-commerce app project, you can break it down into little bits    such as homepage, stripe integration, products, prices, search bar,  etc. 

2. Increase Cohesion 

Everything that is grouped together 'makes sense' & fits together.

Eg. desiging things that should be grouped such as math packages. you only include  math packages together, not including other packages.  

It's a way to make the code simpler & easier to find.

3. Reducing Cupling

Cupling is how interdependant two modules, code, and relationships between the code are. 

The problem is that if one aspect of the code isnt wokring, then a big chunk of the code won't run as a result of being interdependant. 

By reducing it, you can reduce the relaince between the code so that IF you have an error or soemthing does not work, you are able to find and fix it without the system crashing. 

4. Increase Abstraction

Abstraction is better. using functions that can be applied to multiple peices of code.


5. Increase Reusablity

Like abstraction. 

Reusable code saves you time & can be more easy to work with.

6. Design for flexibility

Code with the mindset that it will change in the future. 

Think in terms of scalability such as designing the back end for more people so that you don't have to come up with an entirley new design. 

7. Anticipate Obsolescence

Be careful on what dependencies you are using as they may not work in future versions of your app. 

8. Design for portability

Anticipate that you code will be used for other devices other than the one you started on. 

9. Design for testibility

Make sure that the code works. for bigger projects this is key as it may not work as expected. 

10. Design defensivley

Idiot proof your code.

Design with the thought in mind that the users are dumb and that you must make it as SIMPLE as possible. 