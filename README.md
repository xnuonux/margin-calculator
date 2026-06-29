# usage pricing margin calculator

a single self contained html file that computes usage based pricing. you enter the vendor cost per unit, a target margin percent, and the number of units. as you type it shows the price to charge per unit, total revenue, total cost, and profit.

how the math works:

- margin is defined as profit divided by price, so price per unit = cost / (1 - margin).
- total revenue = price per unit times units.
- total cost = cost per unit times units.
- profit = revenue minus total cost.

to run it: open index.html in any browser. no server, no build step, no external libraries. all css and javascript are inline.

aesthetic: a minimal dark planetarium look with a deep navy background, soft silver text, and one cobalt accent.
