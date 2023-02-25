# The Blender 2.8 Encyclopedia
Udemy Course by Lee Salvemini, Chris Plush, CG Masters <br>
<https://www.udemy.com/course/the-blender-encyclopedia/>

## Section 2: Understanding Blender
18 Lectures, 1h 49 min

### 4. User Interface
*   **Splash Screen**:
    * **Disappear**: with ***ESC*** or ***Click*** anywhere.
    * **Reappear**: click the *icon* on the top left and select *splash screen*.
*   **Screen Areas**: *(t = 1:00)*
*   * **Editor**: every area shows a different one.
    * **Header** of options and tools is at the top. If the area is to **narrow** for all the header
      tools, ***Middle Click and drag*** the header left or right.
    * **Editor type menu** in the top left corner to change the editor.
    * **Hidden tool bars**: *(t = 2:20)* are indicated by a little arrow at the border. ***Click***
      to expand. ***Click and hold*** the tool bar's border and drag it back to hide. Already 
      visible bars can be hidden. For some editors press the ***T*** and ***N*** keys for left and 
      right tool bars.

### 5. Customizing the Layout
*   **Maximize Area**:
*   * Hover over it and hit ***Ctrl+Space***. Leaves menu bar at top and the info bar at bottom.
*   * **Full screen** the area with ***Ctrl+Alt+Space***. Leaves no bars at top or bottom.
*   * Select *Header Menu->View->Area->Toggle Maximize Area* or *Toggle Fullscreen Area*.
*   **Resize Areas**: hover over the border until cursor changes into a dubble arrow, then
    ***Click and drag***.
*   **Split Areas**:
*   * Hover over a corner until cursor changes into a cross, then ***Click and drag*** left/right
    for **vertical split** and up/down for **horizontal split**.
    * ***Right Click*** the corner and select *horizontal split* or *vertical split* from the *Area 
    Options* pop-up menu.
*   **Join Areas**:
*   * Hover over a corner until cursor changes into a cross, then ***Click and drag*** corner towards
      the adjacent window you wanna join with. Appearing arrow indicates the area to join into.
    * ***Right Click*** the corner and select *Join Areas* from the *Area Options* pop-up menu.
*   **Swap Areas**:
*   * ***Crtl+Left Click*** an area's corner and ***drag*** to the editor you wanna swap with.
    * Choose *swap areas* from the *Area Options* pop-up menu.
*   **Editor in seperate Window**: ***Shift+Left Click and drag*** an area's corner to pop it out.
*   **Flip Header Position**: ***Right Click*** on header menu and choose
    *(Header->)Flip to Bottom/Top*.
*   **Reorder Panel Items** by **Click and drag** them into the new position by the handler icon (=).
*   **Zoom Text**:
*   * In some editors ***Middle Click and drag***.
    * For **overall** text scale select *Main Menu->Edit->Preferences-->Interface->Resolution Scale*.
*   **Safe Interface Settings**: Select *Main Menu->File->Defaults->Save Startup File*. All changes
    made will be **default** for **new files**. This **includes values** and other settings, even
    **3D objects**.

### 6. Workspaces
*   Predefined **Workspaces** are found to the right of the main menu (*Layout, Modeling, Sculpting, etc.*).
*   **Customize** them and **save** the changes with *Main Menu->File->Defaults->Save Startup File*.
*   **Add additional** workspaces with the *plus icon* and **cloning** an **existing** one.
*   **Reorder** and **delete** is possible by ***Right Click*** on the **name** of the workspace.

### 7. General Editors
*   **Editor Menu** is the leftmost icon below the main menu and shows all **editor types**.
*   **3D Viewport Editor** for modeling, texturing, animationg, etc.
*   **Image Editor** a **2D drawing** tool. Allows to edit images mapped on 3D objects in real time.
*   **UV Editor** to map 2D images on 3D objects.
*   **Shader Editor** defines how an obj looks and responds to light by using **shader nodes**.
*   **Composer Editor** for **post processing** of the renders, animations and video sequences. Adds
    glow or color balance etc.
*   **Texture Node Editor** to create different textures for the world or **brushes**. This can even
    shape the surface of a **3D** object!  
    In *Blender 3.2.2.* this is probably complemented by the **Geometry Node Editor**.
