## Turn @some_decorator() into @some_decorator  
Originally published: 2011-08-02 23:53:02  
Last updated: 2011-08-04 18:48:36  
Author: Eric Snow  
  
A decorator factory is a function that returns a decorator based on the arguments you pass in.  Sometimes you make a decorator factory to cover uncommon use cases.  In that case you'll probably use default arguments to cover your common case.