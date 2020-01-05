
Version 1 (v1):
---------------
05/08/2018	Base release of v1

Version 2 (v2) Aug 10th, 2018:
-----------------------------
08/10/2018 Release of v2 with addition of Tashkeel to listings of Ayas and Words. Added Fields: Sura_Number_Words, Aya_Number_Words, Aya_Text_Othmany_Tashkeel, and Word_Text_Othmany_Tashkeel. Updated the Word_Root field values to fix multiple root errors. 
08/28/2018 Updated Word_Text_Othmany_Tashkeel to remove symbols for Sajda.
Known Issues: Aya_Root field needs to be updated to reflect the updates under Word_Root.

Version 3 (v3)  Sept. 3rd, 2018:
--------------------------------
1- Renamed v2 Jummal fields to v3 Jummal_400 to reflect using a value of 400 for Taa_Marbouta
2- Added to v3 Jummal_5 values to reflect a value of 5 for Taa_Marbouta
3- Added Jummal_5 listing for Suras, Ayas, Words, 
5- Updated field names for letters with their Jummal values
6- Changed spacing in aya listings from Hex value 2000 to Hex value 0020 to allow searching in Access and Excel for Aya's text.
7- Removed fields related to Aya roots, will re-update in a future release insha Allah.
8-Added Sura_Number_Ayas, Sura_Number_Words, Sura_Number_Letters fields
9-Added fields Sura_114_flags, and Aya_6236_flags to allow filtering entire table on new Sura rows (count 114) or new Aya rows (count 6236)

NOTE:
--------
version 3 has an issue with Sura Yousef 12 Aya 39, 41 in the word for the placement of the Alf Khunjaria on an Alf_Maqsoura instead of on the Saad letter "Ì’ÏÕ»Ï" which should be written as "Ì’Õ»Ï". This issue persists in some electronic versions of the Quran such as QuranExplorer on iPhone and Android phones. This issue increased the number of letter count by 2, and the Jummal400 by 20, and Jummal5 by 20 for the Quran. This was corrected in version 4, and all affected numbers re-computed.


Version 4 (v4), Nov 9th, 2018:
_____________________________

1- Corrected the issue indicated above with word "Ì’Õ»Ï" which is described above in v3 for sura 12 ayas 39, 41.
2- Recomputed all affected numbers as a result of #1.
3- Added FirstScript columns to compute the number of letters and their jummal values per the first script written during the prophet's time, without any free Hamza or Hamza_Superscript values.
4- Added Jummal values per the decending order of occurence per letter in the Quran, considering Alf Maqsoura as a Yaa, Hamza on Alf Maqsoura as Yaa, and Hamza as Alf, Hamza_Superscript as Alf, and Hamza on Waw as a Waw.
5- Added Jummal values per the sequence of occurence per letter since the start of the Quran
6- Added the Tarmeez_1, Tarmeez_2, Tarmeez_3, Tarmeez_1_2, Tarmeez_1_3, Tarmeez_2_3, and Tarmeez_1_2_3 Jummal values to the tables per the Book from Mr. Atif Ali Saleebi referenced at https://www.facebook.com/atef.ali.9212
7-Made Quran jummal values columns accumulative for all word jummal values at every rows instead of displaying the final total value for all rows.
8- Added the following field for accumulative letter numbers so it makes letter counting easier for users:
Letter_Number_Aya
Letter_Number_Sura
Letter_Number_Quran
Letter_Number_Aya_End
Letter_Number_Sura_End
Letter_Number_Quran_End
Letter_Number_Aya_FirstScript
Letter_Number_Sura_FirstScript
Letter_Number_Quran_FirstScript
Letter_Number_Aya_End_FirstScript
Letter_Number_Sura_End_FirstScript
Letter_Number_Quran_End_FirstScript

9- Added Aya roots, and added aya occurences in the Quran by root, and in the Sura by root.
Aya_Occurences_Sura_Root
Aya_Occurences_Quran_Root

10- Added the following counters for Aya numbers from the End of the Sura and the End of the Quran
Aya_Position_Sura_End
Aya_Position_Quran_End

Hint: Use the flag columns Sura_114_Flags and Aya_6236_Flags to filter the table of 77444 words down to 6236 ayas or down to 114 suras rows.


