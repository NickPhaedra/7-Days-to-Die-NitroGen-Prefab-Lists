# 7-Days-to-Die-NitroGen-Prefab-Lists
Prefab lists for the NitroGen Random World Generator by Damocles for the game 7 Days to Die


TL;DR version of the main text below:

To generate a map using the preconfigured lists I have posted:

1. Copy the POI files you want NitroGen to include in your map into your standard 7DTD Data -> Prefabs folder (steamapps\common\7 Days To Die\Data\Prefabs); don't overwrite any standard files.

   - For Ravenhearst, the needed files are the abandoned_house_xxnew and the rh5_xx files from the Ravenhearst prefabs folder (Ravenhearst_5_1_Vanilla_Textures_A17_2_Edition\Data\Prefabs).
   - For Darkness Falls, the needed files are the DFalls_xx (if needed), the resource_xx (or only the resource_iron_xx, if needed), the xcostum_xx and the xvanilla_xx files from the Darkness Falls prefabs folder
     (Darkness_Falls\Data\Prefabs).
   
2. Choose the list that suits your taste for the map creation (for a standard Ravenhearst game, use the prefablist_Ravenhearst_vanilla_vxx).
3. In the NitroGen resources folder (NitroGen_WorldGenerator\resources), rename the original prefablist.txt to something else (e.g. original_prefablist.txt).
4. Copy the chosen preconfigured prefablist to the NitroGen resources folder and rename it to prefablist.txt (NitroGen requires a file with that exact name for map generation).
5. Run NitroGen and generate your map.

The lists I have posted are basically one and the same, as I had built an original list from the vanilla (unmodded) POIs included by Damocles, the Ravenhearst POIs and the Darkness Falls POIs. These are all included in the list. The various list variations only include commented-out POIs for certain purposes, e.g. one list is for playing Ravenhearst with the standard POIs, the Ravenhearst POIs and also the Darkness Falls POIs, all together.

You can edit the list(s) as needed with a standard TXT editor (e.g. Notepad or Notepad++). I'd recommend Notepad++ ( https://notepad-plus-plus.org ), as it has far more and better functions and can also be used for programming, and it's free.
You comment out lines by putting a double slash // at the beginning. Commented-out lines are not read by NitroGen, meaning the POI behind the // isn't generated in your world.




Detailed instructions / FAQ (go right to step 5 if you just want to know how to actually generate a map):

1. What the heck is this?

   These are prefab lists for the NitroGen Random World Generator made by Damocles for the game 7 Days to Die.
   
   Original link for NitroGen, respective prefab lists and the Prefab List Generator by Xylvier:
   https://7daystodie.com/forums/showthread.php?114207-Tool-NITROGEN-a-random-world-generator-for-7DtD

   
2. What is the purpose of these prefab lists?

   These (and other) prefab lists are used in the NitroGen map generation to let POIs spawn on the map. POIs are Points of Interest or also "prefabs", prefabricated sites, e.g. buildings, resource piles etc..
   
   Prefab lists tend to be filled with individual data, according to the creator's taste:
   Generating a NitroGen map for use in 7 Days to Die using a certain prefab list might produce very different results than another prefab list by the same or by a different creator.


