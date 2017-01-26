# tt : CLI translation tool

## Requirement

- Go

## Installtion

```
$ export GOBIN=/path/to/bin
$ go get github.com/ysugimoto/tt/...
```

This command connet to [Microsoft Translator Text API](https://www.microsoft.com/en-us/translator/translatorapi.aspx), So you need to get API key on Azure.

## Usage

First, create key file:

```
$ echo "[Your API key]" > ~/.ttkey
```

Put statement following `tt` command arguments:

```
$ tt hello world
>> ハローワールド;
```

This tool detect automatic translation from->to. Translation supports `en->ja` or `ja->en` only.

## Author

Yoshiaki Sugimoto <sugimoto@wnotes.net>

## Lisence

MIT

