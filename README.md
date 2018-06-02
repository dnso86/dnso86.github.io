# Isdal Woman name finder
This is an online tool running in any up-to-date browser helping finding out partially missing / assumed to be modified names from evidence collected in the [Isdal Woman](https://en.wikipedia.org/wiki/Isdal_Woman) case.

Some additional links at the [bottom](#do-you-remember-this-woman) of this page.

*TL;DR* The basic idea is identifying an original name based on the leftovers, by brute-forcing a list of possibly relevant first and last names against characters we think we could still recognise. 

***
➡️ [CLICK HERE TO OPEN THE TOOL!](isdal.html) ⬅️
***

## I still don't get how this works?

In other words - if we know that:

- A name - that we don't know - consisted of three letters,
- started with **A**
- the second letter was **c** or **d**

and we have huge lists of all names used in the world - we can just go through all of them! 

That is exactly what this piece of software does. And it will tell us `Acy,Ada,Adi,Adè` among others.

If our original assumptions 🔝 were correct, and we did have a list containing all names ever used in the world - the name we were looking for is one of those we got as a result. 

## Idea 1 - the eczema cream tube

This evidence - a tube of eczema cream - is pictured [here](https://imgur.com/a/GWErhsA). There is another, large image of it [here](1ivtA9cvDXk6cGu2tuk39Qxd_19Mb9TWlcZkfZSXv7Og.jpg).

As we can see, most of the original name of the patient it was prescribed to is scraped off from the label (also the date, and the doctor's name).

- The label was made on a typewriter, therefore it is monospaced - the characters are fixed-length.
- The first name probably consisted of seven characters.

It is useful to find images of *sans-serif* typefaces used in the typewriters of the sixties for comparison. The Lucida Sans font is somewhat similar:

![](http://www.fontage.com/_images/large/ltype.gif)

This original idea stems from the book *Kvinnen i Isdalen*, by Dennis Zacher Aske - ISBN 9788241916601. 

## Idea 2 - names on the fake passport(s)

The other day an interesting [theory](https://www.facebook.com/groups/deathinicevalley/permalink/598847540485132/) popped up in the [Facebook-group](https://www.facebook.com/groups/deathinicevalley/) of the BBC podcast. Some of the name-changes could be made by very slight modifications in the names - usually adding or removing short lines:

- TIELT ➡️ NIELSEN
- ZARNE ➡️ JARLE
- FENELLA LORCH ➡️ LEENHOUWER

not to mention L. SELLING ➡️ E. VELDING she probably used on flights.

On an [image](https://imgur.com/a/CjerN0x) of a Belgian passport from the early sixties, we can see that the last name was given in block capitals - easy to modify. Remember she had a scalpel with - to remove existing lines perhaps? - and a pen is possible to obtain anywhere.

The tool could be used for such investigations too - if we give all the possible combinations containing **AR** in the middle and containing **E** at the fifth letter, we'll have a list of matching names: **-AR-E**:

- `Carle`
- `Carne`
- `Harle`
- `Marle`

These may or may not be other aliases or the original name on the fake (?) passport. Also a good example on the limitations of this approach - since at the time of writing this, neither Jarle nor Zarne are amongst the used names, they won't show up at all.

A note - in the pre-PC/printer era, they used so-called [lettering guides](https://en.wikipedia.org/wiki/Lettering_guide) to write such text in any sort of official documentation such as plans, passports etc. So this might give an idea to find those characters which could be altered to look like the other.

I'll be adding some presets to the tool ASAP for these name combinations.

## Options

- It is possible to choose different lists of names on the right side.
- Custom names can be added as: `Alpha,Bravo,Charlie` etc., and will be treated as the built-in ones.
- If *Fixed length names* is checked, the length of a possible name should be equal to the length we look for - if it is 4, and we set the first `A`, then `Anne,Abby,Alma` etc. will be found.
- But if it is unchecked, the shorter names will be found too - `Ali,Ana,Amy` in addition to the 4-character long ones.

## Presets

There are a few settings pre-defined - so to get a rough idea, just click on the *My idea 1* button for instance. Also if you can only recognize a round character at the beginning and perhaps an *I* afterwards, try the *Minimal* preset - it just shows results for that.

## License notes

The code itself is under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

[![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc/4.0/)

***

# Do you remember this woman?

Can you help us with a 47 year old unsolved criminal case?

![](https://gfx.nrk.no/QlzNqhT3Q1fwTH6TL-EtwgClPzJcuH35FGy3nvPgE6Xg)

- [Do you remember this woman?](https://www.nrk.no/dokumentar/do-you-remember-this-woman_-1.13215629)

- [Death in Ice Valley](https://www.bbc.co.uk/programmes/p060ms2h)

- [Gåten i Isdalen](https://www.nrk.no/dokumentar/gaten-i-isdalen-1.13182053)

