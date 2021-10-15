# Project 1 Documentation
## by Ahmed Sorour

## Introduction

This is a quizgame built with JavaScript, jQuery, HTML, and CSS.

## Technologies used

- HTML
- CSS
- JS
- jQuery

## Challenges

#### First Attempt at retrieving my data

After my first attempt to retrieve my data using AJAX, I got an error page. After retracing my steps, I found out that I entered the wrong environment id in the URL. I had put ```main``` instead of ```master```.

#### Inconsistent Player Score Updates

I noticed that the player scores were not updating for certain questions. After inserting some console logs, I was able to pinpoint the problem as being additional spaces in some of the Contentful entries. After removing the additional spacing, the scores updated as expected.