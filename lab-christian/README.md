## INSTA CLONE APP (MONGO)

## Installation

1. Clone this repository
2. Navigate to your cloned directory, and run an `npm i`
3. Install mongodb -- on a Mac, run `brew update` then `brew install mongodb`. For extra database configuration issues, see `https://treehouse.github.io/installation-guides/mac/mongo-mac.html`!
3. Once the packages are installed, you can run `npm run start` to start the server, or `npm run test` to run the tests.

## User routes

#### POST REQUEST: `localhost:3000/api/signup` Enter a username, email, and password to sign up

#### GET REQUEST: `localhost:3000/api/signin` Enter a username and password to sign in 

## Gallery Routes

#### POST REQUEST: `localhost:3000/api/gallery` Create a new gallery 

#### GET REQUEST: `localhost:3000/api/gallery/:galleryId` Get a gallery by using a valid ID in the URL

#### PUT REQUEST: `localhost:3000/api/gallery/:galleryId` Update a gallery by using a valid ID in the URL

#### DELETE REQUEST: `localhost:3000/api/gallery/:galleryId` Delete a gallery by using a valid ID in the URL

## Photo Route

#### POST REQUEST: `localhost:3000/api/gallery/:galleryId/photo` Post a photo that belongs to a specific gallery. Make sure to have a photo `tester.png` in the `data` directory to pass all tests.