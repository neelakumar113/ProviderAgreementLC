In the provider initiated case, the Patient Liaison or Patient Liaison Specialist needs to be able to indicate during their negotiation with the provider that the provider agreed to not balance bill the patient
display a checkbox that may be manually set on the Negotiation Results screen toward the top of the screen - could put this inside the Provider Actions component, or could have a new component either above or below Provider Actions
The checkbox may be manually set or reset with no edit rules applied
If the checkbox is set, then a value must be selected for the method that was used to identify that the provider agreed to not balance bill the patient
“Verbal” (over the phone with the patient liaison)
“Written” (email)
“Website” (sometimes the provider will post their policy to not balance bill on their website)
If the checkbox is reset, then any value that was selected in the method should be removed

If a subsequent patient initiated case is created where the provider actually did balance bill the patient for the same claim number that was in the provider initiated case (provider initiated cases will only have one claim according to UHC rules),
include the indicator and method from the related provider initiated case as new columns in the Related Cases with Same Claim component
The new columns will be visible in the Related Cases with Same Claim on the Case Details tab. 

Also, add the Related Cases with Same Claim component with the new columns to the Negotiation Prep tab so that it will be visible to the Patient Liaison.  Position the Related Cases with Same Claim component right below the Original Claim Information component on Negotiation Prep.
