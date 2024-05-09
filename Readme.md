// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyDgg1msuCNlNLUswkixoJIMOMzCCUE2Ev4",
  authDomain: "faceless-data-a6950.firebaseapp.com",
  projectId: "faceless-data-a6950",
  storageBucket: "faceless-data-a6950.appspot.com",
  messagingSenderId: "548350924332",
  appId: "1:548350924332:web:0d4fc2ca5b9a6956fd6389",
  measurementId: "G-B86MRWKKVG"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
