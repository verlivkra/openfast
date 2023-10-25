2023.10.25 -- ADP

This branch is not intended for general use.  This branch contains a quick hack for the special use case where the drivetrain is modeled with SubDyn, but the AD15 tower is needed for tower shadow.

Modifications include:
 - change AD15 tower motion mapping from the ED tower to mapping from the ED PlatformPtMesh instead (point to line mapping -- AD15 tower is now rigid)
 - removal of all mapping from the AD15 loads to the ED tower
 - removed ED_L_2_AD_L_T and AD_L_2_ED_P_T mesh mappings
