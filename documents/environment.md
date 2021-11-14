## Environment

### Installation MacOS

#### XCode

1. Install `XCode` using `App Store`
2. Open `XCode` at least once to confirm and agree with certificates.

#### MacOS installation helper
1. Install `Homebrew` using this [turtorial](https://brew.sh/)
2. Restart `Terminal`

#### Git
Install `git` using this command: 
```
brew install git
```
After the git has been installed we need to register generate and register private/public key in the repository in order to get access to the actual code.

For the generation of keys the following [turtorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) should be finished.
The public key should be registered inside of a repo.

To clone the repo you need to run the following commands using `Terminal`
```
mkdir Dev/startup
```
```
cd Dev/startup/
```
```
git clone git@github.com:Samusiel/core-engine.git
```
At this point, if all of the steps have been finished properly: the `core-engine` repo will appear in the folder.

#### Further installation
In order to have all libs and dependencies in sync the script `install.sh` should be called by using the command:
```
./scripts/install.sh
```
Note, that `./` means the current folder you're in. In our cause you need to be inside of `core-engine`.

The script will install all apps needed for development, as well as register all environment variables in the system.