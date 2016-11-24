# angularjs2-with-typescript-quickstart

Install project:

1. Install latest stable version of NodeJS:

Check the current version you have:

node -v
The following clears your cache.

sudo npm cache clean -f
Install n

sudo npm install -g n
You can tell it to install a specific version like so:

sudo n 0.8.11
Or just tell it to install the latest stable version. Both may take a while.

sudo n stable
To see if it actually upgraded, run:

node -v


2. Install latest stable version of NPM ( sudo npm install npm -g )

3. Install TypeScript ( sudo npm install -g typescript )

4. Clone project files

5. Run: sudo npm install

6. Install AngularJS 2 in our project (sudo npm install --save @angular/core @angular/compiler @angular/common @angular/platform-browser  @angular/platform-browser-dynamic rxjs@5.0.0-beta.6 zone.js@0.6.12)

7. Install Typings:

a) sudo npm install -D typings
b) sudo ./node_modules/.bin/typings init
c) sudo ./node_modules/.bin/typings install --ambient es6-shim

8. Run: sudo npm start

9. Access the project at: http://localhost:3000/ 
<br/><br/>

Author: Eusebiu Schipor
