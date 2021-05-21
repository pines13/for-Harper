# for-Harper
DeDRM problem

On windows 10 calibre did not clean this book and others from Kindle unlimited


the log file is as follows

calibre Debug log
calibre 5.18 [64bit]  embedded-python: True is64bit: True
Windows-10-10.0.19041 Windows ('64bit', 'WindowsPE')
('Windows', '10', '10.0.19041')
Python 3.8.5
Windows: ('10', '10.0.19041', '', 'Multiprocessor Free')
Interface language: en_GB
Successfully initialized third party plugins: DeDRM (7, 2, 1)
calibre 5.18 [64bit]  embedded-python: True is64bit: True
Windows-10-10.0.19041 Windows ('64bit', 'WindowsPE')
('Windows', '10', '10.0.19041')
Python 3.8.5
Windows: ('10', '10.0.19041', '', 'Multiprocessor Free')
Interface language: en_GB
Successfully initialized third party plugins: DeDRM (7, 2, 1)
Turning on automatic hidpi scaling
devicePixelRatio: 2.0
logicalDpi: 96.0 x 96.0
physicalDpi: 81.28 x 80.68235294117646
Using calibre Qt style: True
[0.00] Starting up...
[0.00] Showing splash screen...
[0.31] splash screen shown
[0.31] Initializing db...
[0.31] db initialized
[0.31] Constructing main UI...
[0.72] main UI initialized...
[0.72] Hiding splash screen
Starting QuickView
DeDRM v7.2.1: Trying to decrypt Hard Road (A Jon Reznick Thriller Book 1).azw3
Using Library AlfCrypto DLL/DYLIB/SO
Using Library AlfCrypto DLL/DYLIB/SO
MobiDeDrm v1.0.
Copyright © 2008-2020 The Dark Reverser, Apprentice Harper et al.
Decrypting Kindle Format 8 ebook: Hard Road (A Jon Reznick Thriller Book 1)
Found 0 keys to try after 0.1 seconds
Crypto Type is: 2
DeDRM v7.2.1: Failed to decrypt with error: No key found in 0 PIDs tried.
DeDRM v7.2.1: Looking for new default Kindle Key after 0.1 seconds
searching for kinfoFiles in C:\Users\neilw\AppData\Local
No K4PC kindle.info/kinf/kinf2011 files have been found.
DeDRM v7.2.1: Ultimately failed to decrypt after 0.1 seconds. Read the FAQs at Harper's repository: https://github.com/apprenticeharper/DeDRM_tools/blob/master/FAQs.md
[10.19] splash screen hidden
[10.19] Started up in 10.19 seconds with 208 books
stdout+stderr from file dialog helper: [b'', b'']
piped data from file dialog helper: [b'%\xad\x19\xcf*g\x94\x9d\x13\xb6w\xb6$\xbfeI\xfc\xbeA\x88\xa0?\xab\xee\xec\x8b\xf6\xb7%\xf7\x19N', b'C:\\Users\\neilw\\Downloads\\Hard Road (A Jon Reznick Thriller Book 1).azw3']
Added Hard Road (A Jon Reznick Thriller Book 1) to db in: 1.7
Running file type plugin DeDRM failed with traceback:
Traceback (most recent call last):
  File "calibre_plugins.dedrm.__init__", line 540, in KindleMobiDecrypt
  File "calibre_plugins.dedrm.k4mobidedrm", line 238, in GetDecryptedBook
  File "calibre_plugins.dedrm.mobidedrm", line 484, in processBook
calibre_plugins.dedrm.mobidedrm.DrmException: No key found in 0 PIDs tried.

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "calibre\customize\ui.py", line 176, in _run_filetype_plugins
  File "calibre_plugins.dedrm.__init__", line 633, in run
  File "calibre_plugins.dedrm.__init__", line 583, in KindleMobiDecrypt
calibre_plugins.dedrm.DeDRMError: DeDRM v7.2.1: Ultimately failed to decrypt after 0.1 seconds. Read the FAQs at Harper's repository: https://github.com/apprenticeharper/DeDRM_tools/blob/masAdded 1 books in 2.0 seconds
Worker Launch took: 0.00 seconds


Hope you can solve this problem
