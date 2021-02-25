# Release notes for Learning Content Education


## Version 3.0
* Delete element lceStartEtry for fixed text in gaps, now use attribute answertype
* Add value "fixed" to attribute answertype
* Add new attributes: 
    * contentclass: semantic meaning of an element
    * answerlength: expected length of an answer
    * answerformat: string, integer, decimal, date and math
    * placeholder: for text which can be overwritten by the user
* Add new element: lceBox. Based on fig. Can be used everywhere fig can be used.
* Redesigned all graphic interactions. All now use a standard base content model with lceGraphicInteractionMap and lceGraphicInteractionArea as main elements.
* Changed: lceGraphicTextEntry and lceGraphicAssociate. Both are not downwards compatible.
* Add new interactions: 
    * lceGraphicGapMatch2. The old lceGraphicGapMtch still remains because it is used quite a lot. New user should use lceGraphicGapMatch2
    * lceGraphiHotspot. In this hotspot question the element lceExplanation can be used.
    * lceChoiceInteraction. The child lcAnswerOptionGroup2 is allowed more often. Text can be put in between.
    * lceOrderInteraction. The child lcSequenceOptionGroup2 is allowed more often. Text can be put in between.

## Version 2.3 / 2.4
* Add new interaction: lceGraphicAssociate - interaction where you can reate hotspots and set relation between hotspots (drawing lines)
* Add new element lceExplanation: based on div, available in undbounded choice group with lcAsset2; should be used to explain the content/context of a question/answer. In graphic interaction2 questions beside lcHotspot2 avalaible after the lcQuestion2 element.

## Version 2.2.1
* Changed content model of lcePerformQuestion.content: add lcOpenAnswer2


## Version 2.2
* Add new interactions: lceChainMatching - matching items from more than two bukkets

## Version 2.1
* Add new interaction: GraphicTextEntry
