# CODE.NOW!

<p align="center">
  <img src="https://github.com/AccentureChallenge/Code.Now/blob/master/frontend/src/assets/acnCodeNowHeader.png">
</p>

Are you ready to make an impact? Then join our Accenture Code.Now challenge!​

Air pollution is an important topic and will influence the quality of our future. As the hazards of air pollution remain invisible without air quality data, AirPoll as a young, international startup, has developed and placed air quality monitors all over the world in order to provide the largest air quality database. ​

​You have been hired by the company as a full stack developer to build an air quality app which makes it possible for everyone to check the air quality in their cities. Are you up for the challenge?​

Among all correct submitted codes we will raffle three Oculus Quests! This is a full stack developer challenge which consists of a frontend and a backend development part. Clone the according repository and solve the challenge. To submit you will have to push your work to your own GitHub account and make sure your repository is public. All we need is the link to your repository until 10.01.2020.​

Let`s make an impact together! We are looking forward to your solutions!​

## Use case - AirPoll App

### Background

AirPoll is a young, international startup which is aware of the fact, that the hazards of air pollution will remain invisible without air quality data. AirPoll has developed and placed air quality monitors all over the world in order to provide the largest air quality database.

You have been hired by the company as a fullstack developer to build an air quality app that makes it possible for everyone to check the air quality in their cities.

### Your Tasks

#### In the Frontend:

The client wants you to build a web application to display the air quality index and other relevant properties for countries, its cities and its locations.
The frontend should be user friendly and fulfill the following requirements;

- Responsive UI, ensuring adaptive viewport for mobile devices and PC/laptop
- Clean and modern design
- The following attributes need to be displayed in the order given:
  - the `location` name
  - the `city` and `country` name
  - the `air pollution` value and its `measurement unit` and `particulate matter` parameter
  - the location's `longitude` and `latitude` value
  - the `local date and time` value
- The list must support infinite scrolling and should be sortable by each attribute(ASC and DESC)

Additionally, the client demands a solution capable of filtering the data by;
- one country
- one city

The project will soon scale and more developers will support you on feature development. Therefore, clean code principles, appropriate test coverage and code documentation are key factors and highly valued.

#### In the Backend:

The design and implementation of the backend component is part of your responsibility. The air quality data for the web app is provided by the [Open AQ Platform API](https://openaq.org/#/?_k=bgfemx).
Following featuers need to be considered;

- Fetch data from AQ public API
- Insert data into a database
- Build a webservice to serve the frontend

## Setup

Download and unzip the source repository or clone it using Git.

### Frontend

#### What you need

- A favorite text editor or IDE
- [Node.js 12.16.2](https://nodejs.org/en/download/) or later which includes npm (Node Package Manager)
- Install the [Angular CLI](https://angular.io/guide/setup-local) via npm in your terminal: `npm install -g @angular/cli`

#### How to run the frontend application

- Once checked out, navigate to the `frontend` folder
- In the terminal, run `npm install` to download all dependencies
- To run the application, execute the command `ng serve` (development mode)
- Navigate to `http://localhost:4200/` in your browser to view the application

## Submission

- After you completed the challenge, upload it to your github page and make it public (so our team can review it)
- Use our [npm plugin](https://www.npmjs.com/package/acn-code-now) to submit your work

## Copyright and License

Copyright (c) 2020 Accenture AG

Code released under the MIT License.
