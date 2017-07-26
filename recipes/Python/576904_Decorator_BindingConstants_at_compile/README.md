## Decorator for BindingConstants at compile time  
Originally published: 2009-09-15 00:34:37  
Last updated: 2009-09-15 00:34:37  
Author: Gabriel Genellina  
  
Decorator for automatic code optimization. If a global is known at compile time, replace it with a constant. Fold tuples of constants into a single constant. Fold constant attribute lookups into a single constant.