# IA

Problem Setup:
1.Warehouse Layout:

A grid-based warehouse environment (e.g., 10x10 grid).
Obstacles such as shelves, walls, and dynamic objects (e.g., other robots).
Pickup and delivery points marked on the grid.

2.Robot Actions:

Move: Up, Down, Left, Right.
Pick: Pick up an item at the pickup point.
Drop: Deliver an item at the delivery point.

3.Rewards:

+10 for successfully delivering an item.
-1 for each step taken.
-10 for collisions with obstacles or other robots.
-5 for running out of energy.

4.State Space:

Robot position (grid coordinates).
Item status (picked up or not).
Energy level (e.g., 100 at start, depletes with movement).

5.Goal:

Maximize cumulative rewards by delivering as many items as possible without collisions and before running out of energy.
