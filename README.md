#general idea#

The puzzle invites user to normalize local traffic and decrease annoyance of all members (pedestrians and drivers) by manipulating traffic lights (perfect timing idea)

#game mechanics#

- every member of the traffic has his own level of annoyance
- annoyance grows when traffic member waits for his turn to cross the road or continue moving along the road
- annoyance grows faster when it seems for member that waiting is senseless
	> for example, there is no pedestrians near the traffic light, but the driver has to wait for green light for long time. The same for pedestrians (if there is no cars)
- every traffic member has own traits (behavior modifiers) like:
	 - amiability - will to avoid annoyance for everyone
	 - impulsiveness - will to reach own goal despite any other members
- there are random events (based on chances) like:
	- pedestrian decides to stop or continue moving depending on traffic light timing
	- driver decides to move earlier (yellow light) or continue moving after light change
	- traffic member moves on wrong light signal
- there is ability to control any traffic light manually (if something goes wrong) (?)

#game process#

- level starts from unbalanced traffic
- every level has own level of maximum (summarized) annoyance that must not be crossed (?)
- every entity has more or less detailed information (spawn timing, traits, etc)
- player needs to check all available entities (spawn points, etc) and plan traffic to reach lower level of annoyance for every traffic member
- level ends when traffic is balanced on acceptable level of annoyance

#entities#

- pedestrian - walks between key points, crosses roads in specific points
- car (driver) - drives between key points
- car entry point (spawns single cars periodically)
- pedestrian entry point (spawns single pedestrians)
- subway entrance (spawns groups of pedestrians periodically)
- crossroads

#milestones#

- procedural "city" generation (graphs)
- road rules imitation (traffic infractions)