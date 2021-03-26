# Exercise 7 - JavaFX Basics

## Learning Goals

This exercise targets the understanding of the following subjects:
* To write a simple JavaFX program and understand the relationship among stages, scenes, and nodes (14.3)
* To create user interfaces using panes, groups, UI controls, and shapes (14.4)
* To update property values automatically through property binding (14.5)
* To use the common properties style and rotate for nodes (14.6)
* To layout nodes using Pane, StackPane, FlowPane, GridPane, BorderPane, HBox, and VBox (14.10)
* To display text using the Text class, and create shapes using the Line, Circle, Rectangle, Ellipse, Arc, Polygon, and Polyline classes (14.11)
* To develop the reusable GUI components (14.12)

## Description

In this exercise, we will implement a graphical calculator for computing reverse polish notation expressions

## Instructions

* Create a package `aup.cs.calc` and a class `Calculator` implementing a JFX application.
* The calculator needs to have a textual screen at the top and the following buttons: 1-9, +, -, \*, /, space, clear and =.
* The semantics of the buttons are as expected on a calculator with = calculating the result and printing it on the screen.
* Make sure to bind the screen to a textual property and to pass this property to all the buttons.
* Buttons should implement `setOnAction` in a way that changes the screen with the right values
* Ensure to use inheritance properly as to maximize code reuse
* Make sure that the layout is correct
* Use CSS styles to make the calculator colorful

