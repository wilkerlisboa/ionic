<h1>Installing Ionic</h1>

<p>Ionic apps are created and developed primarily through the Ionic command-line utility. The Ionic CLI is the preferred method of installation, as it offers a wide range of dev tools and help options along the way. It is also the main tool through which to run the app and connect it to other services, such as Appflow.</P>

<h2>Install the Ionic CLI</h2>

<p>Before proceeding, make sure your computer has Node.js installed. See these instructions to set up an environment for Ionic.

Install the Ionic CLI with npm:</p>

	  $ npm install -g @ionic/cli  
    
<p>If there was a previous installation of the Ionic CLI, it will need to be uninstalled due to a change in package name.</p>

    $ npm uninstall -g ionic
    $ npm install -g @ionic/cli
    
<h3>Start an App</h3>

<p>Create an Ionic app using one of the pre-made app templates, or a blank one to start fresh. The three most common starters are the blank starter, tabs starter, and sidemenu starter. Get started with the ionic start command:</p>

    $ ionic start myApp tabs
    
<h4>Run the App</h4>

<p>The majority of Ionic app development can be spent right in the browser using the ionic serve command:</p>

    $ cd myApp
    $ ionic serve
   
<p>There are a number of other ways to run an app, it's recommended to start with this workflow. To develop and test apps on devices and emulators, see the </p>
