---
layout: post
title: "Lab Report #8"
subheadline: "Building a Bot"
categories:
    - fieldbooks
author: Anna Tobin
comments: false
---

# Lab Report #8
## Building a Bot

For this lab, the piece of poetry I decided to work with was "The Red Wheelbarrow" by William Carlos Williams. 

	so much depends
	upon
	
	a red wheel   
	barrow
	
	glazed with rain  
	water
	
	beside the white  
	chickens

In order to adapt this poem to the code for the mad-lib bot, I decided to substitute the three adjective/noun phrases the poem presents: "red wheelbarrow," "rain water" and "white chickens." The adapted code is written below:

	poem <- paste(c("so much depends upon a ", list_word(adjectives), " ", list_word(nouns), "glazed with ", list_word(adjectives), " ", list_word(nouns), " beside the ", list_word(adjectives), " ", list_word(nouns)), collapse = "")
	
	cat(poem)

And an example of the output of this code:

	so much depends upon a savory wielding glazed with broadcast tunnels beside the neural ideas
	
For this particular poem, creating a randomly generated group of adjectives and nouns changes the meaning of the poem completely from a glimpse of rural life to an infinite possiblity of meanings and contexts. The poem is no longer confined to a thematic realm and becomes something that can place meaning onto anything. However, the nature of the randomness lends some the meaning of some generated poems to be more "meaningful" than others. Similar to the electronic literature bots we looked at in class, much of the value of the output of this code comes from the interpretation and value placed upon it by human users. The success of the tweets that the bot poem.exe generates, for example, depend upon the relatableness and spreadablility of the tweets. It almost seems like a lottery, waiting to see when the random string of words will turn into something that makes coherent sense and may be indestinguisable from a human poet. Despite the randomness that's apparent in the output of the code, the structuring and rationale behind the code itself reveals a level of creativity that is comparable yet unique from the process of a poet composing a poem. 
