# Worlds

World content bundles contain a `world.json` file in the root of the bundle. Here is an example `world.json`.

```json
{
  "schema_version": "1.0",
  "name": "The Longest Night",
  "description": "A lone star casts its light",
  "models": {
    {
      "path": "./world.gltf"
    }
  },
  "shaders": {
     {
      "path": "./shaders/poiyomi-shader-real-legit.spv"
     }
  },
  "modules": {
    {
      "path": "./scripts/world_script.wasm"
    }
  }
}
```

## Object API

- [Interactions](./INTERACTIONS.md)
