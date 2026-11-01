# Student Grade Calculator

A simple Python application that calculates the average grade of a student
and determines whether the student passes.

## Features

- `calculate_average(grades)`: returns the average of a list of grades.
- `is_passing(average)`: returns `True` if the average is 10 or higher.
- `get_grade_category(average)`: returns Excellent (16+), Good (12-15.99),
  Average (10-11.99) or Fail (below 10).

## Continuous Integration

A GitHub Actions workflow runs `flake8` and `pytest` on every pull request
and on every push to `main`.

## Team

| Student | Role | Contribution |
|---|---|---|
| A (`<username-a>`) | Project owner | Repository, CI workflow, reviews, merges |
| B (`islammokdadi-arch`) | Contributor | Grade category feature (Issue #1) |
| C (`<username-c>`) | Contributor | Passing grade limit (Issue #2) |
