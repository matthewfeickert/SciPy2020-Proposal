# Talk Proposal Reviewer Comments

The talk submission [pyhf: a pure Python statistical fitting library with tensors and autograd](https://github.com/matthewfeickert/talk-SciPy-2020) was selected for presentation at SciPy 2020 (in the general track).

SciPy practices a double-open review system.
The following are the reviews for the submission:

- **SUBMISSION:** 89
- **TITLE:** pyhf: a pure Python statistical fitting library with tensors and autograd
- **AUTHORS:** Matthew Feickert, Lukas Heinrich and Giordon Stark

## Review 1

**Overall evaluation:** 3 (strong accept)

### Overall evaluation

Thank you for submitting this proposed talk!
I think its very interesting to see a Python implementation out perform a C++ one.
While I was reading the proposal a few questions came to mind that you may want to address.

* Does the Python implementation out perform C++ with numpy as the default backend?
* GPU support is mentioned, but has pyhf been tested with CuPy?
* What are the typical data sizes on disk and in-memory?
* How are the datasets loaded? (backend dependent?)

Additionally, I think it would be interesting to talk about potential applications outside of HEP.
Also, please be sure to provide the meaning of abbreviations the first time they are mentioned, for example probability density functions (pdfs).
This looks like it would be a great talk!

## Review 2

**Overall evaluation:** 3 (strong accept)

### Overall evaluation

In my opinion, this is a very interesting talk.
The authors will describe how to replace mature software tools, written in Root, with modern python and supporting libraries, such as tensorflow, pytorch and jax.
HEP is married to big data analysis.
For a scientist audience, it will therefore be very rewarding to see how these impressive libraries can be used for tasks other than machine learning.

## Review 3

**Overall evaluation:** 2 (accept)

### Overall evaluation

This looks like  a really interesting project that has applications in a number of pretty diverse domains.
Having looked a little at the github page for the project, it seems to still be pretty focused on HEP use cases which I think might diminish it's broad appeal at the conference.
If the authors can present a good range of use cases form multiple different fields I think that will help with relevance.

## Review 4

**Overall evaluation:** 3 (strong accept)

### Overall evaluation

The abstract describes the pyhf library a Python library for statistical modeling of high energy physics data.
Tensor calculations using a number of Python libraries (including TensorFlow, PyTorch and JAX), enable hardware acceleration on GPUs and improved computational performance, such that it can outperform the traditional C++ implementation.

The abstract is quite technical, however I clearly describes the purpose of the package and its main features.
I believe it will appeal both to scientists interested in statistical analysis, as well as those interested in using machine learning frameworks to improve the performance of their codes.

## Review 5

**Overall evaluation:** 1 (weak accept)

### Overall evaluation

Interesting proposal.
It is well written and easy to follow.

The library seems relevant for many scientists.


## Review 6

**Overall evaluation:** 0 (borderline paper)

### Overall evaluation

As highlighted by the author, the techniques can be useful for many.
