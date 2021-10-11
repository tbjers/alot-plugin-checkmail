# checkmail plugin for alot

A plugin that checks mail asynchronously, giving you feedback through the process via notifications.

## Installation

Run the following in the environment that alot's `hooks.py` uses:

```sh
pip install --upgrade alot-plugin-checkmail
```

You may need to use `sudo` if your Python installation is owned by `root`.

## Configuration

Insert the following stanza in your `~/.config/alot/config` file:

```toml
[checkmail]
  command = '/path/to/your/binary/or/script -abc --with --any --parameters'
```
