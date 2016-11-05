# Package bufpool

bufpool provides a thin wrapper around sync.Pool that is used
to store \*bytes.Buffer. 

I've implemented this enough times that this small dependency comes in 
pretty handy in reducing boilerplate code.
