# Interactive Visualization of Differentiability Using R Shiny

## About Me

I am a computer science student interested in mathematical modeling, programming, data visualization, and computational problem solving. I enjoy using technology to make technical and mathematical ideas easier to understand.

## Project Overview

This project is an interactive R Shiny application designed to help users understand differentiability through graphs and numerical approximations.

The application connects the mathematical definition of a derivative with a visual representation of how differentiability works. Users can explore how secant lines approach tangent lines and compare left-hand and right-hand derivative estimates at a selected point.

The goal of the project was to take a concept that can feel abstract when shown only through equations and make it easier to explore interactively.

## Skills and Technologies

- R
- Shiny
- Calculus
- Mathematical modeling
- Numerical approximation
- Data visualization
- Technical communication

## Project Features

- Interactive function visualization
- Secant line visualization
- Tangent line visualization
- Left-hand derivative estimates
- Right-hand derivative estimates
- Differentiability analysis
- Mathematical theory and explanation

## Mathematical Idea

The project is based on the definition of the derivative:

f'(x) = lim(h -> 0) [f(x + h) - f(x)] / h

The application uses numerical approximations to show how the slope of a secant line approaches the slope of the tangent line as the points move closer together.

A function is differentiable at a point when the left-hand and right-hand derivative estimates approach the same value.

## Project Preview

Add a screenshot of the main application here.

![Main Application Screenshot](images/main-app.png)

Add a second screenshot showing the derivative or secant/tangent visualization here.

![Differentiability Visualization](images/differentiability-example.png)

## What I Learned

This project helped me connect theoretical calculus with programming and visualization. I learned how numerical approximations can be used to represent limits and derivatives and how interactive applications can make mathematical concepts easier to communicate.

I also learned that creating a working program is different from creating a project that another person can easily understand. Revising the project for a portfolio required me to think more about presentation, documentation, usability, and how to explain the mathematics clearly.

## Project Links

- **Live Shiny App:** [Add your Shiny app link here]
- **Full Mathematical Modeling Report:** [Add your report link or file here]
- **Source Code:** This repository contains the project source code.

## Repository Structure

```text
differentiability-shiny/
├── README.md
├── app.R
├── images/
│   ├── main-app.png
│   └── differentiability-example.png
└── report/
    └── Differentiability_Report.pdf
```

If your Shiny application uses separate files such as `ui.R` and `server.R`, you can use those instead of `app.R`.

## Running the Application

To run the application locally, open the project in RStudio and run:

```r
shiny::runApp()
```

Make sure the required R packages are installed before running the application.
