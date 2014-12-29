listsafe
========

Safe operations on lists.

Data.List includes a handful of partial functions - `head`, `tail`, `(!!)`, etc. - that throw
uncatchable exceptions when given empty lists. This package
provides safe alternatives for such functions based on
MonadThrow which can provide a variety of failure
cases: Nothing, IOException, Left, etc.
