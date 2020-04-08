---
layout: post
title:      "Hashes and its Importance within Ruby"
date:       2020-04-08 02:03:22 +0000
permalink:  hashes_and_its_importance_within_ruby
---

A hash is a data structure that stores items by a number of associated keys. This is different from  arrays, which store items by an ordered index. Entries in a hash are often referred to as key value pairs. 

Most commonly a hash is created using symbols as keys and any data types as values. All value pairs in a hash are surrounded by curl braces {} and comma signifying the value.

Hashes can be created with with a => sign to separate the key and the value and Curly braces to group the entities.

Example being 

{ "1st" => "First", "2nd" => "Second" , "3rd" => "Third" }

This defines a Hash that contains 3 value pairs, meaning that we can look up three values First Second and Third using the key strings 1st 2nd and 3rd. 

In order to look up these values we can use square braces [] and use puts to find the string assocaited with the value

Position = { "1st" => "First", "2nd" => "Second" , "3rd" => "Third" }

puts dictionary["1st"]

This will out put "First"

You can also store any objects as keys or any objects as values. Even multiple values strings such as

{ "Distance" => ["Miles", "Kilometres"], "Weight" => ["Pounds", "Kilograms"] }

This is using Arrays as values in Hashes. So if you’d look up the key "Distance" you’d now get an Array back of Miles and Kilometres. 

The main purpose of a Hash is being able to lookup a value by a key. You can do certain things with hashes like Merge them(.merge), find the number of values within the hash(.length) and also return the Key values(.Key).

 { "1st" => "First" }.merge({ "2nd" => "Second" })
 
>= { "1st" => "First", "2nd" => "Second" }



 dictionary = { "1st" => "First", "2nd" => "Second" }
 
 dictionary.keys
 
=> ["1st", "2nd"]

dictionary.length

=> 2

There are many uses for hashes and its a key tool within ruby programming. It allows us to find and structure all of our data more meaninfully. 

