#  JavaScriptMVC Todo Application (variation)

##Getting Started

JMVC is broken down into 4 separate projects that can be used independently of each other. These are:
<ul>
	<li><b>jQueryMVC</b> - MVC extensions for jQuery</li>
	<li><b>StealJS</b> - Dependency management, build process, code generators</li>
	<li><b>FuncUnit</b> - A web testing framework</li>
	<li><b>DocumentJS</b> - A JavaScript documentation framework</li>
</ul>

To get started with the Todo application, you'll first need to add a few project dependancies to your todo project directory. You have two options for how to achieve this, either using *submodules* to checkout the submodules as their own repositories (recommended) or alternatively by cloning their repos locally.

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

