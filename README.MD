# Demo scene

Contains Mime character with mapped face shapes and proxy HIK character, mapped to `Ryan` actor.
Also contains a single camera nested in an empty group, mapped to `Camera-1` prop.

![gloves](readmeImages/DemoSceneRec.gif)
![gloves](readmeImages/DemoSceneRecProps.gif)

# Gloves scene

Contains character with only hands geometry and proxy HIK character, mapped to `Ryan` actor.


---
> NOTE: Proxy character is the one which receives live stream.

# Steps to live stream gloves

## Step 1. Prepare gloves mesh

Gloves is normal character with valid skeleton. Which needs to have HIK characterization.

![gloves](readmeImages/prepareHandsHIK.png)

Including fingers

![fingers](readmeImages/characterizationFingers.png)

## Step 2. Follow normal hik pipeline

* Start receiver and create HIK for actor
* Map actor to newly created HIK
* Set newly created HIK as source for Gloves HIK

![fingers](readmeImages/streamGloves.gif)

# Links
Here you can find a requirements for default T-Pose

https://help.autodesk.com/view/HUMANIK/2016/ENU/?guid=__files_GUID_85AEC0B3_AA98_4BEE_9D59_B1D5AE2782EA_htm
