# PHP Undefined Variable Notice: Handling Undefined Variables

This repository demonstrates a common error in PHP: using undefined variables.  It shows how this can lead to notices, unexpected output, and potential issues in larger applications.

## The Problem

The `bug.php` file contains code that attempts to echo a variable (`$userName`) without first checking if it's defined. This will trigger a notice-level error in PHP, alerting you to the problem, but the script will likely continue execution, potentially leading to unexpected results.

## The Solution

The `bugSolution.php` file shows the correct way to handle this.  Before using the variable, we check if it's set using `isset()`.  If it's not, we provide a default value, preventing the error and ensuring predictable behavior.

This approach is crucial for writing robust and reliable PHP applications.