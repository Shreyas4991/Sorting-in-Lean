# Sorting in Lean

The goal is to have efficient implementations of sorting algorithms in lean with a non-exclusive focus on stable algorithms. In the short run, we hope to implement efficient versions of. Proving properties is not a priority.

### Current Targets

The current targeted sorting algorithms are listed below alongwith the most directly used reference for each.

* [] [Insertion Sort](https://en.wikipedia.org/wiki/Insertion_sort) : To be used as a primitive in other sorting procedures.

* [] [Naive Quicksort](https://leanprover-community.github.io/mathlib4_docs/Init/Data/Array/QSort/Basic.html#Array.qsort) : Reference Implementation from mathlib. I want to reimplement this as an exercise for myself.

* [] [Stable Quicksort]() : Used as a primitive in other sorting procedures. Learnt about this in the context of fluxsort and glidesort. According to the README page of glidesort, wikipedia claims that quicksort is unstable, which is false per this repo (see below)
* [] [Merge Sort](Any_textbooks) : textbook merge sort with one extra array.
* [] [Power Sort](https://en.wikipedia.org/wiki/Powersort)
* [] [Quad Sort](https://github.com/scandum/quadsort)
* [] [Flux Sort](https://github.com/scandum/fluxsort)
* [] [Block Sort](https://en.wikipedia.org/wiki/Block_sort)
* [] [Glide Sort](https://github.com/orlp/glidesort)

## Important note

The initial goal is to faithfully implement these algorithms as they are specified in their respective references in lean. Subsequent goals might include optimising them for the particular execution model and memory management style of lean (such as the functional-but-in-place feature).