simpleJS
========

SimpleJS Frameworks


USAGE:
myPreloader = new sPreloader({

contentDiv: ‘mainContent’,  //ID of your mainContent

loaderDiv: ‘loader’, //ID of your loading DIV

excludingClass: ‘no’,  //Name of class to exclude from the preloader

logProgress: true, //log the percentage through console.log

animation: ‘fade’, //animation type: fade | none

animationSpeed: ‘1.0’ //animation speed

});

myPreloader.start();    

myPreloader.percentage; //outputs the current percentage; for progress bar use.    