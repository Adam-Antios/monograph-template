# Monograph

## Introduction

Monograph is a template, suitable mainly for diploma theses and doctoral dissertations.

## Instructions for Use

The best way to use this template is to download it as a zip file and upload it as it is (as a zip file) to Overleaf.Overleaf is an online LaTeX editor and has pre-installed all the necessary packages to compile this template into a PDF file.

Should you decide to proceed with this method then, once you sign in to your Overleaf account, you must open the Menu button on the top left corner and choose `XeLaTeX` as the compiler and the `Monograph.tex` as the main document.

## Configuration Options

1. The default language for the template is English. If you want to change it to Greek for example, then configure the `babel` package in the `Preamble.sty` as following:

	```
	\RequirePackage[english, greek]{babel}
	```

	By doing so, you declare that there will be two languages in the document, Greek and English, with the Greek being the default one. Note that in the `babel` package the active language is the last one.
	
## Licensing Agreement

MIT License

Copyright (c) 2022 Adam Antios

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
