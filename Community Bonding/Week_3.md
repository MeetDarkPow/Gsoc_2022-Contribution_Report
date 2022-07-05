## June 5, 2022 - June 8, 2022

Link - https://github.com/r-devel/rcontribution/tree/main/collaboration_campfires/translations

Executed `get_r_translation_status` function in local workspace and understood it's workflow.


## June 9, 2022 - June 10, 2022

The datasets are saved in the output directory with the names `metadata.csv` and `message_status.csv`. Analysing the both the csv files and their column names and the values associated with them.

Variables associated with `metadata.csv` file and their meaning:

`sha`: the shortened SHA for the git commit of the r-svn repo that the data were obtained from
`date`: the date of the git commit of the r-svn repo that the data were obtained from
`package`: the name of a package containing messages to be translated
`po_file`: the name of .po files in the package sources
`component`: the "component" of the package the PO file relates to, either "C", "R", "RGui" (the latter is only in the base package)
`language`: the name of the language in English with the region as a suffix if applicable (e.g. "English_GB" vs "English")
`r_version`: the name of the R version to PO file relates do (does not always match pot_creation_date)
`bug_reports`: where to report bugs related to this PO file
`pot_creation_date`: the date the PO template file was created (when messages last updated), YYYY-MM-DD format
`po_revision_date`: the date the PO file was revised, YYYY-MM-DD format
`last_translator`: the name and email of the last translator
`team`: the name and/or email of the translation team

## June 11, 2022 - June 12, 2022

Analyzed and understood the variables associated with `message_status.csv` file. 

`message`: Relates to the message belonging to PO file
`translated`: Logical value for confirmation if message has been translated
`fuzzy`: a logical value indicating if the translation is flagged as "fuzzy", i.e. a fuzzy match of an old translation to a message that has had a minor update