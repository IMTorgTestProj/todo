#  JavaScriptMVC Todo Application (variation)

##Getting Started

JMVC is broken down into 4 separate projects that can be used independently of each other. These are:
<ul>
	<li><b>jQueryMVC</b> - MVC extensions for jQuery</li>
	<li><b>StealJS</b> - Dependency management, build process, code generators</li>
	<li><b>FuncUnit</b> - A web testing framework</li>
	<li><b>DocumentJS</b> - A JavaScript documentation framework</li>
</ul>


###Setup

To get started with the Todo application, first clone the Todo repo to a local directory as follows:

<pre>
git clone git@github.com:addyosmani/todo.git	
</pre>

You'll then need to add a few project dependancies to your todo project directory. You have two options for how to achieve this, either using *submodules* to checkout the submodules as their own repositories (recommended) or alternatively by cloning their repos locally.

###Submodules
<pre>
git submodule add git://github.com/jupiterjs/steal.git steal
git submodule add git://github.com/jupiterjs/jquerymx.git jquery
git submodule add git://github.com/jupiterjs/funcunit.git funcunit
git submodule add git://github.com/jupiterjs/documentjs.git documentjs
</pre>

###Cloning

Cloning repositories using GitHub is a fairly straight-forward process and the todo application just requires the following commands to be executed to get you setup:

<pre>
git clone git://github.com/jupiterjs/steal.git
git clone git://github.com/jupiterjs/jquerymx.git
git clone git://github.com/jupiterjs/funcunit.git
git clone git://github.com/jupiterjs/documentjs.git
</pre>

###Structure

In order to correctly build the todo application, you'll need to ensure that you have the following directory structure, unless you decide to change the build files in the todo/scripts directory:

<pre>
funcunit
jquery
steal
todo
	todo
		index.html, todo.js etc.
		scripts
		test
</pre>

Note that as per JupiterIT's original Todo application, jquerymx is actually stored in the directory called jquery in case we decide to sync up any changes made to the codebase.