*   **Video Sequence Editor** <https://www.youtube.com/c/MikeycalMeyers/playlists>
*   **Movie Clip Editor** Adding **VFX** to **existing** material with motion tracking and masking.

### 8. Animation Editors
*   **Dope Sheet** gives an **overview** of all **key frames**. They can be **modified** individually
    or all at  once. *(t = 0:55)*
*   **Graph Editor** allows to edit the **rate of change** of a given parameter modified by the key
    frames in a graphical way. For e.g. the coordinates of a moving object. *(t = 1:50)*
*   **Drivers Editor** let's **objects interact** with each other. For e.g. the rotation of one 
    object changes the movement of another. Like a **mechanical simulator**. *(t = 2:40)*
*   **Non linear Animation** allowes to **overlap** predefined **animations** or **actions** such as
    walking and waving of a character. It also allowes to **repeat** and **fade** in/out the movents.

### 9. Scripting Editors
*   **Text Editor** can run a **script** or be used to **take notes**.
*   **Python Console** with full **system API** access.
*   **Info Bar** shows all information involved in an action, for e.g. when duplicationg an object.
    Possibly gives a lot of insights for scripting.

### 10. Data Editors
*   **Outliner** used to **search** for and **select** object in the scene, **organize** them into
    **collections**. (Collections replace Layers from older versionsof blender.)
*   **Properties Editor** changes render and world settings, add modifiers, materials and physics.
*   **File Browser** opens also with ***Ctrl+O*** to open or ***Ctrl+Shift+S*** to safe a file, etc.
*   **Preferences Editor** can also be accessed by *Main Menu->Edit->Preferences*. Contains most
    options to **cutomize** blender such as **hot keys**, interface **colors**, etc.

### 11. User Preferences and Suggested Changes
*   **Saving Preferences menu** (bottom left icon) of the **preferences editor** (*Main Menu->Edit->Preferences*). If **Auto-Save** is checked, all changes are saved to the **blender default** file. Otherwise it's only saved for the current project. Use **Safe Preferences** to manually add changes made to the default file. You can also revert to the **last saved** and **Load Factory Preferences**.
* Preferences **Sections**:
    * **Interface** section is all about the overall look of blender. **Resolution scale** for e.g. adjusts the **font size**.
    * **Themes** is about **colors** and interface **style**. For e.g. adjust *Themes->3D View->Vertex Size*.
    * **Viewport** is about **display** options.
    * **Lights** adjusts the **preview** and **studio** light sources.
    * **Editing** and **Animation** are specific to working with objects in different modes.
    * **Add-ons** to search and **install** tons of 'em.
    * **Input** has options for input **devices**.
    * **Navigation** is about navigating in **3D space**.
    * **Keymap** manages all the **hot keys**.
        * **Hover** over any menu option and ***right click*** to **assign** a hot key.
        * **Search** for a **name** or existing **key binding** in the search bar.
        * **Export/Import** key configuration with the buttons in the top right corner.
    * **System** has technical options, for e.g. using **CUDA and CPU** as render devices.
    * **Save & Load** about blend files and loading **User Interface** (UI) settings.
    * **File Paths** defines where to save to and load from. For e.g. render outputs.
* **Suggested changes**:
    * Turn off *Interface->Editors: Navigation Controls*. Use **hot keys** instead.
    * Set *Interface->Menus->Pie Menus: Animations Timeout* to **0**.
    * Install *Add-ons->Node: Node Wrangler*.
    * Check *Navigation->Orbit&Pan->Auto->Depth*. Stets the **pivot point** that the view rotates around in 3D space, when ***Middle click and drag***.
    * Check *Navigation->Zoom->Zoom To Mouse Position*.
    * Add ***Alt+F11*** as a **hot key** for the menu option *Main Menu->Window->Toggle Window Fullscreen*.
    * Set *Keymap->3D View->3D View (Global)->Pan View* to ***Mouse Button4***.
    * Use *OptiX* on GPU and CPU under *System->Cycles Render Devices*.
    * If *Save & Load->Blend Files->Load UI* is checked, it loads the UI settings that come with the blend file.

