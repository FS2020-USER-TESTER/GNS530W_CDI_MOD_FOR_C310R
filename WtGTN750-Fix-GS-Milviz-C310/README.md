# WT_GTN750_GS_FIX_FOR_C310R VERSION 1.0.6

This mod patches the Blackbird C310R to improve compatibility with WTT version of GTN750 mod including fixes to glide slope indicators.

This mod is intended to be used with the WTT GTN750 package available for download in the Airplanes page of PMS50.COM.

The mod is only slightly different from the mod created for WT GNS530.  
  
**This mod is not supported by Blackbird.**


# Change List

Version 1.0.6 - Improve HSI and CDI support for PMS50 GTN750 with WTT 

## Install

1. Delete any earlier version from community. Delete WtGNS530-Fix-CDI-Milviz-C310 if present.
2. Download, unzip and install WtGTN750-Fix-GS-Milviz-C310 to community folder
3. You will need to install pms50-instrument-gtn750 and pms50-gtn750wtt-aircraft-milviz-cessna310 mods downloaded from pms50.com

## Support

You may report issues or ask questions here: https://github.com/FS2020-USER-TESTER/GNS530W_CDI_MOD_FOR_C310R/issues


## Features provided by the mod:

1. The HSI and NAV2 CDI behavior code has been improved to use latest simvars and to provide correct indicator flags.
2. The TO/FROM flag for HSI and CDI are correctly calculated in GPS operation.
3. The latest core fix for autopilot startup PID reset is enabled. This can provide smoother autopilot startup. It is suggested that pilot trim the aircraft before engaging the AP for smoothest transition.


###Supported Configuration 1:

- Community contains: pms50-instrument-gtn750 and pms50-gtn750wtt-aircraft-milviz-cessna310 
- C310R is forced to use only PMS50 GTN750 w/WTT by the PMS50 mod.

###Unsupported Configuration

- pms50-instrument-gtn750 only
