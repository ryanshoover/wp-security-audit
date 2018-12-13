# WordPress Security Audit

*Note* This is a work in progress.

## Installation

1. Clone this repo to your local computer
    ```shell
    git clone git@github.com:ryanshoover/wp-security-audit.git
    ```
2. Install the dependencies
    ```shell
    composer install
    ```

## Usage

1. `cd` into the directory that houses the code
2. Run the composer script, passing the path to your files as a parameter
    ```shell
    composer run test -- ~/path/to/files-needing-tested/
    ```
