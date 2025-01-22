# Uncommon HTML Input Element Errors

This repository demonstrates two uncommon but potentially problematic errors related to the HTML `input` element: incorrect use of the `min` and `max` attributes with the `type="number"`, and a mismatch in data types between an `input` element and its associated `datalist`.

## Bug 1: Invalid min/max Values in Number Inputs

Using non-numeric values for the `min` or `max` attributes of a number input can lead to unexpected behavior.  The browser may ignore the invalid attributes or throw an error.

## Bug 2: Type Mismatch in Datalist

The `datalist` element should contain values that match the type of its associated `input` element. Using strings in a `datalist` for a numeric `input` will not result in an error but will likely produce unexpected behavior.

## Solutions

The solution files demonstrate the correct usage of these attributes and elements.  Ensure that `min` and `max` attributes contain valid numbers and that `datalist` options match the input type.