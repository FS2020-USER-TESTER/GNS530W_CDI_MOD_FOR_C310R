# GNS530W_CDI_MOD_FOR_C310R VERSION 1.0.6

This mod patches the Blackbird C310R to improve compatibility with AAU1 release of WT GNS530W including providing split CDI.
The WT GNS530W is now available as production release. 
All aircraft config changes recommended by WT document are included.
  
# Download and install WtGNS530-Fix-CDI-Milviz-C310-V105.zip to community folder
- Allows tablet to switch between Radio, WT GNS530/430, and TDS GTN750Xi
- Note: PMS50 standard GTN750 can be selected but has autopilot issues. See note below.


**This mod is not supported by Blackbird.**


# Change List

Version 1.0.6 - Improve HSI support for PMS50 GTN750 and TDS custom GS variables
Version 1.0.5 - Additional logic on the disable flags when switching GPS
Version 1.0.4 - Rework the disable variables to allow swith to GTN750
                Minor bug for NAV2 CDI switch
                Choose the production WT GNS530 directly without the Beta mod in Marketplace installed
Version 1.0.3 - Patch panel.cfg so GNS530 is chosen for pop-out
              - Implemented User suggested change "controls_reactivity_scalar" for improved control sensitivity
Version 1.0.2 - HSI GS indication improved

## Install

1. Delete any earlier version from community
2. Download WtGNS530-Fix-CDI-Milviz-C310.zip file and unzip contents into community folder
3. If GTN750 is desired, download and install into community your choice of GNT750 mods from appropriate site - see notes below. 

## Support

You may report issues or ask questions here: https://github.com/FS2020-USER-TESTER/GNS530W_CDI_MOD_FOR_C310R/issues

## Using External Controls for GNS530:

1. Users that map GNS530/430 to external buttons need to assign the CDI button to a script. Here are suggested scripts:

* 1 (>H:AS530_CDI_Push, Number)
* 1 (>H:AS430_CDI_Push, Number)

## Features provided by the mod:

1. There is a GNS530 and a GNS430 available in the C310R. With this mod the units can be in unmatched CDI states - one in VLOC and one in GPS.
2. The HSI and NAV2 CDI behavior code has been improved to use latest simvars and to provide correct indicator flags.
3. The TO/FROM flag for HSI and CDI are correctly calculated in GPS operation.
4. When in Dual Radio mode the state of the hidden GPS units is ignored when calculating HSI/OBS indicators.
5. The latest core fix for autopilot startup PID reset is enabled. This can provide smoother autopilot startup. It is suggested that pilot trim the aircraft before engaging the AP for smoothest transition.
6. Enable/disable control of GNS530W is provided removing issues with used with GTN750. See paragraph below for details.


## PMS50 and TDS GTN750 mods:

1. This mod includes latest recomended variable settings to correctly allow GPS selection using EFB tablet. When either GTN750 mod is present but not selected it is disabled.    
2. PMS50 has posted a 'WT GNS530 Compatibility' patch mod. This is not needed with this C310R mod.
3. The GPS selection in tablet should be made on the ground before programming GPS.  Switching selected GPS in the air is not recomended.  
4. Recommend to restart flight after making change to selected GPS on the C310R tablet to make sure new GPS is correctly initialized.
5. If user wishes to use PMS50 GTN750, need to download and install pms50-instrument-gtn750 and pms50-gtn750wtt-aircraft-milviz-cessna310 mods available from pms50.com.  Using pms50-instrument-gtn750 alone is not recommended. 
6. If user wishes to use TDS GTN750Xi remove the all PMS50 mods from community 

###Supported Configuration 1:

- Community contains: no GPS package.
- C310R can switch Radio <-> GNS530W 

###Supported Configuration 2:

- Community contains: TDS GTN750NXi package. 
- C310R can switch Radio <-> GNS530W <-> TDS GTN750

###Supported Configuration 3:

- Community contains: pms50-instrument-gtn750 and pms50-gtn750wtt-aircraft-milviz-cessna310 
- WtGNS530-Fix-CDI-Milviz-C310 is removed.
- C310R can use only PMS50 GTN750 w/WTT

###Unsupported Configuration

- pms50-instrument-gtn750 only
