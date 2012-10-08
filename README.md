5-Band Sound Equalizer in Flex
=============================

While there are several <a href="http://www.everydayflash.com/blog/index.php/2008/03/26/classic-sound-equalizer-in-flashas3/">tutorials</a> out there for "graphic equalizers" in Flash, these "equalizers" aren't actually affecting the sound being produced, only reporting what is heard. 

What is really needed is something that could modify the sound output. After weeks of googling, there were a <a href="http://stackoverflow.com/questions/1099103/create-a-flash-equalizer-modify-output-sound">few</a> <a href="http://www.webdesign.org/web/flash/tutorials/sound-equalizer.5020.html">leads</a>, but nothing seemed to be complete.

Luckily, along I ran across a tutorial about a <a href="http://www.blixtsystems.com/2008/05/simple-3-band-eq-with-flash-player-10/">3-band equalizer in flash</a> using the <a href="http://livedocs.adobe.com/flex/3/langref/flash/media/Sound.html#extract">sound.extract</a> function of AS3/Flash 10.

Finally, a working example! Except it didn't work. The example was created for a beta version of Flash 10, and the latest version used a different event name. But it was enough to get things flowing.

After upgrading the function names, customizing the script for 5-bands of equalization and converting it to run in Flex, it finally worked. It was a long journey, but hopefully this post makes it a short path for anyone else out there trying to create a true sound/graphic equalizer in Flex/Flash.

I really don't understand how the math changes the frequencies, so if you have any tips there, they'd also be appreciated.