# factorial-cli

Fill your factorial shifts with ease

[![asciicast](https://asciinema.org/a/pbJ7VoYhm4NsW7qv9XRaS3Uzk.svg)](https://asciinema.org/a/pbJ7VoYhm4NsW7qv9XRaS3Uzk)

## Installation

```sh
deno install --allow-env --allow-net https://raw.githubusercontent.com/DanielRamosAcosta/factorial-cli/main/src/factorial.ts
```

Env permissions are optional.

## Usage

```
Fills the shifts of the given year and month
  factorial fill-shifts --year 2021 --month 1

USAGE:
    factorial fill-shifts [OPTIONS]
OPTIONS:
    -y, --year <YEAR>
            Sets the year to fill the shifts

    -m, --month <MONTH>
            Sets the month to fill the shifts

    -e, --email <EMAIL>
            The email of your factorial account. Also configurable via FACTORIAL_USER_EMAIL env variable.

    -p, --password <PASSWORD>
            The password of your factorial account. Also configurable via FACTORIAL_USER_PASSWORD env variable.

    -r, --randomness <RANDOMNESS>
            The amount of minutes for the shift clock in and out entropy. Also configurable via SHIFT_MINUTES_RANDOMNESS env variable.

        --entryTime <ENTRY_TIME>
            The default entry time you want to set to fill shifts. Also configurable via ENTRY_TIME env variable.
        
        --exitTime <EXIT_TIME>
            The default exit time you want to set to fill shifts. Also configurable via EXIT_TIME env variable.
```
