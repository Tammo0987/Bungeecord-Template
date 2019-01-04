# Workspace Setup

You can use this template to develop your own BungeeCord plugins with [Gradle](https://gradle.org/).

## Setup Template

> **Note** This setup is actual only for IntelliJ

+ Creating a new project from VCS in IntelliJ and clone this repository.
+ Import the project with gradle.
+ Then execute the **Setup BungeeCord Proxy** run configuration and the template will download the proxy jar file.

Then you can start coding :)

## Deploy Task

You can export your plugin to the plugins directory from your working directory with the **Deploy** run configuration. The task will **build and copy** your plugin **automatically**.

## Debugging the Server

You can use and debug the installed test proxy by running the **Bungeecord** run configuration. Every time you start the server, the plugin will be deployed. You can disable it, when you edit the Server run configuration.