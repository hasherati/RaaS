# RaaS
Randomness as a Service
#
Every time I create an SSH key on server, I ponder just how random the entropy source is for that system.  The Linux kernel PRNG used to be sufficient, but as computing power increases, it becomes a more serious issue, especially with the rise of IoT.  Instead of leaving this to chance, this project will set out to create a service on a system that has a hadware random number generator on it.  It will expose that service as input to a virture deivce PRNG that a client system can use as it's source for entropy generation.
