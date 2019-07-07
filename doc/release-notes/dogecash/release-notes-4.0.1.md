DogeCash Core version *4.0.1* is now available from:  <https://github.com/dogecash/dogecash/releases>

This is a new minor version release, including various bug fixes and performance improvements, as well as updated translations.

Please report bugs using the issue tracker at github: <https://github.com/dogecash/dogecash/issues>

Non-Mandatory Update
==============

DogeCash Core v4.0.1 is a non-mandatory update to address bugs and introduce minor enhancements that do not require a network change.

How to Upgrade
==============

If you are running an older version, shut it down. Wait until it has completely shut down (which might take a few minutes for older versions), then run the installer (on Windows) or just copy over /Applications/DogeCash-Qt (on Mac) or dogecashd/dogecash-qt (on Linux).

Compatibility
==============

DogeCash Core is extensively tested on multiple operating systems using
the Linux kernel, macOS 10.8+, and Windows Vista and later.

Microsoft ended support for Windows XP on [April 8th, 2014](https://www.microsoft.com/en-us/WindowsForBusiness/end-of-xp-support),
No attempt is made to prevent installing or running the software on Windows XP, you
can still do so at your own risk but be aware that there are known instabilities and issues.
Please do not report issues about Windows XP to the issue tracker.

DogeCash Core should also work on most other Unix-like systems but is not
frequently tested on them.

Notable Changes
==============

GUI Updates
--------------

### Add Update notification code 

This new code,which is taken from Devault checks if 33% of peers have a newer version of the wallet, if so,then shows a update available message on the wallet,making it easier to know if there was a update released recently
### Fix color and readability issues

Previous wallet colors were not readable by many,specially the governance page and the on hover labels,this is now fixed.

### Add blockhash + datadir to information tab

Adds blockhash and datadir info to information tab.

User Experience
--------------

### Add seeder to vSeed list

Many users were not able to get initial connections to peers,due to the seednodes being already fully connected,this release should fix the problem and give the users the most reliable peers possible.

*3.1.1* Change log
--------------

Detailed release notes follow. This overview includes changes that affect behavior, code moves, refactoring and string updates. For convenience in locating the code changes and accompanying discussion, both the pull request and git merge commit are mentioned.

### GUI
 - `7946315651a869b5c2693226d4a79e0f439f893c` Fixed Color codes of governance and on hover labels (Liquid369)
 - `48d08c4d27d29477adac0f4d855bc3e03fcbe330` Add Update dialog code from DeVault (Modified to work with PIVX codebases) (akshaynexus)
 - `258f3b45e1d9d6855e4d6c9f0de5338b206afae3` Add blockhash + datadir to information tab (Mrs-X)
 
## Credits
Thanks to everyone who directly or indirectly contributed to this release:

 - Mrs-X
 - spock
 - akshaynexus
 - Liquid369
 - Warrows
