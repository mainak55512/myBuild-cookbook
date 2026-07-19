# CLI Reference

`myBuild` is invoked as:

```
myBuild <command> [args]
```

Running `myBuild` with no command prints a short usage summary and exits with status `1`.

## Commands

### `init`

Initialize a new myBuild project in the current directory.

```
myBuild init
```

---

### `add <url>`

Add a remote library dependency by URL.

```
myBuild add <url>
```

**Arguments**

| Argument | Description |
|---|---|
| `url` | The URL of the library to add as a dependency |

---

### `add-lib [args...]`

Add one or more local libraries to the project.

```
myBuild add-lib [args...]
```

**Arguments**

| Argument | Description |
|---|---|
| `args...` | One or more local library paths/names to register |

---

### `add-flag [args...]`

Add one or more compiler/build flags to the project configuration.

```
myBuild add-flag [args...]
```

**Arguments**

| Argument | Description |
|---|---|
| `args...` | One or more flags to add to the build configuration |

---

### `build`

Build the project.

```
myBuild build
```

---

### `run`

Build (if needed) and run the project.

```
myBuild run
```

---

### `gen`

Generate a `compile_commands.json` file for the project, for use with editor/IDE tooling and language servers.

```
myBuild gen
```

---

### `sync`

Sync project dependencies (e.g. fetch/update declared libraries).

```
myBuild sync
```

---

## Exit Codes

| Code | Meaning |
|---|---|
| `0` | Command completed successfully |
| `1` | No command provided, or an unknown command was given |

## Quick Reference

| Command | Description |
|---|---|
| `init` | Initialize a new project |
| `add <url>` | Add a remote library dependency |
| `add-lib [args...]` | Add local library dependencies |
| `add-flag [args...]` | Add build flags |
| `build` | Build the project |
| `run` | Build and run the project |
| `gen` | Generate `compile_commands.json` |
| `sync` | Sync dependencies |

