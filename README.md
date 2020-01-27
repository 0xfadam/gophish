Gophish
=======

[![Build Status](https://travis-ci.org/gophish/gophish.svg?branch=master)](https://travis-ci.org/gophish/gophish) [![GoDoc](https://godoc.org/github.com/gophish/gophish?status.svg)](https://godoc.org/github.com/gophish/gophish)

Gophish: Open-Source Phishing Toolkit

[Gophish](https://getgophish.com) is an open-source phishing toolkit designed for businesses and penetration testers. It provides the ability to quickly and easily setup and execute phishing engagements and security awareness training.

### Modifications

In this repository, the **X-Mailer** is removed from the headers.

Also, the attachment is a SVG file, that includes the RID.
This allows attachment tracking.

In order to use your own SVG, you still need to upload a SVG file in the email template.
The content of the SVG will be replaced by the content of the variable **ct**
