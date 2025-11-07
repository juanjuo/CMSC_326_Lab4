# CMSC_326_Lab4
Juan Diego Mora /
Hameed Azad

# NOTE

Using Pintos version from Lab3. with thread blocking/unblocking implemented

# TO DO (to get this working before anything else)

## Make processor flags to be able to run pintos on bochs with or without mlfqs flag
 - If pintos is run without the mlfqs flag, it should properly run using the ready_list and no priority scheduling.  

## Create New Tests (what are we testing for?)
 - Read the pintos tests and read Lab tests and create some new ones

## Get idle_thread running separately from all other threads (not in a queue)

## Have threads run except when sleep / blocked

## Just Some Questions.....
 - How do we keep track of how long each thread has run? each is supposed to run for as long as x quantums (depending on priority level)... but how do we check? What if it blocks? do we still count that as valid use of quantum time?

 - In the lab description it says "You do not consider priority when selecting processes to run that are waiting on a lock, semaphore, or condition variable." does that mean that when these proceses get to run they just run in any order? Do they stay in the same priority or do their priorities reset after blocking?

