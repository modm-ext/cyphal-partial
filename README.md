# OpenCyphal partial tree

- https://github.com/OpenCyphal/libcanard
- https://github.com/OpenCyphal/public_regulated_data_types
- https://github.com/dronecan/libcanard
- https://github.com/dronecan/DSDL

This is just a partial copy of the Cyphal and DroneCAN libraries and data types
to reduce repository size. The following paths are extracted:

- `libcanard/LICENSE`
- `libcanard/libcanard/`
- `libcanard/lib/cavl2/`
- `public_regulated_data_types/LICENSE`
- `public_regulated_data_types/reg/`
- `public_regulated_data_types/uavcan/`
- `dronecan/libcanard/`: `LICENSE`, `canard.c`, `canard.h`, `canard_internals.h`
- `dronecan/dsdl/`: `LICENSE` and the `*.uavcan` files of all namespaces

This repository is updated periodically by GitHub Actions.
