---
layout: post
title: Wednesday, Week 7
date: '2014-03-13T02:27:10-07:00'
tags:
- phase 3
- week 7
- dev bootcamp
- capybara
tumblr_url: http://mknudsen01.tumblr.com/post/79440231271/wednesday-week-7
---
Armando and I paired again today.

I really liked our lesson for the day: test-driven development. With TDD, we make tests for our code, see that the test is failing, write some code to make the test pass, and then see the code pass.

TDD is an awesome way to develop, and it’s the way that I would like for most of my development to happen. It was a slow process today, but that’s because we’re still not the best at testing or coding. As we get better with both, TDD will become faster and easier.

With test-driven development, we know that our code is doing what we want it to do. We write a test for the feature or bit of functionality that we want. We run our tests and see that the feature does not yet exist. Then we write some code and see that test pass.

At that point, we know that the code we wrote is doing exactly what we want it to do. It was only going to pass the test we wrote if it does exactly as we had planned.

So, with TDD, we get peace of mind. We know that we have all of these tests that are testing the exact functionality of our program. As we write more and more tests and more and more code, instead of having to click through the entire website to see that all of our code still works, we can just run our test suite. If all of the tests pass, then we’re golden. We can rest assured that the site still works, without having to spend the time looking at all of our pages any time we make a change.

TDD also helps us to write better code. We have to really sit and think about how everything is going to work and interact. We can only write a test once we know how we want a specific method or function to behave.

So, TDD forces us to think through our project before we write any code. And having all of those tests affords the assurance that all of our code is working. We win all of the things.

Capybara


Armando and I also fell down the rabbit hole of Capybara today.

All of our tests were integration tests that used Capybara, which is a ruby gem that clicks through your website for you. For example, one of the bits of functionality that we wanted to test was that when we filled out a form correctly, the title that we put in the form showed up on the page.

To do that manually, we would visit the page with the form, click on the input field, type in the information, click the submit button, and then check to see that the title indeed did show up on the next page.

It would be so0ooO0oper great if there was a way to automate that process, right? It takes a good ten or fifteen seconds to do. If I want to test that bit of functionality every time I change some code (to make sure that the code I wrote didn’t break anything), those 10 to 15 seconds would start to add up.

That’s where Capybara comes in. We can write some code that has our computer click through the website for us. We can tell it to follow the steps that would otherwise have to follow manually. It saves time, and it’s kind of way awesome to watch your browser open and click through all of the pages so quickly when you run your tests.

We learned it today, but it’s really not something that should be used often. The tests that we make with Capybara are still far slower than the other tests that we write. And pretty much every integration test with Capybara can be made into a controller or model test. Those don’t require opening the browser, and so they’re much faster.

Though we’re supposed to use Capybara sparingly, it was a great to spend the day diving deep with it. There’s still much to explore, but I feel like I have a firm grasp of the fundamentals, which is always a good feeling.

Backbone

Tonight, I’m taking a little break from Rails and testing to read about Backbone.js, which is a tool to help make single-page applications that are interactive. So far, it’s a pretty cool read, and I’m hoping to make a project with it this weekend.

Project

Tomorrow and Friday, we’re supposed to have a group project. We’ll finally be making something that we don’t really know how to make in Rails. So far, it’s been great to explore Rails by making apps that we’d made before with Sinatra.

I’m getting a little antsy to push myself with Rails, though, so I’m excited to have a bigger project to work on. We’re going to be making a clone of Stack Overflow, and it’s gonna be pretty sweet.

Alright, off to work.
