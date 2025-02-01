# Pomodoro Timer

A simple terminal-based Pomodoro timer to boost your productivity.

## Installation

### Via Homebrew Tap

Tap the repository and install:

```
brew tap monoganog/pomodoro
brew install pomodoro
```

## Usage

To start a 10 minute work session followed by a 1 minute break simply type `pomodoro -w 10 -r 1` in your terminal.

## Command-line Flags

`-w` Sets the duration of the work session in minutes.
For example, -w 10 will run a 10-minute work period (default: 25).

`-r` Sets the duration of the break session in minutes.
For example, -r 1 will run a 1-minute break period (default: 5).

`-l` Sets the number of Pomodoro cycles (default: 1).

## License

This project is licensed under the MIT License.
