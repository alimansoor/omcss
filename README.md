# OMCSS

OMCSS (Organisable and Maintainable CSS) is an approach towards creating a scalable and modular architecture for your CSS that you can expand and maintain with ease.

## Getting Started

OMCSS provides a bootstrap framework that will help you get started with your application's stylesheet. You can download OMCSS framework from the below options available:

* [Download OMCSS framework](http://www.omcss/download/)
* Clone the repo: `git clone https://github.com/twbs/bootstrap.git`
* Install with npm: `npm install omcss`

### Prerequisites

[Sass](https://sass-lang.com) compiler is a must to compile individual files into your application stylesheet.

Please visit [https://sass-lang.com/install](https://sass-lang.com/install) to setup Sass based on your environment i.e. Linux, Windows, Mac OS X.

### File Structure

```
omcss/
├── base/
│   ├── _grid.scss
│   ├── _helper.scss
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

### Installing

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Creators

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

