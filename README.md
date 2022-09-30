# Todo App with React Firebase

- Go to`https://firebase.google.com/`
- Add project
- Create firebase.js in the src/
- Install firebase

  ```
  npm install firebase
  ```

- Install Material UI
  ```
  npm install @mui/icons-material
  ```
  ```
  npm install @mui/material @emotion/react @emotion/styled
  ```
- Add fire store

  ```
  npm install firebase
  ```

  ```
  import { initializeApp } from "firebase/app";
  import { getFirestore } from 'firebase/firestore';

  const firebaseConfig = {
    .......................
  };
  const firebaseApp = initializeApp(firebaseConfig);
  const db = getFirestore(firebaseApp);
  export { db }
  ```

- From firebase
  - Go to console > Select Firebase Project
  - Cloud Firestore
  - Start Collection
    - todos
