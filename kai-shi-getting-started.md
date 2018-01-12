# 1.版本控制软件发展史

## **Local Version Control Systems**

Many people’s version-control method of choice is to copy files into another directory \(perhaps a time-stamped directory, if they’re clever\). This approach is very common because it is so simple, but it is also incredibly error prone. It is easy to forget which directory you’re in and accidentally write to the wrong file or copy over files you don’t mean to.

To deal with this issue, programmers long ago developed local VCSs that had a simple database that kept all the changes to files under revision control.

![](/assets/import.png)Figure 1. Local version control.

One of the more popular VCS tools was a system called RCS, which is still distributed with many computers today. RCS works by keeping patch sets \(that is, the differences between files\) in a special format on disk; it can then re-create what any file looked like at any point in time by adding up all the patches.

