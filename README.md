# Goproxy China

A trusted Go module proxy located in China.

This project has fully implemented the Go's
[module proxy protocol](https://golang.org/cmd/go/#hdr-Module_proxy_protocol).
And it's a non-profit project that will (when it is fully tested) run on China's
well-trusted cloud service provider [Qiniu Cloud](https://www.qiniu.com). The
goal of this project is to provide a free, trusted, always on, and CDNed Go
module proxy for Gophers in China and around the world.

Happy coding, Gophers! ;-)

## Usage

### macOS or Linux

Open your terminal and execute

```bash
$ export GOPROXY=https://goproxy.cn # Temporary
```

or

```bash
$ echo "GOPROXY=https://goproxy.cn" >> ~/.profile && source ~/.profile
```

done.

### Windows

Open your PowerShell and execute

```poweshell
C:\> $env:GOPROXY = "https://goproxy.cn" # Temporary
```

or

```md
1. Open the Start Search, type in "env"
2. Choose the "Edit the system environment variables"
3. Click the "Environment Variables…" button
4. Under the "User variables for <YOUR_USERNAME>" section (the upper half)
5. Click the "New..." button
6. Choose the "Variable name" input bar, type in "GOPROXY"
7. Choose the "Variable value" input bar, type in "https://goproxy.cn"
8. Click the "OK" button
```

done.

## Community

If you want to discuss this project, or ask questions about it, simply post
questions or ideas [here](https://github.com/goproxy/goproxy.cn/issues).

## Contributing

If you want to help build this project, simply follow
[this](https://github.com/goproxy/goproxy.cn/wiki/Contributing) to send pull
requests [here](https://github.com/goproxy/goproxy.cn/pulls).

## License

This project is licensed under the Unlicense.

License can be found [here](LICENSE).
