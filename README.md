## MyBuild CookBook

Paste the recipe for the dependency in the `dependencies` section of your myBuild.json file and run `myBuild sync`.

### Arena (lang: C)
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

### CString (lang: C)
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

### Container (lang: C)
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

### Cmap (lang: C)
```json
        "Cmap": {
            "version": "0.0.3",
            "include_paths": [
                "include"
            ],
            "src": [
                "lib"
            ],
            "remote": "https://github.com/mainak55512/Cmap"
        }
```

### yyjson (lang: C)
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

### Crow (lang: C++)
```json
        "Crow": {
            "version": "1.1.1",
            "flags": [
                "-std=c++17",
                "-O3",
                "-DASIO_NO_DEPRECATED",
                "-DCROW_ENABLE_SSL",
                "-DCROW_ENABLE_COMPRESSION"
            ],
            "include_paths": [
                "include"
            ],
            "src": [],
            "lib_links": [
                "-lpthread",
                "-lssl",
                "-lcrypto",
                "-lz"
            ],
            "remote": "https://github.com/CrowCpp/Crow"
        }    
```
