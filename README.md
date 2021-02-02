![](https://github.com/serpafi/TAO-MKV/blob/master/image/logo.png)


### TRAVAIL EN COURS POUR LA VERSION 3 en date du 02.02.2021
### Version exploitable

#### Modifications en cours
- fixed barre de progression
- recherche pour une implantation du codec VP9

#### Logiciel
- graphisme : 95%
- entrelacement : 10%
- scission : 10%
- lien des controles entre eux : 98%
- mediainfo : 100%
- gestion des listview ( comparaison des noms, caractères unicode et autres, couleurs pour les bugs erreurs et corrections) : 20%
- gestion des erreurs : 0%
- menu classique : 90%
- menu paramètre : 85%
- menu info : 50%
- multilangue : 95% ( en évolution, actuellement en français)
- thème différent : 1 actuellement, violet et noir
- système d'installation automatique : 10%

### système d'exploitation
- windows 7   64 Bits
- windows 8   64 Bits
- windows 10  64 Bits

### video

## Extension :
mkv, mp4, avi, flv, mp3, mp2 ac3, aac, pcm

## Codec: 
- H264 (avec ou sans GPU) ou H265 (avec ou sans GPU)
- ---- en attente de AV1 (VP10) , VVC(H266) et MPEG-5 ---- 

#### pour HEVC avec GPU minimum requis avec "YUV 4:4:4" :
- Nvidia           
A partir de :             
GeForce GTX 1050 / 1050 Ti               
FAMILY : Pascal              
CHIP : GP107            
Generation : 6th Gen              

#### Pour HEVC MAXIMUM 4K en "YUV 4:2:0" :   
GeForce GTX 750 / 950 - 960 	Maxwell (2nd Gen) 	       
GeForce GTX 965M 	Maxwell (2nd Gen)             
GeForce GTX 965M > 980M / 980MX 	Maxwell (2nd Gen)              
GeForce GTX 960 Ti - 980 	Maxwell (2nd Gen)                
GeForce GTX 980 Ti 	Maxwell (2nd Gen) 	       	              
GeForce GTX Titan X                 

Compatibilité des Gpu Nvidia : https://developer.nvidia.com/video-encode-and-decode-gpu-support-matrix-new

- AMD         
incompatible avec AMD et le VCE.  

## Résolution : 
- 640x360 / 720x480 / 852x480 / 960x540 / 1280x720 / 1920x1080 / 3840x2160 / 4096x2160

## Pixel: 
- yuv410p / yuv411p / yuv420p / yuv420p9le / yuv420p10le / yuv420p16le / yuv422p / yuv422p9le / yuv422p10le / yuv422p16le /
- / yuv440p / yuv444p / yuv444p9le / yuv444p10le / yuv444p16le / yuva420p / yuva420p9le / yuva420p10le / yuva420p16le  / 
-  yuva422p / yuva422p9le / yuva422p10le / yuva422p16le / yuva444p / yuva444p9le / yuva444p10le / yuva444p16le



## Preset: 
veryslow | slower | slow (2 pass) | medium (1 pass) | fast (1 pass) | faster | veryfast | superfast | ultrafast

## Bitrate video
- 512k / 1M / 2M / 3M / 4M / etc...


## Framerate: 
- 23.976 | 24 | 25 | 29.97 | 30 | 59.94 | 60


### AUDIO
## Echantillonnage:
24KHz | 32KHz | 44.1KHz | 48KHz

## Codec audio: 
- AAC, AC3, PCM, MP3, MP2

### Autres fonctionnalités :
- conversion PGS vers SRT
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
