# profiling-module
Learn how you can check to see if work is well balanced across the available processors and spot performance issues relating to garbage collection or poor load balancing.

See examples from https://github.com/simonmar/parconc-examples PCPH

Tooling wise dig into https://wiki.haskell.org/ThreadScope


Content is available at http://dev.stephendiehl.com/hask/#threadscope

# spaceleaks

- https://ro-che.info/articles/2017-01-10-nested-loop-space-leak
- http://blog.ezyang.com/2011/05/anatomy-of-a-thunk-leak/

# pusher
TL;DR is looks like the wrong technology was chosen for the problem space:

https://making.pusher.com/latency-working-set-ghc-gc-pick-two/ and followup at https://stackoverflow.com/questions/36772017/reducing-garbage-collection-pause-time-in-a-haskell-program?noredirect=1#comment61127896_36772017

# table of contents


# checklist
- https://github.com/haskell-perf/checklist

# ghc garbage collector fundamentals
- optimises for X over Y
- wherecan folks learn more?
- http://www.scs.stanford.edu/16wi-cs240h/slides/rts-lecture-annot.pdf

# exercises
https://simonmar.github.io/slides/Haskell%20in%20the%20datacentre.pdf
https://www.youtube.com/watch?v=vmFdJPs3DvU
tba

# additional materials

- https://www.youtube.com/watch?v=vmFdJPs3DvU
- https://www.microsoft.com/en-us/research/publication/parallel-performance-tuning-for-haskell/
- https://www.microsoft.com/en-us/research/publication/runtime-support-for-multicore-haskell
- https://www.microsoft.com/en-us/research/publication/a-tutorial-on-parallel-and-concurrent-programming-in-haskell
- https://simonmar.github.io/pages/pcph.html


- http://www.well-typed.com/blog/2014/02/ghc-events-analyze/
