# Personnel
   Clare McGillis and Audrey Soo

# Problem:
   To find one path through a maze starting at a designated beginning ending at the treasure without reaching any stepping       
   stone more than once.
  
# Recursive Abstraction
   When I am asked to 
   find one path through a maze starting at a designated beginning ending at the treasure without reaching any stepping stone more than once,
      
   The recursive abstraction can
     find one path through a maze starting one step closer to the treasure ending at the treasure without reaching any stepping stone more than once

# Base Case
   The explorer is at the treasure

# English or pseudocode description of algorithm
   move in all directions possible (North, South, East, West)
   
   if person is not at a dead end
   
      invoke abstraction
      
   move back

# class(es), with fields and methods

# version*n* wish list
   - All possible paths to the treasure
   - The shortest path to the treasure
   - Reach multiple treasures?
# version *0* wishlist
   check for if a move is possible -- boolean
   array of moves represented by integers
   integer representing how many moves done
   
   Types of paths:
   - straight line
   - simple one way path
   - paths that have loops
   
