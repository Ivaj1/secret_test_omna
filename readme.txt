'*' is replaced with the booth ID

dealers json:
https://torvid21.github.io/secret_test_omna/furality/booth_data.json
dealer url:
https://torvid21.github.io/secret_test_omna/furality/Booth/Booth_*.png
dealer url mobile:
https://torvid21.github.io/secret_test_omna/furality/Booth_mobile/Booth_*.png
backwall url image:
https://media.cdn.furality.online/dealers/f7/booth/*/backwall.png
backwall url video:
https://media.cdn.furality.online/dealers/f7/booth/*/backwall.mp4
web link url:
https://furality.online/explore/dealers?id=*

booth images are 2048x2048
mobile booth images are 512x512


gallery json:
https://torvid21.github.io/secret_test_omna/furality/gallery_data.json
gallery image url:
https://torvid21.github.io/secret_test_omna/furality/ArtGallery/art_*.png
gallery image url mobile
https://torvid21.github.io/secret_test_omna/furality/ArtGallery_mobile/art_*.png

gallery images are resized to have a *max* dimension of 2048
mobile gallery images are resied to have a *max* dimension of 512



9 pavillions
ID order:
[100, 200, 300], [400, 500, 600], [700, 800, 900]

32 + 4 booths per pavillion

after 31 it skips to 50, 51, 52, 53 for the special booths

json
  {
    "id": 100,
    "avm": [],
    "island": "Avatar Bases",
    "name": "[Cinners] Avatars",
    "backwall": "mp4",
    "category": [ "Other", "Merchandise Creation" ],
    "avatars": []
  },
  {
    "id": 101,
    "avm": [ "prod_00000000-0000-0000-0000-000000000000", "prod_00000000-0000-0000-0000-000000000000","null" ],
    "island": "Avatar Bases",
    "name": "ArcticAsper",
    "backwall": "png",
    "category": [ "Other", "Merchandise Creation" ],
    "avatars": [
      "avtr_74494c73-beaa-4815-80f4-f0761bd08fd9",
      "avtr_777f3fd3-3b9c-47fd-810b-53d643591fe3",
      "avtr_7a788c7d-dc79-4318-87e9-df5990ef16a5"
    ]
  },
  {
    "id": 101,
    "avm": [ "null","null" ],
    "island": "Avatar Bases",
    "name": "ArcticAsper",
    "backwall": "png",
    "category": [ "Other", "Merchandise Creation" ],
    "avatars": [
      "avtr_74494c73-beaa-4815-80f4-f0761bd08fd9",
      "avtr_777f3fd3-3b9c-47fd-810b-53d643591fe3"      
    ]
  },
  {
    "id": 103,
    "avm": [ 
      "prod_00000000-0000-0000-0000-000000000000",
      "null",
      "prod_00000000-0000-0000-0000-000000000001"
    ],
    "island": "Avatar Bases",
    "name": "Natch Deux avatars",
    "backwall": "png",
    "category": [ "Other", "Merchandise Creation" ],
    "avatars": [
      "null",
      "avtr_0fd9b92a-854c-4292-aeb2-a6cd8be282d1",
      "avtr_ad9e9b09-43a0-4032-b985-4ee834e08d3a"
    ]
  },

"videoUrl": either mp4 or png for the back wall
"imageUrl": png for the rest of the booth
"id": booth ID
"avm": secret data?, need to be the same size as avatars, max size 3
"island": island name, valid names: "Avatar Bases", "Avatar Assets", "Avatar Services", "2D Illustration", "Other"
"name": name
"category": list of categories. valid categories: "Anthro Character Art", "Avatar Assets", "Avatar Bases", "3D Modeling", "3D Rendered Art", "Avatar Modeling", "Avatar Retextures", "Comics/Books", "Digital Art", "Fursuits", "Merchandise", "Merchandise Creation",, "Musician", "Traditional Art", "Twitch Production", "Video Production", "World Creation", "Other"
"avatars": list of avatar IDs, max size 3
"backwall": format of the backwall (png or mp4)

