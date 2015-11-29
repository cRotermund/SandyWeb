//This file does a simple build to bring resources from the 
//node_modules directory into the static directory and ready for serving

var fse = require('fs.extra');

fse.mkdirp('./public/bootstrap');
fse.mkdirp('./public/bootstrap/dist')
fse.copyRecursive('./node_modules/bootstrap/dist', './public/bootstrap/dist');

