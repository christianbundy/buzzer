# Buzzer

Twilio endpoint to turn your callbox into a digital buzzer.

## Installation

- Set up a Twilio account and get a phone number.
- Configure your callbox to ring your Twilio phone number.
- Point your Twilio endpoint at the designated server.
- Download Buzzer:

    ```sh
    git clone https://github.com/christianbundy/buzzer.git
    ```

## Usage

- Unlock your callbox

    ```sh
    python -m SimpleHTTPServer unlocked
    ```
    
- Lock your callbox

    ```sh
    python -m SimpleHTTPServer locked
    ```

## Support

Please [open an issue](https://github.com/christianbundy/buzzer/issues/new) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/christianbundy/buzzer/compare/).
