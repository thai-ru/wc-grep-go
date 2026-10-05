# wc-grep-go

Clones of the Unix `wc` and `grep` tools, written in Go from scratch.

**Status:** in progress (Step 0: repo setup)

## Why

After a couple of years away from full-time work, I wanted to stop circling between interests and choose one path. I'm rebuilding my skills in public through 13 infrastructure projects in Go, starting with clones of wc and grep. The goal is depth, finished work, and a visible record of how I think.
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