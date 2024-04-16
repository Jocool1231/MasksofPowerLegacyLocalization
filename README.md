# Masks of Power: Legacy Localization
This is a repo for translating the Bionicle Fan game, "Masks of Power: Legacy".

## How to Translate:
It's quite simple, First download the file "BMOPEn.po".

_(If your language needs gender information, you can find a refrence here: https://drive.google.com/file/d/1_z7j_OgCjw-ll-Mcsa49y06z3gQswmng/view?usp=sharing)_

Then rename your copy of "BMOPEn.po" to the relevant abbreviation for your language. (For example Spanish would be: "BMOPEs.po")

After you've done that you can open the .po file in the text editor of your choice and start translating! 

_(We reccomend trying Poedit! Found here: https://poedit.net/)_

A few rules: 
  - Only translate text next to **msgstr** tag.
  - Keep formatting intact and **untranslated**.

## Formatting:
  - **$T** inserts the players's name into the scentence, this can be male or female depending on their current Toa.

  - Style tags:
    - Example:
      This is regular text. < Key >This is white text</> This is regular text again.

  - Anything within **{}** curly brackets is replaced with a variable, these need to remain verbatim in the translation.
    - Example: 
      “It’s {Character}’s Birthday” 
      {Character} needs to be retained in a translation. 
      “{Character} hat heute Geburtstag”
  
    - Variables can also be used with modifiers. 

    -  Plural modifier example:
	      "{NumCats} {NumCats}|plural(one=cat,other=cats)"

	      NumCats = 1
	      	1 cat
    	  NumCats = 2
    	  	2 cats
    -  Gender modifier example:
	      “Like {Gender}|gender(He, She, They) {Gender}|gender(has, has, have) told me.”

    A more comprehensive list and more modifiers can be found here: https://docs.unrealengine.com/5.1/en-US/text-localization-in-unreal-engine/#textformatting


When you want to submit your changes, make a pull request including the new file, and if everything is in order it will be approved.

We reccomend reading the Unreal Engine Text Localization documentation before translating: https://docs.unrealengine.com/4.27/en-US/ProductionPipelines/Localization/Formatting/
