![1 Send us a message](https://user-images.githubusercontent.com/93486996/155018471-e5784a89-7d79-495e-b8ad-bd77a0a395af.jpg)

![2  A feltöltés sikeres volt](https://user-images.githubusercontent.com/93486996/155018483-7b35d133-3bd0-44c1-923e-8a6e47958083.jpg)

![3 Firebase-Database](https://user-images.githubusercontent.com/93486996/155018495-5cf7be7d-95f7-4579-90e3-8169695470f7.jpg)

*********************
Fontos! 
( "react-native-firebase": "^5.6.0", 
    "react-dom": "^17.0.2",
    "firebase": "^8.1.1" )

- Kell készítened egy " env.local " file amiben amiben tároljuk a kapcsolódási adatokat.
- Github az " env.local " file nem tölti fel. 
- Azért szervezzük át ide a kapcsolódási adatokat mert nem akarjuk hogy más lássa őket. (Biztonsági okok miatt) 

*********************
Important!
( "react-native-firebase": "^5.6.0", 
    "react-dom": "^17.0.2",
    "firebase": "^8.1.1" )

- You need to create an "env.local" file in which to store the connection data.
- Github does not upload the "env.local" file.
- Let's reorganize the contact information here because we don't want anyone else to see it. (For security reasons)

*********************
" env.local " -> 

REACT_APP_FIREBASE_API_KEY=
REACT_APP_FIREBASE_AUTH_DOMAIN=
REACT_APP_FIREBASE_PROJECT_ID=
REACT_APP_FIREBASE_STORAGE_BUCKET=
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=
REACT_APP_FIREBASE_APP_ID=
