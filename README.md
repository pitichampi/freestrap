# Freestrap

`a nice CSS2 css framework for freenet`

## Introduction

Freenet is a great network. It offers many informations and a feeling of real freedom. Knowledge is shared and the comunity is great.

However it lacks of tools to make great design and let creativity express itself.

There are lot of constraints in terms of technology such as no javascript, limited css2 only compatibility and files as small as possible.

With these contraints I still think that we can do something nice, easy to use and creative.

## List of CSS2 functionalities

After testing freenet with the ACID test v2 (created for CSS2), I've encountered a few errors. A few functionalities are disabled in freenet environement (fred) such as base64 images or some other things like pseudo classes.

The first thing to do is to list all CSS2 functionalities and test them to see what does or not work. We should then create a test file to see what does or not work. For these tests I'll use this cheatsheet : https://appletree.or.kr/quick_reference_cards/CSS/CSS2-Visual-Cheat-Sheet.pdf

A table of functionalities will be displayed there after the tests.

## Keep it simple and tiny

In order to keep everything as tiny as possible, we will try to make the framework as modular as possible. Thanks to scss, only things that you really nead can be used and optional things removed. For example, most sites do not require forms, some people want to get only a grid and other want to define their own colors.

We do advise you to use a css minifier and compressor before injecting the code in your page.

