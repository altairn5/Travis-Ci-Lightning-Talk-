
# Travis CI (WDI-21 Lightning Talk)

This repository is a basic introduction to Travis – CI’s testing platform.

#### Continuous Integration (CI)
is a development practice that requires developers to integrate code into a shared repository several times a day. Each check-in is then verified by an automated build, allowing teams to detect problems early.)


### What is Travis CI?


 * Travis CI is a hosted continuous integration platform, which is free for 	public repositories. 
 
### What is Travis CI good for?
 
 * Good for running tests before [deployment to Heroku](http://docs.travis-ci.com/user/deployment/heroku/)
 * Good for working on collaborative projects because of its automated builds 

 ### Documentation
 Follow the links below for  Ruby and Javascript specific documentation. [Other programming languages are also supported.](http://docs.travis-ci.com/user/getting-started/)
 ![alt tag](https://github.com/altairn5/Travis-Ci-Lightning-Talk-/blob/master/trv1.png)
 
 * [Ruby](http://docs.travis-ci.com/user/languages/ruby/) Documentation
 * [Javascript](http://docs.travis-ci.com/user/languages/javascript-with-nodejs/) Documentation (Node.js)
 * [Travis-CI's GitHub](https://github.com/travis-ci/travis-ci) Repositories

### Steps

#### Overview (Detailed steps below)
![alt tag](https://github.com/altairn5/Travis-Ci-Lightning-Talk-/blob/master/trv2.png)

###### 1) Access [Travis CI](https://travis-ci.org/auth) using your GitHub account.
![alt tag](https://github.com/altairn5/Travis-Ci-Lightning-Talk-/blob/master/step%201.0.png)

###### 2) Go to the root of your repository, and create a file name ".travis.yml"
![alt tag](https://github.com/altairn5/Travis-Ci-Lightning-Talk-/blob/master/step%201.1.png)

###### 3) Inside the ".travis.yml" file, specify the programming language used in your project. Also, specify the version that you want Travis CI to test your project against. For more details, see [Travis CI Documentation](http://docs.travis-ci.com/)
![alt tag](https://github.com/altairn5/Travis-Ci-Lightning-Talk-/blob/master/step%201.2.png)

###### 4) After creating the ".travis.yml" file,
* git add	
* git commit
* git push
![alt tag](https://github.com/altairn5/Travis-Ci-Lightning-Talk-/blob/master/step%201.3.png)

###### 5) In your Travis CI profile page, click "+" next to the "My Repositories" link
![alt tag](https://github.com/altairn5/Travis-Ci-Lightning-Talk-/blob/master/step%201.4.png)

###### 6) Enable access to the desired repo
![alt tag](https://github.com/altairn5/Travis-Ci-Lightning-Talk-/blob/master/step%203.png)

###### 7) Now click on the Travis CI link to be redirected to the testing page.
![alt tag](https://github.com/altairn5/Travis-Ci-Lightning-Talk-/blob/master/step%204.png)

###### 8) Refresh if necessary to initiate the build
![alt tag](https://github.com/altairn5/Travis-Ci-Lightning-Talk-/blob/master/step%205.png)

###### 9) If the build fails, you will be able to see reason(s).
![alt tag](https://github.com/altairn5/Travis-Ci-Lightning-Talk-/blob/master/step%206.png)



