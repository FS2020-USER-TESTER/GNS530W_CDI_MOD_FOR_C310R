# GNS530W_CDI_MOD_FOR_C310R
This mod changes the Blackbird C310R to improve compatibility with WT provided GNS530W including split CDI.
All aircraft config changes recommended by WT are included.


## Install

1. Unzip WtGNS530-Fix-CDI-Milviz-C310.zip placing WtGNS530-Fix-CDI-Milviz-C310 into community folder
2. This mod is only functional while flying the Blackbird C310R.

## Support

You may report issues or ask questions here: https://github.com/FS2020-USER-TESTER/GNS530W_CDI_MOD_FOR_C310R/issues
Updates will be posted here when submitted: https://github.com/FS2020-USER-TESTER/GNS530W_CDI_MOD_FOR_C310R/releases
This mod is not supported by Blackbird. 


## Using External Controls for GNS530:

1. Users that map GNS530/430 to external buttons need to assign the CDI button to a script. Here are suggested scripts:

* 1 (>H:AS530_CDI_Push, Number)
* 1 (>H:AS430_CDI_Push, Number)

## Features provided by the mod:

1. There is a GNS530 and a GNS430 available in the C310R. With this mod the units can be in unmatched CDI states - one in VLOC and one in GPS
2. The HSI behavior code has been tweaked to use latest simvars and to fix indicator flag issues.
3. The TO/FROM flag for HSI and OBS are correctly calculated in GPS operation.
4. When in Dual Radio mode the state of the hidden GPS units is ignored when calculating HSI/OBS indicators.
5. The latest core fix for autopilot startup PID reset is enabled. This can provide smoother autopilot startup. It is suggested that pilot trim the aircraft before engaging the AP for smoothest transition.

## Usable with both GNS530 mods:

1. The primary target of this add-on mode is the WT GNS530W mod installed from marketplace or AAU1.
2. The mod from pms50.com can also be used and split CDI should be functional. 

## What about the GTN750 mods:

1. This mod includes latest recomended variable settings to correctly allow GPS selection using EFB tablet. When either GTN750 mod is present but not selected it is disabled.
2. The GPS selection in tablet should be made on the ground before programming GPS.  Switching selected GPS in the air is not recomended.
2. The hot-swap feature remains a work-in progress. Consult your GTN750 provider's discord for latest information on using GTN750 with the C310R.
3. The split CDI behavior is not available in GTN750 mods at this time.
