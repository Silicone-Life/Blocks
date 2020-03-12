# Blocks

Blocks are the most basic representations of living cells. They are simple, dumb, functional and programmable. Think stem cells IRL. 

# The Rules
1. Complexity arises during runtime. Not in the source.
2. Must not do any complex tasks.
3. Actor model based and can scale out.
4. Each block contains a manifest which specifies what it is capable of.
5. They can replicate if required to perform something complex.
6. Don't try to do anything fancy with blocks. Stick to the basics. 
7. If a block is programmed to print some text into the console, don't try to change it and print to a web page. Build a new web-printer-block. Being mouthful is okay.
8. Blocks must be non-blocking. m>_<m
9. All interblock communications must happen through a fast stateless binary compressed comm channel.
10. Any runtime errors will kill the block and it's children. End of story. Yes, each block can build it's own family tree to get something done. (as defined in manifest)
11. Each block has a unique address, derived via it's manifest or manually specified.  
12. This is NOT a block-chain.

