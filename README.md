# yo-k8s-template
1. Create repository to phabricator.
2. Clone repository.
3. Install yeoman `npm install -g yo`
4. Run in new repository `yo @ptcs/yo-k8s-template`
5. Commit and push changes, now CI pipeline builds project, publishes containers and deploy k8s files. After CI is complete you can navigate `https://project-name.protacon.cloud`. Project name is asked after you run yo.
