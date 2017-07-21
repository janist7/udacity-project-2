# Portfolio page

## Description

This site is a portfolio page containing links to all my future work.
The real project is located elswehere - https://github.com/janist7/udacity-movie-site-development, this reposatory contains just the generated content from all templates and sass partials.

### Prerequisites

For usage on a local enviroment requires [jekyll](https://jekyllrb.com/).
Then navigate to project file location and run ```jekyll serve```
Page should be accesible at - http://localhost:4000.

## Instalation and usage

The jekyll code can be acessed here - [https://github.com/janist7/udacity-movie-site-development](https://github.com/janist7/udacity-movie-site-development)
Webpage here - [https://janist7.github.io/udacity-project-2/](https://janist7.github.io/udacity-project-2/) ( uses generated content that is in _site )
For use locally in _config.yml - baseurl needs to be set to "/" and url to
http://localhost:4000 so that links work.
Url needs to be changed in _variables.scss for jumbotron image.

## File structure

Has folowing main folders for this [https://github.com/janist7/udacity-movie-site-development](https://github.com/janist7/udacity-movie-site-development):

* **_includes** - *Contains all svg and html includes for layouts.*
* **_layouts** - *Contains html layouts for pages.*
* **_portfolio** - *Contains pages to projects, is a seperate page with possibility to add description of a project.*
* **_posts** - *Not used yet.*
* **_sass** - *Contains all scss partials.*
* **_site** - *Contains jekyll generated site files, updated after each "jekyll serve"*
* **_pages** - *Contains rest of possible pages, for now only the default about and the readme.md file.*
* **css** *Contains generated plain css file.*
* **js** *Contains site specific and vendor js.*
* **img** *Contains regular image files used in this page.*
* **python** *Not used yet.*

And generates folder structure accordingly, which is used by this github page.

To generate FP content index.html is used.

## Built With

Project generated using [jekyll](https://jekyllrb.com/)

## Future plans

Integrate multiple projects into this page.

## Authors

* **Jānis Tidriķis** - *Initial work*

## License

This project is licensed under the GPLv3 License - see the [LICENSE.md](https://github.com/janist7/udacity-movie-site/blob/master/LICENSE) file for details

## Acknowledgments and Thanks

Thanks to Billie Thompson for providing a nice readme [template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
