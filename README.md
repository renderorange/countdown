
# NAME

countdown - print how many until a date

# SYNOPSIS

    countdown [--to <YYYY-MM-DD>]
              [--in <seconds, minutes, hours, days>]
              [--version]
              [--help]

# OPTIONS

- --to <YYYY-MM-DD>

    Print days until <YYYY-MM-DD>

- --in &lt;seconds, minutes, hours, days>

    Print how many in seconds, minutes, hours, or days

- --version

    Print the version and exit

- --help

    Print this dialogue

# DESCRIPTION

`countdown` is a program that prints how many &lt;seconds, minutes, hours, days> there are (or have been) until (or since) a defined date.

# EXAMPLES

- Print the seconds, minutes, hours, and days until January 20, 2029.

        $ countdown --to 2029-01-20
        There are 124423849 seconds or 2073730 minutes or 34562 hours or 1440 days until 2029-01-20

- Print the days until January 20, 2029.

        $ countdown --to 2029-01-20 --in days
        There are 1440 days until 2029-01-20

- Print the minutes, days until January 20, 2029.

        $ countdown --to 2029-01-20 --in minutes --in days
        There are 2073682 minutes or 1440 days until 2029-01-20

- Print the days since January 20, 2024.

        $ countdown --to 2024-01-20 --in days
        There have been 387 days since 2024-01-20

# COPYRIGHT AND LICENSE

Copyright (c) 2025 Blaine Motsinger under the MIT license.

# AUTHOR

Blaine Motsinger <blaine@renderorange.com>

