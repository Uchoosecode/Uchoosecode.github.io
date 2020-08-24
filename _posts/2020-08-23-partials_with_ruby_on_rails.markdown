---
layout: post
title:      "Partials with Ruby on Rails"
date:       2020-08-24 03:09:01 +0000
permalink:  partials_with_ruby_on_rails
---


As software developers we try our best to keep our coding D.R.Y.(Don't Repeat Yourself).  Using partials is a great way to help with that. Partials are taking pieces of code from your templates to seperate files and allows you to reuse that chunk of code throughout all your templates. To create a partial file, it must start with an underscore. An example of that is _partial.html.erb. To access a partial in your templates you have to render them inside of content tags as a string. An example of this would look like <%= render "partial" %>. When rendering a partial you don't include the underscore. If the partial is located in a different folder, that path has to be included. An example of the would look like <%= render "path/partial" %>. To create a global partial that can be rendered anywhere without having to reference an exact path, that partial will have to be created in the application path(views/application). An example of that path would be app/views/application/_partial. Then you can just render this file anywhere like this <%= render "partial" %>.
