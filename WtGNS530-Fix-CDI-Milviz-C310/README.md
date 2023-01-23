# GNS530W_CDI_MOD_FOR_C310R VERSION 1.0.3

This mod patches the Blackbird C310R to improve compatibility with early release WT GNS530W including split CDI.
The GNS530W is currently available optionally in Marketplace but will become the standard GPS implementation in 2023.
All aircraft config changes recommended by WT document are included.

This mod is not supported by Blackbird. 

# Change List

Version 1.0.3 - Patch panel.cfg so GNS530 is chosen for pop-out
              - Implemented User suggested change "controls_reactivity_scalar" for improved control sensitivity
Version 1.0.2 - HSI GS indication improved

## Install

1. Delete any earlier version from community
2. Unzip WtGNS530-Fix-CDI-Milviz-C310.zip placing WtGNS530-Fix-CDI-Milviz-C310 into community folder
3. This mod is only functional while flying the Blackbird C310R.

## Support

You may report issues or ask questions here: https://github.com/FS2020-USER-TESTER/GNS530W_CDI_MOD_FOR_C310R/issues

## Using External Controls for GNS530:

1. Users that map GNS530/430 to external buttons need to assign the CDI button to a script. Here are suggested scripts:

* 1 (>H:AS530_CDI_Push, Number)
* 1 (>H:AS430_CDI_Push, Number)

## Features provided by the mod:

1. There is a GNS530 and a GNS430 available in the C310R. With this mod the units can be in unmatched CDI states - one in VLOC and one in GPS
2. The HSI and NAV2 CDI behavior code has been improved to use latest simvars and to provide correct indicator flags.
3. The TO/FROM flag for HSI and CDI are correctly calculated in GPS operation.
4. When in Dual Radio mode the state of the hidden GPS units is ignored when calculating HSI/OBS indicators.
5. The latest core fix for autopilot startup PID reset is enabled. This can provide smoother autopilot startup. It is suggested that pilot trim the aircraft before engaging the AP for smoothest transition.
6. Enable control of GNS750 is provided removing issues with used with GNT530W.

## Usable with both GNS530 mods:

1. The primary target of this add-on mode is the WT GNS530W mod installed from marketplace or AAU1.
2. The mod from pms50.com can also be used and split CDI should be functional. 

## What about the GTN750 mods:

1. This mod includes latest recomended variable settings to correctly allow GPS selection using EFB tablet. When either GTN750 mod is present but not selected it is disabled.
2. The GPS selection in tablet should be made on the ground before programming GPS.  Switching selected GPS in the air is not recomended.
2. The hot-swap feature remains a work-in progress. Consult your GTN750 provider's discord for latest information on using GTN750 with the C310R.
3. The split CDI behavior is not available in GTN750 mods at this time.
