# Builder  

The Builder pattern handles the construction of objects that may contain a lot of parameters, and we want to make the object immutable once we're done constructing it.  

I want to look at a class that can be possibly used for creating lunch orders. It can be used to build out individual orders. It will contain fields for the different components of an order. I will apply the Builder pattern so that a lunch order is immutable once it has been built. The Builder pattern will also make it easier to define the contract of what a valid lunch order is.
