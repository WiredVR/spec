# Interactable World Objects

Inside of a world content bundle, individual meshes can have flags specified in the `extras` object property, as keys:

- `activatable` -> Can be "pressed" if `true`
- `grabbable` -> Can be picked up be the user if `true`
- `object_id` -> String ID of a object. Used to identify the object within scripts.
