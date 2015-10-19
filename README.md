# Scroll Spider

This script is a silly little decoration for Halloween. It appends a spider to the document which will scroll down as you scroll the document... and scare the person who is scrolling. The spider also serves as a means to go back to the top of the page.. well actually, it punishes you for trying to squash it with your cursor.

## Configuration

The script contains various settings for personalization and prefences inside the ``config`` object at the top. You can find informantion on each config property below.

| **Property** | **Description** |
| :----------: | ------------- |
| ``side`` | Defines the side of the screen the spider should appear on. There are two values : ``left`` and ``right``. Defaults to ``right`` if an incorrect value is specified. |
| ``offset`` | Defines how far away the spider should display from the specified side of the screen. |
| ``tooltip`` | Defines the texts that should display when you hover over the spider. |
| ``image`` | Defines the image URL for the spider. |
| ``web`` | The web attached to the spider is designed using CSS. This property allows you to change the design of the spider web by specifying a CSS Sting. |

## Demo
![Demo](http://i21.servimg.com/u/f21/18/21/41/30/scroll10.gif)
