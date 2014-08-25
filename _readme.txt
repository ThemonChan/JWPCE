JWPce version 1.50

Copyright (C) 1997-2004, 2005, glenn rosenthal

JWPce is free software; you can redistribute it and/or modify 
it under the terms of the GNU General Public License as 
published by the Free Software Foundation; either version 2 of 
the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, 
but WITHOUT ANY WARRANTY; without even the implied warranty of 
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the 
GNU General Public License for more details. 

You should have received a copy of the GNU General Public 
License along with this program; if not, write to the Free 
Software Foundation, Inc., 59 Temple Place - Suite 330, 
Boston, MA 02111-1307, USA.

============================================================
Windows CE:  Additional information

If you are running a Windows CE version of JWPce, please check
the file wince.txt!

============================================================
UNIX/LINUX:  Additional information

JWPce can run on UNIX/LINUX systems under Wine.  If you are
interested in running JWPce in such a way please get the 
jwpcenix.zip file.  The necessary files are contained in the 
archive, along with a UNIX.txt file with instructions.

============================================================
Disclaimers:  The legal stuff or you get what you pay for. 

Because this program is free software, it is distributed in 
the hope that it will be useful, but WITHOUT ANY WARRANTY; 
without even the implied warranty of MERCHANTABILITY or 
FITNESS FOR A PARTICULAR PURPOSE. This means that if you 
lose millions of dollars because you used the program, 
tough. So there! 

If you encounter any bugs, have suggestions, or want to 
make a comment, you should e-mail the information to me 
and I will attempt to respond.

============================================================
Installation Requirements: What do I need to get it running?

JWPce requires a PC computer system running Windows 95, 98, 
NT, or 2000. Windows 3.x is not supported (I suggest that you 
consider upgrading). The amount of memory required by the 
program depends primarily on the fonts and dictionaries 
installed. With minimum font and dictionary installation, 
JWPce requires less than 9MB of disk space. A full install 
using all of the standard bitmapped fonts, dictionaries, and 
the manuals, requires approximately 19MB of disk space.  If 
you install TrueType fonts, the space requirements depend on 
the fonts you install (TrueType fonts are not distributed with 
JWPce, unless someone wants to donate a public-domain Japanese 
TrueType font). Similarly, if you install a number of 
supplemental dictionaries, the space requirements will depend 
on exactly which dictionaries you install. 

============================================================
Installation Instructions: How to I get it working?

Installation of JWPce is very simple: 

JWPce does not have a standard installation program that you run 
to perform the installation, but don't worry, the installation 
procedure is very simple, and contains only four steps.

1. Obtain the distribution .zip files: One way or another obtain 
   the distribution .zip files. Depending on where you obtained 
   your distribution copy you may have different numbers of zip 
   files.  (Some JWPce files are available as self-extracting 
   .exe files.)

2. Generate a directory: Make a directory that will be your 
   installation directory. If you are installing over a previous 
   version of JWPce or JWP you can simply use your existing 
   directory.

3. Decompress the .zip files: Decompress the .zip files into 
   your installation directory. If you are installing over an 
   older version of JWPce or over JWP you can safely overwrite 
   any files. At this point you can delete the .zip files, as 
   they are no longer necessary. NOTE: Currently it is a 
   requirement that essentially all the JWPce support files are 
   located in the same directory as the executable (jwpce.exe).  
   If you are installing from self-extracting .exe files, you 
   only have to double click on the archive file to extract 
   the contents.

4. Run the Program: Run the executable program "jwpce.exe". This 
   will automatically complete the installation, and prompt 
   you for any information needed.

--------------------------------------
What if I already have JWP?

If you already have JWP, you can install JWPce in the same 
directory. For the most part they use the same files, so you 
will not have to duplicate files. Where they don't use the same 
files, the files have different names, so they will not 
interfere with each other. 

   Tip: My recommendation would be to upgrade completely to JWPce.  
   At this point JWPce has many more features than JWP had, is 
   smaller, faster, and more stable on 32-bit operating systems.

