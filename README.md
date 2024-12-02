# Masks of Power: Legacy Localization
This is a repo for translating the Bionicle Fan game, "Masks of Power: Legacy".

## How to Translate:
It's quite simple, First download the file "BMOPEn.po".

_(If your language needs gender information, you can find a reference here: https://drive.google.com/file/d/1_z7j_OgCjw-ll-Mcsa49y06z3gQswmng/view?usp=sharing)_

Then rename your copy of "BMOPEn.po" to the relevant abbreviation for your language. (For example Spanish would be: "BMOPEs.po")

After you've done that you can open the .po file in the text editor of your choice and start translating! 

_(We recommend trying something like Poedit! Found here: https://poedit.net/)_

When you want to submit your changes, make a pull request including the new file (or new version of that file), and if everything is in order it will be approved.
**Make sure to make pull requests often! Especially when adding a new language to the repo.**

If you spot a spelling mistake, or any other kind of issue, make an issue to report it! (Including in the English version)

A few rules: 
  - Only translate text next to **msgstr** tag.
  - Keep formatting intact and **untranslated**.

## Formatting:
Name tags:

 - **$T** inserts the players's name into the scentence, this can be male or female depending on their current Toa.

	- Example:
   
     		 "Welcome $T!"
      
     		 Would become,
      
     		 "Welcome Tahu!"

Style tags:

 - Styling tags are used to change the look of text. They tell the text system to use a different font / size / material for the encapsulated piece. Styling tags do not support line breaks inside them.

	- Example:
   
      		This is regular text. < Key >This is white text</> This is regular text again.

Variables:

  - Anything within **{}** curly brackets is replaced with a variable, these need to remain verbatim in the translation.

	- Example:
   
     		 “It’s {Character}’s Birthday”
      
     		 {Character} needs to be retained in a translation.
      
     		 “{Character} hat heute Geburtstag”
  
  	Variables can also be used with modifiers. 

   	- Plural modifier example:
   
	     	"{NumCats} {NumCats}|plural(one=cat,other=cats)"

       		NumCats = 1
       
	      	1 cat
       
    	  	NumCats = 2
       
    	  	2 cats
       
    -  Gender modifier example (You may replace words with this):
   
	      	“Like {G}|gender(He, She, They) {G}|gender(has, has, have) told me.”

    A more comprehensive list and more modifiers can be found here: https://docs.unrealengine.com/5.1/en-US/text-localization-in-unreal-engine/#textformatting

If you would like a more in depth look at localization in Unreal Engine, we reccomend reading the Unreal Localization documentation: https://docs.unrealengine.com/4.27/en-US/ProductionPipelines/Localization/Formatting/

# Textures:
To translate a texture, make sure you have the "Goudy Trajan Regular" font installed, create a new image with the same dimensions of the English variant, and attempt to match the English version's stylings.
	
While It's not necessary to translate the matoran text images, it is encouraged. So that the text can be understood by those familiar with the matoran language.

The Wall of Prophices images have normal maps, if possible please generate normal maps for your language as well. (Otherwise I'll have to do it)

For any other questions please ping Jocool1231 on the Bionicle: Masks of Power server, in the #legacy_translation channel.
