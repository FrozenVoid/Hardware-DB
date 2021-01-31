a scratchpad cache is a dedicated low-latency memory area
that implemented as user-accesible cache.
It can be used to faciliate fast vector operations(Memory to memory architecture vs register-based vectors),
speedup execution by keeping variables in the scratchpad area
for most of time and store rapidly changing data that could
cause cache flushes normally(which ruins performance).
https://en.wikipedia.org/wiki/Scratchpad_memory
