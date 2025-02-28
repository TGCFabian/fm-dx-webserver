# FM-DX Webserver 📻🌐

FM-DX Webserver is a cross-platform web server designed for FM DXers who want to control their TEF6686 / F1HD receiver through a web interface.

## Features

- 🌐 **Web-Based Control:** Access and control your TEF6686 / F1HD receiver from any device with a web browser.
- 📻 **FM DXing:** Enhance your FM/AM DXing experience with a user-friendly web interface.
- **Cross-Platform:** You can run this on both Windows and Linux servers along with xdrd.
- **Tuner control:** Control your FM tuner on the go. Phone? Tablet? No problem.
- **Low-latency streaming**: Built in directly into the webserver, no external apps needed for users

##  Features to be added
Check here for an up to date task list: https://github.com/NoobishSVK/fm-dx-webserver/issues/3

## Community
Join our **Discord community** to get the latest development update info, share feedback and receive support.
[<img alt="Join the TEF6686 Discord community!" src="https://i.imgur.com/lI9Tuxf.png" height="120">](https://discord.gg/ZAVNdS74mC)  

## Getting Started
Please install **node.js version 21.5.0** or older to make this work.   

Version >=21.6.0 is currently not working correctly. 



1. Download or install ffmpeg (optional, but needed if you want the audio stream to work)

    ```bash
    Linux (Ubuntu/Debian): 
    sudo apt install ffmpeg

    Windows: 
    https://www.geeksforgeeks.org/how-to-install-ffmpeg-on-windows/
    ```

2. Clone the repository (or alternatively download it manually):

    ```bash
    git clone https://github.com/NoobishSVK/FM-DX-Webserver.git
    ```

3. Nagivate to the fm-dx-webserver folder in your terminal and run this command:
    ```bash
    npm install
    ```


4. Start the server:

    ```bash
    npm run webserver
    ```

4. Open your web browser and navigate to `http://web-server-ip:web-server-port` to access the web interface.

## Dependencies

This project utilizes the [librdsparser](https://github.com/kkonradpl/librdsparser) library for RDS parsing. Make sure to check out the library for more information.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests. Your input is valuable!

## License

This project is licensed under the [GNU-GPL v3 License](LICENSE.md).

## Acknowledgments

- Thanks to [librdsparser](https://github.com/kkonradpl/librdsparser) for providing the RDS parsing functionality.

Happy DXing! 🎶📡
