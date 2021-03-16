# esp-idf-vscode-boilerplate
Boilerplate for developing ESP32 projects using ESP-IDF and VS Code

  > Note 1: You need to have installed [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools) extension in your VS Code.

  > Note 2: Make sure that you have `ESP_IDF` environment variable (which leads to esp-idf folder) and path to XTENSA compiler _bin_ folder needs to be present on the `PATH`.

## How to use

1. Clone repository
```
git clone https://github.com/abobija/esp-idf-vscode-boilerplate.git my-project
```

2. Go inside of project folder
```
cd my-project
```

3. Start VSC
```
code .
```

## Config, Build and Flash

```
idf.py set-target esp32
idf.py menuconfig
idf.py build
idf.py -p (PORT) flash
```

## Demo

[![Get started with ESP32 in VS CODE ... ESP-IDF](https://img.youtube.com/vi/aQi8qiW9fmg/mqdefault.jpg)](https://www.youtube.com/watch?v=aQi8qiW9fmg)

## Author

GitHub: [abobija](https://github.com/abobija)<br>
Homepage: [abobija.com](https://abobija.com)

## License

[MIT](LICENSE)