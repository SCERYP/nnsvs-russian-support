# nnsvs russian support
Files for Russian NNSVS dataset creation

Hed and table files required for Russian NNSVS training    
Atlas for LyricInputHelper for easy writing in utau  
The phonemes is based on Rus CVC( by Hiden.BZR )   
Hed file based on polish SzopaTatyJarka ( https://github.com/SzopaTatyJarka/nnsvs-polish-support )  
For good quality data i recommend 1h - 3h data (without silence)
# nnsvs russian in_dim settings 
change it in /train/conf/train//model/.yaml
acoustic_conv.yaml: 262
acoustic_mdn.yaml: 229

duration_lstm.yaml: 258
duration_mdn.yaml: 225

timelag_ffn.yaml: 258
timelag_mdn.yaml: 225
