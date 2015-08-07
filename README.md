BOTE - Back of the Envelope
=========

**Wiki**: [Back-of-the-envelope calculation](https://en.wikipedia.org/wiki/Back-of-the-envelope_calculation)

Often when designing systems we must to understand whats possible and where the bottlenecks could arise based on the architecture choices. A simple back of the envelope calculation would give you an approximate of what's achievable.

References: 

  1. [General latency numbers] (refs/latency.txt)
  2. [Jeff Dean's paper] (http://research.google.com/people/jeff/stanford-295-talk.pdf)
  3. [Using BOTE for best design](http://highscalability.com/blog/2011/1/26/google-pro-tip-use-back-of-the-envelope-calculations-to-choo.html) 

While thats good, the current hardware you have might not actually reflect the latency you are expecting. So a quick and easy way to validate some of the characteristics of hardware is key earlier in the project. 

This project is an attempt to document some techniques and tools to measure the latency and benchmarks in infrastructure. The information would be a best represented on top of a infrastructure diagram.
