# Flash

Flash is a Discord bot written in .go that automatically claims and redeems Discord nitro publicly sent to any server you are apart of. 

### Requirements

Flash uses a number of open source projects to work properly:

* Go
* CLI

### Installation
Flash requires [Go](https://golang.org/dl/) to run.

Flash also uses a number of dependencies which can be installed by running the commands below in the bot directory:
```sh
$ go get encoding/json
$ go get flag
$ go get fmt
$ go get github.com/bwmarrin/discordgo
$ go get github.com/fatih/color
$ go get github.com/valyala/fasthttp
$ go getio/ioutil
$ go get os
$ go get os/exec
$ go getos/signal
$ go get regexp
$ go get strconv
$ go get strings
$ go get syscall
$ go get time
```
Not sure if there is a way to collectively import the packages from a text file but for now this is the way to go about it.

Lastly, add your [Discord user token](https://github.com/Tyrrrz/DiscordChatExporter/wiki/Obtaining-Token-and-Channel-IDs) to the token.json file. After you have added your token, run the command below to start the bot.
```sh
$ go run flash.go
```
### Screenshots
![Bot](https://i.imgur.com/ebsvBrh.png)
