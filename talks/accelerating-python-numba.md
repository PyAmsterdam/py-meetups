# Is it a bird? Is it a plane? Accelerating Python with numba

by [Juan Luis Cano Rodríguez](https://www.linkedin.com/in/juanluiscanor/)

## Abstract

We are lucky there are very diverse solutions to make Python faster that have
been in use for a while: from wrapping compiled languages (NumPy), to altering
the Python syntax to make it more suitable to compilers (Cython), to using a
subset of it which can in turn be accelerated (numba), and many many more.
However, each of these options has a tradeoff, and there is no silver bullet.

Some years ago I chose numba for poliastro, my personal project, because of its
simplicity, effectiveness, and not having to learn a hybrid dialect of Python.
numba compiles numerical Python code on the fly using the LLVM machinery,
producing extremely performant code... when it works!

On the other hand, even though it is quite mature as a library and most of the
Python syntax and NumPy functions are supported, there are still some
limitations that affect its usage. In particular, I strive to offer a high-
level API with support for physical units (extensions of NumPy) and reusable
functions which can be passed as arguments, which sometimes require using
complex objects or introspective Python behavior which is not available.

In this talk we will introduce numba, describe its basic usage, and then
discuss the strategies and workarounds we have developed to overcome its
limitations, as well as some advanced numba features we can leverage. We will
focus mostly on CPUs, and mention very briefly its GPU capabilities.
