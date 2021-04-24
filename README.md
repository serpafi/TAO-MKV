![](https://github.com/serpafi/TAO-MKV/blob/master/image/logo.png)


### TRAVAIL EN COURS POUR LA VERSION 3 en date du 02.04.2021
### Version exploitable

un launcher offline est en cours de développement avec TAO-MKV version 3.0.2.0

#### Modifications en cours
- la barre de progression n'est toujours pas opérationnelle
=========================================================================================

## système d'exploitation
- windows 7   64 Bits
- windows 8   64 Bits
- windows 10  64 Bits

## video

#### Extension :
mkv, mp4, avi, flv, mp3, mp2 ac3, aac, pcm, mov

#### Codec: 
- AVC:     
H.264 / AVC (libx264) (sans GPU)  
H.264 / Nvidia (avec GPU)
H.264 / AMD (avec GPU)        
H.264 / Intel QuickSync           
H.264 / RBG     

- HEVC:       
H.265 / HEVC (libx265) (sans GPU)          
H.265 / Nvidia (avec GPU)        
H.265 / AMD (avec GPU)            

- VP9:     
VP9   / libvpx           
VP9   / Intel QuickSync            

- AV1:     
AV1   / libaom        
AV1   / librav1e       

- ---- en attente de VVC(H266) et MPEG-5 ---- 

##### pour HEVC avec GPU minimum requis avec "YUV 4:4:4" :
- Nvidia           
A partir de :             
GeForce GTX 1050 / 1050 Ti               
FAMILY : Pascal              
CHIP : GP107            
Generation : 6th Gen              

##### Pour HEVC MAXIMUM 4K en "YUV 4:2:0" :   
GeForce GTX 750 / 950 - 960 	Maxwell (2nd Gen) 	       
GeForce GTX 965M 	Maxwell (2nd Gen)             
GeForce GTX 965M > 980M / 980MX 	Maxwell (2nd Gen)              
GeForce GTX 960 Ti - 980 	Maxwell (2nd Gen)                
GeForce GTX 980 Ti 	Maxwell (2nd Gen) 	       	              
GeForce GTX Titan X                 

Compatibilité des Gpu Nvidia : https://developer.nvidia.com/video-encode-and-decode-gpu-support-matrix-new

- AMD         
possibilité de travailler avec les GPU AMD mais pas testé.

#### Résolution : 
- 640x360 / 720x480 / 852x480 / 960x540 / 1280x720 / 1920x1080 / 3840x2160 / 4096x2160

#### Pixel: 
- yuv410p / yuv411p / yuv420p / yuv420p9le / yuv420p10le / yuv420p16le / yuv422p / yuv422p9le / yuv422p10le / yuv422p16le /
- / yuv440p / yuv444p / yuv444p9le / yuv444p10le / yuv444p16le / yuva420p / yuva420p9le / yuva420p10le / yuva420p16le  / 
-  yuva422p / yuva422p9le / yuva422p10le / yuva422p16le / yuva444p / yuva444p9le / yuva444p10le / yuva444p16le



#### Preset: 
veryslow | slower | slow (2 pass) | medium (1 pass) | fast (1 pass) | faster | veryfast | superfast | ultrafast

#### Bitrate video
- 512k / 1M / 2M / 3M / 4M / etc...


#### Framerate: 
- 23.976 | 24 | 25 | 29.97 | 30 | 59.94 | 60


## AUDIO
#### Echantillonnage:
24KHz | 32KHz | 44.1KHz | 48KHz

#### Codec audio: 
- AAC, AC3, PCM, MP3, MP2

## SOUS-TITRE
- conversion PGS vers SRT


#### Autres fonctionnalités :
- Choisir les pistes audio, sous-titre, chapitres, pièce-joints et vidéo à garder.
- LOG en real time avec possibilité d'enregistrer le LOG en format TXT et de l'activer/désactiver pendant le processus.
- Drag & Drop
- Vérification de la correspondance des noms entre les 2 listes
- entrelacement
- scission
- conversion video et audio
- option décalage et étirement des pistes
- ;; choix entre bitrate video ou CRF (de 0 à 50)
- vérification de l'intégrité mkv
- étirement et décalage des pistes pour chaque liste
- conversion audio 5.1 vers stéréo
- détéction des blocks endommagés (video qui se coupe) 

### preview de la V3
![](https://github.com/serpafi/TAO-MKV/blob/master/image/preview%20video.png)
![](https://github.com/serpafi/TAO-MKV/blob/master/image/preview%20audio.png)
![](https://github.com/serpafi/TAO-MKV/blob/master/image/preview%20log.png)
