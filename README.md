# td - Command Line Todo Manager

td is a simple command-line application built in Go using Cobra that allows you to manage your local todo list effortlessly. This project is a work in project so may not work as expected at present.

## Installation

Install td using `go install`:

```bash
go install github.com/yourusername/td@latest
```

## Usage

Commands:

- `td add` or `td a` - Add a new task to your todo list.
- `td list` or `td l` - List all tasks in your todo list.
- `td update` or `td u` - Update a task in your todo list.
- `td delete` or `td r` - Delete a task from your todo list.

Examples:

- To add a task:
  `./td add "Buy groceries"` or `./td a "Buy groceries"`

- To list all tasks:
  `./td list` or `./td l`

- To update a task:
  `./td update 1 "Buy more milk"` or `./td u 1 "Buy more milk"`

- To delete a task:
  `./td delete 1` or `./td r 1`

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## License

This project is licensed under the MIT License.
