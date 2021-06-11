# Timestream Travel

A simple CLI application to backup time-series data from Amazon Timestream to S3.

## Requirements
 - Go 1.16+

## Build

```shell
$ go mod tidy
$ go build .
```

## Example usage

```shell
$ ./timestream-travel backup --debug --from "2021-06-09 00:00:00" --to "2021-06-12 00:00:00" --rows 200
```

## Usage documentation

```shell
$ ./timestream-travel -h
$ ./timestream-travel backup -h
```