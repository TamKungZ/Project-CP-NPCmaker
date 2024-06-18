![image](https://github.com/TamKungZ/Project-CP-NPCmaker/assets/170596410/4dfa0146-e758-4d86-bb30-43f84ca33443)
# TamkungZ_'s NPC Maker
</p><p data-sourcepos="5:1-5:203"><span>This code creates a graphical user interface (GUI) for creating content for the game Stardew Valley using a content patcher.</span><span> The GUI allows users to input data for NPCs and export the data as JSON files.</span></p><p data-sourcepos="7:1-7:18"><strong>User Interface</strong></p><p data-sourcepos="9:1-9:71"><span>The GUI is divided into three sections:</span><span> Manifest,</span><span> Content,</span><span> and Texture.</span></p><ul data-sourcepos="11:1-13:50"><li data-sourcepos="11:1-13:50"><p data-sourcepos="11:3-11:14"><strong>Manifest</strong></p><ul data-sourcepos="12:5-13:50"><li data-sourcepos="12:5-12:154"><span>This section allows users to input data for the mod manifest,</span><span> including the mod name,</span><span> author,</span><span> version,</span><span> description,</span><span> unique ID,</span><span> and Nexus project ID.</span></li><li data-sourcepos="13:5-13:50"><span>A button allows users to export the manifest data to a JSON file.</span></li></ul></li><li data-sourcepos="15:1-21:0"><p data-sourcepos="15:3-15:13"><strong>Content</strong></p><ul data-sourcepos="16:5-21:0"><li data-sourcepos="16:5-19:54"><span>This section allows users to input data for NPC content,</span><span> including:</span><ul data-sourcepos="17:9-19:54"><li data-sourcepos="17:9-17:97"><span>NPC information:</span><span> name,</span><span> position,</span><span> direction,</span><span> favor/like/normal/dislike messages and IDs.</span></li><li data-sourcepos="18:9-18:66"><span>Personality and behavior options through dropdown menus.</span></li><li data-sourcepos="19:9-19:54"><span>Birthday information through dropdown menus.</span></li></ul></li><li data-sourcepos="20:5-21:0"><span>A button allows users to export the content data to a JSON file.</span></li></ul></li><li data-sourcepos="22:1-23:31"><p data-sourcepos="22:3-22:13"><strong>Texture</strong></p><ul data-sourcepos="23:5-23:31"><li data-sourcepos="23:5-23:31"><span>This section allows users to specify the location of the portrait and sprite images for the NPC.</span></li><li data-sourcepos="24:5-24:59"><span>Browse buttons allow users to select the image files.</span></li><li data-sourcepos="25:5-26:0"><span>A button allows users to export the image paths to a JSON file.</span></li></ul></li></ul><p data-sourcepos="27:1-27:12"><strong>Schedule</strong></p><p data-sourcepos="29:1-29:234"><span>The code also includes functionality for exporting NPC schedules,</span><span> but it is not currently integrated into the GUI.</span><span> The schedule data includes a list of entries for each day,</span><span> where each entry specifies a time and an associated message.</span></p><p data-sourcepos="31:1-31:18"><strong>Code Structure</strong></p><p data-sourcepos="33:1-33:128"><span>The code is well-structured and uses functions to modularize different functionalities.</span><span> Here's a breakdown of the key functions:</span></p><ul data-sourcepos="35:1-38:39"><li data-sourcepos="35:1-35:111"><code class="">relative_to_assets</code><span>:</span><span> This function takes a path as input and returns the path relative to the assets folder.</span></li><li data-sourcepos="36:1-36:81"><code>export_json_manifest</code><span>:</span><span> This function exports the manifest data to a JSON file.</span></li><li data-sourcepos="37:1-37:79"><code>export_json_content</code><span>:</span><span> This function exports the content data to a JSON file.</span></li><li data-sourcepos="38:1-38:39"><code>texture_set</code><span>:</span><span> This function sets the NPC's portrait and sprite paths and exports them to a JSON file.</span></li><li data-sourcepos="39:1-39:121"><code>export_schedule_json</code><span>:</span><span> This function exports the NPC schedule data to a JSON file (not currently integrated into GUI).</span></li><li data-sourcepos="40:1-40:90"><code>add_schedule_entry</code><span>:</span><span> This function adds a new entry to the schedule for a specific day.</span></li><li data-sourcepos="41:1-41:124"><code>get_day_schedule</code><span>:</span><span> This function gets the schedule data for a specific day in the format required by the content patcher.</span></li><li data-sourcepos="42:1-43:0"><code>setup_day_schedule</code><span>:</span><span> This function sets up the schedule for a specific day in the GUI.</span></li></ul><p data-sourcepos="44:1-44:126"><strong>Overall, this code provides a user-friendly interface for creating NPC content for Stardew Valley using a content patcher.</strong></p></div>


# Project-CP-NPCmaker

## License

MIT License

© 2024 TamKungZ_

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to use the Software for the sole purpose of studying and understanding the Software's processes, subject to the following conditions:

1. Redistribution: The Software may not be distributed, republished, or shared in any form or by any means, including but not limited to electronic, mechanical, photocopying, recording, or other means, without the prior written permission of the copyright owner.

2. Commercial Use: The Software may not be used for commercial purposes. This includes, but is not limited to, selling, licensing, renting, or any other form of commercial exploitation.

3. Modification: The Software may not be modified, adapted, translated, or altered in any way without the prior written permission of the copyright owner.

4. Attribution: Users of the Software must not claim authorship, endorsement, or association with the Software's creator, TamKungZ_, in any derivative works or associated materials.

5. No Warranty: The Software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the Software or the use or other dealings in the Software.

6. Compliance: Any use of the Software must comply with all applicable laws, regulations, and policies.

This license shall automatically terminate if you violate any of these restrictions and may be terminated by the copyright owner at any time.

For permissions beyond the scope of this license, you must obtain explicit written consent from TamKungZ_.

Project uploaded on GitHub for the sole purpose of study and process understanding. For any other use, please contact the creator.

Contact Information:
[[Contact TamKungZ_]](https://linktr.ee/TamKungZ_)
