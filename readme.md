> Note: This is a snapshot of Tolstyak's Sick Beard fork as of 2013-09-05. It has since been removed and is no longer being maintained. This repo is for historical purposes. It runs well but may have bugs that have since been fixed upstream.

> This was forked from [midgetspy/Sick-Beard](https://github.com/midgetspy/Sick-Beard) with an important addition: **Failed Download Handling (FDH)**.

> Tolstyak was the first to develop FDH in March 2012. Several PRs were made to midgetspy/Sick-Beard but they were never merged so development moved to this fork.

> The FDH code was later implemented in [mr-orange/Sick-Beard](https://github.com/coach0742/Sick-Beard) and [SickRage](https://github.com/SickRage/SickRage) where it is still in use today.

> To ensure correct operation, Sick Beard forks with FDH should be used with the [nzbToMedia](https://github.com/clinton-hall/nzbToMedia) post-processing scripts. Read its [Wiki](https://github.com/clinton-hall/nzbToMedia/wiki) for more information.

Sick Beard - Tolstyak's branch
=====

Original SickBeard readme is [here][originalreadme]

The primary new feature of my branch is the handling of failed downloads.
If you're using SABnzbd, set the following options under Switches:

* Enable Abort jobs that cannot be completed
* Disable Post-Process Only Verified Jobs

And under Special:

* Enable empty_postproc

## Bugs

Report bugs in github

[originalreadme]: https://github.com/midgetspy/Sick-Beard/blob/master/readme.md
