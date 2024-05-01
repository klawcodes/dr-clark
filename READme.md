
# Dr. Clark

<div style="text-align:center">
[Dr. Clark](https://i.ibb.co/6bnfRB4/2024-05-01-15-58.png)
</div>
🚀 Fetch and display cryptocurrency prices right from your terminal!

## Usage

### Linux/Mac

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/klawcodes/dr-clark
    ```

2. Navigate to the directory containing the script:

    ```bash
    cd dr-clark
    ```

3. Make the script executable:

    ```bash
    chmod +x drclark
    ```

4. Move the script to a directory included in your PATH (e.g., ~/.local/bin):

    ```bash
    mv drclark ~/.local/bin
    ```

5. Run the script with your desired cryptocurrency symbol (e.g., BTC or ETH):

    ```bash
    drclark BTC
    ```

### Windows

#### Using Batch File

1. Clone the repository to your local machine or download the script file (`drclark`).

2. Create a batch file (e.g., `crypto_prices.bat`) with the following content:

    ```batch
    @echo off
    bash /path/to/your/script %*
    ```

    Replace `/path/to/your/script` with the path to your `drclark` file.

3. Save the batch file and move it to a directory included in your PATH.

4. Run the batch file from the Command Prompt with your desired cryptocurrency symbol:

    ```batch
    drclark BTC
    ```

#### Using Cygwin

1. Install Cygwin by downloading and running the installer from the [Cygwin website](https://www.cygwin.com/).

2. Open the Cygwin terminal and navigate to the directory containing the script.

3. Run the script with your desired cryptocurrency symbol:

    ```bash
    bash drclark BTC
    ```

#### Using Third-Party Terminal Emulator

You can also use third-party terminal emulators like Git Bash or ConEmu, which provide a Unix-like environment on Windows.

## Additional Features

- Add a favorite cryptocurrency symbol:
  ```bash
  drclark --add-favorite BTC
- Show favorite cryptocurrency that have been added:
	```bash
	drclark show-favorite
- Remove favorite cryptocurrency:
  ```bash
  ddrclark --remove-favorite BTC
- Show the list of favorite cryptocurrencies:
	```bash
	drclark favorite-list
