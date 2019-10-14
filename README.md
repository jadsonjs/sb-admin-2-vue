# sb-admin-2-vue
   A vue.js project with sb-admin-2 bootstrap template.


SB Admin 2 Vue is an **Vue** front-end application based on [SB Admin 2](https://startbootstrap.com/template-overviews/sb-admin-2/) Bootstrap template 


![Screenshot](https://github.com/jadsonjs/sb-admin-2-vue/blob/master/sb-admin-2.png)


<p align="center">
  <strong>
      <a href="https://blackrockdigital.github.io/startbootstrap-sb-admin-2/pages/index.html" target="_blank">View HTML Demo Version of Original SB Admin 2</a>
  </strong>
</p>


This project has no communication with back-end, it is just a generic font-end project to be adapted to a full project.


**Version 1.0.0**


	The project structure:
	
```
├── src/                                      # root folder of the projects
|   ├── assets/                               # third-party static js and css files                       
|   ├── components/                           # Vue.js components
|   |   └── ...       
|   ├── router/                               
|   |   └── index.js /                        # Vue.js router file
|   └── main.js                               
|   └── App.vue                               # Vue main component 
├── static/
|   ├── sbadmin/                              # original boostrap project
```




## 1.Introduction

This project was generated with [Vue CLI](https://cli.vuejs.org/) version 2.9.6.


## 2.Getting Started

```
git clone https://github.com/jadsonjs/sb-admin-2-vue.git
```

## 3. Install Node.js and Vue-CLI

You first need to install [NodeJs](https://nodejs.org/en/) thats include npm. 

After install node.js, you need to install Vue CLI:

```
npm install -g @vue/cli (vue cli 3)

```

## 4. Build the project

```
cd sb-admin-2-vue
npm install
npm run dev
```

Open the web brower in http://localhost:8080


## 5. Build for production

```
npm run build
```

This command will generate a *_"dist"_* folder.

Serve it on some HTTP server like Node.js static file server, apache, tomcat or PM2.

See https://cli.vuejs.org/guide/deployment.html#general-guidelines

You can also rename the "dist" folder to the your "app name".
In this case, you will need to change the public path to your "app name" in config/index.js

https://stackoverflow.com/questions/48578498/vue-webpack-build-show-blank-page




