# 7-Days-to-Die-NitroGen-Prefab-Lists
## Prefab lists for the [NitroGen Random World Generator by Damocles](https://7daystodie.com/forums/showthread.php?114207-Tool-NITROGEN-a-random-world-generator-for-7DtD/) for the game [7 Days to Die](http://www.7daystodie.com/)


### TL;DR version of the main text below:

To generate a map using the preconfigured lists I have posted:

1. Copy the POI files you want NitroGen to include in your map into your standard 7DTD Data\Prefabs folder, as this folder is (currently) read by NitroGen to retrieve the prefab information:

   `steamapps\common\7 Days To Die\Data\Prefabs`

   Don't overwrite any standard files.

   - *For Ravenhearst, the needed files are the **abandoned_house_xxnew**, the **rh5_xx** and the **xvanilla_xx** (if present) files from the Ravenhearst prefabs folder:*
   
     `Ravenhearst_5_4_A17_4_Edition\Data\Prefabs`
     
   - *For Darkness Falls, the needed files are the **DFalls_xx**, the **resource_xx**, the **xcostum_xx** and the **xvanilla_xx** files from the Darkness Falls prefabs folder:*
   
     `Darkness_Falls\Data\Prefabs`


   
2. Choose the list that suits your taste for the map creation. For a standard Ravenhearst v5.4 game, for example, use the

   `Prefab lists for Ravenhearst\Ravenhearst 5.4\prefablist__Ravenhearst_v5.4_plus_vanilla_POIs_for_Alpha17.4.txt` file.
         


3. Rename the original NitroGen prefab list in the NitroGen resources folder

   `NitroGen_WorldGenerator\resources\prefablist.txt`
   
   to something else (e.g. original_prefablist.txt).


   
4. Copy the chosen preconfigured prefablist to the NitroGen resources folder and rename it to `prefablist.txt`.
   (NitroGen requires a file with that exact name for the map generation).
   


5. Run NitroGen and generate your map.




The lists I have posted are basically one and the same, as I had built an original list from the vanilla (unmodded) POIs included by Damocles, the Ravenhearst POIs and the Darkness Falls POIs. These are all included in most lists given here.

The various list variations only include commented-out POIs for certain purposes, e.g. one list is for playing Ravenhearst with the standard POIs, the Ravenhearst POIs and also the Darkness Falls POIs, all together.


You can edit the list(s) as needed with a standard TXT editor (e.g. Notepad or Notepad++).

I'd recommend [Notepad++](https://notepad-plus-plus.org), as it has far more and better functions than the standard Notepad editor and can also be used for programming, and it's free.


You comment out lines by putting a double slash `//` at the beginning.
Commented-out lines are not read by NitroGen, meaning the POI behind the `//` isn't generated in your world.




### Detailed instructions / FAQ (go right to step 5 if you just want to know how to actually generate a map):


