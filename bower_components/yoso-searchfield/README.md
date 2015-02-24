Yoso Search Field
=================

Searchfield with search icon and customizable hint text.
For detailed Examples view the package demo page.

## Installation

Install the package using [bower](http://bower.io/) `bower install yoso-searchfield` to your project.
After installation, link the component in your application html file.
```html
<head>
    <link rel="import" href="bower-components/yoso-searchfield/yoso-searchfield.html">
</head>
```
Do not forget to adjust the bower path to your application.

## Use

**Code:**
```html
<yoso-searchfield hint="Enter your search" text="my search value"></yoso-searchfield>
```

**Attributes:**
A custom hint text can be set using the `hint` attribute.
User entered search value is available via the `text` attribute. The `text` attribute can ba used also to set a search text.



## Developing and testing

Good unit tests are essential to your verification plan but a good way to quickly sanity test your component is to access your demo.html file via a local web server. There are several ways to do this but one easy method is to run a simple web server that ships with Python, using the commands:

```sh
python -m SimpleHTTPServer
```

Or other method using NodeJS:

```sh
http-server ./
```

This starts a web server on port 8000, so you can test your new element by navigating a browser to `localhost:8000/test/index.html`.

### web-component-tester

The tests are also compatible with [web-component-tester](https://github.com/Polymer/web-component-tester). You can run them on multiple local browsers via:

```sh
sudo npm install -g web-component-tester
wct
```
