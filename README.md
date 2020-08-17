# webee-test
This is a repo that gathers the Back and Front end aplications of the Webee challenge that is part of the interviewing process.
In order to test/run the project you will need:
* Linux Debian/Ubuntu
* [NodeJS 10](https://github.com/LautaroJayat/webee_test_backend/runs/995400930?check_suite_focus=true) or [Node 12](https://github.com/LautaroJayat/webee_test_backend/runs/995400944?check_suite_focus=true) for the backend (Click on the links to see the tests)
* MongoDB v4.2
* Angular CLI
* Chrome/Firefox/Brave as browsers

## Instructions 
In Order to run this project I recommend to recursively clone the repo using the following command
```bash
git clone --recursive  https://github.com/LautaroJayat/webee-test.git
```
* For more information about the front-end repo you can see https://github.com/LautaroJayat/webee_test_front_end
* For more information about the back-end repo you can see https://github.com/LautaroJayat/webee_test_backend

### Backend
* Open a terminal in the backend folder and run `yarn` or `npm install` in order to install all the dependencies.
* Check the `dev.test` file and see if that DB URL is safe for you tu use in your local enviroment (we dont want to ruin an existing DB)
* Run **`yarn start:dev`**
* If you want to run the provided tests, check if the DB URL provided in `test.env`is safe for you to use. Then run `yan test`. It will run all tests inside the tests folders.

### Front End
* Go to the Front-end folder and open a terminal there.
* Run **`yarn`** or **`npm install`** to add all the needed dependencies.
* After that, run **`ng serve --open`**, this will start the project in your development enviroment. Make sure that you also started your backend using `yarn start:dev`
* You will need to create a user and then you can log-in.
* After that you will be able to create sensors using the FAB button on the upper right corner, make events, and much more!

## Snapshots
### Login Screen
![login screen](https://github.com/LautaroJayat/webee_test_front_end/blob/master/readme-img/login.jpg)
---
---
### Sign In Screen
![sign in screen](https://github.com/LautaroJayat/webee_test_front_end/blob/master/readme-img/sign-in.jpg)
---
---
### Sensor List Panel
![Sensor list panel](https://github.com/LautaroJayat/webee_test_front_end/blob/master/readme-img/sensors-list.jpg)
---
---
### Registering a Sensor
![Sensor form](https://github.com/LautaroJayat/webee_test_front_end/blob/master/readme-img/register-sensor.jpg)
---
---
### SnackBars for the errors
![Register error](https://github.com/LautaroJayat/webee_test_front_end/blob/master/readme-img/register-errors.jpg)
---
---
### Updating a Sensor
![Update sensor](https://github.com/LautaroJayat/webee_test_front_end/blob/master/readme-img/update-sensor.jpg)
---
---
### Deleting a Sensor
![delete sensor prompt](https://github.com/LautaroJayat/webee_test_front_end/blob/master/readme-img/delete-sensor.jpg)
---
---
### Events List
![event lists](https://github.com/LautaroJayat/webee_test_front_end/blob/master/readme-img/event-list.jpg)
---
---
### Update an Event
![Update Event](https://github.com/LautaroJayat/webee_test_front_end/blob/master/readme-img/update-event.jpg)

