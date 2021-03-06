# pomodoro
A simple CLI application that helps you use the Pomodoro Technique.

## Why another Pomodoro application?
A colleague of mine ([@zehreken](https://github.com/zehreken)) had created a [very simple Pomodoro tool](https://gist.github.com/zehreken/0ab28b74961673ff45fd330a445e298e) using Bash a while ago. I liked it a lot because of its simplicity and have been using that. It works like a charm; however, I wanted to improve it by adding some nifty features like being able to gets stats based on your performance.

## 3rd Party Libraries

* [boltdb](https://github.com/boltdb/bolt) - An embedded key/value database for Go. I use this one to store session logs.

## Usage Examples

* `pomodoro <numberOfMinutes>`: Starting a new timer (e.g. The command `pomodoro 15` starts a new timer that will alert back in 15 minutes).
* `pomodoro -l`: Dumps the session logs.
