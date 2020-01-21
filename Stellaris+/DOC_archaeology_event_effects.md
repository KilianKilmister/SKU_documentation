

ADD LINE NOTATION



scripted_effect:   (often called by archaeological-stage-comletion-events, note 1.scope)
      -custome_tooltip calls for loc.: "$minor_artifacts$ Found:" (note 1.1)
      -The assosiated loc. calls for a string-variable: "$minor_artifacts$".
       but note $minor_artifacts$ (note 1.2) does not have a value set yet
      -The scripded_effect is called once the stage-event-option is triggered by the player.
       so using "random_list" the Event-Window would close before the outcome is decided.
       but using "locked_random_list" (note 2.1) we can determin the outcome before we execute the effect.
       and thus we can get a proper tooltip: (note 2.2/3)
             (custome_tooltip:) |"Minor Artifacts Found:"
           (generated tooltip:) |"£minor artifact£ [amount]"




doesn't generated tooltip
       -owner of [scope] (note 3): gets "Artifact-Tutorial"-eventt



scripted_effect:
      -same as last with different amount
