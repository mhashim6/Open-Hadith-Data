# Open-Hadith-Data-Project
**An open Hadith Library that contains full databases of 9 different books (including the Six Books), with the Elaboration of the 'Ahadith', all the following are included:**

 - Sahih al-bukhari (صحيح البخاري).
 - Sahih Muslim (صحيح مسلم).
 - Sunan Abu-Dawud (سُنن ابي داود).
 - Jami al-Tirmidhi (جامع الترمذي).
 - Al-Sunan al-Sughra, collected by al-Nasa'i (السُنن الصغري).
 - Sunan ibn Majah (سُنن بن ماجه).
 - Muwatta Malik (موطأ الإمام مالك).
 - Musnad Ahmad ibn Hanbal (مُسند الإمام أحمد بن حنبل).
 - Sunan al-Darimi (سُنن الدارمي).


----------


**Each folder contains 2 files:**

 1. A (.csv) file of the 'Ahadith' and 'Tafseel' **with** Arabic diacritics (tashkeel تشكيل), and Elaboration of Hadith (Tafseel  تفصيل الحديث).
 
 2. A (.csv) file of the 'Ahadith' only **without** Arabic diacritics.
 
 >  this structure will overcome Arabic Searching problems stated
 > [here](http://safe.phpclasses.net/browse/view/html/file/12751/name/readme.html), so you can search user's input **without** diacritics, and return results **with** diacritics. 

----------


notes:
 - the version with diacritcs include special RTL character that surrounds special words, such as important words or narrator's names. the original writers did that so developers could highlight these words, more information about how to implement this properly is in [this link](https://stackoverflow.com/a/45018642/3578585).
 
 - if you feel uncomfortable with the RTL character, you can remove it, and you would still be able to highlight some important words, as they are surrounded by 2 spaces at the beginning and another 2 at the end.
 - the vresion **without** diacritcs is completely clean, no RTL character, no double spaces.
 - please don't use the version **without** diacritcs as your main database, alwayse show Hadith with diacritcs, so they can be read properly.
 - the code used to remove the diacritics can be found [here](https://gist.github.com/mhashim6/7d96f7ea274c9eb7e509798a332d78ac).
 - UTF-8 encoding is always used.
 - both 'Musnad Ahmad ibn Hanbal' and 'Sunan al-Darimi' don't include elaboration.
 
----------

**The original CSV files can be found in [hadith-islamware repository](https://github.com/ceefour/hadith-islamware).**
