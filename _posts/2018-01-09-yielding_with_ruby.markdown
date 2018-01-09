---
layout: post
title:      "Yielding with Ruby"
date:       2018-01-09 22:52:13 +0000
permalink:  yielding_with_ruby
---


So the past couple of days I have been really struggling with the concept of Yield. I looked up youtube videos, asked in ask a question, and re-read the lab several times and could NOT seem to understand the issue! Even still, I have no problem generating the code, but I almost feel as if I am going through the steps and not truely understanding what I am doing. So this is the best explination I have so far. 

When you are doing a yield statement, you are basically making a variable for blocks to pass through. You have a method that will be passed with an arguement. In all instances I have seen so far, the arguement is an array. The purpose of the yield is so that  you can pass multiple blocks when necessary without re-writing the method for each block. 

Say I have colors, [red, blue, yellow], and I want to define a method that goes thru each color and tells me the number of letters in the number. But I also want a method that prints the names of the letters, but capitalized. Rather than writing 2 different methods, I can create one method that passes through each of the colors and runs them thru a block. So the blocks will be called with:

method(colors_array) {|n| n.count} for the count

and

method(colors_array {|n| n.upcase}

So rather than writing 2 methods for these, you write one method, and whenever you call it you add the {} part to the end, telling the yield which block to place into the method. 

I am still rather confused, I will probably look back at this blog and laugh in a few weeks, but that is my understanding at the moment. 