### 12. Saving and Loading
* Use ***Ctrl+Shift+S*** to save as a new file. With ***Numpad (+)*** a **numeral extension** can be added and increased.
* *Save Copy ...* creates a **backup** but continues working with the **
* When **opening a file** (***Ctrl+O***) select *Load UI* in the top left corner to load the **user interface** locally **saved** in the **file**. Otherwise it opens with the **default** settings.
* The *Trusted Source* option prevents **scripts** in the blender file from **automatically** running when **disabled**.
* The **Filter** icon shows the **file type** filters. They can be **configured** or **disabled** to show **all** files.
* The Icon left of it allows selection of thumbnail **preview** or **list** view.
* The *Favourites* section holds **quick access** to prefered **folders**.

### 13. File Backups and Recovery
* *Main Menu->File->Recover->Last Session* opens up the last file that was **closed** from the file *quit.blend*.
* *Main Menu->File->Recover->Auto Save...* opens the folder with the **auto saved** files. Usually saves every **two minutes**. This can be adjusted under *...->Preferences->Save & Load->Auto Save->Timer*.
* Blender also creates **backup** *\*.blend1* files with the status of the open file **before saving** recent changes. The number of backup files can be increased under *...->Preferences->Save & Load->Blend Files->Save Versions*.

### 14. Importing and Exporting
* **Import** files with *Main Menu->Files->Import*
* **Export** files with *Main Menu->Files->Export*
    * Use *Selection Only* to export **specific** elements only.
* **Add** additional file **formats** under *...->Preferences->Add-ons->Import-Export (drop down)*, for e.g. *AutoCAD*.

### 15. Navigating Through 3D Space
* All **view options** can be found in the *View Menu* at the top of most areas.
* *View Menu->Viewpoint* lists the **numpad shortcuts**.
* **Additional** numpad shortcuts: 
    * Pressing ***Numpad 4/6*** repeadetly, **rotates** in fixed increments around the users **vertical** view axis.
    * Pressing ***Numpad 2/8*** repeadetly, **rotates** in fixed increments around the users **horizontal** view axis.
    * Pressing ***Numpad 5*** toggles between users **Orthographic** and **Perspective** view.
    * ***Numpad 0*** switches to
* ***Middle Mouse and drag*** switches to **Perspective** (vanishing points).
* Pressing ***~*** key opens a **pie menu** of the view points.
* Holding ***Alt*** and **swiping** with ***Middle Mouse*** doesn't work? *(t = 2:30)*
* Alternatively use the **gimbal** in the top right corner of the area.
* **Rotate** the scene by ***Middle Mouse and drag***.
* **Pan** the scene by ***Mouse 4 and drag***.
* Zoom with
    * ***Mouse wheel***
    * Hold ***Ctrl + Middle Mouse and drag*** up and down
    * ***+ / -*** keys
    * **Zoom Box** with ***Shift+B*** then ***Left Mouse and drag***
    * Select an object and press ***Numpad '.'***
    * Press ***Shift+C*** to center scene

### 16. The Axis and Grid
* X,Y,Z-Axis red, green, blue
* Grid divides dynamically in fractions of 10

### 17. Units of Measurement
* Under *Propertes Editor->Scene Properties->Units* the *Unit System* can be selected as well as the *Unit Scale*.
* When working with very **large** objects it may be better to **increase** the *Unit Scale* instead of changing the grid to avaid **numerical precision** problems. Blender doesn't like when objects are scaled **extremely** large or small. *(t = 0:40)*
* If the **scene** is modeled to small, **increasing** the *Unit Scale* can fix this **without rescaling** the **objects** in the scene. *(t = 1:10)*
* With *Separate Units*, for e.g. `1.5m` turns into `1m 50cm`.
* In the *Viewport Overlays Menu (overlapping disc and circle icon)* the grid subdivision can be altered, for e.g. 12 instead of 10.
* Stick to **real world measures** when modeling. Objects will fit in size when **importing**. It also may affect **shaders**.

### 18. Viewport Shading
* TODO Studio light
* Press ***Shift+Z*** to **toggle** between **solid** shading and **wireframe** when modeling.


*continue @ t = 0:00*