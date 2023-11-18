# ALX Intro to SE CSS Flexbox Project

## Overview

Welcome to the ALX Intro to Software Engineering CSS Flexbox Project! This project focuses on mastering the concepts of CSS Flexbox to create flexible and responsive layouts. The purpose of this README is to guide you through key Flexbox concepts and structures implemented in this project.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Flexbox Concepts](#flexbox-concepts)
  - [1. Flex Container](#1-flex-container)
  - [2. Flex Items](#2-flex-items)
  - [3. Flex Direction](#3-flex-direction)
  - [4. Justify Content](#4-justify-content)
  - [5. Align Items](#5-align-items)
  - [6. Flex Wrap](#6-flex-wrap)
  - [7. Align Content](#7-align-content)
  - [8. Flexbox Shorthand](#8-flexbox-shorthand)
- [How to Use](#how-to-use)
- [License](#license)

## Prerequisites

- Basic knowledge of HTML and CSS.
- A code editor (e.g., Visual Studio Code, Sublime Text).


## Flexbox Concepts

### 1. Flex Container

The container becomes a flex container by setting `display: flex;` or `display: inline-flex;` on it. This enables the use of flex properties to control the layout of its children.

### 2. Flex Items

Children of a flex container become flex items. These items can be horizontally or vertically aligned within the container, and their order can be changed using the `order` property.

### 3. Flex Direction

The `flex-direction` property defines the main axis along which the flex items are placed. It can be set to `row`, `row-reverse`, `column`, or `column-reverse`.

### 4. Justify Content

`justify-content` defines how flex items are distributed along the main axis. Values include `flex-start`, `flex-end`, `center`, `space-between`, and `space-around`.

### 5. Align Items

`align-items` determines how flex items are aligned along the cross axis. Values include `flex-start`, `flex-end`, `center`, `baseline`, and `stretch`.

### 6. Flex Wrap

`flex-wrap` controls whether flex items are forced onto one line or can wrap onto multiple lines. Values include `nowrap`, `wrap`, and `wrap-reverse`.

### 7. Align Content

`align-content` is similar to `align-items` but applies to multiple lines of flex items. It can be set to `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, and `stretch`.

### 8. Flexbox Shorthand

The `flex` shorthand property is a combination of `flex-grow`, `flex-shrink`, and `flex-basis`. It is used to set the flexibility of a flex item in one declaration.

## How to Use

1. Clone the repository: `git clone https://github.com/wakassodev/alx_html_css.git`
2. Open `0-index.html` in your preferred web browser or deploy the project on a web server for testing.
3. Explore the HTML structure in `0-index.html` and the styles applied in `css/0-styles.css`.


## License

This project is licensed under the [MIT License](LICENSE).
