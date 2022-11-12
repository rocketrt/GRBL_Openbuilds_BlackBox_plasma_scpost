# GRBL_Openbuilds_BlackBox_plasma_scpost
GRBL_Openbuilds_BlackBox_plasma__with_IHS_scpost_for_Sheetcam

This is a postprocessor for using Openbuilds BlackBox Controller with plasma and torch height sensing with Sheetcam TNG Ver. 7.0.20...

You need to change Z value in this line :
post.ModalText (" G10 L20 P1 Z-4.600\n")
to match your switch offset ** My offset are -4.600 ** in mm.

Thanks to Sheetcam for this working version :-)
