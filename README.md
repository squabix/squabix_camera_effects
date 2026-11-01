# SQUABIX Camera Effects

Camera shake and simple cutscene camera moves for 3D games.

## Classes

- `CameraShake3D`
- `Cutscene3D`

## Use

1. Add a `CameraShake3D` and set `camera`.
2. Call `CameraShake3D.shake(amount, position)` from anywhere.
3. Add a `Cutscene3D` and set `camera`.
4. Call `begin()`, then `cut_to()`, `move_to()`, or `zoom_to()`, then `end()`.

Override `add_trauma()` in a script that extends `CameraShake3D` to turn shake off with your own setting.

## Demo

See it in the game: https://github.com/squabix/craftlander

## Needs

Godot 4.5 or newer.

## License

MIT. See `LICENSE`.
Icons are from another project. See `THIRD_PARTY.md`.
