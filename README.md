# wtr — simple CLI-app to check the weather

The script is based on a famous [wttr.in](https://github.com/chubin/wttr.in) web service by Igor Chubin.

Run `wtr` to get current weather in your location.

Run `wtr -w` to get current weather with wind speed.

Run `wtr -v` to get verbose data along with the weather.

Run `wtr -h` to get a list of arguments.

<details>
  <summary>Planned</summary>
Run `wtr Lviv` or any other town instead as an argument to get current weather in the stated location.
</details>

## Installation

`dpkg -i wtr*.deb` or `apt install ./wtr*.deb`

The only dependency you need is `curl` (installed automatically with `.deb` package). Also, the app wouldn't work without Internet connected.

Remove: `apt purge wtr`

## License

WTFPL.
