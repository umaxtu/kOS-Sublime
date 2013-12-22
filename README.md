kOS-Sublime
===========

Simple [Sublime 3](http://www.sublimetext.com/3) plugin to ease in creation of 
[KerboScript](https://github.com/Nivekk/KOS) files used by kOS in the most awesome thing known as [Kerbal Space Program](http://kerbalspaceprogram.com). It highlights most of the keywords / control structures and offers some completions as well. 

Usage
=====

With Package Control, you can just Add Repository `https://github.com/EdvardM/kOS-Sublime`,
after which you should be able to install the package (Package Control / Install Package -> kos)
and that should be it - then all files ending with '.kos' or '.craft' use k-OS mode by default.

Note: seems like kOS reads only .txt files (maybe something else too?), so using .kos or .craft is not recommended.

Want to contribute?
===================

I'm happy to accept improvements. Currently I provide both the convenient json file and the actual plist file that both Sublime and TextMate use. The easiest way I found to update the plist (.tmLanguage) file automatically was to use Ruby and plist gem ( running ´bundle && rake´ should do it, if you have Ruby and bundler installed), if you know an easier way I'd be eager to learn of it.

