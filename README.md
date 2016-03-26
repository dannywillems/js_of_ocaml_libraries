List of js_of_ocaml libraries
=============================

- Standard library [gen_js_api]
	Binding to the javascript standard library
	* [ocaml-js-stdlib](https://github.com/dannywillems/ocaml-js-stdlib)

- [JQuery](https://jquery.com/) [js_of_ocaml]
	Jquery provides some objects and methods to improve the DOM manipulation and
	event handling.

	* Binding: [ocaml-jquery](https://github.com/kitec/ocaml-jquery) (more
	  up to date, forked from https://github.com/gabriel-cardoso/ocaml-jquery)

- [Nodejs](https://nodejs.org/en) [js_of_ocaml]
	Instead of using javascript only in a web browser, Nodejs allows you to use
	javascript on your system by providing a javascript interpreter running on
	top of [Google V8 javascript engine](https://developers.google.com/v8/)
	Nodejs has lots of module which give you the possibility to run, for
	example, an http server.
	* Binding: [ocaml-nodejs](https://github.com/fxfactorial/ocaml-nodejs)

- [D3](https://d3js.org/) [js_of_ocaml]
	D3.js is a JavaScript library for manipulating documents based on data. D3
	helps you bring data to life using HTML, SVG, and CSS. D3’s emphasis on web
	standards gives you the full capabilities of modern browsers without tying
	yourself to a proprietary framework, combining powerful visualization
	components and a data-driven approach to DOM manipulation.
	* Binding: [ocaml-d3](https://github.com/seliopou/ocaml-d3) (can be
	  installed with opam install d3)

- [extjs](https://www.sencha.com/products/extjs/#overview) [js_of_ocaml]
	* Binding: [ocaml-extjs](https://github.com/astrada/ocaml-extjs)

## Mobile development

- [Cordova plugins](https://cordova.apache.org/) [js_of_ocaml and gen_js_api]
	Cordova allows you to develop hybrid mobile applications using web
	technologies. Through plugins, you can access to devices features.
	* [Bindings to cordova
	  plugins](https://github.com/dannywillems/ocaml-cordova-plugin-list)
