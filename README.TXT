
Answers to Lab 7, Part III:

#27 Yes.

#28 It is used to reset every cell to 0. 

#29 Yes, the pattern is deterministic.

#31 Because then it would be changing the state[] array within the for loop which would mess
    everything up because some calls are made to the state[] array within the loop.
    It does make a big difference, there is just a diagonal line going left because your changing the state[]
    array each time so the calls to state[i] will be different.

#32 I think the new array option is better because it makes it clearer what is going on and the memory saved from 
    my solution isn't impactful enough to actually matter. 

#35 There are 8 (2^3) possible combinations of left, right and center and two values true and false so 2^8 = 256 possible
    formulas.  
