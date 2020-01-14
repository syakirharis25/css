# CSS
My works related to Cascading Style Sheets (CSS)

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [GitHub notes.](#github)

<a name="introduction"></a>
## Introduction
<img src="css.jpeg" height="150">

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language like HTML CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript

CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple web pages to share formatting by specifying the relevant CSS in a separate .css file, and reduce complexity and repetition in the structural content.

Separation of formatting and content also makes it feasible to present the same markup page in different styles for different rendering methods, such as on-screen, in print, by voice (via speech-based browser or screen reader), and on Braille-based tactile devices. CSS also has rules for alternate formatting if the content is accessed on a mobile device.

The name cascading comes from the specified priority scheme to determine which style rule applies if more than one rule matches a particular element. This cascading priority scheme is predictable. The CSS specifications are maintained by the World Wide Web Consortium (W3C). Internet media type (MIME type) text/css is registered for use with CSS by RFC 2318 (March 1998). The W3C operates a free CSS validation service for CSS documents.

In addition to HTML, other markup languages support the use of CSS including XHTML, plain XML, SVG, and XUL.

<a name="references"></a>
## Official references websites
Cascading Style Sheets documentation by Mozilla : https://developer.mozilla.org/en-US/docs/Web/CSS/Reference
CSS Almanac : https://css-tricks.com/almanac

<a name="github"></a>
## GitHub notes
Initialize repository, adding GitHub remote repository and check the remote repository.
```
$ git init
$ git remote add origin https://github.com/syakirharis25/css.git
$ git remote -v
$ git status
```

If there is an error message.
```
! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https:///github.com/syakirharis25/css.git'
```

Then do this command.
```
$ git merge origin/master --allow-unrelated-histories
$ git push origin master
```
