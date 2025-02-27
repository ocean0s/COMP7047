# Gym App
[![MongoDB][mongo-img]][mongo][![NodeJS][node-img]][node][![EJS][ejs-img]][ejs]
 
 [ejs]: https://ejs.co/
 [ejs-img]: https://img.shields.io/badge/ejs-%23B4CA65.svg?style=for-the-badge&logo=ejs&logoColor=black
[node]: https://nodejs.org
[node-img]: https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white
[mongo-img]: https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white
[mongo]: https://www.mongodb.com

Gym App is a gym reservation management app, for booking and organization, created for gym owners. 

## Installation

To get a local copy of the project just clone the repository and follow the next steps.

### Prerequisites

- A MongoDB server must be running in the system for the document database initialization. `mongoose` library is used for this purpose.
- Install all dependencies listed in `package.json` before attempting to run any type of build:
```
npm install
```
### Running the app
To run a local instance of the app use:
```
node bin/www
```
To deploy this application into a production server take a look at some of the providers listed below, or use any other option. We do not provide any specific version of the software tailored for any specific server instance or provider.
 - [AWS](https://aws.amazon.com)
 - [Azure](https://azure.microsoft.com)
 - [Oracle](https://www.oracle.com/cloud/)

## Usage

Connect to the URL hosting the app and navigate through the different menu options in the top bar. You will be prompted to register or login if you haven't already done so. This is by design.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

Please make sure any sensitive information is not pushed to GitHub, such as API keys or mock data containing real information. 

Please, update the README.md file accordingly to the introduced changes and features. Do not forget to increase the version numbers too.

If you have any question or would like some input on any topic regarding the project, do not hesitate in opening an issue for other contributors to discuss it.

## License

[MIT](https://choosealicense.com/licenses/mit/)
