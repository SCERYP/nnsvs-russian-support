# nnsvs russian support
Files for Russian NNSVS dataset creation

Hed and table files required for Russian NNSVS training    
Atlas for LyricInputHelper for easy writing in utau  
The phonemes is based on Rus CVC( by Hiden.BZR )   
Hed file based on polish SzopaTatyJarka ( https://github.com/SzopaTatyJarka/nnsvs-polish-support )  
For good quality data i recommend 1h - 3h data (without silence)
# nnsvs russian in_dim settings 
change it in /train/conf/train/*/model/*.yaml  
acoustic_conv.yaml: 268   
acoustic_mdn.yaml: 271

duration_lstm.yaml: 264   
duration_mdn.yaml: 267

timelag_ffn.yaml: 264   
timelag_mdn.yaml: 267
