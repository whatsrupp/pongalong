# Pong A Long

## Political Pong like you've never seen before.

## Contributing to this Repository:
2 Sections:
- Basic Git workflow
- Running the local server to see your changes

### Basic Workflow

#### Make sure you have node and yarn installed
ensure home brew is working
```
brew doctor
```
then install node and yarn with homebrew
```
brew install node
```
```
brew install yarn
```
#### Navigate to the directory on your computer you'd like to work from

Use `cd` and `ls` to navigate around your local folders
```
$ cd locaion/of/working/directory
```

#### Clone this repository

To get the online files onto your computer use `git clone` when you are in the right file location

```
$ git clone https://github.com/whatsrupp/pongalong
```
#### Get the latest files
Before you start working, make sure you're up to date
```
$	git pull
```

#### Ensure that all your required packages are up to date
Run yarn (which is our package manager) and it will install all relevant packages for you
```
$ yarn
```
#### Start your own branch
Create your own branch to work on
```
$ git checkout -b your-branch-name
```

#### Make commits to your own branch

Alert git to all file changes in your directory. The full-stop at the end means all files in your current directory.
```
$ git add .
```
Finalise your commit and write an explanatory message
```
$ git commit -m 'My commit message'
```

#### Push up your commits to the github repository

```
$ git push origin your-branch-name
```

#### Submit a pull request for review
On git hub follow the instructions for submitting a pull request

#### Ask If Confused
Don't suffer in silence, ask for help!

### Running the local Server

#### Stating it up
use the yarn start script to boot up the Server
```
$ yarn start
```

#### Checking it out

go to your browser and go to the url
```
http://localhost:3000/
```
