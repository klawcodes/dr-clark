<p align="center">
<img src="https://i.ibb.co/6bnfRB4/2024-05-01-15-58.png" 
style="width:600px">
<p/>
<p align="center">
🚀 Fetch and display cryptocurrency prices right from your terminal!
<p/>

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
    cp drclark ~/.local/bin
    ```

5. Run the script with your desired cryptocurrency symbol (e.g., BTC or ETH):

    ```bash
    drclark BTC
    ```

#### Using Third-Party Terminal Emulator

You can also use third-party terminal emulators like Git Bash or ConEmu, which provide a Unix-like environment on Windows.

## Additional Features

- Display help message:
  ```bash
  drclark -h
- Add a favorite cryptocurrency symbol:
  ```bash
  drclark --add-favorite BTC
- Show favorite cryptocurrency that have been added:
	```bash
	drclark show-favorite
- Remove favorite cryptocurrency:
  ```bash
  drclark --remove-favorite BTC
- Show the list of favorite cryptocurrencies:
	```bash
	drclark favorite-list
