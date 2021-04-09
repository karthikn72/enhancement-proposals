# Dataset Generators

Contributors: @karthikn72

## Introduction

This STEP introduces generators for datasets that could be useful for testing and explaining the difference between estimators for time series data. The preliminary
discussion regarding this could be found on [issue #353](https://github.com/alan-turing-institute/sktime/issues/353) and [PR #759](https://github.com/alan-turing-institute/sktime/pull/759).

## Contents
[table of contents]

## Problem statement
The problem began in [issue #320](https://github.com/alan-turing-institute/sktime/issues/320), where there was a lack of datasets that could sufficiently demonstrate the inner workings of the shapelet tranform. This specific problem was temporarily fixed with [PR #259](https://github.com/alan-turing-institute/sktime/pull/295). However, there is still no effective mechanism in place to generate datasets that could not only be used to demonstrate shapelet transform, but also other classification problems. Currently, there is a simple `make_classification_problem` method that randomly generates data points irresepective of the algorithm applied to it, which is primarily being used for testing purposes.

## Description of proposed solution
A potential solution suggested for this was to introduce dataset generators that could appropriately showcase the available algorithms for time series classification.

## Motivation

## Discussion and comparison of alternative solutions

## Detailed description of design and implementation of proposed solution 
[prototypical implementation if applicable]
