# Pre-requisites

- Install [https://nodejs.org/en/download/](NodeJS) (My preference is to install and use [https://community.chocolatey.org/packages/nvm](NVM))
- Install Google Chrome

# Setup

1. Copy the .bashrc file in this folder to `C:\Users\[user.account]`
2. Open the env file and set the correct path to your aws credential file.
3. In your terminal execute: `npm run build`
4. Then: `npm start` (This starts the node api. If you want to stop it you can run `npm stop`)
5. Open your Chrome browser and navigate to [chrome://extensions/](chrome://extensions/)
6. On the top right of your screen toggle on "Developer mode".
7. On the top left of your screen click the "Load unpacked" button and navigate to/select the `AwsCredentialsExtension` sub folder in this project.
8. You should now see the "Aws Credentials Extension under your extensions in Chrome. Feel free to pin it to your task bar.
9. Navigate to [https://d-90677c91b4.awsapps.com/start#/](https://d-90677c91b4.awsapps.com/start#/), open the extension and click the "Refresh AWS Credentials" button. That's it!
