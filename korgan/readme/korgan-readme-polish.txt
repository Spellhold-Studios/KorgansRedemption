Nawr�cenie Korgana

Mod do BG2:ToB 
Autor: Picollo

Ten mod powsta� pod wp�ywem dyskusji na forum CoB o zawarto�ci wyci�tej z ToB-u.
W przerwie w pracy nad wi�kszym projektem postanowi�em napisa� tego moda, kt�ry w rzeczywisto�ci jest seri� banter�w pomi�dzy Mazzy i Korganem.

TAK, instaluj�c tego moda gracz decyduje si� na to, �e NIE b�dzie mia� wp�ywu na przemian� Korgana. Tw�rcy gry zarysowali ich przyja�� w�a�nie w ten spos�b, i w cz�ci do ToB-u postanowi�em pozostawi� w tej samej formie.

Zalecane jest rozpocz�cie nowej gry w SoA, gdy� tylko wtedy gracz b�dzie mia� mo�liwo�� prze�ledzenia ca�ej znajomo�ci tych dw�ch postaci. Dla os�b, kt�re zdecyduj� si� rozegra� tylko ToB, doda�em tak� mo�liwo��. Przy przywo�ywaniu postaci w sferze kieszeniowej nale�y najpierw przywo�a� Mazzy, a p�niej Korgana. Gracz b�dzie mia� mo�liwo�� dokonania wyboru czy chce, �eby Korgan z Mazzy byli na odpowiednim stopniu za�y�o�ci, �eby odkupienie mog�o si� rozpocz��.

Cz��� banter�w uaktywni si� sama po odpowiednim czasie, ale w jednym przypadku wymagany jest odpoczynek. Poza tym bantery same powinny si� uaktywnia�.

Wszelkie problemy z modem prosz� zg�asza� na forum CoBu w odpowiednim temacie ( http://athkatla.cob-bg.pl/viewtopic.php?t=4669 ).


Lista zmian

Version 10.0.1 (December 14, 2019)
- Fixed an issue with Auto-Package Generator tool: new version of MacOS (Catalina) prevented the mod to be installed.
- Lower cased LABEL name for consistency.

Version 10.0.0 (November 22, 2019)
- Renamed Setup-Korgan.tp2 -> korgan.tp2 to support AL|EN's "Project Infinity".
- Added korgan.ini metadata file to support AL|EN's "Project Infinity".
- Revamped scripts: Replaced old-school trigger conditions !StateCheck("XXX",STATE_SLEEPING) with more accurate CamDawg's !StateCheck("XXX",CD_STATE_NOTVALID) and added InParty("XXX") whenever needed.
- bio.baf: Added Continue() at the end of RESPONSE block.
- ar6200.bcs: Added !Alignment("Korgan",CHAOTIC_NEUTRAL) condition to forbid original epilogue to be displayed.
- Reorganized component (DESIGNATED number) and added "Korgan_Redemption" LABEL.
- Added REQUIRE_PREDICATE process to avoid installing the mod in inaccurate games.
- Added README command in tp2.
- Replaced AUTHOR keyword with SUPPORT.
- Added VERSION flag.
- Added German translation (from the BiG World Textpack German project). 
- Updated and renamed readme files to korgan-readme-%LANGUAGE%.txt.
- Updated French and English translations (Gwendolyne) and integrated Hook71's English typo fixes ( http://www.shsforums.net/topic/46432-korgans-redemption/#entry534930 ).
- Reorganized mod architecture tree: created folders to sort files according to their types.
- Included Linux and Mac Os X versions in the same package (thanks AL|EN!).
- Updated WeiDU installer to v246.
- Transferred mod to SpellHold Studios GitHub account.

Version 9 (July 31, 2019)
- Added native BG2EE compatibility (thanks to Deratiseur).

Version 8 (March 27, 2011)
- francuskie t�umaczenie (podzi�kowania dla Le Marquis za t�umaczenie).
- poprawione kilka b��d�w.

Version 7 (November 18, 2010)
- rosyjskie t�umaczenie (podzi�kowania dla Austina za t�umaczenie).

Version 6 (October 30, 2010)
- angielskie t�umaczenie (podzi�kowania dla Milocha za korekt�).

Version 5
- Przy porz�dkowaniu plik�w do v.4 wkrad� si� malutki b��d, kt�ry niniejszym poprawiam.
- Kosmetyczna zmiana jednej linijki, �eby doda� kompatybilno�� z "Wychowankiem Goriona".

Version 4
- Dodana traifikacja. (Ha! Ju� umiem samemu traifikowa� mody.)
- Lekko uporz�dkowany uk�ad plik�w.

Version 3 (ju� nie beta ;) )
- Nareszcie wykombinowa�em, jak unikn�� podw�jnego odpoczynku w pewnym momencie.
- Kilka banter�w z korganem, w kt�rych uzna�em, �e nowy, odmieniony Korgan odpowiedzia�by inaczej, zmieni�em, aczkolwiek wi�kszo�� zosta�a po staremu (generalnie pasuj� do Korgana CN).

Version 2 (beta)
- Teraz b�dzie pojawia�a si� tylko jedna biografia Korgana.
- Zmieniono bro� pijanemu najemnikowi.
- Poprawiono kilka drobnych liter�wek.
- Kilka drobnych zmian w dialogach.
- Poprawiono skrypty.

Version 1 (beta)
- Pierwsza wersja.
