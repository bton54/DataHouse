I decided to create a simple python script in a JuPyter notebook (for viewing flexibility)
that processes the JSON's "applicants" portion of the dictionary and returns a JSON file
that scores each applicant cumulatively.

The scoring metric is broken down into three parameters and standardized to be between [0,1].

Based on the nature of the context clues, it appears that we are hiring someone for either a spice-eating challenge
or a capsaicin research experiment. The spice tolerance may be included in conjunction with the strength and endurance metrics,
which may be important in determining how capable someone may be in handling spicy dishes. Furthermore, intelligence would also
be important particularly for the latter assumption in the case of recording details and observations.


- Intelligence is weighted at 30% for research and analysis compatibility / ease
- Endurance is weighted at 20% for sustained efforts and long research hours
- Strength is weighted at 10% because of how being physically stronger may make you more tolerant
- Spice tolerance is weighted at 40% because this is what we want to directly observe

