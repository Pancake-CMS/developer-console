# Developer Console

The developer console for the Pancake project. This is an independent web app that lets user access development related features for the Pancake Content Management System

| Just a warning |
|----------------|
| The project is still under development. I would say it is **65% complete**. And it does not create any sort of static pages as of now. Please feel free to look at it and provide your suggestions, but this project is not something that can be used as of now. |

## Installation

### Setting Up Firebase

- Go to Firebase console, and create a new project.
- Go to **Settings** > **General** > **Your apps**  and grab the config keys from **Add Firebase to your web app** button. __You will need them in `development-console.html` file after you fork the project.
- Go to **Authentication** > **Sign In Methods** and enable **Github**, **Google** or **Email**
- Go to **Users** and **Add Users** as in who will be using the CMS

Now your firebase setup is complete

### Running the CMS

- Fork this project and clone it on your machine.
- Make sure **node** is installed.
- Install **bower**
- run `bower install` from the root directory of this project.
- If during the installation of bower packages, bower asks what version of firbase to use, select the one that says `0.9.4`. The other versions fail to get data from firebase. `¯\_(ツ)_/¯`
- Open **index.html** in a browser.