# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full stack open course

Fork the repository to complete course exercises

## Commands

Start by running `npm install` inside the project folder

`npm start` to run the webpack dev server
`npm test` to run tests
`npm run eslint` to run eslint
`npm run build` to make a production build
`npm run start-prod` to run your production build


## 11.1 warming up

Well, I chose C++, or cpp, as the programming language for my project.

### a)
One C++ linter is clang-tidy. It's a clang-based? linter tool. It provides a framework diagnosing and fixing typical programming errors.

I also "chose" Cathch2 for unit testing. It also provides benchmarking and BDD (
Behavior-driven development). Another reasonable choice could be API Sanity Checker which generates automatically reasonable arguments for APIs. It can be used for smoke testing.

For building a C++ project, I would maybe choose SCons. Maybe because we are dwelving in some area that I am very unfamiliar with. It is an OS software construction tool. It seems to have somewhat many benefits when using C++.

### b)
One alternative is CruiseControl. It is used for both CI and continuous build processes. It has an extensive wiki, which could prove to be beneficial. But, its latest release is from 2010. Another one is Eclipse Hudson though its latest release is from 2016. Hudson is a CI tool written in Java. It runs in a servlet container. A more modern option could be the choice here. The internet seems to say that Jenkins would be the option, actually.

### c)
This setup would probably be cloud-based as CruiseControl is a CI server. To make this decision I would need to whether these frameworkds I have discussed are self-hosted, or cloud-based. 
