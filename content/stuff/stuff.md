+++
title= "A page on simple hugo site"
draft= true
+++

## Welcome!

Here is the home page of my simplest hugo site. 

In my Hugo project I have an image file:  <code>static/images/hugo-logo-wide.svg</code>
I'm having problems with the Github Pages version of my project. 
It often can't find these images.  This demo loads this image twice:

- Once with a leading '/' in the file name, and
- Once without.

I do not have 'baseURL' set in the hugo.toml configuration file.  On Github, I use an action that generates its own version of 'baseURL'.


{{< img "/images/hugo-logo-wide.svg" >}}

```
![Hugo logo](/images/hugo-logo-wide.svg)
```
![Hugo logo](/images/hugo-logo-wide.svg)

```
![Hugo logo](images/hugo-logo-wide.svg)
```
![Hugo logo](images/hugo-logo-wide.svg)
