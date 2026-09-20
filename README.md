# About this MOD Dwarf Custom Image

This is basically the wonderful Starless from https://forum.mod.audio/t/starless-by-alabs-development/12853

The ability to have multiple controllers has been added and a few MIDI bits and bobs.

The idea is for some brave souls to test this before it is merged into Starless.

## Improvements in this image

This custom image introduces the following enhancements:

- **Multiple Controllers** You can now map HMI, CC, CV and MIDI at the same time to a control.
- **Midi control of lists** You can now change lists and snapshots from MIDI.
- **Toggle and Momentary MIDI** Midi buttons/switches now supported.
- **MIDI Tap Tempo** Tap Tempo from MIDI buttons/switches.

## Documentation

For more details and to know how to use Starless read the [wiki](https://github.com/sejerpz/alabs-mod-custom-images/wiki)

# How to Install the MOD Dwarf aLabs image

To test this new image, follow the standard update procedure for the MOD Dwarf as described in the official documentation:

🔗 [Official MOD Dwarf Releases Guide](https://wiki.mod.audio/wiki/Releases)

## Installation Steps

1. Read the **manual update procedure** on the documentation page.  
2. Put your Dwarf into **update mode** as described.  
3. Follow the instructions provided in the guide.  
   - **Important:** Instead of downloading a standard image, download the latest **MOD Dwarf aLabs image** from the releases of this git repository [aLabs Releases](https://github.com/sejerpz/alabs-mod-custom-images/releases).

## Reverting to an Official Image

If you decide not to use this firmware image anymore:

1. Repeat the update process.  
2. This time, select and install an **official MOD image** from the official releases.

# Versioning

Alabs custom images, _from version 2_, adopted a simple monotone version convention.

Each release is tagged with a progressive version number and an optional letter for quality:

`v{base mod image version}-alabs{version number}[optional letter quality]`

For example:

`v1.13.5.3315-alabs2a`

base image version: **1.13.5.3315**
alabs version: **2**
_quality_: **a: alpha**

`v1.13.5.3315-alabs3b`

base mod image version: **1.13.5.3315**
alabs version: **3**
_quality_: **b: beta**

`v1.13.5.3315-alabs4`

base mod image version: **1.13.5.3315**
alabs version: **4**
_quality_: **none: stable release**
