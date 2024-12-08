# Tailwind CSS Fractional Widths in Flexbox Issue

This repository demonstrates an unexpected behavior when using Tailwind's fractional width classes (`w-1/2`, `w-1/3`, etc.) within a flex container.  The child elements do not always distribute the space as intended.

## Bug Report

The issue appears when using fractional widths in a flex container. The child elements don't always evenly distribute the available space, resulting in unexpected spacing or layout inconsistencies.  The provided example shows two divs each assigned `w-1/2`, but they don't evenly fill the parent container.

## Solution

The solution involves ensuring that the parent container has no extra space or padding that could interfere with the distribution of fractional widths. If other classes or styles influence the size, it should also be considered.