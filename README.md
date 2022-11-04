# Battleship in your Terminal

Play the traditional game "Battleship", also called "Sea Battle", in your Terminal.

## How to play

Everything is in a single file named `battle`. Download it and make sure you can execute it.

- Check if it's executable :

```bash
ls -l
# should print something beginning with "-rwx"
```

- If not, add the permissions to the user (aka you) :

```bash
chmod u+x ./battle
```

- Execute it

```bash
./battle
```

The game starts. Two players play on the same terminal, the player 1 starts by placing his boats without player 2 looking. Then, when ready, the player 2 can place his boats. Once everything's ready, player 1 first attacks.

## Requirements

The code is written in BASH. Use a version >= 4.3. The game checks your version before starting. It cannot start if the version is too old. In general, Mac users have an older version due to license issues.

## Debugging

If you're a developer and want to change the code a little then uncomment the line 17 to start with fewer boats.

## Author

[CodoPixel](https://github.com/CodoPixel/)

## License

MIT License
