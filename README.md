# OMCSS

OMCSS (Organisable and Maintainable CSS) is an approach towards creating a scalable and modular architecture for your CSS that you can expand and maintain with ease.

## Getting Started

OMCSS provides a bootstrap framework that will help you get started with your application's stylesheet. You can download OMCSS framework from the below options available:

* [Download OMCSS framework](https://github.com/alimansoor/omcss/archive/master.zip)
* Clone the repo: `git clone https://github.com/alimansoor/omcss.git`
* Install with npm: `npm install omcss`

### Prerequisites

[Sass](https://sass-lang.com) compiler is a must to compile individual files into your application stylesheet.

Please visit [https://sass-lang.com/install](https://sass-lang.com/install) to setup Sass based on your environment i.e. Linux, Windows, Mac OS X.

### File Structure

```
omcss/
├── base/
│   ├── _grid.scss
│   ├── _reset.scss
│   └── _typography.scss
│   
├── layout/
│   ├── _header.scss
│   ├── _footer.scss
│   ├── _sidebar.scss
│   └── _form.scss
│   
├── modules/
│   ├── _brand.scss
│   ├── _breadcrumb.scss
│   ├── _card.scss
│   ├── _carousel.scss
│   └── _modal.scss│
│   
├── pages/
│   ├── _home.scss
│   ├── _about.scss
│   └── _contact.scss
│   
├── themes/
│   ├── _default.scss
│   └── _dashboard.scss
│   
├── utils/
│   ├── _config.scss
│   ├── _extends.scss
│   ├── _functions.scss
│   ├── _helpers.scss
│   ├── _mixins.scss
│   └── _variables.scss
│   
├── vendors/
│   ├── _jquery-ui.scss
│   └── _bootstrap.scss
│   
├── shame/
│   └── _shame.scss
│   
└── application.scss

```

### Installation

OMCSS provides a file structure that your can place in your application's source stylesheet directory and make use of it.

```
application/
├── css/
│   ├── omcss/
│   └── application.css
│
├── js/
│
├── img/
│   
└── index.html
```

## Deployment

You need to run sass compiler to compile individual scss files into your application into  main stylesheet:

```
sass css/omcss/application.scss css/application.css
```

an alternative example would be:

```
sass source/stylesheets/omcss/application.scss build/stylesheets/application.css
```

## Documentation

OMCSS is an approach that will help designers and developers write code that will be future-clean and scalable at the same time. OMCSS' file structure helps developer organise their stylesheets in a manner that produces understandable and clean css structure that is easy to organise and maintain - OMCSS

### OMCSS File Structure

OMCSS is a modular approach that helps you arrange your css into `theme`, `pages`, `layouts` and `modules`. Along with these, it also provide helper folders i.e. `base`, `utils` and `vendors` to organise your helper css files.

Below is a complete description of OMCSS file structure:

* **Base**
Base contains css styles on base content such as reset, grid, typography etc.

* **Themes**
Themes contains css styles for your application themes such as primary, secondary, default, dashboard etc.

* **Pages**
Pages contains css styles for your individual pages such as home, about-us, contact etc.

* **Layouts**
Layouts contains css style for main application components such as header, footer, sidebar etc.  

* **Modules**
Modules contains css style for re-usable application ui components such as carousel, navigation, breadcrumb, card etc.

* **Utils**
Modules contains utility styles such as mixins, functions, variables etc.

* **Vendors**
Vendor contains third-party css libraries and frameworks such as jquery-ui, bootstrap, foundation etc.

* **Shame**
Shame contains css styles that you are shame about or you have written as an urgent request and will soon change it and write proper code. Its wise to write messy css for any of the above styles over here.

### Naming Convention

OMCSS follows Kebab case naming convention in its core e.g. `.txt-white`, `.nav-item` etc.

For components that contains sub-classes, OMCSS encourages `_underscore` naming convention which add an underscore as it goes within the tree:

```
.parent {
  ._child {
    .__sub-child {
      ...
    }
  }
}
```

Please note that above convention is not mandatory. It will facilitate developers to write consistent and future-proof code. However you are free to use any convention of your choice.

## Contributing

Please read [CONTRIBUTING.md](https://github.com/alimansoor/omcss/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Creator

**Muhammad Ali Mansoor**

- <https://www.linkedin.com/in/muhammad-mansoor-70857239/>
- <https://github.com/alimansoor>

### Special Contributions

**Ruchi Singhal**

- <https://www.linkedin.com/in/ruchi-singhal>
- <https://github.com/ruchi-singhal>

**Santanu Satapathy**

- <https://www.linkedin.com/in/santanu-satapathy-san-7175234/>
- <https://github.com/sansata>


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* SMACSS, OOCSS, BEM
* Twitter Bootstrap, Foundation CSS, Materialize CSS, Semantic UI, Tailwind, Marvel.
