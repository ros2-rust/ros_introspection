# ros_introspection

`ros_introspection` is a Rust crate designed to parse and analyze ROS (Robot Operating System) message definitions. It provides utilities to introspect ROS message types. This crate is useful for developers building tools or applications that need to interact with ROS environments without relying on the full ROS runtime.

## Features

- Parse ROS message definitions (`.msg` files).
- Inspect and analyze ROS topics and their types.
- Lightweight and efficient, suitable for embedded or resource-constrained systems.

## Use Cases

- Building custom ROS tools or diagnostics.
- Interfacing with ROS systems in non-ROS environments.
- Analyzing or debugging ROS message data.

## Getting Started

Add the following to your `Cargo.toml` to include `ros_introspection` in your project:

```toml
[dependencies]
ros_introspection = "0.1"
```

## Thanks

The development of this project was originally funded by [Rerun](https://rerun.io/), go check them out, they're building really cool stuff!