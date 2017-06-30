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


**Each (.zip) file contains 3 files:**

 1. An SQLite database (.db) file of the 'Ahadith' ***with and without** Arabic diacritics (tashkeel تشكيل)*,
 Elaboration of Hadith (Tafseel  تفصيل الحديث) **with** Arabic diacritics.
 
 2. A (.csv) file of the 'Ahadith' and 'Tafseel' **with** Arabic diacritics.
 3. A (.csv) file of the 'Ahadith' only **without** Arabic diacritics.
 
 >  this structure will overcome Arabic Searching problems stated
> [here](http://safe.phpclasses.net/browse/view/html/file/12751/name/readme.html), so you can search user's input **without** diacritics, and return results **with** diacritics.
> 
 >(use [this program](http://sqlitebrowser.org/) to have a better understanding of files' structure).


----------


notes:
 - the code used to remove the diacritics can be found [here](https://gist.github.com/mhashim6/7d96f7ea274c9eb7e509798a332d78ac).
 - UTF-8 encoding is always used.
 - both 'Musnad Ahmad ibn Hanbal' and 'Sunan al-Darimi' don't include elaboration.
 
----------

**The original CSV files can be found in [hadith-islamware repository](https://github.com/ceefour/hadith-islamware).**
