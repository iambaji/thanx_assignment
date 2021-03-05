# thanx_assignment

## Building for Andorid 

1. clone this respository and in the root directory do "npm install" to install all dependecies for react native project.
2. In root directory, To install fastlane open terminal and do "gem install bundler" followed by "bundle install". it will take the Gemfile which is present 
in this repository to install fastlane.
3. in the root directory, to run the local build with fastlane type "fastlane android build"
4. to integrate with travis CI, create a new repository in github and connect the same repository to travis-ci portal.
5. change the git remote in local repo and push it to the newly created github repo. it will trigger the build in travis ci portal.

## All the necessary files are included in the project repository itself.


