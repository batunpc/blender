## Editing

Create *mesh* **`(SHIFT+A)`** and select **Torus** shape

Major Segments `**40**` and Minor Segments `**16**` values are alway good to keep it low value

Set Minor Radius to `**(0.61)**` 

> “It is always good to keep the square faces, if you are making something organic to have that smooth look” - Blender Guru
> 

You can check this with `**(-> TAB)**`

Open you properties `**(N)`**  to see the scale and dimensions etc.

Navigate to the **Dimensions** panel and set the X and Y to **`10cm`** and Z to `**0.0403m`** These are more realistic numbers for a donut 🍩

‼️ Apply the scale: To apply the scale you go `**CTRL+A`** and select `**scale**`

Then, right click and select the **Shade Smooth**

Go to the Modifier Properties → Add Modifier → **Select the Subdivision Surface**

Set the Levels Viewport to `2` not higher, or the render will be higher

### Proportional editing

Do this with the `o` shortcut and mostly remember to use the `OPT+S` to do the **Shrink/Flatten** effectively.

## Modeling (Icing)

### Selecting half of donut (X-RAY Mode)

To toggle between the view modes use the hotkey `Z` then select the wireframe option. This will let you select all the vertices that are hiding behind the mesh.

### **Duplicate**

Once you selected them properly **duplicate** the selected with the hotkey `**SHIFT+D**`

Click on `ESC` to leave it on the deafult place

### **Separate by selected part of the mesh**

Now you can move this to its on object and create it as separete mesh with `P`

Now you should see that you have 2 objects in the object mode.

‼️ If you messed up **Select Link All**  with `ctrl-L`

- Do not forget to name your objects under collection

### **Making meshes THICK**

Click on the Icing and go to the **Modifier Properties → Add Modifier**

Select **Solidify** from the menu

Set the thickness `0.0025`

Offset `1`

### **Changing the order of modifiers**

To have the edges smooth play with the order of the modifiers.

**Solidify**(thickness) comes **1st** then **2nd Subdivision**(smoothing)

### **Snapping tool 🧲**

Right next to the **snapping tool** there is a tool to select where to **snap to**

Select **Face Project** from the dropdown and select **Project individual elements**

Now you can move some dots up and down to give the icing some texture.

### **Work from reference 🎭**

Find a donut picture from internet you can google something like `donut icing`

Separate the window from top left corner and switch to **Image Editor** and open the image you downloaded

Now put the **modifier (Subdivision)** to the top and set the view port and render to `1`

And select the **apply** from the dropdown

Now after the **Solidify modifier** add the **Subdiv** modifier back so that we can have the smooth edges back. Set the render and viewport to `1`

### **Extend the mesh**

Using `E` shortcut extend the meshes and shape the icing based on the reference.

Note: You can also use `S` to shape the drips.

Now apply the **modifier (Subdivision)** to the body of the donut → Select the donut and apply the subdivision.

<img width="1240" alt="CleanShot 2023-06-11 at 19 48 49@2x" src="https://github.com/batunpc/blender/assets/71259399/bc508fc6-315b-4778-96f4-06627c64d23b">


### **Note: Temporarily hide**

Select the icing and click `H` to hide it. To bring it back, click `OPT+H`
