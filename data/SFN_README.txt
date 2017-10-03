Meaning of the fields in the json file


* id: an id per entailment or presupposition stated in the file
* frame: frame in question
* lus: lus in that frame to which the presupposition or entailment applies


* excludes: Excludes relations in the frame, copied from FrameNet
* coresets: CoreSets in the frame, copied from FrameNet
* corefes: List of FEs with status Core in the frame, copied from FrameNet
* requires: sets of FEs that are in Requires relationships, copied from FrameNet

* cause: FE(s) that are causal for the relation or state that is entailed or presupposed (multiple FEs occur in cases where a Frame provides e.g. both Agent and Cause )
* intent: FE(s) who act(s) intentionally within the frame
* eventfes: FEs that refer to events
* TransitiontoEnd: does the frame report on an event with a transition to an end state? (yes, no, n/a)

* implstatus: is the abstract predicate associated with the frame an Entailment or a Presupposition?
* functor:  the abstract predicate (and concomitant reasoning scheme) that is applicable
* arg1: the FE that fills the first Argument role of the abstract predicate at issue
    example: for Possession, Arg1 corresponds to the Possessor
* arg2: the FE that fills the second Argument role of the abstract predicate at issue
    example: for Possession, Arg2 corresponds to the Possession
* funcpol:  a predicate-specific type of polarity, e.g. for Sentiment polarity refers to e.g. positive/negative (emotional) valence; for Possession it refers to whether the relation holds or not.




comment: linguistic or other notes on this entry in SentiFrameNet
status: workflow status
