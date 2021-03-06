# What Resolutions are Screenshots Taken, Stored, and Displayed?

There are two methods of adding screenshots to steps in IDL (legacy) labs: 
- Take them using the Take Screenshot tool in LOD in the IDL studio 
- Upload an image file. 

To ensure your screenshots display to your users the way you want them to, you will need to know the following terms and information:

- **Native resolution** = the resolution the screenshot was taken at, i.e 1080x1200
- **Stored resolution** = the resolution the screenshot is stored at - prior to Dec 2016: 800x600; after that: native.
Thumbnail resolution = the mini-view that is in the IDL (legacy) viewer.
Information:

All screenshots created using the **Take Screenshot** tool in LOD inside IDL Studio are now taken at the native resolution of the VM. Screenshots taken prior to December 2016 were shrunk to 800x600 and may experience distortion. At all times you can upload custom screenshots at any resolution.

There are five ways a user can ?view? a screenshot.

**Thumbnail**
- Can be set to auto-show or show when clicked
- Is a small, sometimes distorted (depends on native resolution) view of the screenshot
- May contain grey space if the image does not match the fixed size of the display area

**Open in New Window**
- A link on the thumbnail
- Shows at native resolution
- Can be docked, moved, resized, etc.

**Show In Dialog**
- Will show the screenshot over the top of the VM
- Must be closed to interact with the VM
- Set by you in the Create/Edit Task Screen in the IDL Studio

**Show content in separate window**
- Found on the Support tab
- Moves all instructions and images to a separate browser window that can be docked anywhere
- Still able to do the three methods above

**Separate lab manual**
- Shows the lab manual and images in document format, with or without screenshots
- If included, shows screenshots at native resolution.
- Set by you in the lab profile by adding the lab manual as a resource on the Resources tab