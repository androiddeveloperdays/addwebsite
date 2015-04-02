Android Developers Days 2015 site. 
=============

### Live demo www.androiddeveloperdays.com

Original project you can find [here](https://github.com/gdg-x/zeppelin).

1.  Install [Node.js](www.nodejs.org) and [Ruby](https://www.ruby-lang.org/)
2.  Run `gem install bundler`
3.  Install 'grunt-cli' and 'bower' globally with `npm install -g grunt-cli bower`
4.  `$cd` to the directory and run `bundle install`
5.  Run `npm install` to install the necessary "npm" dependencies
6.  Then run `bower install` to install the front-end dependencies
7.  Install [ImageMagick](http://www.imagemagick.org/script/binary-releases.php) to resize images during building
8.  **That's all. Your template is ready**

Following commands are available:

1.  `grunt` (by default it runs `grunt serve`) - build and start your site for **development** (with livereload, js uglifing and sass compilation) 
2.  `grunt serve:dist` - build and start your site with **production** configs (this is how it will look online)
3.  `grunt deploy` - build and deploy your site into a repository you defined in previous steps

### Contributors
Created by [Oleh Zasadnyy](https://github.com/ozasadnyy), [GDG Lviv](https://plus.google.com/102444623953913144164).

### License

Project is published under the [MIT license](https://github.com/ozasadnyy/zeppelin-grunt/blob/master/LICENSE). Feel free to clone and modify repo as you want, but don't forget to add reference to authors :)
