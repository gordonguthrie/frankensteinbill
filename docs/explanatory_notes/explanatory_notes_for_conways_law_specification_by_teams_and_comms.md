# Explanatory notes for Conway's Law

[Conway's Law](https://www.melconway.com/Home/pdf/committees.pdf) tells us that the communication structure of a team that creates software determinest the technical architecture. 

It is profoundly non-intuitive, but also stunningly obvious when it has been pointed out.

Imagine you are god and you decide to create Man. You set up one team of angels to create the forearm and another to create the upper arm. By creating the teams you create an elbow, that which connects the work of the two teams.

So it is with software. Each team produces output and its work communicates with the other teams through interfaces: APIs, ABIs, function invocation, RPC, broadcast, whatever.

There is an iterative design cycle:

* set up 2 or 3 teams
* sketch out a technical architecture/prototypes
* examine the technical architecture/prototypes (and throw them away)
* design a team structure in light of what you have learned
* start building

What we see in the Social Security (Scotland) Act 2018 is the definition of a series of benefits whose policy content and internal structure is to be defined in the future in regulation - so we have made policy decisions. But the very fact that the mininster will lay these regulations at different times implies different teams will be set up to implement them, which in turn conjures up technical architectures: database partitions, web structures, processes, integrations.

These structures may not be what provides the best, fastest, cheapest, most effective services to the citizens.

During the delivery process it might have become apparent that it would be better to merge 1, 2 or 3 of the benefits but because of the delegation of powers that is not possible.

# Eliminating speedbumps of this form

It is important to understand the context here. The Social Security Benefits listed were being transferred from the UK to Scotland - they were not new benefits, but locked into a political and social expectation of continuity - the freedom to deliver radically different forms is constrained by hard political realities.

A mechanism to do this would involve a single power to lay regulations, including but not limited to, those listed, and with the ability to amend or otherwise adjust the list.

Other typical mitigations against sub-optimal implementations due to Conway's Law are formal points in a programme where the organisational structure can be aligned with a different target operating model and technical and depoloyed architectures adjusted to bring them into alignment with the now better understood new world.
