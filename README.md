# Masks of Power: Legacy Localization
This is a repo for translating the Bionicle Fan game, "Masks of Power: Legacy".

## How to Translate:
It's quite simple, First download both files in the repo "NameGenders.ods" and "BMOPEn.po".

_(The Name Genders file is a refrence for character genders, in case your language needs that information!)_

Then rename your copy of "BMOPEn.po" to the relevant abbreviation for your language. (For example Spanish would be: "BMOPEs.po")

After you've done that you can open the .po file in the text editor of your choice and start translating! 

A few rules: 
  - Only translate text next to **msgstr** tag.
  - Keep formatting intact and **untranslated**.

## Formatting:
  - **$T** inserts the players's name into the scentence.
  - Anything inside **<>** angle brackets changes the visuals of the text.
  - **</>** a forward slash inside angle brackets indicates the end of a visual change in the text.
  - Anything within **{}** curly brackets is replaced with a variable.

When you want to submit your changes, make a pull request including the new file, and if everything is in order it will be approved.
