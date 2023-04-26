## Flavor Notes

This is a brief example of a handwritten note in order to spruce up a homebrew with some flavor text. This is done with regular text and styled with CSS, no images used.  

The entirety of the note can be rotated whichever way directly within specific element...small adjustments are best, a few degrees within 0deg/360deg. Done inline, this will only impact one particular note at a time.

This note below consists of three parts: the Greeting, the Note, and the Signature. These individual parts are styled differently (different alignments) by adding "greeting" & "sig" in the class wrapper. I have set this up so the Signature gets a slightly different rotation in relation to the rest of the note, but that rotation can be changed in the CSS (although, it will impact all of your Flavor notes, not just a particular one).  

{{flavor,greeting,sig,transform:rotate(355deg)
Dear Reader -
  
  Zoinks! Here is a handwritten note that brings FLAVOR to the page!
  
-Gazook
}}

  
And that is a handwritten flavor note! Again, wrap the text you want in the note inside a container, and assign it the class **flavor**. Then type your message. Rotation of the entire note can be done inline.

If you want a fancy font, you'll need to be sure the font is 'available' in your brew.  Many of the basic fonts you see in every day life are available, like Helvetica, Arial, Comic Sans, etc.  But it can be hard to find "handwriting" fonts (one decent on is Trattatello).  The two fonts I'm using are 'Rock Salt' and 'Nanum Pen Script'.  These are free fonts [hosted by Google](https://fonts.google.com/).  To make sure they are available for everyone when this view this page, I import the fonts with the @import css attribute.  Google Fonts provides those for you.

### CSS Variables

A quick explanation of the the CSS Variables found at the top of the CSS portion:
1. Changing these variables will change every Flavor note in our brew, so use these variables to make global changes.
2. These variables cover text *color, font, and size*.  There are obviously other things that can be change, but you would have to go further into the CSS to do so.
3. Any changes to these variables is superseded by inline styles, meaning if you specifically want the third flavor note to have pink text, you can do so by adding "color:pink;" to the style='' portion of a div without impacting the rest of the flavor notes.

\column

{{note
##### CSS
Place the below into Style Editor:

> @import url('https://fonts.googleapis.com/css2?family=Nanum+Pen+Script&family=Rock+Salt&display=swap');  
     
> :root {
   	--base-text-color:maroon;  
   	--greeting-color:inherit;  
   	--note-color:inherit;  
   	--signature-color:inherit;  
   	--base-text-font:'rock salt';  
   	--greeting-font:inherit;  
   	--note-font:inherit;  
   	--signature-font:inherit;  
     --base-text-size:12px;  
 }  
   /* Handscript */  
 .flavor {  
   	font-family:var(--base-text-font);  
   	color:var(--base-text-color);  
   	margin-bottom:10px;  
     font-size:var(--base-text-size);  
 }  
 .flavor p {  
   	text-align:center;
   	font-family:var(--note-font);  
  	transform:rotate(0deg);  
  	color:var(--note-color);  
   	font-size:inherit;  
 }  
 .flavor.greeting p:first-child {  
   	font-family:var(--greeting-font);  
   	text-align:left;  
   	transform:rotate(0deg);  
   	font-size:inherit;  
   	padding-top:0;  
   	height:auto;  
   	color:var(--greeting-color);  
   	font-weight:unset;  
 }  
 .flavor.sig p:last-child {  
   	font-family:var(--signature-font);  
   	text-align:right;  
   	transform:rotate(-4deg);  
   	font-size:inherit;  
   	padding-top:0;  
   	height:auto;  
   	font-weight:unset;  
   	border:none;  
   	color:var(--signature-color);  
   }  
 .flavor.sig.wide p:last-child {  
   	margin-top:5px  
 }

}}

### Note on below text
The below flavor text has some minor additional inline styling to help position it, such as 'position:absolute', left and right properties, and a preset width.  Those are *not* necessary attributes are specific to this brew.

{{flavor,greeting,sig,wide,transform:rotate(-2deg),color:#777777,font-size:16px,font-family:"nanum pen script",position:absolute,bottom:10px,left:10%,width:80%
I almost forgot! -
  
  Notes can also be made "WIDE" by adding "wide" to the class names in the DIV.  And, just like changing the rotation, you can also change the text COLOR and FONT and SIZE inline for each note as well!
  
-Gazook
}}


\page

## Note Components
Here are some examples for how the structure of the note can change.

### Greeting, Body, & Signature
This note is achieved by setting {{flavor,greeting,sig

{{flavor,greeting,sig
Dear Reader-
  
  Zoinks! Here is a handwritten note that brings FLAVOR to the page!
  
 -Gazook
}}
  
### Body & Signature only

This note has no Greeting, only the body text and a Signature.  This is done with {{flavor,sig
  
{{flavor,sig
  Here is a note that doesn't have any Greeting on it, so ideally the body text is centered, and the Signature is right-justified.
  
-Gazook
}}
  
### Greeting & Body only
This note only has a Greeting and the body text, no signature.   This is done by setting {{flavor,greeting

{{flavor,greeting
  Okay...
  
  That seemed to work...now let's try a Greeting, body text, and no Signature this time....The Greeting should be left-justified, and the body text centered....
}}
  
### Body only
This note is only the body text, with no greeting or signature.  To get this, set {{flavor 

{{flavor
  Woohoo, this seems to be working! So finally, let's try ONLY body text. This should be centered, with no greeting and no signature.
  
Oh baby, now we're cooking with FIRE!
}}

\column

## Styling
Here are some examples of how to change other styling aspects such as the color, font, rotation, size...Again, these are just inline styles specific to each note.  You can also do global style changes in the CSS, and of course you can always do much more style changes with a lot more specialized CSS. 

### Rotation
Change the rotation of your note by setting transform:rotate(ndeg), changing n to any number between 0-360.  You can also use negative numbers as well.  Small adjustments, in my opinion, are better. 

{{flavor,greeting,sig,transform:rotate(350deg)
Dear Reader-
  
  Zoinks! Here is a handwritten note that brings FLAVOR to the page!
  
 -Gazook
}}

### Text Color
Change the text color in a note by setting the color:choice, and replacing *choice* with whatever color you want.  You can use color names (look online to see what names are accepted), or hex or rgb/rgba values.
  
{{flavor,sig,color:darkgreen
  Here is a note that doesn't have any Greeting on it, so ideally the body text is centered, and the Signature is right-justified.
  
-Gazook
}}
  
### Font
You can change the font used in a particular note by setting the font-family:"choice", and replacing *choice* with your font.  Be sure your font is a common web font, or that you have imported the font from Google Fonts into the top of your brew.

{{flavor,greeting,font-family:"trattatello"
  Okay...
  
  That seemed to work...now let's try a Greeting, body text, and no Signature this time....The Greeting should be left-justified, and the body text centered....
}}
  
### Text Size
If you want a smaller or larger text, you can set font-size:choice, and replace *choice* with either a pixel amount, or fraction of the normal size using "em" units (i.e. 2em sets the font twice the size).  You can also use keywords like *small*, *smaller*, *large*, and *larger*.

{{flavor,font-size:.6em
  Woohoo, this seems to be working! So finally, let's try ONLY body text. This should be centered, with no greeting and no signature.
  
Oh baby, now we're cooking with FIRE!
}}
