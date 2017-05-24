# vbdm (Virtual Block Device Manager)

Virtual Block Device Manager is a utility created by Gradyn Wursten for creating and managing virtual block devices. It has many uses, such as cloning flashdrives to files and vise versa, creating portable filesystems, etc...

# Usage
You can run vbdm without any arguments to get this from inside the software at any time

Usage: vbdm (command) [arg1] [arg2]

Commands:

license: displays the MIT license with copyright notice

create-ntfs (arg1: name of file, arg2: size in MiB): Creates an ntfs Virtual Block Device

create-ext4 (arg1: name of file, arg2: size in MiB): Creates an ext4 Virtual Block Device

delete (arg1: name of file): Delete a Virtual Block Device

mount (arg1: name of file): Mount a Virtual Block Device

unmount (arg1: name of file): unmount a Virtual Block Device

goto (arg1: name of file): cd's into a virtual device file

make-real (arg1: name of file, arg2: device to clone to): Clones a Virtual Block Device onto an actual device

make-virtual (arg1: device to clone from, arg2: name of file): Clones an actual device onto a Virtual Block Device
   
# Am I allowed to (Insert thing here)?
   This software is licened under the MIT license. This means as long as you leave the "Copyright Gradyn Wursten 2017" bit at the top of the document and at the start of the software, you are allowed to do whatever you wish. The full license is avalible in the LICENSE file or via the "vbdm license" command
   
# Contributing
 Pull requests and bug reports are allways welcome!
