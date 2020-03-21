---
layout: post
title:      "Significance of Iteration"
date:       2020-03-21 04:25:42 +0000
permalink:  significance_of_iteration
---



Iteration is a common and important aspect of everyday programing. Iterators are methods that loop over a set of data and allow you to operate on each element within that data.It is commonly associated with Loops and Looping. Looping allows us to go create code that repeats itself until a certain condition is met.  For example 

X = 0
loop do
  X  += 2
  puts X
  if X  == 5
    break      
  end
end


A basic Loop, prints X until X is equal to 5 and the loop itself simply adds 1 to the total number after every loop starting at 0. The numbers aren't important but the concept itself.  But why is this related to iterations? Because Iterators allow us to pull specific entries a data pool. 
For example if we take an Array which can be a list of ordered entities and we want to output or print those entities we can do so with an .each method. Heres an example below with some Names

names = ['AJ', 'James', 'Lucy', 'Nayru', 'Tanada', 'Gina']

names.each { |name| puts name }

We have called the .each method using the dot operator on our array. What this method does is loop through each element in our array, in order, starting from 'AJ'. Then it begins executing the code within the line blocks || The blocks beginning and end points are defined by the curly brackets {}. Each time we iterate over the array, we need to assign the value of the element to a variable. In this example we have named the variable name and placed it in between two block lines ||. After that, we write the logic that we want to use to operate on the variable, which represents the current array element. So basically using puts to print name onto screen. This will list all names in the order we've written in the method itself

Ok so Why is this important to understand and why is iteration used a lot? Its simple. Iteration allows us to use loops to find the exact data we want and to build code to find that data more easily and efficiently. If we need to go through data to find a specific person called "James" Then we can use methods and loops to go through each data until it matches with the name "James" Or Maybe its not a name but an attribute of a person or object. Mabe we cna't find "James" but if we use another method to search for Age or height we can use an iterator. Either way Iteration allows us to create solutions to find the data we need. 



