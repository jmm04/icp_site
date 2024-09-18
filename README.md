# Initializing DFX

Run dfx in separate terminal

```
dfx start --clean
```

# Configuring dfx.json

```
{
    "canisters": {
      "icp_site": {
        "frontend": {
          "entrypoint": "src/index.html"
        },
        "source": ["src"],
        "type": "assets"
      }
    },
    "dfx": "0.23.0",
    "version": 1
  }
```

# Deploying your landing page (frontend)

Open VS Code and open a terminal instance and run:

```
dfx deploy
```
