---
layout: post
title: "Blog for hacker"
description: "{ :blog => 'Hacker' }"
category: ruby
tags: [ruby, jekyll, blog]
---
{% include JB/setup %}




![Blog 4 Hacker](http://blog4hacker.herokuapp.com/images/bgs/bg-hack.jpg "Blog 4 Hacker")


Презентацию можно посмотреть [здесь](http://blog4hacker.herokuapp.com)

Что такое Jekyll?
> Jekyll is a simple, blog aware, static site generator.

Хочешь знать больше? [http://jekyllbootstrap.com](http://jekyllbootstrap.com)

<!-- -**-END-**- -->

### Как добавить статью в блог?

##### 1) Устанавливаем jekyll gem 

    gem install jekyll

##### 2) Клонируем блог

    git@github.com:ruby-way/ruby-way.github.com.git

##### 3) Запускаем

    jekyll --server --auto  

смотрим изменения [http://localhost:4000](http://localhost:4000/)

##### 4) Добавляем статью
 
    rake post title="Blog 4 Hacker"

##### 5) Пишем статью

    ./_posts/2012-10-24-blog-4-hacker.md

используя [markdown](http://daringfireball.net/projects/markdown/syntax)

##### 6) Деплоим

    git add .
    git commit -m "add post: blog 4 hacker"
    git push origin master