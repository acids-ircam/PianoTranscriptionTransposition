<link href="style.css" rel="stylesheet">

<script type="text/javascript"> 
      // Show button
      function look(type){ 
      param=document.getElementById(type); 
      if(param.style.display == "none") param.style.display = "block"; 
      else param.style.display = "none" 
      } 
</script>

# Overview
We propose a model to improve automatic music transcription by adding a perceptual objective using differentiable rendering, 
while permitting automatic timbre-based arrangement to different musical instruments from the original.

# Transcription

# Arrangement

## Orchestra to strings (Dvorak - Symphony No.9 Fourth movement)
The sounds of strings are stationary.

|Original sound|Arrangement|
|:-:|:-:|
|<img src="data/arrangement/dvorak_original_orchestra.png"><br><audio controls><source src="data/arrangement/dvorak_original_orchestra.wav"></audio>|<img src="data/arrangement/dvorak_generated_strings.png"><br><audio controls><source src="data/arrangement/dvorak_generated_strings.wav"></audio>|

## Orchestra to organ (Holst - The Planets, Jupiter)
The sound of a organ is stationary.

|Original sound|Arrangement|
|:-:|:-:|
|<img src="data/arrangement/jupiter_original_orchestra.png"><br><audio controls><source src="data/arrangement/jupiter_original_orchestra.wav"></audio>|<img src="data/arrangement/jupiter_generated_organ.png"><br><audio controls><source src="data/arrangement/jupiter_generated_organ.wav"></audio>|

## Orchestra to piano (Haydn - Menuet)
The sound of a piano is non-stationary.

|Original sound|Arrangement|
|:-:|:-:|
|<img src="data/arrangement/haydn_original_orchestra.png"><br><audio controls><source src="data/arrangement/haydn_original_orchestra.wav"></audio>|<img src="data/arrangement/haydn_generated_piano.png"><br><audio controls><source src="data/arrangement/haydn_generated_piano.wav"></audio>|
