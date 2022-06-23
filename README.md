# nnsvs russian support
Files for Russian NNSVS dataset creation

Hed and table files required for Russian NNSVS training    
Atlas for LyricInputHelper for easy writing in utau  
Table for OpenUtau for easy using
The phonemes is based on Rus CVC( by Hiden.BZR )   
Hed file based on polish SzopaTatyJarka ( https://github.com/SzopaTatyJarka/nnsvs-polish-support )  
For good quality data i recommend 1h - 3h data (without silence)
# russian nnsvs 50min test
BETA Ver. test of Lolita AI

https://user-images.githubusercontent.com/75198282/170233135-25eef1cc-ec72-4d01-b0d1-b139c0f97dc9.mp4

UST by Heiden.BZR
# nnsvs russian in_dim settings 
change it in /train/conf/train//model/.yaml

|   Standard   | In_dim settings |
|--------------|-----------------|
| acoustic_conv.yaml | 284       |
| duration_lstm.yaml | 280       |
| timelag_ffn.yaml   | 280       |
| in_rest_idx        | 19        |
| in_lfx0_idx        | 235       |

|   MDN        | In_dim settings |
|--------------|-----------------|
| acoustic_mdn.yaml | 234        |
| duration_mdn.yaml | 230        |
| timelag_mdn.yaml  | 230        |
| in_rest_idx       | 19         |
| in_lfx0_idx       | 185        |

# nnsvs russian flags

| Flag | Purpose               |
|------|-----------------------|
| F    | falsetto              |
| HV   | head voice            |
| SF   | soft                  |
| P    | power                 |
| D    | dark                  |
| W    | whisper               |
| S    | scream                |
| G    | growl                 |
| C    | cute                  |
| SW   | sweet                 |
| SO   | solid                 |
- Emotion flags
 
| Flag | Purpose               |
|------|-----------------------|
| HPY  | happy                 |
| SAD  | sad                   |
| MAD  | mad                   |
| ANG  | angry                 |
- Custom flags
 
| Flag | Purpose               |
|------|-----------------------|
| 1    | additional_1          |
| 2    | additional_2          |
| 3    | additional_3          |
