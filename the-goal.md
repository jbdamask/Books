# The Goal
### Eli Goldratt

## Opinion
Fantastic book on operations. Theory of Constraints is a powerful, intuative, methodology to control the flow of work through a complex system. The Phoenix Project is the IT version (another great book but this is the root).

## Grade: A+

## Points of note

Quote | Page 
--- | ---
We simply need to look at reality and think logically and precisely about what we see.|-1 (Introduction)
"Look at your efficiencies. Don't come crying to me about not enough people until you show me you can effectively use what you've got"|pg 5
Productivity is meaningless unless you know what your goal is|pg 32
There is only one goal|pg 37
I make a list of all the items people think of as being goals: cost-effective purchasing, employing good people, producing products, etc <br/><br/> If the goal is for the company to make money, an action that moves us toward making money is productive. And an action that takes away from making money is non-productive|pg 41
The minimum number of measurements needed to know if you're makeing money?<br/><br/>* Net profit<br/>* ROI<br/>* Cash flow|pg 49
So this is the goal: To make money by increasing net profit, while simultaneously increasing return on investment, and simultaneously increasing cash flow<br/><br/>I've found one clear goal and worked out three related measurements to evaluate progress towards that goalI've found one clear goal and worked out three related measurements to evaluate progress towards that goal<br/><br/>How do I build a direct connection between the three measurements and what goes on in my plant?|pg 49
The operational rules that can be devised from these are: <br/>1 Throughput - the rate at which the system generates money through sales<br/>2 Inventory - all the money that the system has invested in purchasing things which it intends to sell<br/>3 Operational expense - the money the system spends in order to turn inventory into throughput<br/><br/>This goal is expressed as: Increase Throughput while simultaneously reducing both Inventory and Operational expense|pg 60
Express the goal in terms of the measurements|pg 61
JBD - For a company to evaluate whether a new platform, such as cloud computing, is beneficial it can consider Throughput as the rate of solution delivery, Operational expense as the amount spent to support the throughput. Inventory isn't straighfoward as this is knowledge-work. You may say that a software package is a product, and therefore inventory, but that's not clean. Maybe technical debt? One way to think about it is if the platform results in lower technical debt then teams can deliver quality faster. How is this measured? Tickets wouldn't work in cases where many products were being developed by many teams having local standards. Maybe a proxy measure is system architecture, e.g. loosely coupled components make changes easier. This goes to our developer strategy of leveraging managed services as much as makes sense and designing "high in the stack". If people are still building monoliths on persistent EC2s then they're not getting the benefits from the cloud. | Personal note
Jonah was using the measurements in the crude form of simple questions: did we sell any more products? did we lay off anybody? did our inventories go down?|pg 67
(This part of the book talks about robots and how they haven't resulted in increased sales and, therefore, only increased costs)<br/>The bottom line is this: to give the robots more to do, we released more materials, which in turn increased inventories, which has increased our costs. But the cost of those parts went down, didn't it? What about the added carrying cost of inventories? That's operational expense and if that went up, how could the cost of parts go down?|pg 71
Bob: How can you account for everythig in the whole damn system with three lousy measurements?<br/>Lou: Well for capital expenses on things like machines, the depreciation on that machine is operational expense. Whatever portion of the investment still remains in the machines, which could be sold, is inventory. <br/>Bob: What? I thought inventory was products we are going to sell.<br/>Lou: The whole plant is an investment which can be sold, so investment is the same thing as inventory. Any money we've lost is operational expense, any investment that we can sell is inventory|pg 75
Consider the above whenever looking to make a significant expense. You need to know how you'll measure the increase in value you assume you'll get out of it|Personal note
**A plant in which everyone is working all the time is very inefficient**|pg 84
The goal is not to reduce operational expense by itself. The goal is not ito improve one measurement in isolation. The goal is to reduce operational expense and reduce inventory while simulaneously increasing throughput|pg 87
**_Whoever is moving the slowest is the one who governs throughput_** <-- this is the crux of the Theory of Constraints |pg 115
This combination of dependency and fluctuations is why we have so many late orders<br/> You can imagine what happens when we've got dependency running through ten or fifteen operations|pg 137
You should not balance _capacity_ with demand. What you need to do instead is balance the _flow of product_ through the plant with demand from the market. Let me repeat: Balance flow, not capacity. The bottleneck flow should be on par with demand|pg 139
Adjust capacity so the bottleneck is at the front of production|pg 140
You can't find the constraint unless you track the work backlog. In an IT shop this is all the more reason for all work to be in tickets. If you're on a team that seems crazy busy, make sure each activity is a ticket. |Personal note
Your bottlenecks are not maintaining a flow sufficient to meet demand; you need to find more capacity. To increase the capacity of the plant is to increase the capcity of _only_ the bottlenecks. What you must do is find enough capacity for the bottlenecks to become more equal to demand|pg 152
Some percentage of a non-bottleneck's time _should_ be idle; but on a bottleneck, it's exactly the opposite|pg 153
I want to know where you do quality inspection on bottleneck parts. (Al takes Jonah over to QC). Did these parts come through a bottleneck? Yes. Do you realize what the rejection means? We lost time on the bottleneck, which means we lost throughput! We should put QC in front of the bottleneck. Be sure the process controls on bottleneck parts are very good|pg 157
In an IT shop, activities for bottleneck areas should be checked for value and specific requirements before going into their backlog|Personal note
Make the bottlenecks work only on what will contribute to throughput _today_, not nine months from now. The other way to increase bottleneck capacity is to take some of the load off the bottlenecks and give it to non-bottlenecks|pg 159











<br /> 