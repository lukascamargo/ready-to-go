# Ready to Code NodeJS Backend

## About

This is a repository to facilitate software development. If you have an project idea or anything you may use this project instead of creating the whole NodeJS, Express and MongoDB configuration from zero. 

In the future we may use NPM to install this project, change its name and change its git url. 

## Installation 

To use this ready-to-go setup you should clone the project and then change the git url to what your project is going to use. 

## Running

Hey there.

To implement this backend service you should create a file named .env with the following variables:

```env
PORT=
DB_URI=
APP=
```

Where PORT is the port where the backend will run, DB_URI is the mongodb database URI and the APP is the application address.

Then, you should build the application before running it. To build the application you should have installed typescript globally.

```bash
tsc
```

You are ready to go.

```bash
npm run prod
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


