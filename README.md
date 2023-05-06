# KIconMaker

<img src="https://i.gyazo.com/12eb93628cc36b23702e501de9fd4511.png" />

## Installing:
1. clone this `repo` or download the `zip file` (https://gitlab.kmods.de/Kyrium/kiconmaker[https://gitlab.kmods.de/Kyrium/kiconmaker])
2. copy it to `<your project>/Plugins/`.
3. open the editor and go to KIconMaker Content
4. open the `IconMaker` level

## Using:

<img src="https://i.gyazo.com/6a942f885b71dd09710d0b1b285c086e.png" />

### Actions
- `Export` - Automatically name the icon and export it to the path specified in `mExportPath`.
- `Hide indicator` - Try to find the production indicator and remove it from the actor.

### Select the object where we want to create a ICON
- `mBuildingClass` - The class of the build (used only if `mItemMesh` AND `mItemClass` is none; set automatically if `mItemClass` OR `mItemMesh` not none)
- `mItemClass` - the class of the object (used only if `mItemMesh` is none)
- `mItemMesh` - if you want to snap a static mesh, use this (automatically set by `mItemClass`)

### Camera (Custom):
- `mActorRotation` - Is for the rotation of the ChildActor (The object you want to create an icon in).
- `mCameraArm` - Sets the distance between the object and the camera
- `mCameraRotation` - is for the rotation around the object
- `mFOVAngle` - is the FOV for the camera
- `mCameraLocation` - to set an offset for the position of the camera (move the arm, not the camera itself)

### Light
- `mLight` - is the object for the light (DirectionalLight)
- `mLightIntensity` - light intensity small helper to set the intensity easily in Icon Maker
- `mSkyRoation` - light rotation small helper to set the position easily in Icon Maker

## After Export (if you DONT use the invert Alpha feature!)
After export you will get an image that is blue and has an alpha in the middle. Now you have to invert the alpha, for example with Paint. NET or PS.
Small tip for Paint. NET : https://forums.getpaint.net/topic/9625-invert-alpha/

After that scale the image to 512x512 (for buildings) or 256x256 (for items)

<img src="https://i.gyazo.com/5eb1c34ee1c3558e0c922dbe94390955.png" />
<img src="https://i.gyazo.com/0a863c927f05d4535f74fc70ad289cd1.png" />
