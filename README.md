# conferencedb
Website with a list of conferences

## Getting Started

For install dependence and test your application in local server

1. cd conferencedb
2. npm install -g gulp bower && npm install && bower install
3. gulp serve


For deploy your application on firebase hosting

1. gulp
2. ONLY FIRST TIME: firebase init 
3. Chose this parameters: 
	1. Firebase Service: Only hosting
	2. Public folder: dist
	3. Rewrite all urls to Index.html: y
	4. Overwrite index.html: N
	5. Chose your project or create a new project
4. firebase deploy

