# Synchronization-Simulator
You will write a synchronization simulator to show the different
results of concurrent processes / threads accessing shared data
variables with and without using synchronization tools.

• Assume a critical section that changes the values of shared variables
by adding or subtracting values from these variables from n
processes or threads. (See water well example below)

• Your simulator should define the used processes (n1 adders and n2
subtractors) or threads (see example below) and run these processes
random number of times. (n1 /adders and n2 / subtractors / removers
are also random and not necessarily equal)

• The simulator should show the expected correct values of the shared
variables (by calculating the number of times each adder process
accesses a variable and the same for subtractors) and compare it to
the real resultant values of these variables assuming no
synchronization tools were used.

• The simulator should show the expected correct values of the shared
variables (by calculating the number of times each adder process
accesses a variable and the same for subtractors) and compare it to
the real resultant values of these variables assuming synchronization
tools were used.
