# Vocabulaire : Extensions

---

- [Extensions d'activité](#activity)
- [Extensions de résultat](#result)
- [Extensions de contexte](#context)


<a name="activity"></a>
## Extensions d'activité


### assessment

**IRI:** `http://vocab.xapi.fr/extensions/assessment`

Cette extension dont la valeur est `true` ou `false` permet d'indiquer qu'une activité à vocation d'évaluation ou non. Elle est particulièrement utile lorsque le type d'activité ne permet pas cette distinction.


### concept-family

**IRI:** `http://vocab.xapi.fr/extensions/concept-family`

Alors que le type d'une activité est supposé décrire relativement précisément la nature de l'activité, cette extension permet de catégoriser les activités en grandes familles. Cette classification présente un intérêt en termes d'analyse statistique.


### correct-responses

**IRI:** `http://vocab.xapi.fr/extensions/correct-responses`

Cette extension est applicable aux activités de type question. Elle permet de spécifier la liste des bonnes réponses attendues. C'est une alternative à `correctResponsesPattern` lorsque l'on ne souhaite pas utiliser le format de question `cmi.interaction`.


### duration

**IRI:** `http://vocab.xapi.fr/extensions/duration`

Cette extension permet de spécifier la durée théorique d'une activité (format ISO 8601).


### learning-outcomes

**IRI:** `http://vocab.xapi.fr/extensions/learning-outcomes`

Cette extension permet de préciser une liste d'objectifs pédagogiques associés à l'activité, sous forme de tags ou IRIs.


### more-description

**IRI:** `http://vocab.xapi.fr/extensions/more-description`

Cette extension permet de fournir une description détaillée de l'activité, en complément de la propriété `definition.description` et en respectant le même format (language map).


### number-of-options

**IRI:** `http://vocab.xapi.fr/extensions/number-of-options`

Cette extension est applicable aux activités de type question. Elle permet de préciser le nombre d'options disponibles pour formuler la réponse.


### platform-concept

**IRI:** `http://vocab.xapi.fr/extensions/platform-concept`

Alors que le type d'une activité est supposé rester générique et indépendant de la plateforme qui le supporte, cette extension permet de préciser le concept correspondant au sein de la plateforme VLE.


### question-type

**IRI:** `http://vocab.xapi.fr/extensions/question-type`

Cette extension est applicable aux activités de type question. Elle permet de préciser le type de question. La valeur de cette extension sera préférentiellement une des valeurs prévues par le format `cmi.interaction` pour la propriété `definition.interactionType`, mais d'autre valeurs peuvent être utilisées si nécessaire.


### remedial

**IRI:** `http://vocab.xapi.fr/extensions/remedial`

Cette extension dont la valeur est `true` ou `false` permet de préciser si l'activité est un activité de remédiation ou non.


### standard

**IRI:** `http://vocab.xapi.fr/extensions/standard`

Cette extension permet de préciser le standard respecté par l'activité : `scorm`, `lti`, `imscp`, `cmi5`, etc.





<a name="result"></a>
## Extensions de résultat


### assessment-items

**IRI:** `http://vocab.xapi.fr/extensions/assessment-items`

Cette extension permet de lister des éléments d'évaluation relevés par exemple lors d'un test, en précisant pour chacun d'eux leur identifiant (`id`) et la note obtenue (`value`). 


### responses

**IRI:** `http://vocab.xapi.fr/extensions/responses`

Cette extension est applicable aux résultats dans le cadre de la réponse à une question posée. Elle permet de préciser la liste des réponses fournies. Contrairement à la propriété standard `result.response`, cette extension prend la forme d'une liste, et nom d'une chaine de caractères.


### satisfactory-indicators

**IRI:** `http://vocab.xapi.fr/extensions/satisfactory-indicators`

Cette extension permet de lister des indicateurs considérés comme satisfaisants dans le cadre d'une évaluation. Il s'agit d'une liste d'IRIs. 


### unsatisfactory-indicators

**IRI:** `http://vocab.xapi.fr/extensions/unsatisfactory-indicators`

Cette extension permet de lister des indicateurs considérés comme non satisfaisants dans le cadre d'une évaluation. Il s'agit d'une liste d'IRIs. 



<a name="context"></a>
## Extensions de contexte


### question-mode

**IRI:** `http://vocab.xapi.fr/extensions/question-mode`

Cette extension est applicable aux contextes dans le cadre de la réponse à une question posée. Elle permet de préciser un mode de questionnement particulier.


### location

**IRI:** `http://vocab.xapi.fr/extensions/location`

Cette extension permet de définir la localisation d'une activité, en précisant un identifiant (`id`) ainsi qu'un nom de localisation (`name`).


