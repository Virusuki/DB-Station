# DB-Station

## Brain science data classification


|  <center>Major classification leve</center> |  <center>Middle classification level</center> |  <center>Sub classification level</center> |<center>Reference international standard</center> |<center>Unit</center> |<center>File format</center> |<center>etc</center> |
|:--------|:--------:|--------:|--------:|--------:|--------:|--------:|
|**Molecular information** | <center>Omics</center> |<center>Proteomics</center>|  |*2unit and 3unit* |*.csv, .xlsx* |*proteome* |
|**Molecular information** | <center>Omics </center> |<center>transcriptomics</center>|  |*2unit and 3unit* |*.csv, .xlsx* |*Single-cell* |
|**Image/Video information** | <center>Macro(in-vivo)</center> | <center>MRI/fMRI</center> |*BIDS/DICOM* |*3unit* |*.raw(index)* |* * |
|**Image/Video information** | <center>Micro(Ex-vivo)</center> |<center>Electron Microscope</center>|*Electron Midcroscopy public image archive* |*1unit* |*.raw* |*Cell* |
|**Image/Video information** | <center>Reconstruction data</center> |<center>Brain neural circuit mapping(Nano)</center> |*DVID* |*1unit* |*.raw, .h5* |*cell, Brain region* |

## Data API function
*Molecular information()
- MolecularFunctionObject()

#Omics()
- Omics.Proteomics.2unit
- Omics.Proteomics.3unit
- Omics.transcriptomics.2unit
- Omics.transcriptomics.3unit
 
#Image/Video information()
- Macro()
- Macro.MRI_fMRI()
  
#Micro()
- Micro.EM()
  
#Reconstruction_Nano()
- Nano.recon() 
