RACE SIMULATOR READ-ME:
=======================

note: this is not my code, got it from
[here](http://www.reddit.com/r/formula1/comments/2izfll/race_simulator_predictions_russia_2014/)
and [here](https://drive.google.com/folderview?id=0BwS1t9oxSE-6N2xoQnNEdTlIVjQ&usp=sharing) 

Race simulator for Matlab developed by AJK Phillips, 2014.
Please credit use of this simulator to http://f1metrics.wordpress.com/

INSTRUCTIONS:

For running a single simulation, first run prep_sim.m, then run racesim.m

For running many simultions, just run monte_racesim.m

Starting order and track choice are specified in prep_sim.m

Variables for drivers and tracks are specified in:

* ddata_template (driver stats, including 2014 tyre stints)

* times_template (data from qualifying and FP2)

* driver_profiles.m (other driver variables)

* track_profiles.m (all track variables)

Other functions included are:

* tyremodel.m (model of tyre degradation)

* llogcdfinv.m (probability distribution for pit-stop durations)

Have fun!

To contact the author, please email ajk.phillips@gmail.com
