#Introduction

This is more like a **backup** for our mission critical Jenkins server. 

For the next time you need to update Jenkins settings, you can just update it in your box which means more efficient and secure.

*Setup local Jenkin for iOS*
    
	brew install jenkins
	git clone git@github.com:waveface/Jenkins.git ~/.jenkins
	java -jar /usr/local/Cellar/jenkins/1.447/lib/jenkins.war

*Windows*

	TODO windows instructions HERE

Reference [Administering Jenkins](https://wiki.jenkins-ci.org/display/JENKINS/Administering+Jenkins).
Inspired by [homebrew](http://mxcl.github.com/homebrew/). 

#References

##To Setup Jenkins for iOS
http://lifeandcode.net/2011/12/automated-ios-jenkins-builds-with-application-tests-and-core-data/
http://www.infinite-loop.dk/blog/2012/02/code-coverage-and-fopen-unix2003-problems/

##Coverage for iOS
http://www.infinite-loop.dk/blog/2011/12/code-coverage-with-xcode-4-2/
http://hamishrickerby.com/2012/04/05/unit-test-code-coverage-with-xcode-4-dot-3-2/