# Boaty :boat: :speedboat: :sailboat: -- Daniel Gelfand, Tim Marder, Maxwell Vale

![](https://github.com/DanielGelfand/Boaty/blob/master/deque.png)
http://www.java2novice.com/data-structures-in-java/queue/double-ended-queue/
##  :sweat_drops: Step 1 :sweat_drops:  
#### Create Deque interface. :white_check_mark:	



## :sweat_drops: Step 2 :sweat_drops:
#### Write the methods specified by the Deque interface in QQKachoo.
* offerFirst(e)
* offerLast(e)
* pollFirst()
* pollLast()
* peekFirst()
* peekLast()

Methods will be written one at a time using the interface as a guide and compilability will be ensured.

## :sweat_drops: Step 3 :sweat_drops:
#### Test. Test. Test. Profit. :moneybag:

## Why an ArrayList based architecture?
ArrayList methods closely resemble the necessary methods needs for a deque.
The handy ArrayList methods, in addition to automatic resizing, make ArrayList a decent option for a deque.
Although an O(n) runtime will be encountered during element shifts, the ease of use in contrast with the pointers of LLNodes
and the size issues of arrays make it the best option for Boaty.

## Development Plan
1. Select methods for Deque.
2. Write Deque interface.
3. Write Deque methods in QQKachoo with plenty of comments. ArrayList methods will be used for this lab.
4. Test all the methods.
5. Update README.md with anythign notable.
