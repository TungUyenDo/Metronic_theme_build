#THE STEP FOR BUILD Metronic source - by TungUyenDo

<!-- Download the latest theme source from the ThemeForest. -->

<!-- Download and install Node.js from nodejs.org/en/download/ -->

<!-- Start command prompt window or terminal and change directory to -->
#[root]/theme/default/tools/ -->

#cd [root]/theme/default/tools

<!-- Install the latest version of npm. -->
#npm install --global npm@latest

<!-- Install the latest version of yarn. -->
#npm install --global yarn

<!-- Install gulp. -->
#npm install --global gulp-cli

<!-- Install yarn dependencies. Must execute in [root]/theme/default/tools/ folder. -->
#yarn

<!-- Compile the edited assets (sass and js source files) -->
#gulp

<!-- For more information about the Build Tools, click here. -->
<!----------------------------------------------------------------------------------------------------------->
<!-- This is an optional gulp task for demo purpose. It does set all the demo backend URL to point to demo API in server. -->
#gulp apiurl
<!-- For more information about the Build Tools, click here. -->

<!-- Watch the edited assets files (sass and js source files) -->
#gulp watch
<!-- Watcher tracks changes to the files and automatically runs the compiler. -->

<!-- Watch the edited sass files -->
#gulp watch:scss
<!-- Run the watcher for the SASS files only. -->

<!-- Watch the edited js files -->
#gulp watch:js
<!-- Run the watcher for the JS files only. -->