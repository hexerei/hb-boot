# HTML5 Bootstrap boilerplate for Harp

This boilerplate is based on the *HTML5 Bootstrap* boilerplate from [initializr](http://www.initializr.com) with a little update. This boilerplate also includes the current [Bootstrap](http://v4-alpha.getbootstrap.com) *4.0 Alpha*, which is now based on [Sass](http://sass-lang.com). Also this boilerplate contains the source of Bootstrap, which enables you to modify or use variables of Bootstrap in your own style.

**This boilerplate allows you to quickly start your own project without any hassle in 5 simple steps.**

## Step 1: Install Harp

[Harp](http://harpjs.com/) provides you with a local server to run and customize this boilerplate. If you do not have Harp installed yet, you can install it with following commands.

### Install Harp on Linux and Mac OS X

On Linux, Unix or Mac OS X you will need to start the Terminal application to run the following command:

```
$ sudo -H npm install harp -g
```

### Install Harp on Windows

On Windows, NodeJS will have come with the npm application. So start the command prompt and type:

```
> npm install harp -g
```

*Visit the [Harp QuickStart](http://harpjs.com/docs/quick-start) documentation for a more detailed description.*

## Step 2: Create your project

Now that we have harp installed, we can use it, to create the boilerplate template for your own project.

```
$ harp init myproject -b hb-boot
```

This will create a subdirectory ```myproject``` in the current directory and copy all files from this boilerplate template into your project directory. From this point on, you can start working on your own start page, modifiying the index.html file in the ```public``` subdirectory.

## Step 3: Start serving your project

Now Harp comes with its main magic: starting a local server to run and customize this boilerplate. 
Again start the Terminal application, or your command prompt, to run the following command:

```
$ harp server myproject
```

This will start serving your project as a local server wich will run on port 9000 by default. You will not have to publish your files beforehand. Neither will you have to compile your *.scss files. Harp takes care of this and renders your project as pure HTML, CSS and Javascript.

*Visit the [Harp server](http://harpjs.com/docs/environment/server) documentation site to learn about other options.*

## Step 4: View your project in your browser(s)

Open [localhost:9000](http://localhost:9000) in your browser to view the precompiled result of your template. Keep on modifying your project until it suits your needs. You can open the URL with any browser installed on your computer to see the effects for different browsers. And play with the size of your browser window to see responsiveness. 

## Step 5: Compile your project

Export your project to flat static assets – HTML/CSS/JavaScript - that can be published on your live server.
Again start the Terminal application, or your command prompt, to run the following command:

```
$ harp compile myproject
```

Now you will find a directory called ```www``` which will contain your final files that you can publish on your webserver via ssh or ftp connection.

###Enjoy your project! 

Daniel Vorhauer  
[hexerei software creations](http://www.hexerei-software.de)

My grateful thanks goes to the developers of:

 - [Bootstrap 4a](http://v4-alpha.getbootstrap.com)
 - [Harp](http://harpjs.com)
 - [initializr](http://www.initializr.com)
 - [node.js](https://nodejs.org)
 - [Sass](http://sass-lang.com)
 - and all other sources that are used

