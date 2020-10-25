# Demo scene

Contains Mime character with mapped face shapes and proxy HIK character, mapped to `Ryan` actor.
Also contains a single camera nested in an empty group, mapped to `Camera-1` prop.


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