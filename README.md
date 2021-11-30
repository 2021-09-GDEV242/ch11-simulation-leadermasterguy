# Ch10-Simulator
tweaked existing simulation in multiple ways:

 age field is now held within Animal superclass, instead of subclasses
 
 certain methods are now held in the abstract superclass Animal instead of their subclasses:
     breed(), incrementAge(), canBreed()
     
 added abstract methods, with concrete versions within the Animal subclasses to get and set certain fields: 
     setAge(), getAge(), getBreedingAge(), getMaxAge(), getBreedingProb(), getMaxLitter()
     
 added Bear class(subclass of Animal), and implemented into simulation
     Bear eats both foxes and rabbits, gaining food up to a maximum value
     Bear acts nearly identical to fox, outside of addition of eating foxes, hunger changes, and number tweaks
     
 

 
