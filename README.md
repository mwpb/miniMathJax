# miniMathJax

A lightweight subset of MathJax that renders TeX using SVG. 

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

* [Matthew Burke](https://mwpb.uk) - Initial work.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.