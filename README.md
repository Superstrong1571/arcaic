Hey there, hello! Here's all of Arcaic converted to a font, just because!

A little bit of info on what you're seeing here: Arcaic.ttf is arcaic as described by Konkonocturne as a font. Arcaic CL is a variant I made that has what I call _clock ligatures_ (hence the CL in the name).

Note that when you install both fonts, they will show up as the same font on windows, but as seperate fonts within programs. I know how to fix this, but it breaks clock ligatures (or forces clock ligatures onto the base variant of the font, depending on the order you install them in). Unfortunately, we just have to put up with that.

For base arcaic, all letters are on their key, with the exceptions as mentionned [on the fic forum](https://discord.com/channels/1163198773284065394/1186231566070988821/1245698343607210034):
 - (SH) on Q
 - (TH) on H
 - (CH) on C
 - (ZH) on X

Unfortunately, I am unable to produce a key to the right of M on your keyboard for the sole purpose of keeping everything accurate, so alas, consonant Y can be found on hashtag (#).

Both uppercase and lowercase produce the same letters, nothing fancy.

I've also added exactly ___NINE___ punctuation symbols, those being the period (.), the comma (,), the exclamation mark (!), the question mark (?), the apostrophe ('), the quotation mark ("), the hyphen (-), the colon (:), and the semicolon (;).

---

On to clock ligatures!

A brief explanation:

The idea behind clock ligatures is that since all vowels are circles divided by lines that pass through the center, we can use the left half to represent one vowel, and the right half to represent another. Double vowels (eg "ee") are double-lined, with the exception of "aa," which gets a dot in the center.

Clock ligatures are only to be used on diphthongs (two vowels that make the same sound: eg "ea" in beat is a diphthong, but "ea" in create is not).

So with that in mind, how does this affect typing? Not at all (almost)! Clock ligatures are automatically applied (if you're using the clock ligature version of the font). To forcibly seperate them if the vowels don't form a diphthong, you can use a backslash (\\) between the vowels. There is also a bug where the backslash reinstates leading and trailing baselines, but just don't put a backslash at the start or end of a word and you'll be fine. You can literally see in Arcaic_CL.fea that I fixed that but it still does it, I couldn't tell you why.

---

Anyways, with this full explanation of both versions of the fonts, here are some fun facts!

 1) As you might already know, Arcaic has 27 (3\*__9__) letters. But, since I've added exactly 9 punctuation marks, there are exactly 36 (4\*__9__) unicode points in the font. Since _all_ of them have four variants, there are 144 (16\*__9__) glyphs in this font. Neat!
 2) The clock ligature variant of this font takes it a little further: there are six vowels which each gain three new glyphs (one for first vowel in a clock ligature, one for second, and one for a pair of identical vowels). That makes a total of 18 (2\*__9__) new base glyphs, a total of 72 (8\*__9__) extra glyphs on top of the first 144, making for a grand total of 216 (24\*__9__) glyphs!

(For these first two, I'm excluding the spacebar and backslash — they are both whitespace. Just ignore the part where a.lig2.fina and a.lig2.isol are also whitespace.)

 3) I made this font using FontForge and Inkscape. Although conversion of SVGs from Inkscape to FontForge forcibly resized them to a height of 1000px, you can still see my SVGs in this repo. One fact you might notice about the size of the glyphs is that the space between each glyph in Inkscape (with the exception of "d") is of _exactly_ 9px — 4,5px on each side.
 4) You might also notice that the room I left for the top and bottom of the glyph is also of 9px on both sides (ignore the width of the lines — just focus on the center one).
 5) You might also also notice that the gaps left between some glyphs that break the line (eg "j", "n", "r", maybe a few others) are _exactly_ 9px wide.
 6) This one's less of a fun fact about the font itself and more about the process that led to the font as it is now. Originally, as you might notice in "font_data/medial form/j_old.svg" the gap between each character was of 18px — 9 on each side. I reduced it since the characters were too far apart. Also, originally, the canvas was taller, at 108px (11\*__9__). Unfortunately, that lead to letters like "l", "k", and "g" being half the height of the taller ones, which looked funky. I did not want to do a bunch of math to fix this, so I cut the extra nine — I'm sure everyone agrees a nice font is better than an insignificant joke like that.

Sadly, I could not make 9 hidden nines. But 6 is close enough (just nine but upside down), and these should be more than enough for a dumb project like this one.

With that, 14139 (1571\*__9__) out.