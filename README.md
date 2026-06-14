# Free Exercise DB 💪

An open-source, public-domain exercise dataset in **JSON format** with **800+ structured fitness exercises**, designed for developers, fitness apps, and training platforms.

It also includes a simple **browsable and searchable frontend** for easy exploration of the dataset.

---

## 🚀 Why this exists

I was building a fitness-related app and needed a clean, structured, and free exercise database.

I found [`exercises.json`](https://github.com/wrkout/exercises.json), which was a great starting point, but:

- The data structure didn’t fully match my needs  
- It wasn’t optimized for app usage or filtering  
- There was no intuitive way to browse or search the dataset  

So I:

- Restructured the dataset for better usability  
- Standardized fields for development use cases  
- Built a lightweight frontend to browse and search exercises  

---

## 📦 Dataset

- 800+ exercises  
- Structured JSON format  
- Includes muscle groups, equipment, difficulty, and instructions  
- Ready for APIs, mobile apps, and web apps  

---

## 🧾 Example

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
    "Sit on an incline bench with a dumbbell in each hand at arm’s length. Keep elbows close to your torso. This is your starting position."
  ],
  "category": "strength",
  "images": [
    "Alternate_Incline_Dumbbell_Curl/0.jpg",
    "Alternate_Incline_Dumbbell_Curl/1.jpg"
  ]
}
```

## 🔍 Features

- Structured and normalized exercise data  
- Muscle group categorization  
- Equipment-based filtering  
- Beginner → advanced difficulty levels  
- Clean frontend for browsing exercises  
- Easy integration into fitness applications  
- Lightweight and developer-friendly format  

---

## 🧠 Use cases

- Fitness apps  
- Workout generators  
- Personal trainers / dashboards  
- Gym tracking systems  
- Educational fitness tools  
- AI fitness assistants and recommendation systems  

---

## 📁 Project goal

To provide a clean, developer-friendly exercise database that is easy to integrate, extend, and build on top of, enabling faster development of fitness-related applications and tools.

---

## ⚡ License

Public Domain / open usage (based on original dataset inspiration)
