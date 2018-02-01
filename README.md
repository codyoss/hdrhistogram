# hdrhistogram

A pure Go implementation of the [HDR Histogram](https://github.com/HdrHistogram/HdrHistogram).

> A Histogram that supports recording and analyzing sampled data value counts
> across a configurable integer value range with configurable value precision
> within the range. Value precision is expressed as the number of significant
> digits in the value recording, and provides control over value quantization
> behavior across the value range and the subsequent value resolution at any
> given level.

For documentation, check [godoc](http://godoc.org/github.com/codyoss/hdrhistogram).

*NOTE*:

- This is a fork, I am not smart enough to write this quality of code. The reason I forked this is the original repo is archived and no longer accepting PRs.
  This fork has some of the PRs merged in as well.