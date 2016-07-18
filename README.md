# conferencedb
Website with a list of conferences

## Getting Started

For install dependence and test your application in local server

1. cd conferencedb
2. npm install -g gulp bower && cd third\ party/ && npm install && cd .. && bower install
3. cd third\ party/
4. gulp serve


For deploy your application on firebase hosting

1. gulp
2. ONLY FIRST TIME: firebase init 
	1. Chose this parameters: 
	2. Firebase Service: Only hosting
	3. Public folder: dist
	4. Rewrite all urls to Index.html: y
	5. Overwrite index.html: N
	6. Chose your project or create a new project
3. firebase deploy

