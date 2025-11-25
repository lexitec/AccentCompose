# AccentCompose
Copyright © 2025 Kari Eveli and Lexitec. AccentCompose is a free software product download for non-commercial personal use. For full license details, see the attached license file.

AccentCompose is available in two versions: This GitHub version uses a plain US keyboard and consists of an .XCompose file and layout documentation. The version available from https://www.uskbd.eu/ supports custom localized layouts created on top of the US keyboard hardware. This is accomplished using custom Windows keyboard DLLs which contain the most important localized keys for each supported language (most European languages are supported). There is a setup program and national layouts that can be easily switched on the fly. All layouts and versions share the same .XCompose file. The main differences are as follows: the GitHub version can be used regardless of OS just by installing the .XCompose file, the USKBD.EU version is Windows only and requires the use of custom keyboard DLLs and of WinCompose or similar software to run. Both versions support the entry of all the accented letters and other symbols included in the AccentCompose .XCompose file. 

The main purpose of the AccentCompose system is to enable easy typing of all accented letters present in European languages. Additionally, the .XCompose file supports many symbols, enclosed alphanumerics, Greek and Cyrillic letters as well as IPA phonetics. 

AccentCompose GitHub plain US version consists of
1. US, Cyrillic and Greek keyboard layouts as well as a CheatSheet for all the key sequences (PDF diagrams that can be printed and laminated)
2. a ready-to-use key sequence file for WinCompose (Windows) or any other similar rendering engine in other operating systems (.XCompose).

**Hardware requirements:** standard US keyboard (key combinations may work with other keyboards but labeling and the supplied layout charts may be confusing)

**Software requirements:** .XCompose rendering engine like in X.Org-based Linux distributions: Ubuntu, Red Hat, Centos, Fedora, or Arch Linux. In Windows, WinCompose is recommended. In any case, only AccentCompose .XCompose file should be loaded to avoid key sequence conflicts.

# Downloading WinCompose for Windows use
No Windows Compose key engine is provided with AccentCompose. Instead, you will need to install a Unicode-capable Windows Compose Key system and load AccentCompose .XCompose file into it. To date, WinCompose is your best bet. WinCompose is a separate free product that supports standard .XCompose files. We only supply a standard .XCompose file for use with WinCompose or any other similar product. See: http://wincompose.info/ and/or https://github.com/samhocevar/wincompose

# Setting up WinCompose for AccentCompose
Install WinCompose normally. You can use the portable zip or the setup exe version. Start WinCompose. Make a backup of the WinCompose .XCompose file in case you have customized it. Replace the WinCompose .XCompose file with the AccentCompose .XCompose file (go to WinCompose context menu from the notification area, Show sequences, Edit button, paste the contents of AccentCompose .XCompose file replacing the previous contents of the file, save the file, press Reload). From the taskbar icon, go to Options, General, Change Autodetect to English. Otherwise the Show sequences, Unicode characters items may not show the comment text which follows key sequence definitions in the .XCompose file. You can choose your Compose key here. 

# Choosing a physical Compose key
For example in WinCompose, go to the Composing tab. These are the keys that should work in any case: LeftWin, RightWin, Menu, and RightCtrl. LeftWin is recommended for typing accented letters. It is not advisable to use LeftAlt or LeftCtrl or CapsLock as the Compose key. As WinCompose allows you to define two Compose keys, it is good practise to do so. To select the Compose keys in WinCompose, open Options, Composing, Behavior, Compose Key...

# Editing .Xcompose
The supplied .XCompose has probably all you ever need but it can be freely edited if you choose to do so. You can add new key sequences for unsupported special characters. Check that your new key sequences do not conflict with key sequences already in use. Read the editing tips in the .XCompose file.

# Design philosophy
Most accents can be input from the unshifted level (exceptions are macrons and strokes that use _ and + respectively). When choosing which keys to type accents with, the leading idea has been ease of typing and mnemonics (e.g. / for acute, \ for grave, [ for circumflex, v for caron/há?ek, u for breve, _ for macron, - for tilde, comma for cedilla/comma accent, c for ogonek, + for stroke/slash, point for dot above, o for ring above, ] for diaeresis/umlaut/trema and = for hungarumlaut/double acute). In this GitHub version, mnemonic characters ^ and " on the shift plane can also be used for circumflexes and umlauts respectively. Triggering characters that follow the Compose key are used for groups of letters (e.g. 1 for standalone accents, 2 for Cyrillic, 4 for currencies, 7 for IPA phonetics and 8 for Greek). 

In the USKBD.EU version, the keys `/~, ;/: and '/" are reserved for localized additions (e.g. German ü/ä/ö). They appear “as is” in the GitHub US and US localized versions. Note that these characters are not used for typing accents in any AccentCompose version (as is the case in standard Linux .XCompose implementations).

As the Compose approach is entirely sequential (Compose key followed by 2 or 3 keypresses), there is no need for acrobatic keypresses that the dead key approach sometimes requires (e.g. AltGr+Shift+letter). The Compose method is chosen as a technically superior input method.

# Keyboard stickers
In this GitHub version, only circumflex (ˆ) and umlaut (¨) accents, which are entered by pressing [ and ] respectively, would need non-standard keyboard markings. In non-US localized USKBD.EU language versions, the national additions (e.g. ü, ä, ö for German, à, é, è for French, etc.) could benefit from keyboard sticker markings. As only 5 keycaps need relabeling, they could also easily be remembered after an initial reference to the layout diagrams.

# Localized versions
Localized AccentCompose versions are ideal for users that

1) want to use a US keyboard with small national additions for convenience, like ü/ä/ö or å/ä/ö or à/é/è)

2) type different languages using the one localized layout and the Compose key, some of which have accents (French) and/or umlauts (German, Swedish, Finnish), or change between compatible localized versions (e.g. German/French) with different localized additions without losing the same basic familiar arrangement of keys

6) like the idea of inputting accented and special characters with a Compose key with easy-to-type and easy-to-remember sequences

While they share the same .XCompose file and the same Compose sequences, localized versions have separate keyboard DLLs for different European languages. They are all US QWERTY layout-based independent of the language supported. They come with printable localized layout charts and with a 2-page AccentCompose Cheat Sheet.

Download AccentCompose localized versions setup program from https://www.uskbd.eu/download.html

