# wc-grep-go

Clones of the Unix `wc` and `grep` tools, written in Go from scratch.

**Status:** in progress (Step 0: repo setup)

## Why

[One honest line in your own words: why you're building this.]

## Layout

- `cmd/wc`, `cmd/grep`: one `main` package per binary
- `internal/wc`, `internal/grep`: the logic behind each tool

## Build

```
go build -o bin/wc ./cmd/wc
go build -o bin/grep ./cmd/grep
```

## Credits

Inspired by John Crickett's Coding Challenges (codingchallenges.fyi).
This is project 1 of a series of 13 infrastructure projects in Go.