3. How do the prefab lists differ from each other? Which one do I choose?

   This depends on what you want; note that most of these lists are basically one and the same, created from a single main list I made. They are just *preconfigured* (fancy word for saying that
   certain values are activated, while others are deactivated) for a certain use already, meaning that most lists contain POI values from the standard (= unmodded or "vanilla") 7 Days to Die and additionally
   POI values for the 7 Days to Die modifications Ravenhearst and Darkness Falls (these modification (or "MOD") POIs might also already equal certain other existing MOD packs, so you can use them for those
   already as well).
   
   - If you just want to create a NitroGen map and start playing on it as fast as possible, you can simply choose one of the following lists, which meets your aim:
   
     prefablist_Darkness_Falls_vanilla_vxx.txt
     -> This list is for a standard Darkness Falls map, with the vanilla and the Darkness Falls POIs.
     
     prefablist_Ravenhearst_vanilla_vxx.txt
     -> This list is for a standard Ravenhearst map, with the vanilla and the Ravenhearst POIs.
     
     prefablist_Ravenhearst_with_DF_POIs_combined_vxx.txt
     -> This list is for a map with combined POIs, with the vanilla, Darkness Falls and Ravenhearst POIs.*
     
     prefablist_Ravenhearst_with_resource_piles (iron from DF included)_vxx.txt
     -> This list is for a standard Ravenhearst map with additional vanilla resource piles (nitrate etc.) and also iron piles from Darkness Falls.
     
     prefablist_vanilla_vxx.txt
     -> This list is for a standard map, which contains the standard 7 Days to Die prefabs, with adjustments of my own (mainly different or slightly different NitroGen zone settings).
     
     prefablist_vanilla_with_resource_piles (iron from DF included)_vxx.txt
     -> This list is for a standard map with additional vanilla resource piles (nitrate etc.) and also iron piles from Darkness Falls.

     *Many Ravenhearst prefabs are basically the same as the Darkness Falls ones, so one could also just play Ravenhearst with the Darkness Falls POIs instead. However, having the same prefabs
     twice can make for a more interesting game, as you increase the spawn chance for those POIs. Apart from being the same POIs, there are also differences often, like different POI dimensions
     between the Ravenhearst and the Darkness Falls prefabs etc..
	
     (Note that the "vxx" near the filename's end is just a placeholder for a certain file version; I may get rid of the version indicators altogether in the future.
     Currently they are just used to indicate the list compatibility with a certain NitroGen version, e.g. v3 lists are compatible with NitroGen v0.26 and below.)


   - If you want to create your own list(s), you can, e.g., choose one or more as your template(s) and start editing them according to your needs.
	 
	 You can edit the list(s) as needed with a standard TXT editor (e.g. Notepad or Notepad++). I'd recommend Notepad++ ( https://notepad-plus-plus.org ), as it has far more and better functions and can also be used for programming, and it's free.
	 
     Values (lines) with a double slash ( // ) in front of them are comments without any effect on the actual map generation. This way you can also keep certain POI values in the list(s), but deactivate them,
     so the respective prefabs cannot spawn on your map.
	
     A more detailed explanation on how to create your own list(s) is by Damocles himself and can also be found at the beginning of his original prefab list (and of course also at the beginning of the modified lists):
     https://7daystodie.com/forums/showthread.php?114207-Tool-NITROGEN-a-random-world-generator-for-7DtD&p=966733&viewfull=1#post966733
	
     To add only the Ravenhearst values to your own existing list(s) conveniently, you can download the file
	
     prefablist_ravenhearst_5.13_vxx.txt,
	
     as this file only contains the values for Ravenhearst. Just copy & paste them into your own list(s) and modify them as you see fit.


     Be wary that two POIs *have* to be commented out for Ravenhearst, else you will receive an "Array Index Out of Range" exception error when trying to load the map into Ravenhearst:

     apartment_adobe_red_5_flr,Downtown;ResidentialNew,2,-10,45,36,37,citycenter;downtown

     and

     rh5_rave_factory(by_orak),downtown;industrial,2,1,99,43,112,citycenter;smalltown;downtown;alone.
	
     These are already commented out (= deactivated) in the preconfigured lists.
	

4. I'm new to using GitHub; how do I download these prefab lists?

   Usually, you would use one of two ways; either:
   
   - click on the green "Clone or download" button, followed by "Download ZIP" for downloading all files you can see in a single zip file, which you just have to extract afterwards
   - left-click on the file that you want in order to view / open it, then mark the content you want and copy it into a TXT file (e.g. into the original prefablist.txt by Damocles himself)
     that you want to use as your own prefab list

	 
5. Ok, I have the prefab lists, what now? What do I do with them?

   To generate a map with additional POIs (e.g. from Ravenhearst, Darkness Falls or modded 7DTD versions with their POIs in general) successfully, you have to manually copy the needed prefab files from the mods into your standard
   7DTD installation folder *before* generating a map, as NitroGen will use the standard (= unmodded) 7DTD installation folder for map generation:

   1. Backup your 7DTD Data -> Prefabs folder first (basically you don't really have to do this, as you can always revalidate the files via Steam if anything becomes messed-up, but it's always handy to have a backup).
   2. Copy the POI files you want NitroGen to include in your map into your standard 7DTD Data -> Prefabs folder (steamapps\common\7 Days To Die\Data\Prefabs); don't overwrite any standard files.

      - For Ravenhearst, the needed files are the abandoned_house_xxnew and the rh5_xx files from the Ravenhearst prefabs folder (Ravenhearst_5_1_Vanilla_Textures_A17_2_Edition\Data\Prefabs).
      - For Darkness Falls, the needed files are the DFalls_xx (if needed), the resource_xx (or only the resource_iron_xx, if needed), the xcostum_xx and the xvanilla_xx files from the Darkness Falls prefabs folder
      (Darkness_Falls\Data\Prefabs).

      E.g., if you want to play a standard Ravenhearst map, you have to copy all abandoned_house_xxnew and the rh5_xx files from your Ravenhearst prefabs folder into the 7DTD Data -> Prefabs folder.


      If you want to combine POIs from different MODs (e.g. play Ravenhearst together with Darkness Falls POIs), you additionally have to copy the respective MOD's POI files into the corresponding MOD's Prefabs folder, else the MOD
      cannot load the needed prefabs when loading the map.
   
      E.g., if you want to play a Ravenhearst map together with the Darkness Falls POIs, you not only have to copy all abandoned_house_xxnew and the rh5_xx files from your Ravenhearst prefabs folder and all DFalls_xx (if needed),
      the resource_xx (or only the resource_iron_xx, if needed), the xcostum_xx and the xvanilla_xx files from the Darkness Falls prefabs folder into the 7DTD Data -> Prefabs folder, but additionally all DFalls_xx (if needed),
      the resource_xx (or only the resource_iron_xx, if needed), the xcostum_xx and the xvanilla_xx files from the Darkness Falls prefabs folder into the Ravenhearst Data -> Prefabs folder.(!)
   
   3. Choose the list that meets your aim for the map creation (e.g., for a standard Ravenhearst game, use the prefablist_Ravenhearst_vanilla_vxx).
   4. In the NitroGen resources folder (NitroGen_WorldGenerator\resources), rename the original prefablist.txt to something else (e.g. original_prefablist.txt).
   5. Copy the chosen preconfigured prefablist to the NitroGen resources folder and rename it to prefablist.txt (NitroGen requires a file with that exact name for map generation).
   6. Run NitroGen and generate your map.


6. Are there issues with any prefabs in the list?

   Two POIs cause problems when playing Ravenhearst (and possibly other MODs). Those were mentioned already. Others are mentioned directly in the lists in comments.
   
   There is a nuclear power plant POI (xcostum_Nuclear_Powerplant(by_Rocky)) that looks a bit strange when placed into the world, like it is spawned too high. In my view, the prefab itself is made a bit unfortunate,
   as it doesn't clearly show whether the whole thing should spawn *on* the ground or a bit *below* ground, like sunken below. In my view, both options are possible, but to make the POI accessible easily,
   I'll probably change its height values in a future version (v4 and above) of the lists (current height is -6, future height would be -10), so it will appear a bit sunken below ground, which is probably
   what's intended by the author anyway.
   
   Also, I think the culvert_01 prefab (sewerage pipe below a street) in general looks strange when spawned. I might comment this out in the future.
   
   Note there might still be a few other prefabs that might not really match the biome they spawn in. Not much that can be done about that at this time, apart from adjusting a list for very specific purposes
   (e.g. create a desert-only map) only or commenting those POIs out in general.
   

7. Where do these lists come from? How were they made?

   The prefab lists contained in this repository were made by myself ("MelT" from the 7 Days to Die forums) and created the following way (history-wise),
   in case others want to build their own lists, but don't quite know how to start or are generally interested in the process I followed:
   
   1. I used the original prefablist.txt made by Damocles for his NitroGen map generator as a start and followed his advice in adding new POIs.
   2. I extracted all of the prefab filenames from the respective Ravenhearst MOD folder (Ravenhearst_5_1_Vanilla_Textures_A17_2_Edition\Data\Prefabs).
      This can, for example, be done with a single line in the command prompt: dir /b /a-d > files.txt
   3. I added the filenames as well as all of the remaining list values manually, loading every prefab into the 7 Days to Die / Ravenhearst prefab editor
      for checking its respective dimensions and manually checking the prefab XML and other files. This way I had created my first list and named it prefablist_ravenhearst_5.12.
   4. After adding my list values to the original prefablist.txt and testing it in NitroGen, I found that the map was generated just fine, but Ravenhearst crashed when loading it with an
      "Array Index Out of Range" exception error.
   5. In the meantime, a user named "Xylvier" had posted a script for extracting the XML information from the prefab files automatically, and he used his script for creating a prefab list
      for the 7 Days to Die modification "Darkness Falls", which I liked, knew and played as well.
   6. I decided to use Xylvier's script for extracting and comparing the Ravenhearst values once again (in case I made any errors) and to merge the Darkness Falls POI values into my own list
      for personal use as well.
   7. After comparing my manual with the automated values, I found no errors in my Ravenhearst POI values; my main goal at the time was to get rid of the "Array Index Out of Range" error, so I
      could finally enjoy a NitroGen map in Ravenhearst, and I had to search for possible errors in all directions for this.
   8. I found no logical errors whatsoever in my own combined prefab lists, but found after trying out a vanilla NitroGen map with only the standard values by Damocles that I could actually load
      such a vanilla map into Ravenhearst, so the problem had to be at least one certain POI in my lists after all.
      (I later found that the working vanilla map(s) didn't include the apartment_adobe_red_5_flr prefab from the vanilla values, which by chance did not spawn, so I knew that was one of the problematic POIs; also see below.)
   9. A long and arduous testing ensued, where I created a temporary prefab list only for checking single POIs, created maps with only those POIs and checked every created map for the "Array Index
      Out of Range" exception error and finally found that indeed two specific POIs in the whole list caused this error in Ravenhearst, namely
	  
	  apartment_adobe_red_5_flr,Downtown;ResidentialNew,2,-10,45,36,37,citycenter;downtown (from the vanilla values)
      
	  and

      rh5_rave_factory(by_orak),downtown;industrial,2,1,99,43,112,citycenter;smalltown;downtown;alone (from the Ravenhearst values).
	  
	  (Don't ask my why the Ravenhearst Rave Factory would cause that error, since the Darkness Falls values include the same prefab with the same values, but the Darkness Falls variant works.)
	  I commented these two prefabs out, and lo and behold, maps generated with this modified prefab list of mine worked from now on.
   10. After testing out my new list, which contained the vanilla and both the Ravenhearst and the Darkness Falls values, I noticed that most Darkness Falls POIs spawned at a completely messed-up
      height in the world due to the automated value extraction (most spawned in the ground or high above ground, but not *on* the ground), whereas only a few Ravenhearst POIs (and even some vanilla)
	  had the same issue. Furthermore, I wasn't too happy with the set NitroGen zone for many of the POIs, so testing time occurred again.
	  I created map after map with temporary prefab lists and corrected all height values for every included POI in the list manually, checked for more issues and set the NitroGen zone for every
	  POI to something (for my taste) more suitable.
	  Also, I like my lists more readable, so I put more comments into them, commented out POIs that don't work, corrected some typos and sorted them into sections, putting commented-out values at
	  the beginning of each section.
	  
      As a side note, the whole testing process took me approximately two weeks (spare-time speaking).
