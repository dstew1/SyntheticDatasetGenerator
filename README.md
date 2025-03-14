# SyntheticDatasetGenerator
Welcome to the Synthetic Dataset Generator! This Python tool lets you create synthetic datasets using a customizable configuration dictionary. Whether you need data for testing, demos, or just to mess around with some fun fake numbers, this generator has you covered.

> **Disclaimer:** I do not recommend using this generator for training machine/deep learning models. Use it for fun, testing, or whatever u need it for. 

---

## Overview

This generator provides a flexible framework for creating synthetic datasets. Each column of your dataset is defined in a configuration dictionary, where you can specify:

- **Lists:** Randomly select a value from a list.
- **Callables:** Use functions (or lambdas) to generate values. If a callable accepts the current row, you can create dependencies between columns.
- **Template Dictionaries:** Combine multiple fields into one column using a formatted template.
- **Fixed Values:** Use static values when needed.

The generator includes features for ensuring unique rows, reporting progress, and limiting the number of attempts to generate unique rows. It's highly customizable and extendable to fit your data creation needs.

---

## Features

- **Customizable Data Generation:** Define how each column's data is created using lists, functions, or templates.
- **Unique Row Enforcement:** Option to ensure every generated row is unique.
- **Progress Reporting:** See progress as rows are generated.
- **Easy to Extend:** Add your own functions or configuration rules to create any synthetic dataset you can dream up.

---

## Getting Started

### Prerequisites

- Python 3.x installed on your machine.
- Familiarity with basic Python programming.

### Installation

Clone the repository or download the script to your local machine.
