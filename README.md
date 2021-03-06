Welcome to my Github page!

My name is Chester and I am a IT technical consultant based in Singapore

- š» Iām currently working on an backend application to explore the software development cycle
- š„ Iām learning Javascript, Node.js, PostgreSQL, Docker, Automated testing, CI/CD, Cloud Services and infrastructure provisioning
- š« I can be reached at: Discord: kageneko#2670 or Email: chester91.jp@gmail.com
- š Github gists: https://gist.github.com/Kamatoro64/
- ā” Fun fact: I'm a coffee enthusiast, speak 5 languages and play the bamboo flute


Currently Researching
- Prometheus Monitoring 
- Infrastructure as code
- GitHub Actions vs Travis CI for CI/CD
- Istio service mesh
- Template engines Focus -> EJS (Others for Express: Pug, Mustache). Branch into React and Angular's built in template engine
- Template engines big picture = server side rendering vs client site rendering pros and cons
- passport.js

API-and-Firewalls tasks
- [x] Merge PostgreSQL Dockerfile directly into docker-compose.yml
- [x] Node app and PostgreSQL database should run in 2 separate containers
- [x] Test cycle should be executed correctly with docker-compose up
- [x] Implement Github Actions workflow for automated-testing branch
- [x] Fix Docker volume issue -> Each test cycle should create a new Docker volume
- [ ] Optimise test cycle timings 
- [ ] Implement front end with authentication -> passport_login

passport_login tasks
- [x] Set up ejs templates for login and register routes
- [x] Set up GET routes for login and register -> Use res.render which requires app.set('view-engine', 'ejs')  
- [x] Set up POST routes for login and register -> POST /register to push users with bcypt encrypted password into users array
- [ ] Set up authentication using passport.js - DONE but further study on passport.js is required
- [ ] Re-implement users array with a database
