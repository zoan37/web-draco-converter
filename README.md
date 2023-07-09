# web-draco-timing

This is a port of the Draco Decode Timing demo from the [Draco repo](https://github.com/google/draco) that is deployable on the web (with WASM and local file upload).
It is useful for timing how long it takes Draco to decode a compressed OBJ, STL, or PLY file on the web browser.

For using Draco encoding/decoding on the web in practice, it is probably better to go with Three.js [DRACOLoader](https://threejs.org/docs/#examples/en/loaders/DRACOLoader ) and [DRACOExporter](https://threejs.org/docs/?q=draco#examples/en/exporters/DRACOExporter ).
