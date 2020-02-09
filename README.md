# ga-raytracer

Geometric Algebra 2D Raytracer using c2ga and OpenGL

## Notes

The inner product of two normalized points gives the square of the Euclidean distance.

## TODO

- [x] Create point
- [x] Create point pair
- [x] Create line
- [x] Create circle
- [x] Intersect lines
- [x] Intersect circles
- [x] Project point on line
- [x] Project point on circle
- [x] Display the two points from a point pair
- [x] IsPointInCircle
- [ ] Get position of point on a line
- [ ] Fix mirror bug in intersection with circle

## Optimisation

- [x] glTexImage2D
- [x] Randomize array of pixel to draw
- [x] Draw only range by range of pixels
- [x] In fragment shader, fill the blanks based on neighbours pixels color.
