# SignalGenerator
Quickly create an apparently random signal to test regression against.

The idea with this is to be able to build an output from any number of inputs that take a seed column and run it through some mathematical function. Each individual column is very simple to regress from the seed, but combined together and then scrambled makes the whole system appear to be pure noise. This can then be used in pair with machine learning techniques to demonstrate how much can be accomplished beyond what a person alone can.
