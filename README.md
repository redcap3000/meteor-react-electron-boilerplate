#meteor-react-electron-boilerplate
![meteor react screenshot macosx](https://raw.githubusercontent.com/redcap3000/meteor-react-electron-boilerplate/master/meteor-react-screenshot.png)
Based on the simple 'mr-kanban' project this includes support for electron to create desktop applications.

Designed to allow for relatively easy prototyping. It initally makes use of package meteor-electron(https://github.com/electron-webapps/meteor-electron). But ultimately using something like Electrify (https://github.com/arboleya/electrify) to make the end-executable.

So I am maintaining this repository to act as a starting point for a desktop-react based project.

##Quickstart
All commands from meteor project directory*

```
meteor npm install
```

**meson:electron**
```
meteor
```

**electrify**

```
sudo npm install -g electrify
electrify
```

##What this includes

|------|----------------------------|
|.gitignore | ignores the most of the common things you don't want in your repo. Including .DS_Store and various hidden folders.|
|Meteor| v.1.4.2.3|
|Meteor Packages| meteor-react-data,meson:electron |
|Npm Packages| meteor-node-stubs,react,react-addons-pure-render-mixin,react-dom|

## meson:electron vs npm electrify

*meson:electron* is a easy to use meteor module. *electrify* is an easy to use npm package that can only build for the platforms its running on. The build process for meson:electron is kind of complex and seems to be dependent on a server to upload the application via internet. YMV.

## future plans

Make this but with google's material design.