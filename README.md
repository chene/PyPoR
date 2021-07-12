# PyPoR

## A pure-(Py)thon implementation for various (po)int- and line-based (r)egistration algorithms.

**(work in progress)**

Point- and line-based registrations, with and without known correspondance, are commonly used in computer-assisted surgery (CAS) to align two set of datasets. Categorically speaking, there are two types of point-based registrations:
- **With 1:1 known correspondance**: This is more appropriately known as [Orthogonal Procrustean Analysis](https://global.oup.com/academic/product/procrustes-problems-9780198510581?cc=ca&lang=en&), where the cardinality (the size) of two pointsets are the same, and the correspondance between elements of these pointsets are known explicitly, and
- **Without known correspondance**: This happends when the cardinality of the pointsets are not equal. Moreover, the correspondance between elements of these pointsets are unknown.