**1. What the heck is this?**

   These are prefab lists for the NitroGen Random World Generator made by Damocles for the game 7 Days to Die.
   
   You can find NitroGen and respective prefab lists [here](https://7daystodie.com/forums/showthread.php?114207-Tool-NITROGEN-a-random-world-generator-for-7DtD/), along with the Prefab List Generator by Xylvier.
   
   On the same page there are instructions how to set up a dedicated server using a NitroGen map. What I have tried and tested is also [RAT](https://7daystodie.com/forums/showthread.php?38806-7D2D-RAT-Remote-Admin-Tool/), which works nicely with NitroGen-generated maps.



**2. What is the purpose of these prefab lists?**

   These (and other) prefab lists are used in the NitroGen map generation to let *POIs* spawn on the map. POIs are *Points of Interest* or also *"prefabs"*, prefabricated sites, e.g. buildings, resource piles etc..
   
   
   Prefab lists tend to be filled with individual data, according to the creator's taste: Generating a NitroGen map for use in 7 Days to Die using a certain prefab list might produce very different results than another prefab list by the same or by a different creator.



**3. How do the prefab lists differ from each other? Which one do I choose?**

   This depends on what you want; note that most of these lists are basically one and the same, created from a single main list I made. They are just *preconfigured* (fancy word for saying that certain values are activated, while others are deactivated) for a certain use already. This means that most lists contain POI values from the standard (= unmodded or *"vanilla"*) 7 Days to Die and additionally POI values for the 7 Days to Die modifications [Ravenhearst](https://7daystodie.com/forums/showthread.php?76822-Ravenhearst-Mod/) and [Darkness Falls](https://7daystodie.com/forums/showthread.php?80827-Darkness-Falls-They-mostly-come-out-at-night/).
   
   These modification (or *"MOD"*) POIs might also already equal certain other existing MOD or prefab pack POIs, so you can use them for those already as well.
   
   
   Very handy for installing MODs for 7 Days to Die is the [7 Days to Die MOD Launcher](https://7daystodie.com/forums/showthread.php?48537-The-7D2D-Mod-Launcher-A-Mod-Launcher-for-7-Days-to-Die/). Just saying.
   
   
   **Scenario 1: Use an existing prefab list file**
   
   If you just want to create a NitroGen map and start playing on it as fast as possible, you can simply choose one of the following lists, which meets your aim:
   
   
   `Prefab lists for Darkness Falls\Darkness Falls xx\prefablist__Darkness_Falls_vxx_plus_vanilla_POIs_for_xx.txt`
     
   -> This list is for a **standard *Darkness Falls*** map, with the standard NitroGen and the Darkness Falls POIs.
     
     
   `Prefab lists for Ravenhearst\Ravenhearst xx\prefablist__Ravenhearst_vxx_plus_vanilla_POIs_for_xx.txt`
     
   -> This list is for a **standard *Ravenhearst*** map, with the standard NitroGen and the Ravenhearst POIs.
     
     
   `Prefab lists for Darkness Falls\Darkness Falls xx\prefablist__Darkness_Falls_vxx_plus_Ravenhearst_vxx_plus_vanilla_POIs_for_xx.txt`
     
   -> This list is for **playing *Darkness Falls* on a map with combined POIs**, with the standard NitroGen, Darkness Falls and Ravenhearst POIs.
     
     
   `Prefab lists for Ravenhearst\Ravenhearst xx\prefablist__Ravenhearst_vxx_plus_Darkness_Falls_vxx_plus_vanilla_POIs_for_xx.txt`
     
   -> This list is for **playing *Ravenhearst* on a map with combined POIs**, with the standard NitroGen, Darkness Falls and Ravenhearst POIs.
     
     
   `Prefab lists for Ravenhearst\Ravenhearst xx\prefablist__Ravenhearst_vxx_plus_resource_piles_plus_vanilla_POIs_for_xx.txt`
     
   -> This list is for **playing *Ravenhearst* with additional standard resource piles (coal, lead, nitrate, oil shale)**.
     
     
   `Prefab lists for vanilla (unmodded) 7 Days to Die instances\prefablist__vanilla_POIs_for_xx.txt`
     
   -> This list is for a ***standard 7 Days to Die*** map, which contains the standard 7 Days to Die prefabs, with adjustments of my own (mainly different or slightly different NitroGen zone settings for certain POIs, compared to Damocles' original prefab list).
     
          
   `Prefab lists for vanilla (unmodded) 7 Days to Die instances\prefablist__vanilla_plus_resource_piles_POIs_for_xx.txt`
     
   -> This list is for **playing a *standard 7 Days to Die* map with additional standard resource piles (coal, lead, nitrate, oil shale)**.
     
     
   *Note that many Ravenhearst prefabs are basically the same as the Darkness Falls ones, so one could also just play Ravenhearst with the Darkness Falls POIs instead and vice versa. However, having the same prefabs twice can make for a more interesting game, as you increase the spawn chance for those POIs. Apart from being the same POIs, there are also certain differences often, like different POI dimensions between the "same" Ravenhearst and Darkness Falls prefabs etc..*
	
	
   An "xx" in a filename is just a placeholder for a certain MOD or Alpha version. Use the lists for the MOD and Alpha version you have installed.



   **Scenario 2: Create your own prefab list file**
   
   If you want to create your own list(s), you can, e.g., choose one or more as your template(s) and start editing them according to your needs.
	 
   You can edit the list(s) as needed with a standard TXT editor (e.g. Notepad or Notepad++). I'd recommend [Notepad++](https://notepad-plus-plus.org), as it has far more and better functions than the standard Notepad editor and can also be used for programming, and it's free.
	 
   Values (lines) with a double slash `//` in front of them are comments without any effect on the actual map generation. This way you can also keep certain POI values in the list(s), but deactivate them, so the respective prefabs cannot spawn on your map.
	
   A more detailed [explanation](https://7daystodie.com/forums/showthread.php?114207-Tool-NITROGEN-a-random-world-generator-for-7DtD&p=966733&viewfull=1#post966733) on how to create your own list(s) is by Damocles himself and can also be found at the beginning of his original prefab list (and of course also at the beginning of the modified lists).
	
   To add only the Darkness Falls and / or Ravenhearst values to your own existing list(s) conveniently, you can use the files
	
   `Prefab lists for Darkness Falls\Darkness Falls xx\prefablist___only_Darkness_Falls_vxx_POIs_for_xx_for_manual_addition.txt`
     
   and / or
     
   `Prefab lists for Ravenhearst\Ravenhearst xx\prefablist___only_Ravenhearst_vxx_POIs_for_xx_for_manual_addition.txt`,
	
   as those files only contain the respective values for Darkness Falls / Ravenhearst. Just copy & paste them into your own list(s) and modify them as you see fit.


   ~~Be wary that two POIs *have* to be commented out for Ravenhearst, else you will receive an "Array Index Out of Range" exception error when trying to load the map into Ravenhearst:~~

   ~~`apartment_adobe_red_5_flr,Downtown;ResidentialNew,2,-10,45,36,37,citycenter;downtown`~~

   ~~and~~

   ~~`rh5_rave_factory(by_orak),downtown;industrial,2,1,99,43,112,citycenter;smalltown;downtown;alone.`~~
	
   ~~These are already commented out (= deactivated) in the preconfigured lists.~~
     
   The formerly mentioned "Array Index Out of Range" error and apparently all other bugs I have encountered with the POIs so far have gone using newer NitroGen versions. I have tested this with NitroGen 0.352, and the POIs included in the lists are working now.



**4. I'm new to using GitHub; how do I download these prefab lists?**

   Usually, you would use one of two ways; either:
   
   - click on the green "Clone or download" button, followed by "Download ZIP" for downloading all files you can see in a single zip file, which you just have to extract afterwards
   
   - left-click on the file that you want in order to view / open it, then mark the content you want and copy it into a TXT file (e.g. into the original prefablist.txt by Damocles himself) that you want to use as your own prefab list


	 
**5. Ok, I have the prefab lists, what now? What do I do with them?**

   To generate a map with additional POIs (e.g. from Ravenhearst, Darkness Falls or modded 7DTD versions with their POIs in general) successfully, you have to manually **copy the needed prefab files from the mods into your standard
   7DTD installation folder *before* generating a map**, as NitroGen will use the standard (= unmodded) 7DTD installation folder for map generation:

   1. Backup your 7DTD Data\Prefabs folder first (basically you don't really have to do this, as you can always revalidate the files via Steam if anything becomes messed-up, but it's always handy to have a backup).
   
   
   2. Copy the POI files you want NitroGen to include in your map into your standard 7DTD Data\Prefabs folder (`steamapps\common\7 Days To Die\Data\Prefabs`); don't overwrite any standard files.


      - *For Ravenhearst, the needed files are the **abandoned_house_xxnew**, the **rh5_xx** and the **xvanilla_xx** (if present) files from the Ravenhearst prefabs folder:*
   
        `Ravenhearst_5_4_A17_4_Edition\Data\Prefabs`
     
      - *For Darkness Falls, the needed files are the **DFalls_xx**, the **resource_xx**, the **xcostum_xx** and the **xvanilla_xx** files from the Darkness Falls prefabs folder:*
   
        `Darkness_Falls\Data\Prefabs`


      For example, if you want to play a standard Ravenhearst map, you have to copy all **abandoned_house_xxnew**, the **rh5_xx** and the **xvanilla_xx** (if present) files from your Ravenhearst prefabs folder into the 7DTD Data\Prefabs folder for the map generation.


      If you want to combine POIs from different MODs (e.g. play Ravenhearst together with Darkness Falls POIs), you additionally have to copy the respective MOD's POI files into the corresponding MOD's Prefabs folder, else the MOD
      cannot load the needed prefabs when loading the map.
   
      For example, if you want to play Ravenhearst together with the Darkness Falls POIs, you not only have to copy all **abandoned_house_xxnew**, the **rh5_xx** and the **xvanilla_xx** (if present) files from your Ravenhearst prefabs folder and all **DFalls_xx** (if needed), the **resource_xx** (or only the **resource_iron_xx**, if needed), the **xcostum_xx** and the **xvanilla_xx** files from the Darkness Falls prefabs folder into the 7DTD Data\Prefabs folder, but ***additionally*** all **DFalls_xx** (if needed), the **resource_xx** (or only the **resource_iron_xx**, if needed), the **xcostum_xx** and the **xvanilla_xx** files from the Darkness Falls prefabs folder into the Ravenhearst Data\Prefabs folder.(**!**)
   
   
   3. Choose the list that meets your aim for the map creation. For a standard Ravenhearst v5.4 game, for example, use the

      `Prefab lists for Ravenhearst\Ravenhearst 5.4\prefablist__Ravenhearst_v5.4_plus_vanilla_POIs_for_Alpha17.4.txt` file.
   
   
   4. In the NitroGen resources folder (NitroGen_WorldGenerator\resources), rename the original prefablist.txt to something else (e.g. original_prefablist.txt).
   
   
   5. Copy the chosen preconfigured prefablist to the NitroGen resources folder and rename it to prefablist.txt (NitroGen requires a file with that exact name for map generation).
   
   
   6. Run NitroGen and generate your map.



**6. Are there issues with any prefabs in the list?**

   ~~Two POIs cause problems when playing Ravenhearst (and possibly other MODs). Those were mentioned already.~~ 
   
   Whenever there are "technical" issues with any POIs, this will be mentioned directly within the lists in comments.
   
   ~~There is a nuclear power plant POI (xcostum_Nuclear_Powerplant(by_Rocky)) that looks a bit strange when placed into the world, like it is spawned too high. In my view, the prefab itself is made a bit unfortunate,
   as it doesn't clearly show whether the whole thing should spawn *on* the ground or a bit *below* ground, like sunken below. In my view, both options are possible, but to make the POI accessible easily,
   I'll probably change its height values in a future version (v4 and above) of the lists (current height is -6, future height would be -10), so it will appear a bit sunken below ground, which is probably what's intended by the author anyway.~~
   
   Apart from that, I think the culvert_01 prefab (sewerage pipe below a street) in general looks strange when spawned.
   Furthermore, in the Ravenhearst 5.4 version, quite a few new POIs have been added, especially POIs which resemble airport parts or military trenches. Those POIs start with **rh5_norwg** in their filenames. NitroGen probably won't generate those "partial" POIs in a meaningful way, at least not at this time, so it might be better to comment those specific POIs out, according to your taste(s).
   
   Note there might still be a few other prefabs that might not really match the biome they spawn in. Not much that can be done about that at this time, apart from adjusting a list for very specific purposes (e.g. create a desert-only map) or commenting those POIs out in general.
   
   

**7. Where do these lists come from? How were they made?**

   The prefab lists contained in this repository were made by myself ("MelT" from the 7 Days to Die forums) and created the following way (history-wise), in case others want to build their own lists, but don't quite know how to start or are generally interested in the process I followed:
   
   1. I used the original prefablist.txt made by Damocles for his NitroGen map generator as a start and followed his advice in adding new POIs.
   
   2. I extracted all of the prefab filenames from the respective Ravenhearst MOD folder (Ravenhearst_5_1_Vanilla_Textures_A17_2_Edition\Data\Prefabs).
      This can, for example, be done with a single line in the command prompt:
      
      `dir /b /a-d > files.txt`
      
   3. I added the filenames as well as all of the remaining list values manually, loading every prefab into the 7 Days to Die / Ravenhearst prefab editor for checking its respective dimensions and manually checking the prefab XML and other files. This way I had created my first list and named it prefablist_ravenhearst_5.12.
   
   4. After adding my list values to the original prefablist.txt and testing it in NitroGen, I found that the map was generated just fine, but Ravenhearst crashed when loading it with an "Array Index Out of Range" exception error. (Note this error is not an issue anymore with the latest NitroGen version(s).)
   
   5. In the meantime, a user named "Xylvier" had posted a script for extracting the XML information from the prefab files automatically, and he used his script for creating a prefab list for the 7 Days to Die modification "Darkness Falls", which I liked, knew and played as well.
   
   6. I decided to use Xylvier's script for extracting and comparing the Ravenhearst values once again (in case I made any errors) and to merge the Darkness Falls POI values into my own list for personal use as well.
      
   7. After comparing my manual with the automated values, I found no errors in my Ravenhearst POI values; my main goal at the time was to get rid of the "Array Index Out of Range" error, so I could finally enjoy a NitroGen map in Ravenhearst, and I had to search for possible errors in all directions for this.
   
   8. I found no logical errors whatsoever in my own combined prefab lists, but found after trying out a vanilla NitroGen map with only the standard values by Damocles that I could actually load such a vanilla map into Ravenhearst, so the problem had to be at least one certain POI in my lists after all. (I later found that the working vanilla map(s) didn't include the apartment_adobe_red_5_flr prefab from the vanilla values, which by chance did not spawn, so I knew that was one of the problematic POIs; also see below.)
   
   9. A long and arduous testing ensued, where I created a temporary prefab list only for checking single POIs, created maps with only those POIs and checked every created map for the "Array Index Out of Range" exception error and finally found that indeed two specific POIs in the whole list caused this error in Ravenhearst, namely
	  
	  `apartment_adobe_red_5_flr,Downtown;ResidentialNew,2,-10,45,36,37,citycenter;downtown` (from the vanilla values)
      	  
	  and
          
	  `rh5_rave_factory(by_orak),downtown;industrial,2,1,99,43,112,citycenter;smalltown;downtown;alone` (from the Ravenhearst values).
	  
	  (Don't ask me why the Ravenhearst Rave Factory would cause that error, since the Darkness Falls values include the same prefab with the same values, but the Darkness Falls variant works.)
	  
	  I commented these two prefabs out, and lo and behold, maps generated with this modified prefab list of mine worked from now on.
	  
	  (As mentioned earlier, the "Array Index Out of Range" error with those two POIs is not an issue anymore with the latest NitroGen version(s).)
	  
   10. After testing out my new list, which contained the vanilla and both the Ravenhearst and the Darkness Falls values, I noticed that most Darkness Falls POIs spawned at a completely messed-up height in the world due to the automated value extraction (most spawned in the ground or high above ground, but not *on* the ground), whereas only a few Ravenhearst POIs (and even some vanilla) had the same issue. Furthermore, I wasn't too happy with the set NitroGen zone for many of the POIs, so testing time occurred again.
       
       I created map after map with temporary prefab lists and corrected all height values for every included POI in the list manually, checked for more issues and set the NitroGen zone for every POI to something (for my taste) more suitable.
       Also, I like my lists more readable, so I put more comments into them, commented out POIs that don't work, corrected some typos and sorted them into sections, putting commented-out values at the beginning of each section.
       
   As a side note, the whole testing process took me approximately two weeks (spare-time speaking).
   While creating a list for my personal use, I figured that I might save others the bulk of the invested time and uploaded the lists for everyone to use. So - here you are.
