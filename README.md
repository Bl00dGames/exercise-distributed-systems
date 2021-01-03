# dhbw

Exercise: Let's open the best cake bakery in town!

So you already got the bakery "Piece of cake" and one chef.

**CHANGE** It comes to the point that one chef can't handle all the orders of the customers.

**1.** How do you handle more orders?
Ask the chef to work harder, pay him more and his output will rise.
> Vertical scaling: optimise processes and increase throughput the same resources.

> Preprocessing & Cron jobs: Prepare beforehand at non-peak hours (let's say around 5 a.m.)

Now our business is set up. Great!

**GOAL** Resilience (recovering from failures quickly)
One day your chef is sick so there won't be any business that day.
You hire a backup chef that gets paid for the days the original chef can't work.
The chance of losing business is now very low.

> Backups: Use backups to avoid a single point of failure. 

This now something like a Master-Slave architecture with a master chef and a slave chef.

**CHANGE** Business still keeps growing and again you can't handle all the orders. Your backup chef is already working fulltime.

**2.** How do you handle more orders?
You hire more chefs and more backup chefs. Now you have 10 chefs and 3 backups.
> Horizontal scaling: Hire more resources

Great. Your backery works so well, that it is now time for ...

**GOAL** Expansion
