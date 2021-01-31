# PatchBotExamples

Example recipes for PatchBot.

You no longer need to alter the `.pkg` recipe override. Details on running JPCImporter as an AutoPkg post
processor are at https://macintoshguy.wordpress.com/2020/07/31/patchbot-update/

If you look at `Firefox.prod.recipe` you can see the recipe sets the variable `delta`. This specifies the
number of days between test and production stages for this  package. Here we set it to zero which means go
from test to production immediately. 

Details can be found at https://github.com/Honestpuck/PatchBot
