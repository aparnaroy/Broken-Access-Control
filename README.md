# Broken-Access-Control

A CTF problem demonstrating BROKEN ACCESS CONTROL.

// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
apiKey: "AIzaSyCIhm-b7dVmRujv_OSQDgLMsRirerFRXqg",
authDomain: "bada-beep-boop.firebaseapp.com",
projectId: "bada-beep-boop",
storageBucket: "bada-beep-boop.firebasestorage.app",
messagingSenderId: "716619185794",
appId: "1:716619185794:web:565772fd131cc52258fe9b",
measurementId: "G-83673KX4VQ"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