The only real problem is in whether or not to allow JWPce to 
take over the associations for the file extensions. These 
associations determine what program will be started when you 
double click on a file of the type (.jwp, .jis, .euc, etc.). 
Unfortunately, both programs use the same file extensions, so 
you will have to decide which one should handle the associations. 

============================================================
Updating JWPce:

If you are installing an updated version of JWPce, you can 
either get an updated package or install a complete version of 
JWPce over your existing version.  

Update packages are smaller and faster to download and install.  
If you get an update package, please check the instructions, 
since the update versions now require that you have at lease a 
certain version of JWPce to update from.  `This was done to 
keep the size of the update versions small.

Reinstalling JWPce over your existing version has some advantages 
too.  In particular you will get the newest copy of the main 
dictionaries.  These are not included in the update packages, 
because this would defeat the purpose of the updates.

Because there have been internal changes in the versions of 
JWPce I am now distributing a small program called UPDATE.EXE 
with each version of JWPce.  This program will check your version 
of JWPce and update any necessary files to the current version.  
You run this program by simply double clicking on it.  After you 
have run UPDATE.EXE you can simply delete the program, as it will 
no longer be necessary.  You can run UPDATE.EXE as often as you 
like, it will not hurt any of the files.

--------------------------------------
Windows CE Updates

I have not generated a version of UPDATE.EXE for each of the 
Windows CE versions.  I believe that most people who are using the 
CE versions also have a version on their desktop.  You can simply 
copy the updated files from your desktop to your CE machine.  Also 
the next section contains a list of things that have changed from 
version to version so you can see what UPDATE.EXE would be doing.

--------------------------------------
Update History

This section contains a history of major file changes in the 
various versions of JWPce.  If you are updating from an older 
version of JWPce you can see what files have been modified.

Version 1.33:

Due to changes in the kana->kanji conversion system, the files 
WNN.DCT and WNN.IDX have been replaced with the files WNN.DAT and 
WNN.DIX.  Additionally, the format of the user kana->kanji 
conversion file (USER.CNV) has changed to match the format used by 
WNN.DAT.  UPDATE.EXE will update the format USER.CNV, as well as 
offer to delete the obsolete files.

============================================================
International Support:

The appearance of JWPce's interface can be changed by the use of 
a language or localization file (JWPCE_LANG.DLL).  These files can 
replace virtually all the text strings used by the program, as 
well as menus and dialog boxes.  This system was designed to allow 
creation of alternative interface modules in different languages.

If a language support file is available for a language you are 
interested in, you can simply copy the support file to the same 
location as JWPCE.EXE.  During startup JWPce will detect the 
language file and switch interfaces.  There is an internal check to 
make sure the language support file matches the version of JWPce 
you are using.

Currently JWPce supports only one interface language at a time.  
Further the language is set when JWPce starts.  At a later date, 
support for switching interface languages on the fly may be 
implemented.

If you are interested in translating JWPce's interface to another 
language please contact me or obtain the translation kit 
(jwpcetra.zip).  This kit contains instructions, notes and tools 
used to generate a translation file.   (Please don't underestimate 
the amount of effort that this will take, JWPce contains around 
300 message strings, 50 dialog boxes, a two menus containing 
nearly 100 items.  Most of these will require translation.  This 
is not even considering the manual, help, or adjustments 
necessary for Windows CE PPCs and HPCs.)

============================================================
Dictionary files:

JWPce uses newer versions of EDICT and ENAMDICT (which was part 
of EDICT in JWP 1.31). The newer files can be used by JWP; and 
JWPce can use the older dictionary files, but doing so will 
disable some of its features. In particular, if you use the 
wrong dictionary version with one of the programs, that program 
will not be able to block name entries. The best choice is to 
use the newer dictionaries, then you can either add or not add 
ENAMDICT to JWP's dictionary list to get the best searching 
options. 

There are a number of advantages to dividing the dictionaries.  
People who do not need the name dictionary can simply not 
install it.  This gives you a smaller size.  Additionally, when 
searching for words, excluding names, JWPce does not even look 
in the name dictionary.  This makes things much faster. 

The new forms of the dictionaries are not distributed with the 
upgrade version of JWPce.  Your old dictionary will still work, 
but because of coding changes, personal and place names will not 
be filtered.

============================================================
Some Instructions for JWPce
--------------------------------------
<<<TECHNICAL>>> User Files Location <<<TECHNICAL>>>

   WARNING!  This section deals with technical issues related 
   to setting up JWPce to be run over a shared network, or for 
   a single user to run multiple configurations.  If this does 
   not fit your configuration or you are uncomfortable with 
   such issues, simply skip this section.

JWPce was originally designed as a single user program. The 
program originally stored all information about the user 
configuration in the same directory as the executable. This is 
efficient, but makes the program difficult to use in a network 
configuration, where many different users may be using the 
program at the same time. In such a case multiple users would 
end up saving their configurations on top of each other and no 
one would be happy. Since JWPce is being used in academic 
situations over networks (something I never envisioned when I 
started the project), support for network configurations has 
become more important. 

  Network configurations are not supported on Windows CE 
  versions.

JWPce allows a command line argument to specify the directory 
for user configuration files.  Normally JWPce will attempt to 
read all files from the user's directory, but if a 
configuration file is missing, it will read the file from the 
default directory (where the program is located).  This allows 
the default configuration to be used to initialize all 
configurations.  When writing, JWPce will always attempt to 
write user configuration information into the user directory, 
and will never write back into the default directory.

The command line argument to specify the user directory 
location is: 

        (+|-)user_directory

If the plus (+) option is used all error checking will remain 
active. This should be the normal configuration. If the minus 
(-) option is used errors will not be reported when writing 
user configuration files. Note: Using the minus option does 
not have any effect on user data files, where all error 
reporting remains active! 

Generally the minus option should not be used, but it has some 
advantages in special situations.  For example, if you do not 
want users to save their configuration files then you could 
use this option and provide an invalid directory for the 
user_directory.  This will prevent the user form saving 
configurations and prevent generation of error messages. 
Another special situation might be if the users save their 
configurations on a floppy disk, but you want the program to 
run quietly when no disk is in the machine.  In such a case 
you could use the configuration option:

        -a:\

All JWPce features will work even when the user cannot save 
configuration information; however, any changes the user 
makes to the configuration will not be preserved from 
session to session. 

Files Affected

Following is a list of the files that JWPce considers to be 
user configuration files.  These are simply files that may 
change as the user works with JWPce but that are not actual 
data files:

   colkanji.lst   - Kanji list used by the color-kanji feature.
   jwpce.cfg      - JWPce configuration file, this will be 
                    generated when you run JWPce. 
   jwpce.dic      - JWPce dictionary configuration file. This 
                    file contains information about supplemental 
                    dictionaries you have installed. 
   jwpce_lang.dll - Language interface file.
   user.cnv	      - User kana->kanji conversions. 
   user.dct	      - User dictionary. 
   user.sel       - Holds user selections for kana->kanji 
                    conversions. 

Setup Procedure

The following section describes the things you need to think 
about and steps you need to take when installing JWPce on a 
network. 

1. Install JWPce: Install JWPce as normal on the server 
   system (section 2.1.2). 
2. Set Default Configuration: Set up a default JWPce 
   configuration on the server. At a minimum simply run JWPce, 
   which will generate a jwpce.cfg file that will become the 
   base configuration for the users.  If this is not done, 
   every new user (or users who forgot their disk) will get 
   the message about being unable to load the configuration 
   file, using default values. 
3. Install Supplemental Dictionaries: If you are going to 
   install any of the supplemental dictionaries, you should 
   do this now. This will set up a base dictionary search 
   that the users can use. 
4. Do not generate a user dictionary: Generally you may NOT 
   want to provide a common user dictionary. This is because 
   if the user adds something to this dictionary, the entire 
   dictionary will get copied into the user configuration 
   directory. Additionally, once the user generates his or 
   her own user dictionary, they will not be able to use any 
   changes to the central dictionary that you may make 
   (assuming this is an educational situation). 
5. If you want to provide a central dictionary: If you want 
   to provide a central dictionary that all users can access, 
   and that dictionary was generated as a user dictionary, 
   you can simply rename the user.dct file to any other name 
   and add it to the supplemental dictionaries list using 
   the Searched Dictionaries dialog box.
6. Setup User Executable: You will then need to modify the 
   user executable command line to run JWPce with the correct 
   command line arguments for your network. You may actually 
   need to set up a script file of some kind to fetch the 
   location of the user's directory and pass that information 
   to JWPce. For a very simple setup, where the user is 
   expected to store the configuration files on a floppy 
   disk, you can modify the typical executable line from 

        JWPce.exe

to 

        JWPce.exe +a:\

============================================================
Files: What should be there, and what may be there.

Exactly what files you get with JWPce depends on who 
packaged the files.  I distribute the program in a specific 
way, but since it is freeware, the copy you get may not be 
packaged by me.  The following section describes what files 
should be there, what files may be there, and what they are 
used for.  Any other files, you can probably delete if you 
want to.

If you distribute JWPce please try to make sure that users 
have access to all files included in the full distribution, 
source code, and utilities.  These do not have to be 
distributed together (most users will not want the source 
code or utilities), however, the user should have access to 
all parts of the distribution if they want it. 
JWPce minimum installation includes the following files:

  jwpce.exe    - JWPce executable (this is the program).
  changes.txt  - Changes for this version.
  _cpright.txt - Copyright notice.
  Edict        - Jim Breen's Japanese-English dictionary
  edict.jdx    - Index file for EDICT
  gnugpl.txt   - GNU public license.
  k16x16.f00   - 16x16 bitmapped kanji font.
  kanjinfo.dat - Kanji information database.
  radical.dat  - Radical lookup data file.
  _readme.txt  - Updated information and important changes.
  stroke.dat   - Radical lookup stroke data file.*
  wince.txt    - Windows CE additional information file.  
                 If you are installing a Windows CE version 
                 of JWPce please read this file.
  wnn.dat      - Kana-to-kanji conversion dictionary
  wnn.dix      - Index to wnn.dat.

*These files are slated to be replaced in a later version of 
JWPce.  The new versions will have added functionally or be 
significantly smaller, or both.

JWPce full installation files (Technically, these are all 
optional files):

  classical      - Classical Japanese dictionary.
  Classical.euc  - Documentation for classical dictionary.
  enamdic        - Japanese name dictionary.
  enamdic.jdx    - Index file for Japanese name dictionary.
  jwpce.doc      - Documentation (in Word 97 format).
  jwpce.hlp      - JWPce help file (Windows 95/98/NT only).
  jwpce.cnt      - JWPce help contents (Windows 95/98/NT only).
  jwpce_lang.dll - Localization (language support) file, causes 
                   JWPce to change the system interface to 
                   another language.
  k24x24.f00     - 24x24 bitmapped kanji font (if you have a 
                   good printer you can delete this one).
  k48x48.f00     - 48x48 bitmapped kanji font.

The Windows CE help system contains around 130 files, all of 
which are HTML or gif files.  The help distribution zip 
contains a full list of the files that should be there.

Files that may be in your installation  (These are files 
generated by JWPce, and thus may be included with the files 
you receive.):

  colkanji.lst - Kanji list used by the color-kanji feature.
  jwpce.cfg    - JWPce configuration file, generated when you 
                 run JWPce.
  jwpce.dic    - JWPce dictionary configuration file.  This 
                 file contains information about supplemental 
                 dictionaries you have installed.
  jwpce.gid    - Generated by Windows help to hold bookmarks, 
                 etc.
  user.cnv     - User kana->kanji conversions.
  user.dct     - User dictionary file.
  user.sel     - Holds user selections for kana->kanji 
                 conversions.

============================================================
Obsolete Files:  Files that are no longer required

These files have been replaced with updated files, and thus
are no longer necessary.

Files made obsolete in version 1.33:

  wnn.dct - replaced with wnn.dat
  wnn.idx - replaced with wnn.dix



