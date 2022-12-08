# GNS530W_CDI_MOD_FOR_C310R
This mod changes the Blackbird C310R to improve compatibility with WT provided GNS530W including split CDI.

**BETA - THIS MOD IS RELEASED AS BETA FOR END-USER TESTING. EXPECT ADDITIONAL UPDATES.**

## Install

1. Unzip WtGNS530-Fix-CDI-Milviz-C310.zip into community folder
2. This mod is only functional while flying the Blackbird C310R.

## Using External Controls for GNS530:

1. Users that map GNS530/430 to external buttons need to assign the CDI button to a script. Here is a possible script:

* 1 (>H:AS530_CDI_Push, Number)

## Features provided by the mod:

1. There is a GNS530 and a GNS430 available in the C310R. With this mod the units can be in unmatched CDI states - one in VLOC and one in GPS
2. The HSI behavior code has been tweaked to use latest simvars and to fix a few issues.
3. Improvements to the Dual Radio mode of the panel to avoid HSI incorrect due to hidden GPS state.
4. The latest core fix for autopilot startup PID reset is enabled. This can provide smoother autopilot startup. It is suggested that pilot trim the aircraft before engaging the AP for smoothest transition.

## Usable with both GNS530 mods:

1. The primary target of this add-on mode is the WT GNS530W mod installed from marketplace.
2. The mod from pms50.com can also be used and split CDI should be functional. 

## What about the GTN750 mods:

1. The intention is the behavior of the GTN750 mods will not be changed when this mod is installed.  
2. If pilot only uses GTN750 and does not use GNS530, there is no benefit to that GPS when using this mod however there should be no new malfunction.
3. The split CDI behavior is not available in GTN750 mods at this time.
