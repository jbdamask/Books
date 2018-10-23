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
Until now, we've expedited orders onthe basis of who's screamed loudest. From now on, late orders shoujld get first priority over the others. Let's make sure the bottlenecks are processing parts for those late orders according to the same priority|pg 164
The cause was that the bottleneck parts were held up by this non-bottleneck machine running non-bottleneck parts. The operator couldn't distinguish between an unimportant batch of parts and an unimportant one. Why not? Nobody told him. I guess we need some kind of system'|pg 175
The data we have on heat-treat seems to be very inaccurate. And if this operation is so vital to the plant, then we ought to have valid statistics on it|pg 187
I sit there marveling that we're going to reduce the efficiency of some operations and make the entire plant more productive|pg 194
We've examined four linear relationships involving X and Y. We don't have to look at the trillions of combinations of X and Y to find what is universally true; we can generalize the truth simply by identifying what happens in each of these four cases|pg 209
Wrong assumption that you must make the workers produce 100% of the time, or else get rid of them to 'save' money. A system of local optimums is not an optimum system at all; it is a very inefficient system<br/><br/>He tells us that with an increase in throughput, it is possible to create new bottlenecks. But most plants have so much extra capacity that it takes an enormous increase before this happens. We've only had a 20% increase. He though it unlikely a new bottleneck would have occured|pg 210
Cut batch sizes in half<br/><br/>If we do this then I guess that at any one time we'd have half the work-in-process on the floor|pg 230
The time a piece of material spends inside a plant can be divided into four elements:<br/>1. Setup - the amount of time the part spends waiting for a resource that is preparing itself to work<br/>2. Process time - the amount of time the part spends being modified into a new, more valuable form<br/>3. Queue time - the time the part spends in line for a resource while the resource is busy working on something else<br/>4. Wait time - the time the part waits, not for the resource, but for another part so they can be assembled together<br/><br/>For parts going through the bottleneck, queue is the dominant position. For parts that are only going through non-bottlenecks, wait is dominant. If we reduce batch sizes by half, we also reduce by half the time it will take to process a batch. That means we reduce queue and wait by half as well.|pg 231
An hour lost at a bottleneck is an hour lost for the entire system. An hour saved at a non-bottleneck is a mirage|pg 233
According to the cost-accounting rules that everybody has used in the past, we're supposed to balance capacity with demand first, then try to maintain the flow. But instead we shouldn't be trying to balance capacity at all; we need excess capacity. The rule we should be following is to **balance the flow with demand, not the capacity**|pg 259
(Alex is taking on a new job as divisional manager)<br/><br>Financial numbers only reveal a fraction of the picture. You have to find out what the people think is going on. What do they see as problems? Where do we stand vis-a-vis the clients?|pg 283
(Alex needs to learn about the other companies he manages)<br/><br/>What are the techniques needed for management?|pg 283
What are the first things I should do when I assume my new position?<br/>Meet the staff; do fact finding. And once these "facts" have been assembed then what?<br/><br/>(Alex draws colored shapes on the board to represent "facts")<br/>Ok, I hold a staff meeting and what do I find? Oh, here we find fact A (draws a red circle on the board). And here are three somewhat smaller circles. And here is a tiny one and there are two which are overlapping. Now I talk with another manager and he says Oh, that ciricle isn't as big as you've been led to believe. And now someone says rectabngle exist; now squares, now triangles. The board looks like a nightmare in technicolor<br/><br/>You know, it's worse than just wasting time producing usless, pompous reports. This overconcern about the 'proper way to arrange things' manifests itself in other harmful ways. The merry-go-round that we're all too familiar with; arranging the company according to product lines and then changing it according to functional capabilities. Deciding that the company is wasting too much money on duplicated efforts and thus moving to a more centralized mode. Ten years later, we want to encourage entrepreneurship and we move back to decentralization. How should we arrange and classify these facts?<br/><br/>Throw a dart. That really clarifies what we're dealing with here; the fact that we haven't got any idea of what we're doing. If we're just looking for some arbitrary order, then what's the point of putting so much effort in collecting so much data? This avenue of first collecting data, getting familiar with the facts, seems to lead of nowhere. It's nothing more than an exercise in futility.|pg 287













<br /> 