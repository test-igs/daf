#### Complete Summary of the Mandatory Requirements

1.  A narrative summary in **CarePlan.text**
    -   [**CarePlan.text.status**] is either “generated” or “additional”

1.  One reference to a patient in **CarePlan.subject**
1.  One category in **Careplan.category** which must have:
    -   a fixed **Careplan.category.coding.system**="[<http://argonaut.hl7.org/ValueSet/extension-codes>]"
    -   a fixed*' Careplan.category.coding.code*'=“assess-plan”

1.  One status in **CarePlan.status**
    -   CarePlan.status is bound to **[CarePlanStatus]** Value set (Code set)



  [**CarePlan.text.status**]: http://hl7.org/fhir/valueset-narrative-status.html
  [<http://argonaut.hl7.org/ValueSet/extension-codes>]: Argonaut_Extension_Codes "wikilink"
  [CarePlanStatus]: http://hl7.org/fhir/valueset-care-plan-status.html
  [`CarePlan` `Resource` `Example`]: CarePlan_Resource_Example "wikilink"
