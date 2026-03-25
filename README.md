# The "Rocks!" game

A spaceship shooter game for 2 simultaneous players.

# Run

```
sudo apt install lua5.4 liblua5.4-dev luarocks libsdl2-dev libsdl2-gfx-dev libsdl2-image-dev libsdl2-mixer-dev libsdl2-ttf-dev
sudo luarocks --lua-version=5.4 install pico-sdl 0.2
sudo luarocks --lua-version=5.4 install atmos-lang 0.5
git checkout v0.4
atmos main.atm
```

# Instructions

- Hit the other ship.
- Avoid the rocks!
- Controls:
    - Left Ship: `WASD` to move, `Shift Left` to shoot.
    - Right Ship: Arrow keys to move, `Shift Right` to shoot.