Release 4.1:			«·ÃœÌœ ›Ì «·≈’œ«— 4.1
__________________

Â–Â «·«⁄„œ… ›Ì «·ÃœÊ· Ãœœ  «·„⁄·Ê„«  »Â« · ’ÕÌÕ ›Ì «·Ã–Ê— ·»⁄÷ «·ﬂ·„«  Ê·√⁄„œ… «·≈Õ’«¡ ·· ﬂ—«— »«·Ã–Ê—° Ê√Ì÷«  ÃœÌœ «·⁄œ «· —«ﬂ„Ì «·⁄ﬂ”Ì „‰ ¬Œ— «·ﬁ—¬‰ ··Õ—Ê› Õ Ì  ‘„· Õ’—Ì« ⁄œœ «·Õ—Ê› ··ﬂ·„… „‰ «·”ÿ— «·Õ«·Ì. ·ﬂ· ¬Ì… Ê”Ê—… Ê··ﬁ—¬‰ ﬂ·Â ··—”„ «·⁄À„«‰Ì Ê«·—”„ «·√Ê· 


Updated fields for release 4.1 Nov, 15th 2018:
These fields were updated due to corrections to some root words, and to make the accumulative reverse letter counting from the end of the Quran reflect the count inclusive of the current word number of letters, updates made reverse letter count for each Aya, Sura, and the Quran.

Aya_Occurences_Sura_Root
Aya_Occurences_Quran_Root
Word_Occurences_Aya_Root
Word_Occurences_Sura_Root
Word_Occurences_Quran_Root
Word_Root
Aya_Roots
Letter_Number_Aya_End
Letter_Number_Sura_End
Letter_Number_Quran_End
Letter_Number_Aya_End_FirstScript
Letter_Number_Sura_End_FirstScript
Letter_Number_Quran_End_FirstScript


Release 4.2:			«·ÃœÌœ ›Ì «·≈’œ«— 4.2
__________________
Updated fields for release 4.2 Nov, 17th 2018:
«·ÃœÌœ ›Ì «·≈’œ«— 4.2
Â–Â «·«⁄„œ… ›Ì «·ÃœÊ· Ãœœ  «·„⁄·Ê„«  »Â« ·⁄œ„ ﬂ„«· ÊÃÊœ «·≈Õ’«∆«  ›ÌÂ« ›Ì «·≈’œ«— «·”«»ﬁ. 
„Êﬁ⁄ «·¬Ì… «·⁄«„ «·⁄ﬂ”Ì „‰ ‰Â«Ì… «·ﬁ—¬‰
„Êﬁ⁄ «·¬Ì… «·⁄ﬂ”Ì „‰ ‰Â«Ì… «·”Ê—…

Aya_Position_Quran_End
Aya_Position_Sura_End


These fields were updated due to missing fields of data in it.


Release 4.3:			«·ÃœÌœ ›Ì «·≈’œ«— 4.3
__________________
Updated fields for release 4.3 Nov, 27th 2018:

Â–Â «·√⁄„œ… ›Ì «·Ãœ«Ê· Ãœœ  ·≈⁄ÿ«¡ «· «¡ «·„—»Êÿ… " … " ﬁÌ„… «·Â«¡ " Â " »œ·« „‰ ﬁÌ„… «· «¡ «·„› ÊÕÂ ›Ì «·≈’œ«— «·”«»ﬁ 4.0° 4.1° 4.2
The following fields were updated to set the value of Taa Marbouta … same as Haa Â Instead of the Taa Maftouha "   " as in previous releases 4.0, 4.1, 4.2
 
