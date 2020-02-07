# Use case: Group Travelling

(from [derhuerst](https://github.com/derhuerst), proposed in https://github.com/public-transport/ideas/issues/9)

Let's say there's a group of 6 friends from a medium-sized German city, they want to go on vacation in the Netherlands together.

* They all have different accessibility requirements and/or preferences: silent travel, wheelchair-compatible trains, children compartment, strongly preferring empty trains, etc.
* They don't live in the same place, so they all need to know which train to book for the group to have the most quick/reliable/accessible travel. It might be that the quickest long-distance bus/train/flight to their destination country is not the optimal, because there are no quick/reliable/accessible connecting local trains before/after. This is something that AFAIK nobody has done so far.
* They all have different ticket requirements: some of them are students, some of them have a frequent-traveller ticket, some of them have different degrees of disability and can therefore order price-reduced tickets, some of them have flat-fee tickets.
* On their ways to the long-distance train/bus they all want to take, delays/cancellations in connecting vehicles might occur, or they might have forgotten sth at home. It is very relevant to know, wether they will all catch that long-distance vehicle (especially if they have a group ticket or can't travel alone); For this, we must build better workflows than constantly (manually) forwarding one's realtime status via chat. If they won't catch it, what is the next-best connection, taking all above criteria into account, and how much does it cost? Is it worth paying a taxi across the city in order to catch the train?
* This whole group travel planning story gets much more complicated with every additional factor involved, e.g. travel across borders, several means of transport with different strengths, deadlines (e.g. someone has to be back for a meeting/exam), sudden sickness.

Algorithms & apps that we can built won't ever cover all of these variants, but we can at least make parts of this planning process less frustrating.
