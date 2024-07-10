Thanks for downloading Flashmark!
Proudly developed by Brent Wadleigh // 1nvaload!
This is version 1.0.0 - Please expect bugs

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Progress can be slow on real flash drives, please be patient.
32GB *Real Flash Drive* >> 1m 50s (Medium Accuracy)
2TB *Real Samsung 990 Pro* >> 20s (Medium Accuracy)
"512GB" (64GB) Fake Drive >> 0m 14s (Medium Accuracy)

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Virus Scans for the Compiled Executable:
https://www.hybrid-analysis.com/sample/f36e0b3803b454242ee6d40d19495dc28999fd3627521ea93f74ea0ea614231f
https://www.virustotal.com/gui/file/f36e0b3803b454242ee6d40d19495dc28999fd3627521ea93f74ea0ea614231f

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Common issues:

>Flashmark closes when I type the disk number!
>>>Please run Flashmark with administrative privileges.

>I have a fake drive that claims it is 1TB but Flashmark says is 128GB .... but its real size is 64GB!
>>>Flashmark sometimes makes validation mistakes, re-run Flashmark to get an accurate reading.

>Flashmark takes a long time on my real drives
>>>Flashmark is designed to end its checks upon the first signal of false storage, if the drive is real, it will take time and not end early.

>In disk management when I try to unmount/delete the active partition it says operation not supported!
>>>Please enter CMD as admin and type the following:
>>>Diskpart
>>>List Disk
>>>Select Disk X (X is the disk you want to target. BE CAREFUL and make sure its the right disk!)
>>>Clean
>This will remove the partition and allow Flashmark to run.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