Word_Tarmeez_1, 
Aya_Tarmeez_1, 
Sura_Tarmeez_1, 
Quran_Tarmeez_1_Acc, 
Word_Tarmeez_1_FirstScript, 
Aya_Tarmeez_1_FirstScript, 
Sura_Tarmeez_1_FirstScript, 
Quran_Tarmeez_1_Acc_FirstScript, 
Word_Tarmeez_2, 
Aya_Tarmeez_2, 
Sura_Tarmeez_2, 
Quran_Tarmeez_2_Acc, 
Word_Tarmeez_2_FirstScript, 
Aya_Tarmeez_2_FirstScript, 
Sura_Tarmeez_2_FirstScript, 
Quran_Tarmeez_2_Acc_FirstScript, 
Word_Tarmeez_3, 
Aya_Tarmeez_3, 
Sura_Tarmeez_3, 
Quran_Tarmeez_3_Acc, 
Word_Tarmeez_3_FirstScript, 
Aya_Tarmeez_3_FirstScript, 
Sura_Tarmeez_3_FirstScript, 
Quran_Tarmeez_3_Acc_FirstScript, 
Word_Tarmeez_1_3, 
Aya_Tarmeez_1_3, 
Sura_Tarmeez_1_3, 
Quran_Tarmeez_1_3_Acc, 
Word_Tarmeez_1_3_FirstScript, 
Aya_Tarmeez_1_3_FirstScript, 
Sura_Tarmeez_1_3_FirstScript, 
Quran_Tarmeez_1_3_Acc_FirstScript, 
Word_Tarmeez_1_2, 
Aya_Tarmeez_1_2, 
Sura_Tarmeez_1_2, 
Quran_Tarmeez_1_2_Acc, 
Word_Tarmeez_1_2_FirstScript, 
Aya_Tarmeez_1_2_FirstScript, 
Sura_Tarmeez_1_2_FirstScript, 
Quran_Tarmeez_1_2_Acc_FirstScript, 
Word_Tarmeez_2_3, 
Aya_Tarmeez_2_3, 
Sura_Tarmeez_2_3, 
Quran_Tarmeez_2_3_Acc, 
Word_Tarmeez_2_3_FirstScript, 
Aya_Tarmeez_2_3_FirstScript, 
Sura_Tarmeez_2_3_FirstScript, 
Quran_Tarmeez_2_3_Acc_FirstScript, 
Word_Tarmeez_1_2_3, 
Aya_Tarmeez_1_2_3, 
Sura_Tarmeez_1_2_3, 
Quran_Tarmeez_1_2_3_Acc, 
Word_Tarmeez_1_2_3_FirstScript, 
Aya_Tarmeez_1_2_3_FirstScript, 
Sura_Tarmeez_1_2_3_FirstScript, 
Quran_Tarmeez_1_2_3_Acc_FirstScript



==========================================


Release 5.0: Dec 9th, 2018			«·ÃœÌœ ›Ì «·≈’œ«— 5.0
__________________

√÷›‰« Â–Â «·«⁄„œ… ›Ì «·ÃœÊ· Ê«·„⁄·Ê„«  »Â« ÷Ì› √‰Ê«⁄ ÃœÌœÂ „‰ «·Ã„· ··ﬂ·„… Ê«·¬Ì… Ê«·”Ê—… Ê«·ﬁ—¬‰ ·ﬂ· „‰ «·‰”Œ «·√Ê· Ê«·‰”Œ «·⁄À„«‰Ì:
Ã„· «·›Ê« Õ «·‰Ê—«‰ÌÂ 1 »≈⁄ »«— «·Â«¡ 1 ≈·« »·›Ÿ «·Ã·«·Â «··Â ›ÂÌ 2
Ã„· «·›Ê« Õ «·‰Ê—«‰ÌÂ 2 »≈⁄ »«— «·Â«¡ 2
«·Ã„· «·’€Ì— 22 „‰ 1-28 »≈⁄ »«— «· «¡ «·„—»ÊÿÂ »ﬁÌ„… «· «¡ «·„› ÊÕÂ 22
«·Ã„· «·’€Ì— 7 „‰ 1-28 »≈⁄ »«— «· «¡ «·„—»ÊÿÂ »ﬁÌ„… «·Â«¡ 7
«·Ã„· · ﬂ—«— «·Õ—› »«·¬Ì«  ··„Â‰œ” √„Ì— «·»—ÌÂÌ  
Ê»≈⁄ »«— «· «¡ «·„—»ÊÿÂ »ﬁÌ„… «·Â«¡

Ê√Ì÷« √÷›‰« ≈Õ’«¡ «·„À«‰Ì ··ﬂ·„«  Ê«·¬Ì«  Ê«·”Ê— ··œﬂ Ê— Œ«·œ »ﬂ—Ê 
Ê√Ì÷« ≈Õ’«¡ «·—’› ·⁄œœ «·√Õ—› ··ﬂ·„«  »«·¬Ì«  Ê«·”Ê—
Ê√Ì÷« √÷›‰« ≈Õ’«¡ «·’› Ê≈Õ’«¡ «·’› «·„ﬂ—— ·—’› ⁄œœ «·√Õ—› »«·ﬂ·„«  ··¬Ì«  Ê«·”Ê— 

