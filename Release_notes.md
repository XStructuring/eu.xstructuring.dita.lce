# Release notes for Learning Content Education


## Version 3.0
* Delete element lceStartEtry for fixed text in gaps, now use attribute answertype
* Add value "fixed" to attribute answertype
* Add new attributes: 
    * contentclass: semantic meaning of an element
    * answerlength: expected length of an answer
    * answerformat: string or number
    * placeholder: for text which can be overwritten by the user
* Add new element: lceBox. Based on fig. Can be used everywhere fig can be used.
* Add new interaction: lceHotspot. In this hotspot question the element lceExplanation can be used.


## Version 2.3 / 2.4
* Add new interaction: lceGraphicAssociate - interaction where you can reate hotspots and set relation between hotspots (drawing lines)
* Add new element lceExplanation: based on div, available in undbounded choice group with lcAsset2; should be used to explain the content/context of a question/answer. In graphic interaction2 questions beside lcHotspot2 avalaible after the lcQuestion2 element.

## Version 2.2.1
* Changed content model of lcePerformQuestion.content: add lcOpenAnswer2


## Version 2.2
* Add new interactions: lceChainMatching - matching items from more than two bukkets

