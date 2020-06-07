A [Scoop](https://scoop.sh/) bucket for open source/freeware games and game-related tools.

## Usage

After installing [Scoop](https://scoop.sh/), enter the following line in a
Command Prompt or PowerShell window:

```powershell
scoop bucket add wacko https://github.com/wackoisgod/scoop-personal.git
```

Once this is done, you can install any app from this bucket (check the list
of files in the
[`bucket/` directory](https://github.com/wackoisgod/scoop-personal/tree/master/bucket)).
For instance, use the following command:

```powershell
# Don't include the .json file extension in the app name
scoop install barnacle
```

## License

Copyright © 2018-2020 Andrew Spiering and contributors

Files in this repository are licensed under CC0 1.0 Universal,
see [LICENSE.md](LICENSE.md) for more information.
