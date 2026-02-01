## MyBuild CookBook

Paste the recipe for the dependency in the `dependencies` section of your myBuild.json file and run `myBuild sync`.

### Arena
```json
        "arena": {
            "version": "0.1.1",
            "include_paths": [
                "include"
            ],
            "src": [
                "lib"
            ],
            "remote": "https://github.com/mainak55512/arena"
        }
```

### CString
```json
        "CString": {
            "version": "0.1.1",
            "include_paths": [
                "include"
            ],
            "src": [
                "lib"
            ],
            "remote": "https://github.com/mainak55512/CString"
        }
```

### Container
```json
        "container": {
            "version": "0.1.1",
            "include_paths": [
                "include"
            ],
            "src": [
                "lib"
            ],
            "remote": "https://github.com/mainak55512/container"
        }
```

### yyjson
```json
        "yyjson": {
            "version": "0.12.0",
            "include_paths": [
                "src"
            ],
            "src": [
                "src"
            ],
            "remote": "https://github.com/ibireme/yyjson"
        }
```
