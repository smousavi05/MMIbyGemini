## Gemini and physical world: large language models can estimate the intensity of earthquake shaking from multimodal social media posts
                                                                                                  
![GitHub last commit](https://img.shields.io/github/last-commit/smousavi05/MMIbyGemini?style=plastic)
![GitHub stars](https://img.shields.io/github/stars/smousavi05/MMIbyGemini?style=social)
![GitHub followers](https://img.shields.io/github/followers/smousavi05?style=social)
![GitHub forks](https://img.shields.io/github/forks/smousavi05/MMIbyGemini?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/smousavi05/MMIbyGemini?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/smousavi05?style=social)

<img src="https://github.com/smousavi05/MMIbyGemini/blob/main/tweet_example.png" alt="an example of intensity estimation from a tweet related to the 2024 earthquake in New Jersey ">

### Input:
<img src="https://github.com/smousavi05/MMIbyGemini/blob/main/taiwan.gif" alt="A social media post sharing a video capturing the impact of M 7.4 eathquake on 3 April 2024 in Taiwan">


### Gemini's output:
"earthquake_location": "Taiwan (exact location not specified)",
 "shaking_duration": "Approximately 35 seconds based on the video duration.",
 "building_type": "Residential apartment (assumed based on interior furnishings)",
 "humans_reaction": "The person in the video exhibits alarm and attempts to take cover.",
 "video_evidence": {
   "Intense Shaking": "Objects are visibly swaying and moving, with some falling from shelves and surfaces.",
   "Object Movement": "Items on tables and shelves are displaced, indicating significant ground motion.",
   "Person's Reaction": "The individual's attempt to seek cover suggests a perception of danger and strong shaking."},
 "audio_evidence": {
   "Rattling and Crashing": "Sounds of objects shaking and colliding suggest a high degree of ground movement.",
   "Possible Vocalizations": "Sounds of alarm or distress from the person, though not clearly discernible."},
 "textual_evidence": {
   "Post Description": "The user's comment 'I can't imagine being shaken around like that' indicates a perception of intense shaking."},

 "mmi_estimation": "MMI VI or MMI VII",

 "visual_observation": "The video evidence portrays a scene of significant ground shaking, with objects being displaced and falling. The person's reaction further supports the notion of strong shaking.",
 "auditory_cues": "The audio complements the visual evidence by providing the sounds of objects rattling and crashing, adding to the overall impression of intense ground movement.",

 "reasoning": "While the video doesn't show major structural damage, the intensity of object movement and the individual's response suggest a level of shaking that is beyond MMI V. However, without evidence of more severe damage (e.g., large cracks in walls, partial building collapse), assigning MMI VII with high confidence is not possible. Hence, the estimated uncertainty is 0.5, reflecting a moderate level of confidence in the MMI VI or VII range."


-------------------------------------
[Paper](https://academic.oup.com/gji/article/240/2/1281/7921623?trk=public_post_comment-text)

[Listen to its summary](https://illuminate.google.com/library?play=EvwJDC_qTMF3)

[Dataset](https://drive.google.com/file/d/1s78fxDheptTfJwq6TDQq_0qxCgiwGOYC/view?usp=sharing)

[Prompt](https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/gji/240/2/10.1093_gji_ggae436/2/ggae436_supplemental_file.pdf?Expires=1748085392&Signature=RAJ~nDB6kUAkE1I56RGxtct2ololr5GkjcZAPar~V1wpuJD4hZtYUr94e7LDWAZz~PFyRDQkKzrsgoKIu1R2lgrCQgeBSzaER12qwB0oQaqwjYzePM8h1OFX4ISsZayYkl7G5zbcMCAMg52IUPjA4y83s-7hcuZImFVkdk-tX7maji8IMKyiLIfNz49FW2aKdFCOEYVMxVAFAirsah0u3puqFsT0l0AGRQGD~QigQZOfxKyPnjiVSJ1qmt~gIrYTlJ4JVPAEwbam8gtwoY2BPy0j5u2A3lP-NASnKNSrebPtEph4uqIja8DSKrVQ1c3SLe9CLvApsSoT0zA5U-6MTQ__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA)

-------------------------------------
### Reference:

`Mousavi, S. M., Stogaitis, M., Gadh, T., Allen, R. M., Barski, A., Bosch, R., ... & Raj, A. (2025). Gemini and physical world: large language models can estimate the intensity of earthquake shaking from multimodal social media posts. Geophysical Journal International, 240(2), 1281-1294.` 


BibTeX:

@article{mousavi2025gemini,
  title={Gemini and physical world: large language models can estimate the intensity of earthquake shaking from multimodal social media posts},
  author={Mousavi, S Mostafa and Stogaitis, Marc and Gadh, Tajinder and Allen, Richard M and Barski, Alexei and Bosch, Robert and Robertson, Patrick and Cho, Youngmin and Thiruverahan, Nivetha and Raj, Aman},
  journal={Geophysical Journal International},
  volume={240},
  number={2},
  pages={1281--1294},
  year={2025},
  publisher={Oxford University Press}
}

-------------------------------------
