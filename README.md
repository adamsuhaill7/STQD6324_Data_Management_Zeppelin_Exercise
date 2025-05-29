# STQD6324_Data_Management_Zeppelin_Exercise

# Apache Spark MovieLens Analysis

This repository contains a Spark application that analyzes the MovieLens dataset using Scala. The app processes user ratings and movie titles, allowing for insights into the most popular movies based on user ratings.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [License](#license)

## Overview

The application performs the following tasks:
1. Imports user ratings from `u.data` into a Spark DataFrame.
2. Extracts the second and third fields to create a `Rating` case class.
3. Analyzes the most popular movies based on user ratings.
4. Loads movie titles from `u.item` and joins them with ratings.

## Setup

### Prerequisites

- Apache Spark
- Scala
- Zeppelin (optional for running notebooks)
- MongoDB (optional for additional data handling)
