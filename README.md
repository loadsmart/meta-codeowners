# meta-codeowners

Manipulate [CODEOWNERS](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-code-owners) file.

## Installation

```shell
npm install meta-codeowners
```

## Commands

### add

Adds an entry to the `CODEOWNERS` file.

```shell
meta codeowners add --pattern '*' team-a team-b
```

### rename

Replaces `old-team` with `new-team` in `CODEOWNERS` file.

```shell
meta codeowners rename old-team new-team
```

## License

Licensed under MIT. See [LICENSE](./LICENSE) file for details.
