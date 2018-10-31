# EatiGO Clone

This project is a pixel perfect clone of the popular EatiGO application, i built it to enhance my skills in UI/UX development and to really understand how complex
it is to develop such an application yourself. The project utilizes IONIC framework with angular js, cardova and typescript. This is still a work in progress project
and i shall be updating this project regulary to ensure that the final outcome is of high quality.

## Getting Started

Before you get started you may want to readup on IONIC framework and how it functions, basically IONIC is a framework used to make Hybrid applications, it uses basic 
syntax similar to css and html along with angualr js for the backend. IONIC is an advantageus language as it allows you t deploy the same application to multiple plaforms at once including Android, IOS and Windows. Another major advantage is that if you have an IONIC pro account you can build the application in the cloud and deploy for both IOS and Android without configuring a single line of code. Enough talk lets get to action, ensure you have followed the following steps:

1. Install NodeJS the installation file found [here](https://nodejs.org/en/download/)
2. Install Git the installation file found [here](https://git-scm.com/downloads)
3. Install IONIC using the instructions found [here](https://ionicframework.com/getting-started#cli)
4. Clone this repository and place it in your ``` C://Users/xxx/ ``` directory where xxx represents the computer user name
5. Rename the directory eatigo
6. Go to command prompt and type ``` cd eatigo ```
7. Then type, npm install and agree to any installation messages
8. then type ``` ionic serve --lab ``` , agree for installations that are prompted
9. You now will see the app served in your default web browser ready for you to make changes, every time you edit the code and save the screens will change in realtime

### Prerequisites

You would need to have some knowllege on the following to fully understand the architecture of this software

```
HTML
CSS
Angular Routing
REST API methodologies
Firebase

```

### Current Functionality

The following are some functions our application aims to solve

* Splash screen with timer
* Registration of a user linked to a Firebase database (in future will only make use of a custom REST api)
* Custom Navigation sidebar
* All data to be displayed from database by making calls to a custom api
* Automatic price rises and drops on discounted resturaunts

I am planning to make a duplicate of this existing application, so generally the scope isbased on this existing [application](https://play.google.com/store/apps/details?id=com.eatigo&hl=en)

The following are images of current Activities that have been developed to date:

![current progress](http://source2code.com/progress1.png)

## Built With

* [Ionic Framework](https://ionicframework.com/getting-started#cli) - The framework used to develop the mobile application
* [Firebase](https://firebase.google.com/?gclid=EAIaIQobChMI74fwmuTZ2wIVFiQrCh3JhgTUEAAYASAAEgJGJPD_BwE) - The Database system used 

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Daniel Goncalves** - *Initial work* 

If you have also contributed please submit the comit hash and your name so i can also add you

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* IONIC developer website for assisting in understanding certain topics
* Stackoverflow for helping in solving bugs
* Everyone who submitted any issues alerting us of bugs

