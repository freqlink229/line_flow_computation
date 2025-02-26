# line_flow_computation
In any power system having N buses, there are mainly three kind of buses Slack bus, generator bus, load bus, at each bus different quantities are given and the remaining we have to calculate.
Like in case of a slack bus we take voltage as reference so we calculate active and reactive power at slack bus, for a load bus we know about the load i.e(active and reactive power) so we calculate the remaining variable - voltage similarily in case of a generator bus we know the voltage at which the generator will produce the power and how much active power will it produce, so here we calculate remaining voltage angle and reactive power.
There can be various method to do that but here I have implemented the Gauss seidel algorithm to attain these unknown variables!
