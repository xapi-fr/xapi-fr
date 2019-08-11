# Vocabulary: Extensions

---

- [Activity Extensions](#activity)
- [Result Extensions](#result)
- [Context Extensions](#context)


<a name="activity"></a>
## Activity Extensions


### assessment

**IRI:** `http://vocab.xapi.fr/extensions/assessment`

Boolean value (`true` or `false`) which indicates that an activity is used with the goal to assess learners (or not).
This extension is used when the activity type is not precise enought to get this information.


### concept-family

**IRI:** `http://vocab.xapi.fr/extensions/concept-family`

This extension is used to mark an activity as being part of a larger family of activities. 
For instance, *forum* and *chat* activities belong to a larger family named *discussions*.


### correct-responses

**IRI:** `http://vocab.xapi.fr/extensions/correct-responses`

This extension accepts a list of values and is an alternative to the `definition.correctResponsesPattern` property when the activity type is not a `cmi.interaction`.


### deferred

**IRI:** `http://vocab.xapi.fr/extensions/deferred`

This extension accepts a boolean value. The statements of a deferred activity are sent after the activity really happened.


### learning-outcomes

**IRI:** `http://vocab.xapi.fr/extensions/learning-outcomes`

This extension accepts a list of values (tags or IRI) which refer to learning outcomes associated with the activity.


### mandatory

**IRI:** `http://vocab.xapi.fr/extensions/mandatory`

This extension accepts a boolean value. A mandatory activity must be achieved by learners.


### more-description

**IRI:** `http://vocab.xapi.fr/extensions/more-description`

This extension accepts a lang string and gives a more detailed description than the `definition.description` property of the activity, when needed.


### number-of-options

**IRI:** `http://vocab.xapi.fr/extensions/number-of-options`

This extension accepts a positive integer which is the number of possible answers a user can give when answering a question.


### platform-concept

**IRI:** `http://vocab.xapi.fr/extensions/platform-concept`

This extension is used to specify the type of activity as it is specifically known by a platform.
It differs from the activity type which should be as generic as possible.


### question-type

**IRI:** `http://vocab.xapi.fr/extensions/question-type`

This extension is an alternative to the `definition.interactionType` property when the activity type is not a `cmi.interaction`.


### remedial

**IRI:** `http://vocab.xapi.fr/extensions/remedial`

Boolean value (`true` or `false`) which indicates that an activity is a remedial activity (or not).


### standard

**IRI:** `http://vocab.xapi.fr/extensions/standard`

This extension is used to specify a standard the activity complies with (e.g. `scorm`, `lti`, `imscp`, `cmi5`).




<a name="result"></a>
## Result Extensions


### assessment-items

**IRI:** `http://vocab.xapi.fr/extensions/assessment-items`

This extension accepts a list of assessment items being part of an assessment activity.
Each item has an `id` property, as well as a `value` property containing the learner score for the item. 


### remedial-score

**IRI:** `http://vocab.xapi.fr/extensions/remedial-score`

This extension accepts a JSON object. It is equivalent to the result score for activities which need to store both an initial and remedial score.


### remedial-success

**IRI:** `http://vocab.xapi.fr/extensions/remedial-success`

This extension accepts a boolean value. It is equivalent to the result success for activities which need to store both an initial and remedial success.


### responses

**IRI:** `http://vocab.xapi.fr/extensions/responses`

This extension accepts a list of responses and is an alternative to the `result.response` property, which only accepts a string.


### satisfactory-indicators

**IRI:** `http://vocab.xapi.fr/extensions/satisfactory-indicators`

This extension accepts a list of indicators (tags or IRIs) that where satisfied by the learner.


### unsatisfactory-indicators

**IRI:** `http://vocab.xapi.fr/extensions/unsatisfactory-indicators`

This extension accepts a list of indicators (tags or IRIs) that where not satisfied by the learner.



<a name="context"></a>
## Context Extensions


### attempts-number

**IRI:** `http://vocab.xapi.fr/extensions/attempts-number`

This extension defines the number of attempts performed by the learner. 


### launch-method

**IRI:** `http://vocab.xapi.fr/extensions/launch-method`

This extension defines the launching method of a content as it is defined in the CMI5 specification. Possible values are `OwnWindow` and `AnyWindow`. 


### learner

**IRI:** `http://vocab.xapi.fr/extensions/learner`

This extension defines the learner (Agent) concerned by the statement when this learner is neither the actor nor the object of the statement.


### location

**IRI:** `http://vocab.xapi.fr/extensions/location`

This extension defines the location where the action took place.
The location has an `id` property, as well as a `name` property with the name of the location. 


### max-attempts

**IRI:** `http://vocab.xapi.fr/extensions/max-attempts`

This extension defines the maximum number of attempts allowed on the object. 


### max-time

**IRI:** `http://vocab.xapi.fr/extensions/max-time`

This extension defines the maximum time allowed to achieve an activity (ISO 8601).


### page

**IRI:** `http://vocab.xapi.fr/extensions/page`

This extension is used to specify a page ID, number or name.


### platform-event

**IRI:** `http://vocab.xapi.fr/extensions/platform-event`

This extension is used to specify the original event as it is specifically known by a platform.


### question-mode

**IRI:** `http://vocab.xapi.fr/extensions/question-mode`

This extension details the context in which a question were asked.


### scoring-method

**IRI:** `http://vocab.xapi.fr/extensions/scoring-method`

This extension defines which score must be kept when the learner gets multiple scores. 



