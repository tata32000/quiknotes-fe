# Creative Noters

A simple, intuitive, and frictionless [web app](https://creativenoters.vercel.app) for annotating on images and documents.

## Aim
We plan to build an open-source, desktop and mobile quick note-taking and annotating web application that can sync across different devices. Essentially, to build a simple, intuitive, and frictionless web application for annotating on images and documents.

### Implemented Features
- Authentication using email and password, anonymous login, and sign in with Google
- Free drawing tools such as pen and highlighter
- Help page
- Color picker and line thickness slider
- Save and restore the annotations to Firestore Database
- Importing files for annotation
- Exporting as image, bitmap pdf, and vector pdf

### Proposed Features
- Stroke eraser tool
- Real time database

## Tech Stack
### Frontend
- [ReactJS](https://reactjs.org)
- [Konva](https://konvajs.org) (free drawing)
- [pdf.js](https://mozilla.github.io/pdf.js/) (renders PDFs)
- [pdf-lib](https://pdf-lib.js.org) (edits PDFs) 
- [MUI](https://mui.com) 
### Backend
- [Firebase Firestore](https://firebase.google.com/products/firestore?gclid=CjwKCAjwk_WVBhBZEiwAUHQCma01sE_BhxZ6qlNXvleqkKa0__0_kAb7TYZe9CIXBNb0yzIH7Q0AJxoC2aIQAvD_BwE&gclsrc=aw.ds)
- Stretch goal: [Firebase Realtime database](https://firebase.google.com/products/firestore?gclid=CjwKCAjwk_WVBhBZEiwAUHQCma01sE_BhxZ6qlNXvleqkKa0__0_kAb7TYZe9CIXBNb0yzIH7Q0AJxoC2aIQAvD_BwE&gclsrc=aw.ds)
