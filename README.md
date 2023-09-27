# city
Simple procedural city generator. Standalone Flecs project with embedded graphics modules ([live webasm demo](https://flecs.dev/city))

<img width="1194" alt="Screenshot 2023-09-27 at 1 35 29 AM" src="https://github.com/flecs-hub/city/assets/9919222/cc402eb2-e31a-4bbb-bd14-1dac397b8417">

## How to run
Use the following commands to run the demo:

Install bake on macOS/Linux:
```
git clone https://github.com/SanderMertens/bake
bake/setup.sh
```

Install bake on Windows
```
git clone https://github.com/SanderMertens/bake
cd bake
setup
```

or if you already have a bake installation:
```
bake upgrade
```

Then run:
```
bake run flecs-hub/city --cfg release
```

Have fun!

## How to use
To customize the city generation parameters, change the settings in the etc/assets/scene.plecs file.
