# SharepointTools

--- Import Terms and Synonyms ---
Powershell script that imports Terms and Other Labels (Synonyms) from a CSV file to Sharepoint Online. Try the 'No Delay' version of the script first, if there are errors try the delayed version as it works more reliably but slower. CSV formatting is shown in the GUI - you must follow this formatting exactly for the script to work. You can have an unlimited amount of L1Ts and Other Labels.

--- Update List Item ---
Powershell script that adds 1 minute to the modified date of each item in a list. This is useful for when you want to trigger a workflow on each list item when the workflow is set to 'Run when list item is changed'. Ensure that the workflow doesn't spam emails when the script runs by temporarly disabling any automated email alerts.

--- Automatically associate all sites with a single hub site ---
Powershell script that iterates through each site, removes any existing hub site association and then adds the association defined in the parameters.

--- Set Welcome Page ---
Powershell script that sets Welcome/Landing page for when the root URL is entered (e.g what shows when you type http://<tenant>.sharepoint.com/ into URL bar)
