# miniMathJax

A lightweight subset (15.8MB as of 2018-09-22) of MathJax that renders TeX using SVG. 

## Getting started

Clone repo and create a script tag with appropriate source:

```
<script type="text/javascript" src="path-to-root-of-repo/MathJax.js?config=TeX-AMS_SVG"></script>
```

Minimal working example is test.html in the repo:

```
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Test for miniMathJax</title>
	<script type="text/javascript" src="./MathJax.js?config=TeX-AMS_SVG"></script>
</head>
<body>
$$e=mc^2$$
</body>
</html>
```

Modify the path './MathJax.js' as required.

## Built with

[MathJax](https://www.mathjax.org)

## Authors

* MathJax team - creating the MathJax library in the first place.
* [Matthew Burke](https://mwpb.uk) - stripping out non-SVG renderers and non-TeX inputs.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.