Newly added Jummal values include the following for every Word, Aya, Sura, and the Quran in both the First Script and the Uthmany Script:
Fawateh_1 listing for values of fawateh letters with Haa=1 (except with Allah's name it is 2)
Fawateh_2 listing for values of fawateh letters with Haa=2
SmallJummal_22 listing the letters from 1-28 (Taa_Marbouta=Taa_Maftouha)
SmallJummal_5 listing the letters from 1-28 (Taa_Marbouta=Haa)
We added the Jummal LetterInAyas_7 for the number of ayas for occurence of each letter in descending order for Mr. Ameer Alborihi
We also added the binary code representing number of letters per Word, Aya, Sura for Dr. Khaled Bakro and also the Rasf (Stacking) of number of letters in words for all Ayas adn Suras
We also added the Saf (sum of numeric digits) and Saff (iterative sum of numeric digits) for all the Rasf (Stacking) values of number of letters per word in Ayas and Suras.

New Fields:«·√⁄„œ… «·ÃœÌœ…       
-------------------------
Word_Fawateh_1
Aya_Fawateh_1
Sura_Fawateh_1
Quran_Fawateh_1_Acc
Word_Fawateh_1_FirstScript
Aya_Fawateh_1_FirstScript
Sura_Fawateh_1_FirstScript
Quran_Fawateh_1_Acc_FirstScript
Word_Fawateh_2
Aya_Fawateh_2
Sura_Fawateh_2
Quran_Fawateh_2_Acc
Word_Fawateh_2_FirstScript
Aya_Fawateh_2_FirstScript
Sura_Fawateh_2_FirstScript
Quran_Fawateh_2_Acc_FirstScript
Word_SmallJummal_22
Aya_SmallJummal_22
Sura_SmallJummal_22
Quran_SmallJummal_22_Acc
Word_SmallJummal_22_FirstScript
Aya_SmallJummal_22_FirstScript
Sura_SmallJummal_22_FirstScript
Quran_SmallJummal_22_Acc_FirstScript
Word_SmallJummal_5
Aya_SmallJummal_5
Sura_SmallJummal_5
Quran_SmallJummal_5_Acc
Word_SmallJummal_5_FirstScript
Aya_SmallJummal_5_FirstScript
Sura_SmallJummal_5_FirstScript
Quran_SmallJummal_5_Acc_FirstScript
Word_LetterInAyas_7
Aya_LetterInAyas_7
Sura_LetterInAyas_7
Quran_LetterInAyas_7_Acc
Word_LetterInAyas_7_FirstScript
Aya_LetterInAyas_7_FirstScript
Sura_LetterInAyas_7_FirstScript
Quran_LetterInAyas_7_Acc_FirstScript
Word_Letters_Aya_Rasf
Word_Letters_Aya_Rasf_Saff
Word_Letters_Sura_Rasf_Saff
Word_Letters_Bin
Word_Letters_Bin_Ones
Word_Letters_Bin_Zeros
Aya_Letters_Bin
Aya_Letters_Bin_Ones
Aya_Letters_Bin_Zeros
Sura_Letters_Bin
Sura_Letters_Bin_Ones
Sura_Letters_Bin_Zeros
Aya_Letters_Bin_Acc
Aya_Letters_Bin_Acc_Ones
Aya_Letters_Bin_Acc_Zeros
Sura_Letters_Bin_Acc
Sura_Letters_Bin_Acc_Ones
Sura_Letters_Bin_Acc_Zeros
Quran_Letters_Bin_Acc
Quran_Letters_Bin_Acc_Ones
Quran_Letters_Bin_Acc_Zeros
Word_Letters_Aya_Rasf_FirstScript
Word_Letters_Aya_Rasf_Saff_FirstScript
Word_Letters_Sura_Rasf_Saff_FirstScript
Word_Letters_Bin_FirstScript
Word_Letters_Bin_Ones_FirstScript
Word_Letters_Bin_Zeros_FirstScript
Aya_Letters_Bin_FirstScript
Aya_Letters_Bin_Ones_FirstScript
Aya_Letters_Bin_Zeros_FirstScript
Sura_Letters_Bin_FirstScript
Sura_Letters_Bin_Ones_FirstScript
Sura_Letters_Bin_Zeros_FirstScript
Aya_Letters_Bin_Acc_FirstScript
Aya_Letters_Bin_Acc_Ones_FirstScript
Aya_Letters_Bin_Acc_Zeros_FirstScript
Sura_Letters_Bin_Acc_FirstScript
Sura_Letters_Bin_Acc_Ones_FirstScript
Sura_Letters_Bin_Acc_Zeros_FirstScript
Quran_Letters_Bin_Acc_FirstScript
Quran_Letters_Bin_Acc_Ones_FirstScript
Quran_Letters_Bin_Acc_Zeros_FirstScript


Version 5.1 12/29/18
--------------------
1- Added Quran_Page_Number field to all tables

2- Changed field type for Aya_Root to Memo instead of Text to accomodate longer aya text, and Fixed Access table and Excel Tables for empty field for Aya roots in following sura:aya listing: 3:154, 2:196, 4:12, 2:102, 24:61, 73:20, 24,:31, 2:282

3- Added new tables listing for Letter by Letter for 
	a- First Script with 322604 lines one row per letter.
Quran_Letters_MetaData_Khair_FirstScript_v5_1_Letters_Only.xlsx 
Quran_Letters_MetaData_Khair_FirstScript_v5_1.xlsx

	b- Uthmany Script with 325677 lines one row per letter.
Quran_Letters_MetaData_Khair_Uthmany_v5_1_Letters_Only.xlsx 
Quran_Letters_MetaData_Khair_Uthmany_v5_1.xlsx

Version 5.2 12/30/18
--------------
1- Fixed an issue with calculation of Letter count in FirstScript letter tables.

Version 6 05/29/2019
--------------------------
1- Added the following Jummal values
Word_EndingLetterInAya
Aya_EndingLetterInAya
Sura_EndingLetterInAya
Quran_EndingLetterInAya_Acc
Word_EndingLetterInAya_FirstScript
Aya_EndingLetterInAya_FirstScript
Sura_EndingLetterInAya_FirstScript
Quran_EndingLetterInAya_Acc_FirstScript
Word_StartingLetterInAya
Aya_StartingLetterInAya
Sura_StartingLetterInAya
Quran_StartingLetterInAya_Acc
Word_StartingLetterInAya_FirstScript
Aya_StartingLetterInAya_FirstScript
Sura_StartingLetterInAya_FirstScript
Quran_StartingLetterInAya_Acc_FirstScript
Word_EndingLetterInSura
Aya_EndingLetterInSura
Sura_EndingLetterInSura
Quran_EndingLetterInSura_Acc
Word_EndingLetterInSura_FirstScript
Aya_EndingLetterInSura_FirstScript
Sura_EndingLetterInSura_FirstScript
Quran_EndingLetterInSura_Acc_FirstScript
Word_StartingLetterInSura
Aya_StartingLetterInSura
Sura_StartingLetterInSura
Quran_StartingLetterInSura_Acc
Word_StartingLetterInSura_FirstScript
Aya_StartingLetterInSura_FirstScript
Sura_StartingLetterInSura_FirstScript
Quran_StartingLetterInSura_Acc_FirstScript

2- Added Table of Allah Names & Occurences as well as Allah Adjectives and Occurences
Allah_Names_Occurences
Allah_Names_Root_Occurences
Allah_Names
Allah_Names_Roots
Allah_Names_Types
Is_Allah_Name?
Allah_Adjective_Occurences
Allah_Adjective_Root_Occurences
Allah_Adjective
Allah_Adjective_Roots
Allah_Adjective_Types
Is_Allah_Adjective?

3- Updated fields for Word Roots & Occurences, and Aya Roots & Occurences
Aya_Occurences_Sura_Root
Aya_Occurences_Quran_Root
Word_Occurences_Aya_Root
Word_Occurences_Sura_Root
Word_Occurences_Quran_Root
Word_Root
Aya_Roots


Thank you,
Mohammad Khair





