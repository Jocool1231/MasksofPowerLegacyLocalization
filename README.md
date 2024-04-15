# Masks of Power: Legacy Localization
This is a repo for translating the Bionicle Fan game, "Masks of Power: Legacy".

## How to Translate:
It's quite simple, First download the file "BMOPEn.po".

_(If your language needs gender information, you can find a refrence here: https://drive.google.com/file/d/1_z7j_OgCjw-ll-Mcsa49y06z3gQswmng/view?usp=sharing)_

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
