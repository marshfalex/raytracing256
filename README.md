# Raytracer in C++

This project is a simple raytracer implemented in C++ based on the "Understandable RayTracing in 256 lines of bare C++" tutorial by Dmitry V. Sokolov.

## Features

- Renders spheres and a plane (chessboard)
- Implements Phong reflection model
- Supports diffuse and specular lighting
- Calculates shadows
- Handles reflections and refractions
- Uses an environment map for background

## Implementation Steps

1. Image writing to disk
2. Basic ray tracing for a single sphere
3. Multiple sphere rendering
4. Lighting implementation
5. Specular lighting
6. Shadow calculation
7. Reflections
8. Refractions
9. Plane (chessboard) rendering
10. Environment map integration

## Usage

To compile and run the project:

```bash
g++ -std=c++11 simpleraytracing.cpp -o simpleraytracing
./simpleraytracing
```

The program will generate an output image file named `out.jpg`.

## Dependencies

This project uses the `stb` library for image handling, particularly for the environment map feature.

## Configuration

You can modify the following parameters in the `simpleraytracing.cpp` file:

- Image dimensions (width and height)
- Field of view (fov)
- Maximum recursion depth for reflections and refractions
- Scene objects (spheres and plane)
- Light sources

## Acknowledgments

This project is based on the tutorial by Dmitry V. Sokolov. Special thanks to him for providing an understandable approach to raytracing.

## License

This project is open source and available under the MIT License.
