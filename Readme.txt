Works like any other libs, include the libvlc.lib found in libs and the include folder

Make sure to drop the contents of the bin file into the directory of your main cpp file
or executable, which ever works

This is Made for x64

Refrences.

LibVLC discord: https://discord.gg/Rw7jm9qdh4

Vlc app download ( comes with necessary .dll files, download the .zip version ): https://artifacts.videolan.org/vlc/nightly-win64/20230303-0427/

Converting dll to lib: https://wiki.videolan.org/GenerateLibFromDll/

 -converting dll to def, make sure to go with the second method
 -when finally "compiling" the .def file to a .lib file change the machine type to x64 and not x86

Open sorce repo on github ( where include files are derived from ): https://github.com/videolan/vlc/tree/master