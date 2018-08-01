# prolog-projects

Prolog-Assignment(poem classification):

Input format

The input format is a list of lists. List of words form a line and list of lines make a poem for all poems except Doha.
For Doha there is a list of words which make a phrase, list of phrases makes a line and list of lines makes a poem.
For example :- [[[a,b,c,d],[e,f,cat]],[[a,b,c,d],[e,f,cat]]] is a form of Doha
and [[a,b,c,d,e,f,cat],[a,b,c,d,e,f,cat],[a,b,c,d,e,f,cat],[a,b,c,d,e,f,cat],[a,b,c,d,e,f,cat]] is a Fusion Sonnet

Rhyming words-

We are assuming we are given pairs of words that rhyme and are defined by the predicate rhyme(X,Y).
Also we assume that every word rhymes with itself.



Assignment2(part of US constitution):

QUERIES

1.Who can be President?
eligible_for_president(X) - tells us if X is eligible to be president
eligible_presidential_candidates - gives us a list of eligible presidential candidates.

2.Who can the President appoint?
president_appointments(X) - tells us whether the president can appoint anyone in the position X.
president_appointments - tells us the list of positions the president can or cannot make appointments at.

3.Who can the President grant reprieves?
grant_reprieves(X) - Tells us if the president can grant X a reprieve.
grant_reprieves - From a list of offenders tells us who all can and who all cannot be granted a presidential pardon.

4.Can the President pass a certain treaty?
president_treaties - evaluates the votes of senators for a particular treaty proposed by the president and tells us if it can be passed or not.

5.Who all can be electors?
elector_check(X) - Checks if X is eligible to be an elector.
elector_check - Checks if all the electors are eligible to be electors.

6.Which states have the correct number of electors?
electors_in_state_check(X) - Tells us if the number of electors from state X is equal to the number of electors allowed from that state.
electors_in_state_check - Tells us if the number of electors voting from each state is equal to the number allowed from the respective state.
