# PHP Loose Comparison Bug
This repository demonstrates a common but subtle bug in PHP related to loose comparison (`==`) between strings and numbers.  Specifically, the loose comparison considers the string '0' equal to the integer 0. This can lead to unexpected behavior in conditional logic.  The `bug.php` file shows the problematic code, while `bugSolution.php` provides a corrected version using strict comparison (`===`).