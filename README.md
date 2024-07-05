# interview
Tech interview instructions

# Basic web skills test


## Setup

### Get the backend

- **Django Python :** https://github.com/re-connect/interview-django
- **Symfony PHP :** https://github.com/re-connect/interview-symfony
- **NestJs :** https://github.com/re-connect/interview-nest

### Get the frontend

- **React :** https://github.com/re-connect/interview-react
- **VueJs :** https://github.com/re-connect/interview-vue

## A few notices

1. Try to write code as clean as you can, according to your standards.
2. We do not ask 100% code coverage of course, test are good, but not mandatory
3. Feel free to commit on a regular basis
4. You should note your progress timing to know where you spent too much, too little time, or even where you performed well

## Backend variant

* If you want, it may be more relevant to do this test only using a backend, and twig tempalate.
* This will ease the authentication process, so you may improove user experience a bit
* In that case, you shoud try to keep the search behavior that do not fully reloads the page, doing some ajax magic

## Missions

1. Fork the project
2. Make it work
3. Test if routes are working well, if they need authentication, and all
4. Setup a JWT proctected backend (according to the backend, the prerequisites can vary). You can also use sessions backends
   1. **If backend version:** Use session based security
6. Add an authentication page on the frontend that is able to store the token for further requests
   1. **If backend version:** Create authentication form
8. In an authenticated page, display user information in the header
9. **If backend version:**
   1. Implement a basic logged in interface
   2. that displays a list of 12 random non persisted beneficiaries like in the below screenshot
   3. add a random picture for each of the beneficiary randomized on the name
   4. use https://api.dicebear.com/8.x/avataaars/svg?seed={name} to generate random avatars
   5. feel free to take inspiration on any of the frontend repositories where the interface is already implemented
11. Add a search bar for Beneficiaries
   1. Bonus :  **If frontend version:**  Try with frontend search and backend search
   2. **If backend version:** Try full reload and async version
11. Add a simple button to create someone in the database with a random name
   1. Bonus : Add a form to choose the name
   2. Bonus : Persist the logged in user in database as a creator email, creation date also
   3. Bonus : Add a button to delete a beneficiary
   4. Bonus : Allow rename a beneficiary
   5. **If backend version:** Try full reload and async versions for each of these points

<img width="1267" alt="Screenshot 2024-07-05 at 10 01 19" src="https://github.com/re-connect/interview/assets/9215726/21a0496e-7477-44cb-9d5b-5ba52b31be21">
