# DevFest Veneto 2018 Website

### About
This is the repository of the website of the [DevFest Veneto 2018](https://gdg-venezia.github.io/devfest-veneto-18/). This site is based on Project Zeppelin, that allows you to setup awesome GDG DevFest site in 5 minutes.

You can find more information about this template on [the official repo](https://github.com/gdg-x/zeppelin)

## Local development

Check if you have [all requirements for local environment](http://jekyllrb.com/docs/installation/).
To install all development dependencies install [Bundler](http://bundler.io/).
```bash
    gem install bundler
```
and run next command from root folder:

```bash
  bundle install
```  

To start Jekyll run:
```bash
    bundle exec jekyll serve -w
```
Site will be available at http://127.0.0.1:4000/zeppelin/ or http://localhost:4000/zeppelin/ (on Windows)

**NOTE:** in this mode all changes to html and data files will be automatically regenerated, but after changing ```_config.yml``` you have to restart server.

### License
Project is published under the [MIT license](https://github.com/gdg-x/zeppelin/blob/master/LICENSE.txt). Feel free to clone and modify repo as you want, but don't forget to add reference to authors :)
