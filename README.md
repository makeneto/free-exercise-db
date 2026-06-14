# Free Exercise DB 💪 &nbsp;

Open Public Domain Exercise Dataset in `JSON` format, 800+ exercises with a browsable public searchable frontend

### Why?

I started building another fitness related app and was looking for free/open source exercise lists and imagery I stumbled upon
[exercises.json](https://github.com/wrkout/exercises.json) which was amazing though the data wasn't structured the way I wanted it and I also wanted a browsable/searchable frontend to the data inspired by [this issue](https://github.com/wrkout/exercises.json/issues/5) so I restructured the data and built a simple frontend to it :)

### What do they look like?

```json
{
          "id": "Alternate_Incline_Dumbbell_Curl",
          "name": "Alternate Incline Dumbbell Curl",
          "force": "pull",
          "level": "beginner",
          "mechanic": "isolation",
          "equipment": "dumbbell",
          "primaryMuscles": ["biceps"],
          "secondaryMuscles": ["forearms"],
          "instructions": [
                    "Sit down on an incline bench with a dumbbell in each hand being held at arms length. Tip: Keep the elbows close to the torso.This will be your starting position."
          ],
          "category": "strength",
          "images": [
                    "Alternate_Incline_Dumbbell_Curl/0.jpg",
                    "Alternate_Incline_Dumbbell_Curl/1.jpg"
          ]
}
```