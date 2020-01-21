





-note 1.-scope: when called from archaeological-stage-comletion-events: this = fleet(of assigned leader) from = archaeological_site
                    valid scopes: (fleet, ship, planet, pop, leader, army, megastructure, sector, starbase)
            -1: "minor_artefacts" itself has associated locs.:
	                minor_artifacts:0 "Minor Artifacts"
	                minor_artifacts_desc:0 "Minor artifacts ( £minor_artifacts£ ) [ ... continued]"
            -2: investigata: different value for string-variable
-note 2.
            -1: outcome of locked_random_list is chosen ONCE per event-scope
                    (probably through some seed that is generated for each event scope)
            -2: tooltip usin "random_list"    =>||"Minor Artifacts Found:"
            -3: a proper tooltip is important   ||"33% chance of: £minor artifact£ 1"
                    for Archeology-Events as they   ||"33% chance of: £minor artifact£ 3"
                    are printed in the log AS IS.   ||"33% chance of: £minor artifact£ 5"


-note 3:    -Archaeology-Events are
