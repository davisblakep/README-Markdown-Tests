# README-Markdown-Tests
Testing various markdown extensions in the README.md file

<br>

[GitHub Readme Markdown Docs](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams)

<br>

## Flow Chart

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## GeoJSON

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

## TopoJSON

```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "value0"},
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "properties": {"prop0": "value0", "prop1": 0},
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {"prop0": "value0",
            "prop1": {"this": "that"}
          },
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```

## STL 3D Models

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```

## Additional STL File Tests

```stl
    solid MYSOLID created by IVCON, original data in file.obj
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.250000 -2.480000 14.000000
      vertex 3.250000 -2.480000 9.010000
      vertex 3.250000 2.480000 9.010000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.250000 -2.480000 14.000000
      vertex 3.250000 2.480000 9.010000
      vertex 3.250000 2.480000 14.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.773000 -2.480000 14.000000
      vertex 0.773000 -2.480000 9.010000
      vertex 3.250000 -2.480000 9.010000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.773000 -2.480000 14.000000
      vertex 3.250000 -2.480000 9.010000
      vertex 3.250000 -2.480000 14.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.773000 2.480000 14.000000
      vertex 0.773000 2.480000 9.010000
      vertex 0.773000 -2.480000 9.010000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.773000 2.480000 14.000000
      vertex 0.773000 -2.480000 9.010000
      vertex 0.773000 -2.480000 14.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.250000 2.480000 14.000000
      vertex 3.250000 2.480000 9.010000
      vertex 0.773000 2.480000 9.010000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.250000 2.480000 14.000000
      vertex 0.773000 2.480000 9.010000
      vertex 0.773000 2.480000 14.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.773000 2.480000 14.000000
      vertex 0.773000 -2.480000 14.000000
      vertex 3.250000 -2.480000 14.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.773000 2.480000 14.000000
      vertex 3.250000 -2.480000 14.000000
      vertex 3.250000 2.480000 14.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.250000 -2.480000 9.010000
      vertex 0.773000 -2.480000 9.010000
      vertex 0.773000 2.480000 9.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.250000 -2.480000 9.010000
      vertex 0.773000 2.480000 9.010000
      vertex 3.250000 2.480000 9.010000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.470000 -1.290000 17.400000
      vertex 3.470000 -1.290000 15.000000
      vertex 3.470000 1.190000 15.000000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.470000 -1.290000 17.400000
      vertex 3.470000 1.190000 15.000000
      vertex 3.470000 1.190000 17.400000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.601000 -1.290000 17.400000
      vertex 0.601000 -1.290000 15.000000
      vertex 3.470000 -1.290000 15.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.601000 -1.290000 17.400000
      vertex 3.470000 -1.290000 15.000000
      vertex 3.470000 -1.290000 17.400000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.601000 1.190000 17.400000
      vertex 0.601000 1.190000 15.000000
      vertex 0.601000 -1.290000 15.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.601000 1.190000 17.400000
      vertex 0.601000 -1.290000 15.000000
      vertex 0.601000 -1.290000 17.400000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.470000 1.190000 17.400000
      vertex 3.470000 1.190000 15.000000
      vertex 0.601000 1.190000 15.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.470000 1.190000 17.400000
      vertex 0.601000 1.190000 15.000000
      vertex 0.601000 1.190000 17.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.601000 1.190000 17.400000
      vertex 0.601000 -1.290000 17.400000
      vertex 3.470000 -1.290000 17.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.601000 1.190000 17.400000
      vertex 3.470000 -1.290000 17.400000
      vertex 3.470000 1.190000 17.400000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.470000 -1.290000 15.000000
      vertex 0.601000 -1.290000 15.000000
      vertex 0.601000 1.190000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.470000 -1.290000 15.000000
      vertex 0.601000 1.190000 15.000000
      vertex 3.470000 1.190000 15.000000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.150000 -2.470000 8.010000
      vertex 3.150000 -2.470000 3.050000
      vertex 3.150000 -0.486000 3.050000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.150000 -2.470000 8.010000
      vertex 3.150000 -0.486000 3.050000
      vertex 3.150000 -0.486000 8.010000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.892000 -2.470000 8.010000
      vertex 0.892000 -2.470000 3.050000
      vertex 3.150000 -2.470000 3.050000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.892000 -2.470000 8.010000
      vertex 3.150000 -2.470000 3.050000
      vertex 3.150000 -2.470000 8.010000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.892000 -0.486000 8.010000
      vertex 0.892000 -0.486000 3.050000
      vertex 0.892000 -2.470000 3.050000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.892000 -0.486000 8.010000
      vertex 0.892000 -2.470000 3.050000
      vertex 0.892000 -2.470000 8.010000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.150000 -0.486000 8.010000
      vertex 3.150000 -0.486000 3.050000
      vertex 0.892000 -0.486000 3.050000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.150000 -0.486000 8.010000
      vertex 0.892000 -0.486000 3.050000
      vertex 0.892000 -0.486000 8.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.892000 -0.486000 8.010000
      vertex 0.892000 -2.470000 8.010000
      vertex 3.150000 -2.470000 8.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.892000 -0.486000 8.010000
      vertex 3.150000 -2.470000 8.010000
      vertex 3.150000 -0.486000 8.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.150000 -2.470000 3.050000
      vertex 0.892000 -2.470000 3.050000
      vertex 0.892000 -0.486000 3.050000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.150000 -2.470000 3.050000
      vertex 0.892000 -0.486000 3.050000
      vertex 3.150000 -0.486000 3.050000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.230000 -3.960000 14.000000
      vertex 3.230000 -3.960000 9.010000
      vertex 3.230000 -2.480000 9.010000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.230000 -3.960000 14.000000
      vertex 3.230000 -2.480000 9.010000
      vertex 3.230000 -2.480000 14.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.747000 -3.960000 14.000000
      vertex 0.747000 -3.960000 9.010000
      vertex 3.230000 -3.960000 9.010000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.747000 -3.960000 14.000000
      vertex 3.230000 -3.960000 9.010000
      vertex 3.230000 -3.960000 14.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.747000 -2.480000 14.000000
      vertex 0.747000 -2.480000 9.010000
      vertex 0.747000 -3.960000 9.010000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.747000 -2.480000 14.000000
      vertex 0.747000 -3.960000 9.010000
      vertex 0.747000 -3.960000 14.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.230000 -2.480000 14.000000
      vertex 3.230000 -2.480000 9.010000
      vertex 0.747000 -2.480000 9.010000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.230000 -2.480000 14.000000
      vertex 0.747000 -2.480000 9.010000
      vertex 0.747000 -2.480000 14.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.747000 -2.480000 14.000000
      vertex 0.747000 -3.960000 14.000000
      vertex 3.230000 -3.960000 14.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.747000 -2.480000 14.000000
      vertex 3.230000 -3.960000 14.000000
      vertex 3.230000 -2.480000 14.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.230000 -3.960000 9.010000
      vertex 0.747000 -3.960000 9.010000
      vertex 0.747000 -2.480000 9.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.230000 -3.960000 9.010000
      vertex 0.747000 -2.480000 9.010000
      vertex 3.230000 -2.480000 9.010000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.270000 2.460000 14.000000
      vertex 3.270000 2.460000 9.010000
      vertex 3.270000 3.950000 9.010000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.270000 2.460000 14.000000
      vertex 3.270000 3.950000 9.010000
      vertex 3.270000 3.950000 14.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.795000 2.460000 14.000000
      vertex 0.795000 2.460000 9.010000
      vertex 3.270000 2.460000 9.010000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.795000 2.460000 14.000000
      vertex 3.270000 2.460000 9.010000
      vertex 3.270000 2.460000 14.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.795000 3.950000 14.000000
      vertex 0.795000 3.950000 9.010000
      vertex 0.795000 2.460000 9.010000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.795000 3.950000 14.000000
      vertex 0.795000 2.460000 9.010000
      vertex 0.795000 2.460000 14.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.270000 3.950000 14.000000
      vertex 3.270000 3.950000 9.010000
      vertex 0.795000 3.950000 9.010000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.270000 3.950000 14.000000
      vertex 0.795000 3.950000 9.010000
      vertex 0.795000 3.950000 14.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.795000 3.950000 14.000000
      vertex 0.795000 2.460000 14.000000
      vertex 3.270000 2.460000 14.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.795000 3.950000 14.000000
      vertex 3.270000 2.460000 14.000000
      vertex 3.270000 3.950000 14.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.270000 2.460000 9.010000
      vertex 0.795000 2.460000 9.010000
      vertex 0.795000 3.950000 9.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.270000 2.460000 9.010000
      vertex 0.795000 3.950000 9.010000
      vertex 3.270000 3.950000 9.010000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 2.490000 -0.498000 15.000000
      vertex 2.490000 -0.498000 14.000000
      vertex 2.490000 0.493000 14.000000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 2.490000 -0.498000 15.000000
      vertex 2.490000 0.493000 14.000000
      vertex 2.490000 0.493000 15.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 1.500000 -0.498000 15.000000
      vertex 1.500000 -0.498000 14.000000
      vertex 2.490000 -0.498000 14.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 1.500000 -0.498000 15.000000
      vertex 2.490000 -0.498000 14.000000
      vertex 2.490000 -0.498000 15.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 1.500000 0.493000 15.000000
      vertex 1.500000 0.493000 14.000000
      vertex 1.500000 -0.498000 14.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 1.500000 0.493000 15.000000
      vertex 1.500000 -0.498000 14.000000
      vertex 1.500000 -0.498000 15.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 2.490000 0.493000 15.000000
      vertex 2.490000 0.493000 14.000000
      vertex 1.500000 0.493000 14.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 2.490000 0.493000 15.000000
      vertex 1.500000 0.493000 14.000000
      vertex 1.500000 0.493000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 1.500000 0.493000 15.000000
      vertex 1.500000 -0.498000 15.000000
      vertex 2.490000 -0.498000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 1.500000 0.493000 15.000000
      vertex 2.490000 -0.498000 15.000000
      vertex 2.490000 0.493000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 2.490000 -0.498000 14.000000
      vertex 1.500000 -0.498000 14.000000
      vertex 1.500000 0.493000 14.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 2.490000 -0.498000 14.000000
      vertex 1.500000 0.493000 14.000000
      vertex 2.490000 0.493000 14.000000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.250000 -2.500000 9.010000
      vertex 3.250000 -2.500000 8.010000
      vertex 3.250000 2.450000 8.010000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.250000 -2.500000 9.010000
      vertex 3.250000 2.450000 8.010000
      vertex 3.250000 2.450000 9.010000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.771000 -2.500000 9.010000
      vertex 0.771000 -2.500000 8.010000
      vertex 3.250000 -2.500000 8.010000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.771000 -2.500000 9.010000
      vertex 3.250000 -2.500000 8.010000
      vertex 3.250000 -2.500000 9.010000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.771000 2.450000 9.010000
      vertex 0.771000 2.450000 8.010000
      vertex 0.771000 -2.500000 8.010000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.771000 2.450000 9.010000
      vertex 0.771000 -2.500000 8.010000
      vertex 0.771000 -2.500000 9.010000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.250000 2.450000 9.010000
      vertex 3.250000 2.450000 8.010000
      vertex 0.771000 2.450000 8.010000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.250000 2.450000 9.010000
      vertex 0.771000 2.450000 8.010000
      vertex 0.771000 2.450000 9.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.771000 2.450000 9.010000
      vertex 0.771000 -2.500000 9.010000
      vertex 3.250000 -2.500000 9.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.771000 2.450000 9.010000
      vertex 3.250000 -2.500000 9.010000
      vertex 3.250000 2.450000 9.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.250000 -2.500000 8.010000
      vertex 0.771000 -2.500000 8.010000
      vertex 0.771000 2.450000 8.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.250000 -2.500000 8.010000
      vertex 0.771000 2.450000 8.010000
      vertex 3.250000 2.450000 8.010000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.270000 0.465000 8.010000
      vertex 3.270000 0.465000 3.050000
      vertex 3.270000 2.450000 3.050000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 3.270000 0.465000 8.010000
      vertex 3.270000 2.450000 3.050000
      vertex 3.270000 2.450000 8.010000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.795000 0.465000 8.010000
      vertex 0.795000 0.465000 3.050000
      vertex 3.270000 0.465000 3.050000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 0.795000 0.465000 8.010000
      vertex 3.270000 0.465000 3.050000
      vertex 3.270000 0.465000 8.010000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.795000 2.450000 8.010000
      vertex 0.795000 2.450000 3.050000
      vertex 0.795000 0.465000 3.050000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 0.795000 2.450000 8.010000
      vertex 0.795000 0.465000 3.050000
      vertex 0.795000 0.465000 8.010000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.270000 2.450000 8.010000
      vertex 3.270000 2.450000 3.050000
      vertex 0.795000 2.450000 3.050000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 3.270000 2.450000 8.010000
      vertex 0.795000 2.450000 3.050000
      vertex 0.795000 2.450000 8.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.795000 2.450000 8.010000
      vertex 0.795000 0.465000 8.010000
      vertex 3.270000 0.465000 8.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.795000 2.450000 8.010000
      vertex 3.270000 0.465000 8.010000
      vertex 3.270000 2.450000 8.010000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.270000 0.465000 3.050000
      vertex 0.795000 0.465000 3.050000
      vertex 0.795000 2.450000 3.050000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.270000 0.465000 3.050000
      vertex 0.795000 2.450000 3.050000
      vertex 3.270000 2.450000 3.050000
    endloop
  endfacet
endsolid MYSOLID
      ```
      
      <br>
      
 ```stl
 solid MYSOLID
  facet normal  -0.470578     -0.335539      0.816070    
    outer loop
      vertex   0.000000E+00  -12.5120       1.76950    
      vertex   0.460000E-02  -11.7876       2.07000    
      vertex   -1.78420      -11.8027       1.03230    
    endloop
  endfacet
  facet normal  -0.470359     -0.336719     -0.815710    
    outer loop
      vertex   -1.53240      -12.5120     -0.884700    
      vertex   -1.78420      -11.8027      -1.03230    
      vertex   0.460000E-02  -11.7876      -2.07000    
    endloop
  endfacet
  facet normal   0.939923     -0.341387      0.000000E+00
    outer loop
      vertex    1.53240      -12.5120     -0.884700    
      vertex    1.80230      -11.7689      -1.03730    
      vertex    1.80230      -11.7689       1.03730    
    endloop
  endfacet
  facet normal   0.414021     -0.560697      0.717081    
    outer loop
      vertex    1.80230      -11.7689       1.03730    
      vertex    2.47780      -10.5144       1.62820    
      vertex  -0.342400      -10.5144       3.25650    
    endloop
  endfacet
  facet normal   0.418526     -0.555509     -0.718502    
    outer loop
      vertex    1.80230      -11.7689      -1.03730    
      vertex   0.460000E-02  -11.7876      -2.07000    
      vertex  -0.342400      -10.5144      -3.25650    
    endloop
  endfacet
  facet normal  -0.682826     -0.730581      0.000000E+00
    outer loop
      vertex   -1.78420      -11.8027      -1.03230    
      vertex   -1.78420      -11.8027       1.03230    
      vertex   -3.16260      -10.5144       1.62820    
    endloop
  endfacet
  facet normal   0.500029      0.000000E+00  0.866009    
    outer loop
      vertex    1.53240      -15.8553      0.884700    
      vertex    1.53240      -12.5120      0.884700    
      vertex   0.000000E+00  -12.5120       1.76950    
    endloop
  endfacet
  facet normal   0.500029      0.000000E+00 -0.866009    
    outer loop
      vertex   0.000000E+00  -15.8553      -1.76950    
      vertex   0.000000E+00  -12.5120      -1.76950    
      vertex    1.53240      -12.5120     -0.884700    
    endloop
  endfacet
  facet normal   -1.00000      0.000000E+00  0.000000E+00
    outer loop
      vertex   -1.53240      -15.8553      0.884700    
      vertex   -1.53240      -12.5120      0.884700    
      vertex   -1.53240      -12.5120     -0.884700    
    endloop
  endfacet
  facet normal   0.490289     -0.196414      0.849140    
    outer loop
      vertex    1.41990      -16.4167      0.819800    
      vertex    1.53240      -15.8553      0.884700    
      vertex   0.000000E+00  -15.8553       1.76950    
    endloop
  endfacet
  facet normal   0.490283     -0.196476     -0.849129    
    outer loop
      vertex   0.000000E+00  -16.4167      -1.63960    
      vertex   0.000000E+00  -15.8553      -1.76950    
      vertex    1.53240      -15.8553     -0.884700    
    endloop
  endfacet
  facet normal  -0.980507     -0.196486      0.000000E+00
    outer loop
      vertex   -1.41990      -16.4167      0.819800    
      vertex   -1.53240      -15.8553      0.884700    
      vertex   -1.53240      -15.8553     -0.884700    
    endloop
  endfacet
  facet normal  -0.488143      0.136594      0.862009    
    outer loop
      vertex  -0.135800      -23.0301       1.32280    
      vertex   -1.24250      -22.9134      0.677600    
      vertex   -4.36120      -39.3325       1.51330    
    endloop
  endfacet
  facet normal  -0.495804      0.499932E-01 -0.866994    
    outer loop
      vertex   -1.24520      -22.9561     -0.608000    
      vertex  -0.141100      -23.1157      -1.24860    
      vertex   -3.27580      -39.6364     -0.408600    
    endloop
  endfacet
  facet normal   0.982515     -0.186137      0.419557E-02
    outer loop
      vertex   0.965700      -23.2324     -0.603400    
      vertex   0.968300      -23.1897      0.682200    
      vertex   -2.17220      -39.7477       1.52370    
    endloop
  endfacet
  facet normal  -0.494415      0.907475E-01  0.864476    
    outer loop
      vertex   -1.11400      -21.8856      0.643200    
      vertex   -1.24250      -22.9134      0.677600    
      vertex  -0.135800      -23.0301       1.32280    
    endloop
  endfacet
  facet normal  -0.497970      0.332519E-01 -0.866556    
    outer loop
      vertex  -0.126000E-01  -22.0878      -1.28300    
      vertex  -0.141100      -23.1157      -1.24860    
      vertex   -1.24520      -22.9561     -0.608000    
    endloop
  endfacet
  facet normal   0.992283     -0.123977      0.211114E-02
    outer loop
      vertex    1.09680      -22.1618      0.647800    
      vertex   0.968300      -23.1897      0.682200    
      vertex   0.965700      -23.2324     -0.603400    
    endloop
  endfacet
  facet normal  -0.999998      0.000000E+00  0.210009E-02
    outer loop
      vertex   -1.11670      -21.9283     -0.642500    
      vertex   -1.11400      -21.8856      0.643200    
      vertex   -1.11400      -21.0411      0.643200    
    endloop
  endfacet
  facet normal   0.499980     -0.124530E-01 -0.865948    
    outer loop
      vertex   0.000000E+00  -21.0411      -1.28640    
      vertex    1.11400      -21.0411     -0.643200    
      vertex    1.09420      -22.2046     -0.637900    
    endloop
  endfacet
  facet normal   0.500017     -0.208534E-02  0.866013    
    outer loop
      vertex    1.11400      -21.0411      0.643200    
      vertex   0.000000E+00  -21.0411       1.28640    
      vertex  -0.730000E-02  -22.0024       1.28830    
    endloop
  endfacet
  facet normal  -0.486990     -0.226715      0.843470    
    outer loop
      vertex   0.000000E+00  -19.7270       1.63960    
      vertex   -1.41990      -19.7270      0.819800    
      vertex   -1.11400      -21.0411      0.643200    
    endloop
  endfacet
  facet normal  -0.486991     -0.226706     -0.843472    
    outer loop
      vertex   -1.41990      -19.7270     -0.819800    
      vertex   0.000000E+00  -19.7270      -1.63960    
      vertex   0.000000E+00  -21.0411      -1.28640    
    endloop
  endfacet
  facet normal   0.973960     -0.226721      0.000000E+00
    outer loop
      vertex    1.41990      -19.7270     -0.819800    
      vertex    1.41990      -19.7270      0.819800    
      vertex    1.11400      -21.0411      0.643200    
    endloop
  endfacet
  facet normal  -0.500009      0.000000E+00  0.866020    
    outer loop
      vertex   0.000000E+00  -16.4167       1.63960    
      vertex   -1.41990      -16.4167      0.819800    
      vertex   -1.41990      -19.7270      0.819800    
    endloop
  endfacet
  facet normal  -0.500009      0.000000E+00 -0.866020    
    outer loop
      vertex   -1.41990      -16.4167     -0.819800    
      vertex   0.000000E+00  -16.4167      -1.63960    
      vertex   0.000000E+00  -19.7270      -1.63960    
    endloop
  endfacet
  facet normal    1.00000      0.000000E+00  0.000000E+00
    outer loop
      vertex    1.41990      -16.4167     -0.819800    
      vertex    1.41990      -16.4167      0.819800    
      vertex    1.41990      -19.7270      0.819800    
    endloop
  endfacet
  facet normal   0.500009      0.000000E+00  0.866020    
    outer loop
      vertex   0.000000E+00  -16.4167       1.63960    
      vertex   0.000000E+00  -19.7270       1.63960    
      vertex    1.41990      -19.7270      0.819800    
    endloop
  endfacet
  facet normal   0.500009      0.000000E+00 -0.866020    
    outer loop
      vertex   0.000000E+00  -16.4167      -1.63960    
      vertex    1.41990      -16.4167     -0.819800    
      vertex    1.41990      -19.7270     -0.819800    
    endloop
  endfacet
  facet normal   -1.00000      0.000000E+00  0.000000E+00
    outer loop
      vertex   -1.41990      -16.4167      0.819800    
      vertex   -1.41990      -16.4167     -0.819800    
      vertex   -1.41990      -19.7270     -0.819800    
    endloop
  endfacet
  facet normal   0.486991     -0.226706      0.843472    
    outer loop
      vertex    1.41990      -19.7270      0.819800    
      vertex   0.000000E+00  -19.7270       1.63960    
      vertex   0.000000E+00  -21.0411       1.28640    
    endloop
  endfacet
  facet normal   0.486990     -0.226715     -0.843470    
    outer loop
      vertex   0.000000E+00  -19.7270      -1.63960    
      vertex    1.41990      -19.7270     -0.819800    
      vertex    1.11400      -21.0411     -0.643200    
    endloop
  endfacet
  facet normal  -0.973960     -0.226721      0.000000E+00
    outer loop
      vertex   -1.41990      -19.7270      0.819800    
      vertex   -1.41990      -19.7270     -0.819800    
      vertex   -1.11400      -21.0411     -0.643200    
    endloop
  endfacet
  facet normal  -0.500019      0.000000E+00  0.866015    
    outer loop
      vertex   0.000000E+00  -21.0411       1.28640    
      vertex   -1.11400      -21.0411      0.643200    
      vertex   -1.11400      -21.8856      0.643200    
    endloop
  endfacet
  facet normal   0.999882     -0.153457E-01  0.000000E+00
    outer loop
      vertex    1.11400      -21.0411     -0.643200    
      vertex    1.11400      -21.0411      0.643200    
      vertex    1.09680      -22.1618      0.647800    
    endloop
  endfacet
  facet normal  -0.500016      0.320607E-02 -0.866010    
    outer loop
      vertex   -1.11400      -21.0411     -0.643200    
      vertex   0.000000E+00  -21.0411      -1.28640    
      vertex  -0.126000E-01  -22.0878      -1.28300    
    endloop
  endfacet
  facet normal   0.497980     -0.331753E-01  0.866554    
    outer loop
      vertex  -0.730000E-02  -22.0024       1.28830    
      vertex  -0.135800      -23.0301       1.32280    
      vertex   0.968300      -23.1897      0.682200    
    endloop
  endfacet
  facet normal   0.494372     -0.908267E-01 -0.864492    
    outer loop
      vertex    1.09420      -22.2046     -0.637900    
      vertex   0.965700      -23.2324     -0.603400    
      vertex  -0.141100      -23.1157      -1.24860    
    endloop
  endfacet
  facet normal  -0.992281      0.123991     -0.203418E-02
    outer loop
      vertex   -1.11670      -21.9283     -0.642500    
      vertex   -1.24520      -22.9561     -0.608000    
      vertex   -1.24250      -22.9134      0.677600    
    endloop
  endfacet
  facet normal   0.495801     -0.500178E-01  0.866995    
    outer loop
      vertex   0.968300      -23.1897      0.682200    
      vertex  -0.135800      -23.0301       1.32280    
      vertex   -3.26370      -39.5080       2.16090    
    endloop
  endfacet
  facet normal   0.488143     -0.136368     -0.862044    
    outer loop
      vertex  -0.141100      -23.1157      -1.24860    
      vertex   0.965700      -23.2324     -0.603400    
      vertex   -2.17830      -39.8119      0.239000    
    endloop
  endfacet
  facet normal  -0.982475      0.186337     -0.464645E-02
    outer loop
      vertex   -1.24520      -22.9561     -0.608000    
      vertex   -4.36730      -39.3967      0.228500    
      vertex   -4.36120      -39.3325       1.51330    
    endloop
  endfacet
  facet normal  -0.490283     -0.196476      0.849129    
    outer loop
      vertex   0.000000E+00  -16.4167       1.63960    
      vertex   0.000000E+00  -15.8553       1.76950    
      vertex   -1.53240      -15.8553      0.884700    
    endloop
  endfacet
  facet normal  -0.490289     -0.196414     -0.849140    
    outer loop
      vertex   -1.41990      -16.4167     -0.819800    
      vertex   -1.53240      -15.8553     -0.884700    
      vertex   0.000000E+00  -15.8553      -1.76950    
    endloop
  endfacet
  facet normal   0.980507     -0.196486      0.000000E+00
    outer loop
      vertex    1.41990      -16.4167     -0.819800    
      vertex    1.53240      -15.8553     -0.884700    
      vertex    1.53240      -15.8553      0.884700    
    endloop
  endfacet
  facet normal  -0.500029      0.000000E+00  0.866009    
    outer loop
      vertex   0.000000E+00  -15.8553       1.76950    
      vertex   0.000000E+00  -12.5120       1.76950    
      vertex   -1.53240      -12.5120      0.884700    
    endloop
  endfacet
  facet normal  -0.500029      0.000000E+00 -0.866009    
    outer loop
      vertex   -1.53240      -15.8553     -0.884700    
      vertex   -1.53240      -12.5120     -0.884700    
      vertex   0.000000E+00  -12.5120      -1.76950    
    endloop
  endfacet
  facet normal    1.00000      0.000000E+00  0.000000E+00
    outer loop
      vertex    1.53240      -15.8553     -0.884700    
      vertex    1.53240      -12.5120     -0.884700    
      vertex    1.53240      -12.5120      0.884700    
    endloop
  endfacet
  facet normal  -0.360466     -0.686615      0.631367    
    outer loop
      vertex   -1.78420      -11.8027       1.03230    
      vertex   0.460000E-02  -11.7876       2.07000    
      vertex  -0.342400      -10.5144       3.25650    
    endloop
  endfacet
  facet normal  -0.362720     -0.681891     -0.635184    
    outer loop
      vertex   0.460000E-02  -11.7876      -2.07000    
      vertex   -1.78420      -11.8027      -1.03230    
      vertex   -3.16260      -10.5144      -1.62820    
    endloop
  endfacet
  facet normal   0.880471     -0.474100      0.000000E+00
    outer loop
      vertex    1.80230      -11.7689       1.03730    
      vertex    1.80230      -11.7689      -1.03730    
      vertex    2.47780      -10.5144      -1.62820    
    endloop
  endfacet
  facet normal   0.471003     -0.340553     -0.813744    
    outer loop
      vertex   0.000000E+00  -12.5120      -1.76950    
      vertex   0.460000E-02  -11.7876      -2.07000    
      vertex    1.80230      -11.7689      -1.03730    
    endloop
  endfacet
  facet normal  -0.942380     -0.334543      0.000000E+00
    outer loop
      vertex   -1.53240      -12.5120      0.884700    
      vertex   -1.78420      -11.8027       1.03230    
      vertex   -1.78420      -11.8027      -1.03230    
    endloop
  endfacet
  facet normal   0.471365     -0.338448      0.814413    
    outer loop
      vertex    1.53240      -12.5120      0.884700    
      vertex    1.80230      -11.7689       1.03730    
      vertex   0.460000E-02  -11.7876       2.07000    
    endloop
  endfacet
  facet normal  -0.186358     -0.981213      0.499160E-01
    outer loop
      vertex   -4.36730      -39.3967      0.228500    
      vertex   -3.26980      -39.5722      0.876100    
      vertex   -4.36120      -39.3325       1.51330    
    endloop
  endfacet
  facet normal  -0.186353     -0.981215      0.499025E-01
    outer loop
      vertex   -2.17830      -39.8119      0.239000    
      vertex   -3.26980      -39.5722      0.876100    
      vertex   -3.27580      -39.6364     -0.408600    
    endloop
  endfacet
  facet normal  -0.186341     -0.981216      0.499160E-01
    outer loop
      vertex   -3.26370      -39.5080       2.16090    
      vertex   -3.26980      -39.5722      0.876100    
      vertex   -2.17220      -39.7477       1.52370    
    endloop
  endfacet
  facet normal   0.000000E+00   1.00000      0.000000E+00
    outer loop
      vertex    2.47780      -10.5144      -1.62820    
      vertex  -0.342400      -10.5144      0.000000E+00
      vertex    2.47780      -10.5144       1.62820    
    endloop
  endfacet
  facet normal   0.000000E+00   1.00000      0.000000E+00
    outer loop
      vertex   -3.16260      -10.5144      -1.62820    
      vertex  -0.342400      -10.5144      0.000000E+00
      vertex  -0.342400      -10.5144      -3.25650    
    endloop
  endfacet
  facet normal   0.000000E+00   1.00000      0.000000E+00
    outer loop
      vertex  -0.342400      -10.5144       3.25650    
      vertex  -0.342400      -10.5144      0.000000E+00
      vertex   -3.16260      -10.5144       1.62820    
    endloop
  endfacet
  facet normal   0.000000E+00   1.00000      0.000000E+00
    outer loop
      vertex   -3.16260      -10.5144       1.62820    
      vertex  -0.342400      -10.5144      0.000000E+00
      vertex   -3.16260      -10.5144      -1.62820    
    endloop
  endfacet
  facet normal   0.000000E+00   1.00000      0.000000E+00
    outer loop
      vertex  -0.342400      -10.5144      -3.25650    
      vertex  -0.342400      -10.5144      0.000000E+00
      vertex    2.47780      -10.5144      -1.62820    
    endloop
  endfacet
  facet normal   0.000000E+00   1.00000      0.000000E+00
    outer loop
      vertex    2.47780      -10.5144       1.62820    
      vertex  -0.342400      -10.5144      0.000000E+00
      vertex  -0.342400      -10.5144       3.25650    
    endloop
  endfacet
  facet normal  -0.186343     -0.981216      0.499199E-01
    outer loop
      vertex   -2.17220      -39.7477       1.52370    
      vertex   -3.26980      -39.5722      0.876100    
      vertex   -2.17830      -39.8119      0.239000    
    endloop
  endfacet
  facet normal  -0.186350     -0.981215      0.499025E-01
    outer loop
      vertex   -3.27580      -39.6364     -0.408600    
      vertex   -3.26980      -39.5722      0.876100    
      vertex   -4.36730      -39.3967      0.228500    
    endloop
  endfacet
  facet normal  -0.186358     -0.981213      0.499159E-01
    outer loop
      vertex   -4.36120      -39.3325       1.51330    
      vertex   -3.26980      -39.5722      0.876100    
      vertex   -3.26370      -39.5080       2.16090    
    endloop
  endfacet
  facet normal   0.468351E-02  0.997403      0.718698E-01
    outer loop
      vertex   -2.50600      -9.79150      -2.47250    
      vertex   -4.67910      -9.41480      -7.55870    
      vertex   -7.26280      -9.53090      -5.77910    
    endloop
  endfacet
  facet normal   0.214643      0.961522      0.171475    
    outer loop
      vertex   -9.68450      -9.34410      -3.79520    
      vertex   -7.26280      -9.53090      -5.77910    
      vertex   -10.9649      -7.82730      -10.6977    
    endloop
  endfacet
  facet normal   0.392037      0.897377      0.202537    
    outer loop
      vertex   -14.0145      -7.33970      -6.95520    
      vertex   -10.9649      -7.82730      -10.6977    
      vertex   -13.6693      -5.84990      -14.2242    
    endloop
  endfacet
  facet normal   0.223729      0.838132      0.497474    
    outer loop
      vertex   -11.1602      -4.13520      -18.2415    
      vertex   -15.4166      -4.05630      -16.4602    
      vertex   -13.6693      -5.84990      -14.2242    
    endloop
  endfacet
  facet normal   0.885168     -0.117668E-01  0.465123    
    outer loop
      vertex   -18.0793      -2.70980      -11.3588    
      vertex   -15.4166      -4.05630      -16.4602    
      vertex   -15.2184      0.667000      -16.7179    
    endloop
  endfacet
  facet normal   0.628145      0.767964      0.125162    
    outer loop
      vertex   -13.6693      -5.84990      -14.2242    
      vertex   -15.4166      -4.05630      -16.4602    
      vertex   -18.0793      -2.70980      -11.3588    
    endloop
  endfacet
  facet normal   0.753008      0.636664      0.166246    
    outer loop
      vertex   -14.0145      -7.33970      -6.95520    
      vertex   -13.6693      -5.84990      -14.2242    
      vertex   -16.5711      -4.23590      -7.26160    
    endloop
  endfacet
  facet normal   0.326803      0.933963      0.144614    
    outer loop
      vertex   -9.68450      -9.34410      -3.79520    
      vertex   -10.9649      -7.82730      -10.6977    
      vertex   -14.0145      -7.33970      -6.95520    
    endloop
  endfacet
  facet normal   0.819671E-01  0.996573      0.111411E-01
    outer loop
      vertex   -3.60010      -9.88740     -0.837300    
      vertex   -7.26280      -9.53090      -5.77910    
      vertex   -5.11420      -9.77110     -0.100800    
    endloop
  endfacet
  facet normal   0.954687E-02  0.997846      0.649084E-01
    outer loop
      vertex   -3.60010      -9.88740     -0.837300    
      vertex   -2.50600      -9.79150      -2.47250    
      vertex   -7.26280      -9.53090      -5.77910    
    endloop
  endfacet
  facet normal   0.122766      0.962718      0.241044    
    outer loop
      vertex   -7.26280      -9.53090      -5.77910    
      vertex   -4.67910      -9.41480      -7.55870    
      vertex   -10.9649      -7.82730      -10.6977    
    endloop
  endfacet
  facet normal  -0.941263E-01  0.446943      0.889596    
    outer loop
      vertex   -6.59350      -7.47770      -12.6577    
      vertex   -7.57840      -2.54670      -15.2393    
      vertex   -13.6693      -5.84990      -14.2242    
    endloop
  endfacet
  facet normal  -0.463723      0.881726      0.867169E-01
    outer loop
      vertex   -13.6693      -5.84990      -14.2242    
      vertex   -7.57840      -2.54670      -15.2393    
      vertex   -11.1602      -4.13520      -18.2415    
    endloop
  endfacet
  facet normal   0.386369      0.340752E-01  0.921715    
    outer loop
      vertex   -15.4166      -4.05630      -16.4602    
      vertex   -11.1602      -4.13520      -18.2415    
      vertex   -15.2184      0.667000      -16.7179    
    endloop
  endfacet
  facet normal   0.115003      0.901470      0.417284    
    outer loop
      vertex   -13.6693      -5.84990      -14.2242    
      vertex   -10.9649      -7.82730      -10.6977    
      vertex   -6.59350      -7.47770      -12.6577    
    endloop
  endfacet
  facet normal   0.608536      0.790397      0.703973E-01
    outer loop
      vertex   -18.0793      -2.70980      -11.3588    
      vertex   -16.5711      -4.23590      -7.26160    
      vertex   -13.6693      -5.84990      -14.2242    
    endloop
  endfacet
  facet normal   0.727855E-01  0.941102      0.330196    
    outer loop
      vertex   -4.67910      -9.41480      -7.55870    
      vertex   -6.59350      -7.47770      -12.6577    
      vertex   -10.9649      -7.82730      -10.6977    
    endloop
  endfacet
  facet normal   0.850238E-01  0.996329      0.997415E-02
    outer loop
      vertex   -7.26280      -9.53090      -5.77910    
      vertex   -9.68450      -9.34410      -3.79520    
      vertex   -5.11420      -9.77110     -0.100800    
    endloop
  endfacet
  facet normal  -0.207079     -0.967618      0.144338    
    outer loop
      vertex   -5.11420      -9.77110     -0.100800    
      vertex   -9.68450      -9.34410      -3.79520    
      vertex   -7.26280      -10.1583      -5.77910    
    endloop
  endfacet
  facet normal   0.422372E-01 -0.928614     -0.368636    
    outer loop
      vertex   -10.9649      -8.45460      -10.6977    
      vertex   -6.59350      -7.47770      -12.6577    
      vertex   -4.67910      -9.41480      -7.55870    
    endloop
  endfacet
  facet normal  -0.662203     -0.748505     -0.350382E-01
    outer loop
      vertex   -13.6693      -6.47720      -14.2242    
      vertex   -16.5711      -4.23590      -7.26160    
      vertex   -18.0793      -2.70980      -11.3588    
    endloop
  endfacet
  facet normal  -0.182524E-01 -0.877997     -0.478318    
    outer loop
      vertex   -6.59350      -7.47770      -12.6577    
      vertex   -10.9649      -8.45460      -10.6977    
      vertex   -13.6693      -6.47720      -14.2242    
    endloop
  endfacet
  facet normal  -0.382553     -0.303045E-01 -0.923436    
    outer loop
      vertex   -15.2184      0.667000      -16.7179    
      vertex   -11.1602      -4.13520      -18.2415    
      vertex   -15.4166      -4.68360      -16.4602    
    endloop
  endfacet
  facet normal   0.514405     -0.840758     -0.168860    
    outer loop
      vertex   -11.1602      -4.13520      -18.2415    
      vertex   -7.57840      -2.54670      -15.2393    
      vertex   -13.6693      -6.47720      -14.2242    
    endloop
  endfacet
  facet normal   0.134758     -0.438334     -0.888653    
    outer loop
      vertex   -13.6693      -6.47720      -14.2242    
      vertex   -7.57840      -2.54670      -15.2393    
      vertex   -6.59350      -7.47770      -12.6577    
    endloop
  endfacet
  facet normal   0.303590E-01 -0.937197     -0.347476    
    outer loop
      vertex   -10.9649      -8.45460      -10.6977    
      vertex   -4.67910      -9.41480      -7.55870    
      vertex   -7.26280      -10.1583      -5.77910    
    endloop
  endfacet
  facet normal   0.801969E-01 -0.996767     -0.479828E-02
    outer loop
      vertex   -7.26280      -10.1583      -5.77910    
      vertex   -2.50600      -9.79150      -2.47250    
      vertex   -3.60010      -9.88740     -0.837300    
    endloop
  endfacet
  facet normal  -0.367094E-01 -0.995972      0.818052E-01
    outer loop
      vertex   -3.60010      -9.88740     -0.837300    
      vertex   -5.11420      -9.77110     -0.100800    
      vertex   -7.26280      -10.1583      -5.77910    
    endloop
  endfacet
  facet normal  -0.391991     -0.918834     -0.456932E-01
    outer loop
      vertex   -9.68450      -9.34410      -3.79520    
      vertex   -14.0145      -7.33970      -6.95520    
      vertex   -10.9649      -8.45460      -10.6977    
    endloop
  endfacet
  facet normal  -0.761567     -0.638350     -0.111910    
    outer loop
      vertex   -14.0145      -7.33970      -6.95520    
      vertex   -16.5711      -4.23590      -7.26160    
      vertex   -13.6693      -6.47720      -14.2242    
    endloop
  endfacet
  facet normal  -0.672501     -0.737166     -0.657958E-01
    outer loop
      vertex   -18.0793      -2.70980      -11.3588    
      vertex   -15.4166      -4.68360      -16.4602    
      vertex   -13.6693      -6.47720      -14.2242    
    endloop
  endfacet
  facet normal  -0.884812      0.103399E-01 -0.465833    
    outer loop
      vertex   -18.0793      -2.70980      -11.3588    
      vertex   -15.2184      0.667000      -16.7179    
      vertex   -15.4166      -4.68360      -16.4602    
    endloop
  endfacet
  facet normal  -0.127823     -0.820015     -0.557886    
    outer loop
      vertex   -13.6693      -6.47720      -14.2242    
      vertex   -15.4166      -4.68360      -16.4602    
      vertex   -11.1602      -4.13520      -18.2415    
    endloop
  endfacet
  facet normal  -0.473282     -0.871864     -0.125926    
    outer loop
      vertex   -13.6693      -6.47720      -14.2242    
      vertex   -10.9649      -8.45460      -10.6977    
      vertex   -14.0145      -7.33970      -6.95520    
    endloop
  endfacet
  facet normal  -0.357554     -0.932340     -0.538217E-01
    outer loop
      vertex   -10.9649      -8.45460      -10.6977    
      vertex   -7.26280      -10.1583      -5.77910    
      vertex   -9.68450      -9.34410      -3.79520    
    endloop
  endfacet
  facet normal   0.177952     -0.972833     -0.148082    
    outer loop
      vertex   -7.26280      -10.1583      -5.77910    
      vertex   -4.67910      -9.41480      -7.55870    
      vertex   -2.50600      -9.79150      -2.47250    
    endloop
  endfacet
  facet normal   0.203373      0.977730     -0.518080E-01
    outer loop
      vertex   -3.58100      -10.3084       1.68500    
      vertex   -3.26900      -10.4604      0.412000E-01
      vertex   -8.90300      -9.30090     -0.192900    
    endloop
  endfacet
  facet normal   0.678545      0.682559      0.271460    
    outer loop
      vertex   -8.72470      -8.67600      -3.50000    
      vertex   -11.1069      -5.72600      -4.96290    
      vertex   -12.1569      -6.52850     -0.320500    
    endloop
  endfacet
  facet normal   0.893899      0.396359     -0.209388    
    outer loop
      vertex   -11.4195      -5.70050       4.39490    
      vertex   -12.1569      -6.52850     -0.320500    
      vertex   -14.4005      -1.51500     -0.408400    
    endloop
  endfacet
  facet normal   0.930982     -0.134793      0.339269    
    outer loop
      vertex   -12.3139       4.51540      -3.73830    
      vertex   -13.5811       4.22520     -0.376300    
      vertex   -14.4005      -1.51500     -0.408400    
    endloop
  endfacet
  facet normal   0.805076     -0.569020     -0.167534    
    outer loop
      vertex   -12.6538       4.43100       3.38080    
      vertex   -13.5811       4.22520     -0.376300    
      vertex   -10.5345       8.52890     -0.353300    
    endloop
  endfacet
  facet normal   0.842074      0.913809E-01 -0.531564    
    outer loop
      vertex   -10.3231     -0.607500       6.20680    
      vertex   -14.4005      -1.51500     -0.408400    
      vertex   -12.6538       4.43100       3.38080    
    endloop
  endfacet
  facet normal   0.851059      0.358342E-02 -0.525058    
    outer loop
      vertex   -11.4195      -5.70050       4.39490    
      vertex   -14.4005      -1.51500     -0.408400    
      vertex   -10.3231     -0.607500       6.20680    
    endloop
  endfacet
  facet normal   0.704362      0.672168     -0.228178    
    outer loop
      vertex   -8.98510      -8.67600       3.14440    
      vertex   -12.1569      -6.52850     -0.320500    
      vertex   -11.4195      -5.70050       4.39490    
    endloop
  endfacet
  facet normal   0.241744      0.954822     -0.172841    
    outer loop
      vertex   -8.90300      -9.30090     -0.192900    
      vertex   -8.98510      -8.67600       3.14440    
      vertex   -3.58100      -10.3084       1.68500    
    endloop
  endfacet
  facet normal   0.240654      0.951284      0.192727    
    outer loop
      vertex   -3.73830      -10.2753      -1.83240    
      vertex   -8.72470      -8.67600      -3.50000    
      vertex   -8.90300      -9.30090     -0.192900    
    endloop
  endfacet
  facet normal   0.634353      0.752644      0.176418    
    outer loop
      vertex   -8.90300      -9.30090     -0.192900    
      vertex   -8.72470      -8.67600      -3.50000    
      vertex   -12.1569      -6.52850     -0.320500    
    endloop
  endfacet
  facet normal   0.877812      0.397517      0.267256    
    outer loop
      vertex   -12.1569      -6.52850     -0.320500    
      vertex   -11.1069      -5.72600      -4.96290    
      vertex   -14.4005      -1.51500     -0.408400    
    endloop
  endfacet
  facet normal   0.868951     -0.278258E-01  0.494115    
    outer loop
      vertex   -14.4005      -1.51500     -0.408400    
      vertex   -10.7953     -0.584300      -6.69610    
      vertex   -12.3139       4.51540      -3.73830    
    endloop
  endfacet
  facet normal   0.789789     -0.560426      0.249312    
    outer loop
      vertex   -13.5811       4.22520     -0.376300    
      vertex   -12.3139       4.51540      -3.73830    
      vertex   -10.5345       8.52890     -0.353300    
    endloop
  endfacet
  facet normal   0.853614      0.119200      0.507084    
    outer loop
      vertex   -11.1069      -5.72600      -4.96290    
      vertex   -10.7953     -0.584300      -6.69610    
      vertex   -14.4005      -1.51500     -0.408400    
    endloop
  endfacet
  facet normal   0.963523     -0.136252     -0.230346    
    outer loop
      vertex   -14.4005      -1.51500     -0.408400    
      vertex   -13.5811       4.22520     -0.376300    
      vertex   -12.6538       4.43100       3.38080    
    endloop
  endfacet
  facet normal   0.646288      0.752777     -0.125056    
    outer loop
      vertex   -8.98510      -8.67600       3.14440    
      vertex   -8.90300      -9.30090     -0.192900    
      vertex   -12.1569      -6.52850     -0.320500    
    endloop
  endfacet
  facet normal   0.199496      0.978784      0.467277E-01
    outer loop
      vertex   -8.90300      -9.30090     -0.192900    
      vertex   -3.26900      -10.4604      0.412000E-01
      vertex   -3.73830      -10.2753      -1.83240    
    endloop
  endfacet
  facet normal  -0.149843     -0.986890     -0.599655E-01
    outer loop
      vertex   -3.73830      -10.2753      -1.83240    
      vertex   -3.26900      -10.4604      0.412000E-01
      vertex   -9.57770      -9.48830     -0.192900    
    endloop
  endfacet
  facet normal  -0.650769     -0.703073      0.286685    
    outer loop
      vertex   -12.8316      -6.52850     -0.320500    
      vertex   -9.57770      -9.48830     -0.192900    
      vertex   -8.98510      -8.67600       3.14440    
    endloop
  endfacet
  facet normal  -0.914769      0.128439      0.383015    
    outer loop
      vertex   -12.6538       4.43100       3.38080    
      vertex   -14.2558       4.22520     -0.376300    
      vertex   -15.0752      -1.51500     -0.408400    
    endloop
  endfacet
  facet normal  -0.808081     -0.143606     -0.571299    
    outer loop
      vertex   -15.0752      -1.51500     -0.408400    
      vertex   -10.7953     -0.584300      -6.69610    
      vertex   -11.1069      -5.72600      -4.96290    
    endloop
  endfacet
  facet normal  -0.706214      0.612543     -0.355038    
    outer loop
      vertex   -10.5345       8.52890     -0.353300    
      vertex   -12.3139       4.51540      -3.73830    
      vertex   -14.2558       4.22520     -0.376300    
    endloop
  endfacet
  facet normal  -0.829461      0.741023E-01 -0.553627    
    outer loop
      vertex   -12.3139       4.51540      -3.73830    
      vertex   -10.7953     -0.584300      -6.69610    
      vertex   -15.0752      -1.51500     -0.408400    
    endloop
  endfacet
  facet normal  -0.842121     -0.383506     -0.379151    
    outer loop
      vertex   -15.0752      -1.51500     -0.408400    
      vertex   -11.1069      -5.72600      -4.96290    
      vertex   -12.8316      -6.52850     -0.320500    
    endloop
  endfacet
  facet normal  -0.626907     -0.703621     -0.334523    
    outer loop
      vertex   -12.8316      -6.52850     -0.320500    
      vertex   -8.72470      -8.67600      -3.50000    
      vertex   -9.57770      -9.48830     -0.192900    
    endloop
  endfacet
  facet normal  -0.205749     -0.936745     -0.283155    
    outer loop
      vertex   -9.57770      -9.48830     -0.192900    
      vertex   -8.72470      -8.67600      -3.50000    
      vertex   -3.73830      -10.2753      -1.83240    
    endloop
  endfacet
  facet normal  -0.212040     -0.940221      0.266502    
    outer loop
      vertex   -3.58100      -10.3084       1.68500    
      vertex   -8.98510      -8.67600       3.14440    
      vertex   -9.57770      -9.48830     -0.192900    
    endloop
  endfacet
  facet normal  -0.664059     -0.676821      0.317709    
    outer loop
      vertex   -8.98510      -8.67600       3.14440    
      vertex   -11.4195      -5.70050       4.39490    
      vertex   -12.8316      -6.52850     -0.320500    
    endloop
  endfacet
  facet normal  -0.809453     -0.342863E-01  0.586183    
    outer loop
      vertex   -11.4195      -5.70050       4.39490    
      vertex   -10.3231     -0.607500       6.20680    
      vertex   -15.0752      -1.51500     -0.408400    
    endloop
  endfacet
  facet normal  -0.808429     -0.447872E-01  0.586888    
    outer loop
      vertex   -10.3231     -0.607500       6.20680    
      vertex   -12.6538       4.43100       3.38080    
      vertex   -15.0752      -1.51500     -0.408400    
    endloop
  endfacet
  facet normal  -0.727796      0.627832      0.275936    
    outer loop
      vertex   -12.6538       4.43100       3.38080    
      vertex   -10.5345       8.52890     -0.353300    
      vertex   -14.2558       4.22520     -0.376300    
    endloop
  endfacet
  facet normal  -0.863700      0.126020     -0.487998    
    outer loop
      vertex   -15.0752      -1.51500     -0.408400    
      vertex   -14.2558       4.22520     -0.376300    
      vertex   -12.3139       4.51540      -3.73830    
    endloop
  endfacet
  facet normal  -0.865018     -0.381390      0.326013    
    outer loop
      vertex   -15.0752      -1.51500     -0.408400    
      vertex   -12.8316      -6.52850     -0.320500    
      vertex   -11.4195      -5.70050       4.39490    
    endloop
  endfacet
  facet normal  -0.633829     -0.687542     -0.354325    
    outer loop
      vertex   -12.8316      -6.52850     -0.320500    
      vertex   -11.1069      -5.72600      -4.96290    
      vertex   -8.72470      -8.67600      -3.50000    
    endloop
  endfacet
  facet normal  -0.154243     -0.986092      0.619063E-01
    outer loop
      vertex   -9.57770      -9.48830     -0.192900    
      vertex   -3.26900      -10.4604      0.412000E-01
      vertex   -3.58100      -10.3084       1.68500    
    endloop
  endfacet
  facet normal   0.161124E-01  0.994849     -0.100083    
    outer loop
      vertex   -8.31560      -10.2808       6.06910    
      vertex   -5.66530      -10.1224       8.07030    
      vertex   -2.65170      -10.7520       2.29710    
    endloop
  endfacet
  facet normal   0.408385      0.904172     -0.125279    
    outer loop
      vertex   -10.7103      -10.0710       3.71180    
      vertex   -15.1337      -7.72640       6.21400    
      vertex   -12.3009      -8.38900       10.6662    
    endloop
  endfacet
  facet normal   0.724025E-01  0.724180     -0.685800    
    outer loop
      vertex   -14.5968      -6.79310       13.2707    
      vertex   -7.04570      -5.20810       15.7416    
      vertex   -7.53810      -8.04060       12.6986    
    endloop
  endfacet
  facet normal   0.658837      0.731875     -0.174046    
    outer loop
      vertex   -19.1433      -2.84320       12.6699    
      vertex   -17.3534      -3.59130       16.2996    
      vertex   -14.5968      -6.79310       13.2707    
    endloop
  endfacet
  facet normal   0.358249      0.546306     -0.757105    
    outer loop
      vertex   -13.3466      -4.33530       17.6587    
      vertex   -17.3534      -3.59130       16.2996    
      vertex   -18.1667      -1.75650       17.2387    
    endloop
  endfacet
  facet normal  -0.256946E-01  0.875277     -0.482938    
    outer loop
      vertex   -7.04570      -5.20810       15.7416    
      vertex   -14.5968      -6.79310       13.2707    
      vertex   -13.3466      -4.33530       17.6587    
    endloop
  endfacet
  facet normal   0.121869      0.890551     -0.438254    
    outer loop
      vertex   -7.53810      -8.04060       12.6986    
      vertex   -12.3009      -8.38900       10.6662    
      vertex   -14.5968      -6.79310       13.2707    
    endloop
  endfacet
  facet normal   0.933560E-01  0.921596     -0.376756    
    outer loop
      vertex   -5.66530      -10.1224       8.07030    
      vertex   -12.3009      -8.38900       10.6662    
      vertex   -7.53810      -8.04060       12.6986    
    endloop
  endfacet
  facet normal   0.351548E-01  0.996804     -0.717340E-01
    outer loop
      vertex   -3.64830      -10.8395      0.592800    
      vertex   -8.31560      -10.2808       6.06910    
      vertex   -2.65170      -10.7520       2.29710    
    endloop
  endfacet
  facet normal   0.115399      0.992900     -0.288616E-01
    outer loop
      vertex   -5.83860      -10.7442      0.311000E-01
      vertex   -10.7103      -10.0710       3.71180    
      vertex   -8.31560      -10.2808       6.06910    
    endloop
  endfacet
  facet normal   0.253072      0.951969     -0.172362    
    outer loop
      vertex   -8.31560      -10.2808       6.06910    
      vertex   -10.7103      -10.0710       3.71180    
      vertex   -12.3009      -8.38900       10.6662    
    endloop
  endfacet
  facet normal   0.783792      0.605114     -0.139665    
    outer loop
      vertex   -15.1337      -7.72640       6.21400    
      vertex   -17.2317      -4.98760       6.30630    
      vertex   -14.5968      -6.79310       13.2707    
    endloop
  endfacet
  facet normal   0.658973      0.750165     -0.548370E-01
    outer loop
      vertex   -14.5968      -6.79310       13.2707    
      vertex   -17.2317      -4.98760       6.30630    
      vertex   -19.1433      -2.84320       12.6699    
    endloop
  endfacet
  facet normal   0.808962      0.509061     -0.294000    
    outer loop
      vertex   -17.3534      -3.59130       16.2996    
      vertex   -19.1433      -2.84320       12.6699    
      vertex   -18.1667      -1.75650       17.2387    
    endloop
  endfacet
  facet normal   0.443362      0.883601     -0.150595    
    outer loop
      vertex   -14.5968      -6.79310       13.2707    
      vertex   -12.3009      -8.38900       10.6662    
      vertex   -15.1337      -7.72640       6.21400    
    endloop
  endfacet
  facet normal   0.325387      0.782433     -0.530963    
    outer loop
      vertex   -14.5968      -6.79310       13.2707    
      vertex   -17.3534      -3.59130       16.2996    
      vertex   -13.3466      -4.33530       17.6587    
    endloop
  endfacet
  facet normal   0.144526      0.952847     -0.266824    
    outer loop
      vertex   -5.66530      -10.1224       8.07030    
      vertex   -8.31560      -10.2808       6.06910    
      vertex   -12.3009      -8.38900       10.6662    
    endloop
  endfacet
  facet normal   0.570030E-01  0.996959     -0.531292E-01
    outer loop
      vertex   -8.31560      -10.2808       6.06910    
      vertex   -3.64830      -10.8395      0.592800    
      vertex   -5.83860      -10.7442      0.311000E-01
    endloop
  endfacet
  facet normal  -0.323424E-01 -0.998538     -0.433003E-01
    outer loop
      vertex   -5.83860      -10.7442      0.311000E-01
      vertex   -3.64830      -10.8395      0.592800    
      vertex   -8.31560      -10.9258       6.06910    
    endloop
  endfacet
  facet normal  -0.426111E-02 -0.926037      0.377409    
    outer loop
      vertex   -12.3009      -9.03390       10.6662    
      vertex   -8.31560      -10.9258       6.06910    
      vertex   -5.66530      -10.1224       8.07030    
    endloop
  endfacet
  facet normal  -0.223924     -0.764558      0.604408    
    outer loop
      vertex   -13.3466      -4.33530       17.6587    
      vertex   -17.3534      -4.23620       16.2996    
      vertex   -14.5968      -7.43800       13.2707    
    endloop
  endfacet
  facet normal  -0.511326     -0.856204      0.738958E-01
    outer loop
      vertex   -15.1337      -7.72640       6.21400    
      vertex   -12.3009      -9.03390       10.6662    
      vertex   -14.5968      -7.43800       13.2707    
    endloop
  endfacet
  facet normal  -0.875446     -0.393441      0.280711    
    outer loop
      vertex   -18.1667      -1.75650       17.2387    
      vertex   -19.1433      -2.84320       12.6699    
      vertex   -17.3534      -4.23620       16.2996    
    endloop
  endfacet
  facet normal  -0.712124     -0.701692      0.225363E-01
    outer loop
      vertex   -19.1433      -2.84320       12.6699    
      vertex   -17.2317      -4.98760       6.30630    
      vertex   -14.5968      -7.43800       13.2707    
    endloop
  endfacet
  facet normal  -0.789600     -0.607718      0.849126E-01
    outer loop
      vertex   -14.5968      -7.43800       13.2707    
      vertex   -17.2317      -4.98760       6.30630    
      vertex   -15.1337      -7.72640       6.21400    
    endloop
  endfacet
  facet normal  -0.379794     -0.923671      0.508798E-01
    outer loop
      vertex   -12.3009      -9.03390       10.6662    
      vertex   -10.7103      -10.0710       3.71180    
      vertex   -8.31560      -10.9258       6.06910    
    endloop
  endfacet
  facet normal  -0.225407     -0.966653     -0.121543    
    outer loop
      vertex   -8.31560      -10.9258       6.06910    
      vertex   -10.7103      -10.0710       3.71180    
      vertex   -5.83860      -10.7442      0.311000E-01
    endloop
  endfacet
  facet normal   0.466292E-01 -0.998624      0.240037E-01
    outer loop
      vertex   -3.64830      -10.8395      0.592800    
      vertex   -2.65170      -10.7520       2.29710    
      vertex   -8.31560      -10.9258       6.06910    
    endloop
  endfacet
  facet normal   0.128922E-01 -0.909953      0.414512    
    outer loop
      vertex   -5.66530      -10.1224       8.07030    
      vertex   -7.53810      -8.04060       12.6986    
      vertex   -12.3009      -9.03390       10.6662    
    endloop
  endfacet
  facet normal  -0.332627E-01 -0.864984      0.500695    
    outer loop
      vertex   -14.5968      -7.43800       13.2707    
      vertex   -12.3009      -9.03390       10.6662    
      vertex   -7.53810      -8.04060       12.6986    
    endloop
  endfacet
  facet normal   0.580151E-01 -0.822846      0.565295    
    outer loop
      vertex   -7.04570      -5.20810       15.7416    
      vertex   -13.3466      -4.33530       17.6587    
      vertex   -14.5968      -7.43800       13.2707    
    endloop
  endfacet
  facet normal  -0.300509     -0.422416      0.855137    
    outer loop
      vertex   -13.3466      -4.33530       17.6587    
      vertex   -18.1667      -1.75650       17.2387    
      vertex   -17.3534      -4.23620       16.2996    
    endloop
  endfacet
  facet normal  -0.713796     -0.695151      0.852076E-01
    outer loop
      vertex   -14.5968      -7.43800       13.2707    
      vertex   -17.3534      -4.23620       16.2996    
      vertex   -19.1433      -2.84320       12.6699    
    endloop
  endfacet
  facet normal  -0.716661E-02 -0.731373      0.681940    
    outer loop
      vertex   -7.53810      -8.04060       12.6986    
      vertex   -7.04570      -5.20810       15.7416    
      vertex   -14.5968      -7.43800       13.2707    
    endloop
  endfacet
  facet normal  -0.455496     -0.889781      0.285115E-01
    outer loop
      vertex   -12.3009      -9.03390       10.6662    
      vertex   -15.1337      -7.72640       6.21400    
      vertex   -10.7103      -10.0710       3.71180    
    endloop
  endfacet
  facet normal   0.153688     -0.970445      0.186057    
    outer loop
      vertex   -2.65170      -10.7520       2.29710    
      vertex   -5.66530      -10.1224       8.07030    
      vertex   -8.31560      -10.9258       6.06910    
    endloop
  endfacet
  facet normal  -0.955098     -0.246195     -0.164848    
    outer loop
      vertex    11.8939       4.40190       3.63590    
      vertex    12.5886       4.42530     -0.424000    
      vertex    13.7942     -0.254900     -0.419300    
    endloop
  endfacet
  facet normal  -0.380722      0.924307     -0.266014E-01
    outer loop
      vertex    9.86820      -8.33410     -0.429400    
      vertex    5.86880      -9.98140     -0.427500    
      vertex    6.21420      -9.74680       2.78060    
    endloop
  endfacet
  facet normal  -0.737205      0.665519      0.116671    
    outer loop
      vertex    12.5889      -5.05430     -0.428100    
      vertex    10.8003      -6.25000      -4.90910    
      vertex    9.64740      -7.72350      -3.78870    
    endloop
  endfacet
  facet normal  -0.840778      0.713204E-01  0.536661    
    outer loop
      vertex    12.0550       3.96360      -3.70470    
      vertex    9.67090      -3.52140      -6.44510    
      vertex    13.7942     -0.254900     -0.419300    
    endloop
  endfacet
  facet normal  -0.111755      0.993657      0.125479E-01
    outer loop
      vertex    5.86880      -9.98140     -0.427500    
      vertex    2.79660      -10.3272     -0.405800    
      vertex    3.11090      -10.3174       1.61740    
    endloop
  endfacet
  facet normal  -0.628838     -0.749275      0.207726    
    outer loop
      vertex    12.0550       3.96360      -3.70470    
      vertex    12.5886       4.42530     -0.424000    
      vertex    10.0837       6.67550      0.109600    
    endloop
  endfacet
  facet normal  -0.950958     -0.244773      0.189119    
    outer loop
      vertex    13.7942     -0.254900     -0.419300    
      vertex    12.5886       4.42530     -0.424000    
      vertex    12.0550       3.96360      -3.70470    
    endloop
  endfacet
  facet normal  -0.820560     -0.180539E-01  0.571275    
    outer loop
      vertex    10.8003      -6.25000      -4.90910    
      vertex    13.7942     -0.254900     -0.419300    
      vertex    9.67090      -3.52140      -6.44510    
    endloop
  endfacet
  facet normal  -0.759222      0.629734      0.164365    
    outer loop
      vertex    9.64740      -7.72350      -3.78870    
      vertex    9.86820      -8.33410     -0.429400    
      vertex    12.5889      -5.05430     -0.428100    
    endloop
  endfacet
  facet normal  -0.380404      0.923618      0.471350E-01
    outer loop
      vertex    6.20640      -9.72330      -2.76040    
      vertex    5.86880      -9.98140     -0.427500    
      vertex    9.86820      -8.33410     -0.429400    
    endloop
  endfacet
  facet normal  -0.112002      0.993320     -0.277587E-01
    outer loop
      vertex    2.79660      -10.3272     -0.405800    
      vertex    5.86880      -9.98140     -0.427500    
      vertex    3.05560      -10.3329      -1.65480    
    endloop
  endfacet
  facet normal  -0.160672      0.985487     -0.547671E-01
    outer loop
      vertex    3.11090      -10.3174       1.61740    
      vertex    6.21420      -9.74680       2.78060    
      vertex    5.86880      -9.98140     -0.427500    
    endloop
  endfacet
  facet normal  -0.476441      0.864146     -0.162036    
    outer loop
      vertex    6.21420      -9.74680       2.78060    
      vertex    9.64740      -7.66490       3.78870    
      vertex    9.86820      -8.33410     -0.429400    
    endloop
  endfacet
  facet normal  -0.836393      0.459365     -0.299049    
    outer loop
      vertex    9.64740      -7.66490       3.78870    
      vertex    10.9256      -4.39580       5.23540    
      vertex    12.5889      -5.05430     -0.428100    
    endloop
  endfacet
  facet normal  -0.925423      0.232955     -0.298871    
    outer loop
      vertex    12.5889      -5.05430     -0.428100    
      vertex    10.9256      -4.39580       5.23540    
      vertex    13.7942     -0.254900     -0.419300    
    endloop
  endfacet
  facet normal  -0.909454     -0.912050E-02 -0.415704    
    outer loop
      vertex    13.7942     -0.254900     -0.419300    
      vertex    10.6429     -0.248700       6.47480    
      vertex    11.8939       4.40190       3.63590    
    endloop
  endfacet
  facet normal  -0.677473     -0.725675     -0.120107    
    outer loop
      vertex    12.5886       4.42530     -0.424000    
      vertex    11.8939       4.40190       3.63590    
      vertex    10.0837       6.67550      0.109600    
    endloop
  endfacet
  facet normal  -0.160216      0.983363      0.856087E-01
    outer loop
      vertex    5.86880      -9.98140     -0.427500    
      vertex    6.20640      -9.72330      -2.76040    
      vertex    3.05560      -10.3329      -1.65480    
    endloop
  endfacet
  facet normal  -0.923243      0.231297      0.306796    
    outer loop
      vertex    10.8003      -6.25000      -4.90910    
      vertex    12.5889      -5.05430     -0.428100    
      vertex    13.7942     -0.254900     -0.419300    
    endloop
  endfacet
  facet normal  -0.450839      0.872533      0.188228    
    outer loop
      vertex    9.86820      -8.33410     -0.429400    
      vertex    9.64740      -7.72350      -3.78870    
      vertex    6.20640      -9.72330      -2.76040    
    endloop
  endfacet
  facet normal  -0.762031      0.632185     -0.140185    
    outer loop
      vertex    12.5889      -5.05430     -0.428100    
      vertex    9.86820      -8.33410     -0.429400    
      vertex    9.64740      -7.66490       3.78870    
    endloop
  endfacet
  facet normal  -0.907710      0.621412E-01 -0.414971    
    outer loop
      vertex    10.9256      -4.39580       5.23540    
      vertex    10.6429     -0.248700       6.47480    
      vertex    13.7942     -0.254900     -0.419300    
    endloop
  endfacet
  facet normal   0.870794     -0.853430E-01  0.484185    
    outer loop
      vertex    14.4756     -0.254900     -0.419300    
      vertex    10.6429     -0.248700       6.47480    
      vertex    10.9256      -4.39580       5.23540    
    endloop
  endfacet
  facet normal   0.743768     -0.617059      0.256997    
    outer loop
      vertex    9.64740      -7.66490       3.78870    
      vertex    10.5497      -8.33410     -0.429400    
      vertex    13.2703      -5.05430     -0.428100    
    endloop
  endfacet
  facet normal   0.421994     -0.865266     -0.270621    
    outer loop
      vertex    6.20640      -9.72330      -2.76040    
      vertex    9.64740      -7.72350      -3.78870    
      vertex    10.5497      -8.33410     -0.429400    
    endloop
  endfacet
  facet normal   0.877968     -0.219709     -0.425324    
    outer loop
      vertex    14.4756     -0.254900     -0.419300    
      vertex    13.2703      -5.05430     -0.428100    
      vertex    10.8003      -6.25000      -4.90910    
    endloop
  endfacet
  facet normal   0.109725     -0.968955     -0.221557    
    outer loop
      vertex    3.05560      -10.3329      -1.65480    
      vertex    6.20640      -9.72330      -2.76040    
      vertex    6.55020      -10.2178     -0.427500    
    endloop
  endfacet
  facet normal   0.587301      0.783347      0.203580    
    outer loop
      vertex    10.0837       6.67550      0.109600    
      vertex    11.8939       4.40190       3.63590    
      vertex    13.2700       4.42530     -0.424000    
    endloop
  endfacet
  facet normal   0.872392      0.613553E-01  0.484941    
    outer loop
      vertex    11.8939       4.40190       3.63590    
      vertex    10.6429     -0.248700       6.47480    
      vertex    14.4756     -0.254900     -0.419300    
    endloop
  endfacet
  facet normal   0.890875     -0.224454      0.394921    
    outer loop
      vertex    14.4756     -0.254900     -0.419300    
      vertex    10.9256      -4.39580       5.23540    
      vertex    13.2703      -5.05430     -0.428100    
    endloop
  endfacet
  facet normal   0.790302     -0.478412      0.382812    
    outer loop
      vertex    13.2703      -5.05430     -0.428100    
      vertex    10.9256      -4.39580       5.23540    
      vertex    9.64740      -7.66490       3.78870    
    endloop
  endfacet
  facet normal   0.453161     -0.860324      0.233426    
    outer loop
      vertex    10.5497      -8.33410     -0.429400    
      vertex    9.64740      -7.66490       3.78870    
      vertex    6.21420      -9.74680       2.78060    
    endloop
  endfacet
  facet normal   0.121511     -0.980154      0.156629    
    outer loop
      vertex    6.55020      -10.2178     -0.427500    
      vertex    6.21420      -9.74680       2.78060    
      vertex    3.11090      -10.3174       1.61740    
    endloop
  endfacet
  facet normal   0.291926E-01 -0.999517      0.106151E-01
    outer loop
      vertex    2.79660      -10.3272     -0.405800    
      vertex    3.05560      -10.3329      -1.65480    
      vertex    6.55020      -10.2178     -0.427500    
    endloop
  endfacet
  facet normal   0.412826     -0.876767     -0.246685    
    outer loop
      vertex    10.5497      -8.33410     -0.429400    
      vertex    6.55020      -10.2178     -0.427500    
      vertex    6.20640      -9.72330      -2.76040    
    endloop
  endfacet
  facet normal   0.732518     -0.607503     -0.307175    
    outer loop
      vertex    13.2703      -5.05430     -0.428100    
      vertex    10.5497      -8.33410     -0.429400    
      vertex    9.64740      -7.72350      -3.78870    
    endloop
  endfacet
  facet normal   0.787241     -0.210751E-01 -0.616286    
    outer loop
      vertex    10.8003      -6.25000      -4.90910    
      vertex    9.67090      -3.52140      -6.44510    
      vertex    14.4756     -0.254900     -0.419300    
    endloop
  endfacet
  facet normal   0.901149      0.231764     -0.366355    
    outer loop
      vertex    12.0550       3.96360      -3.70470    
      vertex    13.2700       4.42530     -0.424000    
      vertex    14.4756     -0.254900     -0.419300    
    endloop
  endfacet
  facet normal   0.515189      0.801505     -0.303597    
    outer loop
      vertex    12.0550       3.96360      -3.70470    
      vertex    10.0837       6.67550      0.109600    
      vertex    13.2700       4.42530     -0.424000    
    endloop
  endfacet
  facet normal   0.291348E-01 -0.999575      0.315712E-03
    outer loop
      vertex    3.11090      -10.3174       1.61740    
      vertex    2.79660      -10.3272     -0.405800    
      vertex    6.55020      -10.2178     -0.427500    
    endloop
  endfacet
  facet normal   0.788473     -0.261572E-01 -0.614513    
    outer loop
      vertex    14.4756     -0.254900     -0.419300    
      vertex    9.67090      -3.52140      -6.44510    
      vertex    12.0550       3.96360      -3.70470    
    endloop
  endfacet
  facet normal   0.693574     -0.692799     -0.197445    
    outer loop
      vertex    9.64740      -7.72350      -3.78870    
      vertex    10.8003      -6.25000      -4.90910    
      vertex    13.2703      -5.05430     -0.428100    
    endloop
  endfacet
  facet normal   0.419604     -0.890733      0.174721    
    outer loop
      vertex    6.21420      -9.74680       2.78060    
      vertex    6.55020      -10.2178     -0.427500    
      vertex    10.5497      -8.33410     -0.429400    
    endloop
  endfacet
  facet normal   0.919629      0.237207      0.313075    
    outer loop
      vertex    14.4756     -0.254900     -0.419300    
      vertex    13.2700       4.42530     -0.424000    
      vertex    11.8939       4.40190       3.63590    
    endloop
  endfacet
  facet normal  -0.327239      0.923916     -0.198229    
    outer loop
      vertex    7.95590      -8.64700       4.51830    
      vertex    5.38160      -9.02120       7.02390    
      vertex    7.67780      -7.56490       10.0209    
    endloop
  endfacet
  facet normal  -0.143733      0.986374      0.800431E-01
    outer loop
      vertex    12.7017      -5.85220       7.19620    
      vertex    10.3281      -6.70800       13.4800    
      vertex    13.2518      -6.53600       16.6105    
    endloop
  endfacet
  facet normal   0.191523      0.963207     -0.188553    
    outer loop
      vertex    11.3521      -5.23710       21.3162    
      vertex    15.7846      -6.25830       20.6018    
      vertex    13.2518      -6.53600       16.6105    
    endloop
  endfacet
  facet normal  -0.266823      0.963140     -0.341574E-01
    outer loop
      vertex    3.08480      -8.62900       15.8949    
      vertex    10.3281      -6.70800       13.4800    
      vertex    7.67780      -7.56490       10.0209    
    endloop
  endfacet
  facet normal  -0.651108E-01  0.946029     -0.317475    
    outer loop
      vertex   0.166100      -10.5430       3.55880    
      vertex    2.29740      -8.62710       8.83080    
      vertex    5.38160      -9.02120       7.02390    
    endloop
  endfacet
  facet normal  -0.653973      0.753876     -0.631636E-01
    outer loop
      vertex    17.4851      -5.18520       15.8032    
      vertex    15.7846      -6.25830       20.6018    
      vertex    16.7253      -5.32430       22.0097    
    endloop
  endfacet
  facet normal  -0.282430      0.952616      0.112945    
    outer loop
      vertex    13.2518      -6.53600       16.6105    
      vertex    15.7846      -6.25830       20.6018    
      vertex    17.4851      -5.18520       15.8032    
    endloop
  endfacet
  facet normal  -0.542668      0.834855      0.923484E-01
    outer loop
      vertex    12.7017      -5.85220       7.19620    
      vertex    13.2518      -6.53600       16.6105    
      vertex    14.5120      -4.80240       8.34360    
    endloop
  endfacet
  facet normal  -0.318161      0.947995      0.892882E-02
    outer loop
      vertex    7.67780      -7.56490       10.0209    
      vertex    10.3281      -6.70800       13.4800    
      vertex    12.7017      -5.85220       7.19620    
    endloop
  endfacet
  facet normal  -0.412953      0.889459     -0.195785    
    outer loop
      vertex    7.95590      -8.64700       4.51830    
      vertex    7.67780      -7.56490       10.0209    
      vertex    10.6635      -7.01100       6.23980    
    endloop
  endfacet
  facet normal  -0.152634      0.971901     -0.179194    
    outer loop
      vertex    1.14110      -10.7076       1.48930    
      vertex    5.38160      -9.02120       7.02390    
      vertex    2.72940      -10.5776      0.841500    
    endloop
  endfacet
  facet normal  -0.176719      0.971088     -0.160493    
    outer loop
      vertex    1.14110      -10.7076       1.48930    
      vertex   0.166100      -10.5430       3.55880    
      vertex    5.38160      -9.02120       7.02390    
    endloop
  endfacet
  facet normal  -0.109761      0.934712     -0.338033    
    outer loop
      vertex    2.29740      -8.62710       8.83080    
      vertex    3.15380      -7.38240       11.9945    
      vertex    7.67780      -7.56490       10.0209    
    endloop
  endfacet
  facet normal   0.169901      0.937808      0.302737    
    outer loop
      vertex    7.67780      -7.56490       10.0209    
      vertex    3.15380      -7.38240       11.9945    
      vertex    3.08480      -8.62900       15.8949    
    endloop
  endfacet
  facet normal  -0.121742      0.794697     -0.594672    
    outer loop
      vertex    3.08480      -8.62900       15.8949    
      vertex    7.72650      -5.36390       19.3080    
      vertex    13.2518      -6.53600       16.6105    
    endloop
  endfacet
  facet normal   0.933580E-01  0.968769     -0.229718    
    outer loop
      vertex    13.2518      -6.53600       16.6105    
      vertex    7.72650      -5.36390       19.3080    
      vertex    11.3521      -5.23710       21.3162    
    endloop
  endfacet
  facet normal   0.893316E-01  0.801442     -0.591364    
    outer loop
      vertex    15.7846      -6.25830       20.6018    
      vertex    11.3521      -5.23710       21.3162    
      vertex    16.7253      -5.32430       22.0097    
    endloop
  endfacet
  facet normal  -0.263337      0.956208     -0.127753    
    outer loop
      vertex    5.38160      -9.02120       7.02390    
      vertex    7.95590      -8.64700       4.51830    
      vertex    2.72940      -10.5776      0.841500    
    endloop
  endfacet
  facet normal  -0.999403E-01  0.922886     -0.371877    
    outer loop
      vertex    7.67780      -7.56490       10.0209    
      vertex    5.38160      -9.02120       7.02390    
      vertex    2.29740      -8.62710       8.83080    
    endloop
  endfacet
  facet normal  -0.209177      0.967483      0.142202    
    outer loop
      vertex    13.2518      -6.53600       16.6105    
      vertex    10.3281      -6.70800       13.4800    
      vertex    3.08480      -8.62900       15.8949    
    endloop
  endfacet
  facet normal  -0.272822      0.949095      0.157440    
    outer loop
      vertex    17.4851      -5.18520       15.8032    
      vertex    14.5120      -4.80240       8.34360    
      vertex    13.2518      -6.53600       16.6105    
    endloop
  endfacet
  facet normal  -0.413439      0.889138     -0.196216    
    outer loop
      vertex    12.7017      -5.85220       7.19620    
      vertex    10.6635      -7.01100       6.23980    
      vertex    7.67780      -7.56490       10.0209    
    endloop
  endfacet
  facet normal   0.450416     -0.885620      0.113151    
    outer loop
      vertex    7.67780      -8.04640       10.0209    
      vertex    10.6635      -7.01100       6.23980    
      vertex    12.7017      -5.85220       7.19620    
    endloop
  endfacet
  facet normal   0.359228     -0.913691     -0.190061    
    outer loop
      vertex    13.2518      -7.01750       16.6105    
      vertex    14.5120      -4.80240       8.34360    
      vertex    17.4851      -5.18520       15.8032    
    endloop
  endfacet
  facet normal   0.162511     -0.981845     -0.978298E-01
    outer loop
      vertex    3.08480      -8.62900       15.8949    
      vertex    10.3281      -7.18950       13.4800    
      vertex    13.2518      -7.01750       16.6105    
    endloop
  endfacet
  facet normal   0.476667E-03 -0.899567      0.436782    
    outer loop
      vertex    2.29740      -8.62710       8.83080    
      vertex    5.38160      -9.50280       7.02390    
      vertex    7.67780      -8.04640       10.0209    
    endloop
  endfacet
  facet normal   0.333540     -0.942507      0.207673E-01
    outer loop
      vertex    2.72940      -10.5776      0.841500    
      vertex    7.95590      -8.64700       4.51830    
      vertex    5.38160      -9.50280       7.02390    
    endloop
  endfacet
  facet normal  -0.106221     -0.664837      0.739398    
    outer loop
      vertex    16.7253      -5.32430       22.0097    
      vertex    11.3521      -5.23710       21.3162    
      vertex    15.7846      -6.73980       20.6018    
    endloop
  endfacet
  facet normal  -0.134631     -0.943548      0.302640    
    outer loop
      vertex    11.3521      -5.23710       21.3162    
      vertex    7.72650      -5.36390       19.3080    
      vertex    13.2518      -7.01750       16.6105    
    endloop
  endfacet
  facet normal   0.777439E-01 -0.771107      0.631941    
    outer loop
      vertex    13.2518      -7.01750       16.6105    
      vertex    7.72650      -5.36390       19.3080    
      vertex    3.08480      -8.62900       15.8949    
    endloop
  endfacet
  facet normal  -0.264554     -0.917228     -0.297833    
    outer loop
      vertex    3.08480      -8.62900       15.8949    
      vertex    3.15380      -7.38240       11.9945    
      vertex    7.67780      -8.04640       10.0209    
    endloop
  endfacet
  facet normal   0.207303E-01 -0.932269      0.361172    
    outer loop
      vertex    7.67780      -8.04640       10.0209    
      vertex    3.15380      -7.38240       11.9945    
      vertex    2.29740      -8.62710       8.83080    
    endloop
  endfacet
  facet normal   0.110019     -0.985364      0.130205    
    outer loop
      vertex    5.38160      -9.50280       7.02390    
      vertex   0.166100      -10.5430       3.55880    
      vertex    1.14110      -10.7076       1.48930    
    endloop
  endfacet
  facet normal   0.128047     -0.984926      0.116296    
    outer loop
      vertex    1.14110      -10.7076       1.48930    
      vertex    2.72940      -10.5776      0.841500    
      vertex    5.38160      -9.50280       7.02390    
    endloop
  endfacet
  facet normal   0.456793     -0.881537      0.119305    
    outer loop
      vertex    7.95590      -8.64700       4.51830    
      vertex    10.6635      -7.01100       6.23980    
      vertex    7.67780      -8.04640       10.0209    
    endloop
  endfacet
  facet normal   0.372878     -0.926174     -0.562572E-01
    outer loop
      vertex    12.7017      -5.85220       7.19620    
      vertex    10.3281      -7.18950       13.4800    
      vertex    7.67780      -8.04640       10.0209    
    endloop
  endfacet
  facet normal   0.559299     -0.818074     -0.133942    
    outer loop
      vertex    12.7017      -5.85220       7.19620    
      vertex    14.5120      -4.80240       8.34360    
      vertex    13.2518      -7.01750       16.6105    
    endloop
  endfacet
  facet normal   0.364512     -0.915995     -0.167581    
    outer loop
      vertex    17.4851      -5.18520       15.8032    
      vertex    15.7846      -6.73980       20.6018    
      vertex    13.2518      -7.01750       16.6105    
    endloop
  endfacet
  facet normal   0.789900     -0.607581      0.830826E-01
    outer loop
      vertex    17.4851      -5.18520       15.8032    
      vertex    16.7253      -5.32430       22.0097    
      vertex    15.7846      -6.73980       20.6018    
    endloop
  endfacet
  facet normal  -0.534836E-01 -0.931381      0.360095    
    outer loop
      vertex    5.38160      -9.50280       7.02390    
      vertex    2.29740      -8.62710       8.83080    
      vertex   0.166100      -10.5430       3.55880    
    endloop
  endfacet
  facet normal   0.218063     -0.973126      0.739904E-01
    outer loop
      vertex    7.67780      -8.04640       10.0209    
      vertex    10.3281      -7.18950       13.4800    
      vertex    3.08480      -8.62900       15.8949    
    endloop
  endfacet
  facet normal  -0.276697     -0.930422      0.240322    
    outer loop
      vertex    13.2518      -7.01750       16.6105    
      vertex    15.7846      -6.73980       20.6018    
      vertex    11.3521      -5.23710       21.3162    
    endloop
  endfacet
  facet normal   0.198267     -0.971245     -0.131806    
    outer loop
      vertex    13.2518      -7.01750       16.6105    
      vertex    10.3281      -7.18950       13.4800    
      vertex    12.7017      -5.85220       7.19620    
    endloop
  endfacet
  facet normal   0.415935     -0.901519      0.119421    
    outer loop
      vertex    7.67780      -8.04640       10.0209    
      vertex    5.38160      -9.50280       7.02390    
      vertex    7.95590      -8.64700       4.51830    
    endloop
  endfacet
  facet normal  -0.608574E-01  0.978490      0.197114    
    outer loop
      vertex    3.24940      -10.5195      -6.36220    
      vertex    5.56390      -10.7391      -4.55750    
      vertex    9.74070      -9.46810      -9.57730    
    endloop
  endfacet
  facet normal  -0.652377E-01  0.997382     -0.311885E-01
    outer loop
      vertex    3.73570      -10.7109      0.168400    
      vertex    7.77330      -10.5342      -2.62640    
      vertex    5.56390      -10.7391      -4.55750    
    endloop
  endfacet
  facet normal  -0.815741E-01  0.921605      0.379459    
    outer loop
      vertex    5.82530      -8.92630      -11.7349    
      vertex    9.74070      -9.46810      -9.57730    
      vertex    14.9758      -6.41420      -15.8690    
    endloop
  endfacet
  facet normal  -0.661305      0.748966      0.415360E-01
    outer loop
      vertex    14.9758      -6.41420      -15.8690    
      vertex    16.2885      -5.72580      -7.38220    
      vertex    18.1876      -3.67950      -14.0445    
    endloop
  endfacet
  facet normal  -0.333011     -0.398942      0.854371    
    outer loop
      vertex    12.5494      -3.54380      -18.7450    
      vertex    16.3226      -4.00080      -17.4877    
      vertex    15.7740      -2.13070      -16.8283    
    endloop
  endfacet
  facet normal  -0.181048      0.615508      0.767054    
    outer loop
      vertex    14.9758      -6.41420      -15.8690    
      vertex    16.3226      -4.00080      -17.4877    
      vertex    12.5494      -3.54380      -18.7450    
    endloop
  endfacet
  facet normal   0.936676E-01  0.745246      0.660177    
    outer loop
      vertex    5.82530      -8.92630      -11.7349    
      vertex    14.9758      -6.41420      -15.8690    
      vertex    6.45790      -5.44460      -15.7550    
    endloop
  endfacet
  facet normal  -0.190280E-01  0.961012      0.275852    
    outer loop
      vertex    3.24940      -10.5195      -6.36220    
      vertex    9.74070      -9.46810      -9.57730    
      vertex    5.82530      -8.92630      -11.7349    
    endloop
  endfacet
  facet normal  -0.177992      0.978961      0.997697E-01
    outer loop
      vertex    5.56390      -10.7391      -4.55750    
      vertex    7.77330      -10.5342      -2.62640    
      vertex    9.74070      -9.46810      -9.57730    
    endloop
  endfacet
  facet normal  -0.634569E-01  0.997518     -0.305004E-01
    outer loop
      vertex    2.25130      -10.8281     -0.576300    
      vertex    3.73570      -10.7109      0.168400    
      vertex    5.56390      -10.7391      -4.55750    
    endloop
  endfacet
  facet normal   0.293380E-01  0.996069      0.835788E-01
    outer loop
      vertex    5.56390      -10.7391      -4.55750    
      vertex    3.24940      -10.5195      -6.36220    
      vertex    1.45450      -10.8179      -2.17590    
    endloop
  endfacet
  facet normal  -0.349332      0.923641      0.157655    
    outer loop
      vertex    9.74070      -9.46810      -9.57730    
      vertex    12.6110      -8.96520      -6.16360    
      vertex    14.9758      -6.41420      -15.8690    
    endloop
  endfacet
  facet normal  -0.713541      0.618692      0.328755    
    outer loop
      vertex    14.9758      -6.41420      -15.8690    
      vertex    18.1876      -3.67950      -14.0445    
      vertex    16.3226      -4.00080      -17.4877    
    endloop
  endfacet
  facet normal  -0.791309     -0.396301      0.465591    
    outer loop
      vertex    16.3226      -4.00080      -17.4877    
      vertex    18.1876      -3.67950      -14.0445    
      vertex    15.7740      -2.13070      -16.8283    
    endloop
  endfacet
  facet normal  -0.653043      0.756282      0.396645E-01
    outer loop
      vertex    12.6110      -8.96520      -6.16360    
      vertex    16.2885      -5.72580      -7.38220    
      vertex    14.9758      -6.41420      -15.8690    
    endloop
  endfacet
  facet normal   0.934471E-01  0.743010      0.662724    
    outer loop
      vertex    12.5494      -3.54380      -18.7450    
      vertex    6.45790      -5.44460      -15.7550    
      vertex    14.9758      -6.41420      -15.8690    
    endloop
  endfacet
  facet normal  -0.120102E-01  0.999852      0.123585E-01
    outer loop
      vertex    1.45450      -10.8179      -2.17590    
      vertex    2.25130      -10.8281     -0.576300    
      vertex    5.56390      -10.7391      -4.55750    
    endloop
  endfacet
  facet normal  -0.257739      0.963315      0.747981E-01
    outer loop
      vertex    7.77330      -10.5342      -2.62640    
      vertex    12.6110      -8.96520      -6.16360    
      vertex    9.74070      -9.46810      -9.57730    
    endloop
  endfacet
  facet normal   0.312533     -0.949888      0.609708E-02
    outer loop
      vertex    9.74070      -9.93150      -9.57730    
      vertex    12.6110      -8.96520      -6.16360    
      vertex    7.77330      -10.5342      -2.62640    
    endloop
  endfacet
  facet normal  -0.752418E-01 -0.996679      0.311240E-01
    outer loop
      vertex    5.56390      -11.2025      -4.55750    
      vertex    2.25130      -10.8281     -0.576300    
      vertex    1.45450      -10.8179      -2.17590    
    endloop
  endfacet
  facet normal  -0.127063     -0.699314     -0.703431    
    outer loop
      vertex    14.9758      -6.87760      -15.8690    
      vertex    6.45790      -5.44460      -15.7550    
      vertex    12.5494      -3.54380      -18.7450    
    endloop
  endfacet
  facet normal   0.660925     -0.750452     -0.380078E-03
    outer loop
      vertex    14.9758      -6.87760      -15.8690    
      vertex    16.2885      -5.72580      -7.38220    
      vertex    12.6110      -8.96520      -6.16360    
    endloop
  endfacet
  facet normal   0.762643      0.534953     -0.363596    
    outer loop
      vertex    15.7740      -2.13070      -16.8283    
      vertex    18.1876      -3.67950      -14.0445    
      vertex    16.7558      -4.33240      -18.0083    
    endloop
  endfacet
  facet normal   0.740668     -0.652526     -0.160062    
    outer loop
      vertex    16.7558      -4.33240      -18.0083    
      vertex    18.1876      -3.67950      -14.0445    
      vertex    14.9758      -6.87760      -15.8690    
    endloop
  endfacet
  facet normal   0.415601     -0.904745     -0.933431E-01
    outer loop
      vertex    14.9758      -6.87760      -15.8690    
      vertex    12.6110      -8.96520      -6.16360    
      vertex    9.74070      -9.93150      -9.57730    
    endloop
  endfacet
  facet normal  -0.174830     -0.973955     -0.144383    
    outer loop
      vertex    1.45450      -10.8179      -2.17590    
      vertex    3.24940      -10.5195      -6.36220    
      vertex    5.56390      -11.2025      -4.55750    
    endloop
  endfacet
  facet normal   0.222708E-01 -0.993463      0.111958    
    outer loop
      vertex    5.56390      -11.2025      -4.55750    
      vertex    3.73570      -10.7109      0.168400    
      vertex    2.25130      -10.8281     -0.576300    
    endloop
  endfacet
  facet normal   0.290197     -0.956967     -0.838717E-03
    outer loop
      vertex    9.74070      -9.93150      -9.57730    
      vertex    7.77330      -10.5342      -2.62640    
      vertex    5.56390      -11.2025      -4.55750    
    endloop
  endfacet
  facet normal  -0.698893E-01 -0.946762     -0.314257    
    outer loop
      vertex    3.24940      -10.5195      -6.36220    
      vertex    5.82530      -8.92630      -11.7349    
      vertex    9.74070      -9.93150      -9.57730    
    endloop
  endfacet
  facet normal  -0.133121     -0.738721     -0.660734    
    outer loop
      vertex    5.82530      -8.92630      -11.7349    
      vertex    6.45790      -5.44460      -15.7550    
      vertex    14.9758      -6.87760      -15.8690    
    endloop
  endfacet
  facet normal   0.118197E-01 -0.648213     -0.761367    
    outer loop
      vertex    12.5494      -3.54380      -18.7450    
      vertex    16.7558      -4.33240      -18.0083    
      vertex    14.9758      -6.87760      -15.8690    
    endloop
  endfacet
  facet normal   0.242402      0.540052     -0.805968    
    outer loop
      vertex    12.5494      -3.54380      -18.7450    
      vertex    15.7740      -2.13070      -16.8283    
      vertex    16.7558      -4.33240      -18.0083    
    endloop
  endfacet
  facet normal   0.709544     -0.704520     -0.141340E-01
    outer loop
      vertex    18.1876      -3.67950      -14.0445    
      vertex    16.2885      -5.72580      -7.38220    
      vertex    14.9758      -6.87760      -15.8690    
    endloop
  endfacet
  facet normal   0.664286E-02 -0.901765     -0.432176    
    outer loop
      vertex    14.9758      -6.87760      -15.8690    
      vertex    9.74070      -9.93150      -9.57730    
      vertex    5.82530      -8.92630      -11.7349    
    endloop
  endfacet
  facet normal   0.154126     -0.974841      0.161028    
    outer loop
      vertex    5.56390      -11.2025      -4.55750    
      vertex    7.77330      -10.5342      -2.62640    
      vertex    3.73570      -10.7109      0.168400    
    endloop
  endfacet
  facet normal  -0.566088E-01 -0.955634     -0.289066    
    outer loop
      vertex    9.74070      -9.93150      -9.57730    
      vertex    5.56390      -11.2025      -4.55750    
      vertex    3.24940      -10.5195      -6.36220    
    endloop
  endfacet
  facet normal  -0.251095      0.659650      0.708388    
    outer loop
      vertex    2.32940      -9.15820      -7.34500    
      vertex    3.90930      -4.62500      -11.0063    
      vertex  -0.968400      -5.36560      -12.0456    
    endloop
  endfacet
  facet normal   0.335131      0.316720      0.887342    
    outer loop
      vertex   -5.82070      -4.49620      -10.5233    
      vertex  -0.968400      -5.36560      -12.0456    
      vertex   -1.02040      0.479900      -14.1124    
    endloop
  endfacet
  facet normal  -0.485162      0.161104      0.859455    
    outer loop
      vertex   -1.02040      0.479900      -14.1124    
      vertex    4.52840      -1.07310      -10.6890    
      vertex    3.43940       4.14730      -12.2823    
    endloop
  endfacet
  facet normal   0.206811      0.951855      0.226277    
    outer loop
      vertex  -0.820500      -9.79000      -7.18100    
      vertex   -3.93120      -9.12930      -7.11720    
      vertex   -2.53200      -10.4804      -2.71250    
    endloop
  endfacet
  facet normal   0.298229     -0.416364      0.858895    
    outer loop
      vertex   -5.53090       4.91990      -12.2354    
      vertex  -0.996500       4.87050      -13.8338    
      vertex  -0.804500       9.23150      -11.7864    
    endloop
  endfacet
  facet normal   0.331228     -0.615473E-01  0.941541    
    outer loop
      vertex   -1.02040      0.479900      -14.1124    
      vertex  -0.996500       4.87050      -13.8338    
      vertex   -5.53090       4.91990      -12.2354    
    endloop
  endfacet
  facet normal  -0.243764      0.321364      0.915043    
    outer loop
      vertex   -1.02040      0.479900      -14.1124    
      vertex  -0.968400      -5.36560      -12.0456    
      vertex    3.90930      -4.62500      -11.0063    
    endloop
  endfacet
  facet normal   0.168954      0.731702      0.660353    
    outer loop
      vertex   -3.93120      -9.12930      -7.11720    
      vertex  -0.820500      -9.79000      -7.18100    
      vertex  -0.968400      -5.36560      -12.0456    
    endloop
  endfacet
  facet normal   0.590743E-01  0.982886      0.174486    
    outer loop
      vertex  -0.650900      -10.6786      -2.23290    
      vertex  -0.820500      -9.79000      -7.18100    
      vertex   -2.53200      -10.4804      -2.71250    
    endloop
  endfacet
  facet normal  -0.239644E-01  0.983829      0.177501    
    outer loop
      vertex  -0.650900      -10.6786      -2.23290    
      vertex    1.35300      -10.4642      -3.15070    
      vertex  -0.820500      -9.79000      -7.18100    
    endloop
  endfacet
  facet normal  -0.112199      0.733414      0.670459    
    outer loop
      vertex  -0.820500      -9.79000      -7.18100    
      vertex    2.32940      -9.15820      -7.34500    
      vertex  -0.968400      -5.36560      -12.0456    
    endloop
  endfacet
  facet normal   0.223755      0.418892      0.880036    
    outer loop
      vertex   -5.82070      -4.49620      -10.5233    
      vertex   -1.02040      0.479900      -14.1124    
      vertex   -7.32400      0.618200      -12.5755    
    endloop
  endfacet
  facet normal  -0.337976     -0.577674E-01  0.939380    
    outer loop
      vertex   -1.02040      0.479900      -14.1124    
      vertex    3.43940       4.14730      -12.2823    
      vertex  -0.996500       4.87050      -13.8338    
    endloop
  endfacet
  facet normal  -0.359991     -0.383450      0.850513    
    outer loop
      vertex  -0.996500       4.87050      -13.8338    
      vertex    3.43940       4.14730      -12.2823    
      vertex  -0.804500       9.23150      -11.7864    
    endloop
  endfacet
  facet normal  -0.177410      0.950608      0.254696    
    outer loop
      vertex    1.35300      -10.4642      -3.15070    
      vertex    2.32940      -9.15820      -7.34500    
      vertex  -0.820500      -9.79000      -7.18100    
    endloop
  endfacet
  facet normal  -0.522009      0.148031E-01  0.852811    
    outer loop
      vertex    3.90930      -4.62500      -11.0063    
      vertex    4.52840      -1.07310      -10.6890    
      vertex   -1.02040      0.479900      -14.1124    
    endloop
  endfacet
  facet normal   0.229810     -0.171534      0.958000    
    outer loop
      vertex   -5.53090       4.91990      -12.2354    
      vertex   -7.32400      0.618200      -12.5755    
      vertex   -1.02040      0.479900      -14.1124    
    endloop
  endfacet
  facet normal   0.331780      0.642865      0.690396    
    outer loop
      vertex  -0.968400      -5.36560      -12.0456    
      vertex   -5.82070      -4.49620      -10.5233    
      vertex   -3.93120      -9.12930      -7.11720    
    endloop
  endfacet
  facet normal  -0.402323     -0.643099     -0.651582    
    outer loop
      vertex   -3.93120      -9.12930      -7.11720    
      vertex   -5.82070      -4.49620      -10.5233    
      vertex  -0.968400      -5.36560      -12.6613    
    endloop
  endfacet
  facet normal  -0.312394      0.203577     -0.927883    
    outer loop
      vertex   -1.02040      0.479900      -14.7281    
      vertex   -7.32400      0.618200      -12.5755    
      vertex   -5.53090       4.91990      -12.2354    
    endloop
  endfacet
  facet normal   0.582936     -0.290687E-01 -0.811998    
    outer loop
      vertex   -1.02040      0.479900      -14.7281    
      vertex    4.52840      -1.07310      -10.6890    
      vertex    3.90930      -4.62500      -11.0063    
    endloop
  endfacet
  facet normal   0.274690     -0.934356     -0.226989    
    outer loop
      vertex  -0.820500      -9.97450      -7.79670    
      vertex    2.32940      -9.15820      -7.34500    
      vertex    1.35300      -10.4642      -3.15070    
    endloop
  endfacet
  facet normal   0.450088      0.450881     -0.770796    
    outer loop
      vertex  -0.804500       9.23150      -11.7864    
      vertex    3.43940       4.14730      -12.2823    
      vertex  -0.996500       4.87050      -14.4495    
    endloop
  endfacet
  facet normal   0.445454      0.542811E-01 -0.893658    
    outer loop
      vertex  -0.996500       4.87050      -14.4495    
      vertex    3.43940       4.14730      -12.2823    
      vertex   -1.02040      0.479900      -14.7281    
    endloop
  endfacet
  facet normal  -0.300208     -0.429913     -0.851499    
    outer loop
      vertex   -5.82070      -4.49620      -10.5233    
      vertex   -7.32400      0.618200      -12.5755    
      vertex   -1.02040      0.479900      -14.7281    
    endloop
  endfacet
  facet normal   0.275222     -0.693701     -0.665606    
    outer loop
      vertex  -0.968400      -5.36560      -12.6613    
      vertex    2.32940      -9.15820      -7.34500    
      vertex  -0.820500      -9.97450      -7.79670    
    endloop
  endfacet
  facet normal   0.479089E-01 -0.990765     -0.126842    
    outer loop
      vertex  -0.820500      -9.97450      -7.79670    
      vertex    1.35300      -10.4642      -3.15070    
      vertex  -0.650900      -10.6786      -2.23290    
    endloop
  endfacet
  facet normal  -0.729144E-01 -0.989721     -0.123027    
    outer loop
      vertex  -0.650900      -10.6786      -2.23290    
      vertex   -2.53200      -10.4804      -2.71250    
      vertex  -0.820500      -9.97450      -7.79670    
    endloop
  endfacet
  facet normal  -0.328400     -0.690632     -0.644345    
    outer loop
      vertex  -0.968400      -5.36560      -12.6613    
      vertex  -0.820500      -9.97450      -7.79670    
      vertex   -3.93120      -9.12930      -7.11720    
    endloop
  endfacet
  facet normal   0.347348     -0.309845     -0.885068    
    outer loop
      vertex    3.90930      -4.62500      -11.0063    
      vertex  -0.968400      -5.36560      -12.6613    
      vertex   -1.02040      0.479900      -14.7281    
    endloop
  endfacet
  facet normal  -0.437481      0.593165E-01 -0.897269    
    outer loop
      vertex   -5.53090       4.91990      -12.2354    
      vertex  -0.996500       4.87050      -14.4495    
      vertex   -1.02040      0.479900      -14.7281    
    endloop
  endfacet
  facet normal  -0.376951      0.494758     -0.783021    
    outer loop
      vertex   -5.53090       4.91990      -12.2354    
      vertex  -0.804500       9.23150      -11.7864    
      vertex  -0.996500       4.87050      -14.4495    
    endloop
  endfacet
  facet normal  -0.296283     -0.935434     -0.192818    
    outer loop
      vertex   -2.53200      -10.4804      -2.71250    
      vertex   -3.93120      -9.12930      -7.11720    
      vertex  -0.820500      -9.97450      -7.79670    
    endloop
  endfacet
  facet normal   0.558599     -0.133331     -0.818652    
    outer loop
      vertex    3.43940       4.14730      -12.2823    
      vertex    4.52840      -1.07310      -10.6890    
      vertex   -1.02040      0.479900      -14.7281    
    endloop
  endfacet
  facet normal  -0.429223     -0.304471     -0.850332    
    outer loop
      vertex   -1.02040      0.479900      -14.7281    
      vertex  -0.968400      -5.36560      -12.6613    
      vertex   -5.82070      -4.49620      -10.5233    
    endloop
  endfacet
  facet normal   0.329307     -0.660079     -0.675169    
    outer loop
      vertex  -0.968400      -5.36560      -12.6613    
      vertex    3.90930      -4.62500      -11.0063    
      vertex    2.32940      -9.15820      -7.34500    
    endloop
  endfacet
  facet normal  -0.294151      0.224789     -0.928948    
    outer loop
      vertex    5.45360      -5.07480       9.67680    
      vertex  -0.719200      -5.30090       11.5767    
      vertex  -0.418900     -0.522900       12.6378    
    endloop
  endfacet
  facet normal   0.237398     -0.321812     -0.916558    
    outer loop
      vertex   -4.30160       3.07780       10.3679    
      vertex  -0.676300       2.92540       11.3604    
      vertex  -0.418900     -0.522900       12.6378    
    endloop
  endfacet
  facet normal  -0.132277      0.690065     -0.711557    
    outer loop
      vertex    2.74410      -8.44680       7.88200    
      vertex   -1.19620      -8.91050       8.16480    
      vertex  -0.719200      -5.30090       11.5767    
    endloop
  endfacet
  facet normal   0.201711      0.926294     -0.318264    
    outer loop
      vertex   -3.54900      -10.2023       2.91390    
      vertex   -4.79480      -8.19840       7.95660    
      vertex   -1.19620      -8.91050       8.16480    
    endloop
  endfacet
  facet normal  -0.855627E-01 -0.584482     -0.806883    
    outer loop
      vertex    2.76940       3.08970       10.8760    
      vertex  -0.676300       2.92540       11.3604    
      vertex   -1.09530       4.95410       9.93530    
    endloop
  endfacet
  facet normal  -0.436299     -0.529995E-01 -0.898239    
    outer loop
      vertex    7.26450      -1.26410       8.94950    
      vertex  -0.418900     -0.522900       12.6378    
      vertex    2.76940       3.08970       10.8760    
    endloop
  endfacet
  facet normal  -0.430011      0.321463E-01 -0.902251    
    outer loop
      vertex    5.45360      -5.07480       9.67680    
      vertex  -0.418900     -0.522900       12.6378    
      vertex    7.26450      -1.26410       8.94950    
    endloop
  endfacet
  facet normal  -0.254261      0.605645     -0.754020    
    outer loop
      vertex    2.74410      -8.44680       7.88200    
      vertex  -0.719200      -5.30090       11.5767    
      vertex    5.45360      -5.07480       9.67680    
    endloop
  endfacet
  facet normal  -0.581299E-02  0.974198     -0.225621    
    outer loop
      vertex   -1.42710      -10.4095       1.69830    
      vertex   -1.19620      -8.91050       8.16480    
      vertex   0.610000      -10.2104       2.50550    
    endloop
  endfacet
  facet normal  -0.335474E-01  0.973883     -0.224558    
    outer loop
      vertex   -1.42710      -10.4095       1.69830    
      vertex   -3.54900      -10.2023       2.91390    
      vertex   -1.19620      -8.91050       8.16480    
    endloop
  endfacet
  facet normal   0.173517      0.664298     -0.727049    
    outer loop
      vertex   -1.19620      -8.91050       8.16480    
      vertex   -4.79480      -8.19840       7.95660    
      vertex  -0.719200      -5.30090       11.5767    
    endloop
  endfacet
  facet normal   0.561298     -0.935739E-01 -0.822307    
    outer loop
      vertex   -5.75680      -4.74270       9.47440    
      vertex   -6.67530     -0.490800       8.36360    
      vertex  -0.418900     -0.522900       12.6378    
    endloop
  endfacet
  facet normal   0.562225      0.878739E-01 -0.822302    
    outer loop
      vertex  -0.418900     -0.522900       12.6378    
      vertex   -6.67530     -0.490800       8.36360    
      vertex   -4.30160       3.07780       10.3679    
    endloop
  endfacet
  facet normal   0.202163     -0.534648     -0.820537    
    outer loop
      vertex  -0.676300       2.92540       11.3604    
      vertex   -4.30160       3.07780       10.3679    
      vertex   -1.09530       4.95410       9.93530    
    endloop
  endfacet
  facet normal  -0.131300      0.956220     -0.261542    
    outer loop
      vertex   -1.19620      -8.91050       8.16480    
      vertex    2.74410      -8.44680       7.88200    
      vertex   0.610000      -10.2104       2.50550    
    endloop
  endfacet
  facet normal   0.385015      0.458881     -0.800744    
    outer loop
      vertex   -4.79480      -8.19840       7.95660    
      vertex   -5.75680      -4.74270       9.47440    
      vertex  -0.719200      -5.30090       11.5767    
    endloop
  endfacet
  facet normal   0.395648      0.175341     -0.901509    
    outer loop
      vertex  -0.418900     -0.522900       12.6378    
      vertex  -0.719200      -5.30090       11.5767    
      vertex   -5.75680      -4.74270       9.47440    
    endloop
  endfacet
  facet normal  -0.113766     -0.352576     -0.928842    
    outer loop
      vertex  -0.418900     -0.522900       12.6378    
      vertex  -0.676300       2.92540       11.3604    
      vertex    2.76940       3.08970       10.8760    
    endloop
  endfacet
  facet normal   0.242457      0.352873      0.903712    
    outer loop
      vertex    2.76940       3.08970       10.8760    
      vertex  -0.676300       2.92540       11.8646    
      vertex  -0.418900     -0.522900       13.1420    
    endloop
  endfacet
  facet normal  -0.467588     -0.163530      0.868688    
    outer loop
      vertex   -5.75680      -4.74270       9.47440    
      vertex  -0.719200      -5.30090       12.0809    
      vertex  -0.418900     -0.522900       13.1420    
    endloop
  endfacet
  facet normal  -0.447539     -0.461118      0.766210    
    outer loop
      vertex  -0.719200      -5.30090       12.0809    
      vertex   -5.75680      -4.74270       9.47440    
      vertex   -4.79480      -8.19840       7.95660    
    endloop
  endfacet
  facet normal   0.181042     -0.953513      0.240910    
    outer loop
      vertex   0.610000      -10.2104       2.50550    
      vertex    2.74410      -8.44680       7.88200    
      vertex   -1.19620      -8.99610       8.66900    
    endloop
  endfacet
  facet normal  -0.272580      0.632878      0.724683    
    outer loop
      vertex   -1.09530       4.95410       9.93530    
      vertex   -4.30160       3.07780       10.3679    
      vertex  -0.676300       2.92540       11.8646    
    endloop
  endfacet
  facet normal  -0.606568     -0.424263E-01  0.793899    
    outer loop
      vertex   -4.30160       3.07780       10.3679    
      vertex   -6.67530     -0.490800       8.36360    
      vertex  -0.418900     -0.522900       13.1420    
    endloop
  endfacet
  facet normal  -0.604956      0.763785E-01  0.792587    
    outer loop
      vertex  -0.418900     -0.522900       13.1420    
      vertex   -6.67530     -0.490800       8.36360    
      vertex   -5.75680      -4.74270       9.47440    
    endloop
  endfacet
  facet normal  -0.282865     -0.630712      0.722627    
    outer loop
      vertex  -0.719200      -5.30090       12.0809    
      vertex   -4.79480      -8.19840       7.95660    
      vertex   -1.19620      -8.99610       8.66900    
    endloop
  endfacet
  facet normal   0.178033E-01 -0.980016      0.198121    
    outer loop
      vertex   -1.19620      -8.99610       8.66900    
      vertex   -3.54900      -10.2023       2.91390    
      vertex   -1.42710      -10.4095       1.69830    
    endloop
  endfacet
  facet normal   0.172717E-01 -0.980022      0.198140    
    outer loop
      vertex   -1.42710      -10.4095       1.69830    
      vertex   0.610000      -10.2104       2.50550    
      vertex   -1.19620      -8.99610       8.66900    
    endloop
  endfacet
  facet normal   0.302841     -0.625889      0.718715    
    outer loop
      vertex    2.74410      -8.44680       7.88200    
      vertex    5.45360      -5.07480       9.67680    
      vertex  -0.719200      -5.30090       12.0809    
    endloop
  endfacet
  facet normal   0.473916     -0.575073E-01  0.878690    
    outer loop
      vertex    5.45360      -5.07480       9.67680    
      vertex    7.26450      -1.26410       8.94950    
      vertex  -0.418900     -0.522900       13.1420    
    endloop
  endfacet
  facet normal   0.484362      0.116407      0.867089    
    outer loop
      vertex    7.26450      -1.26410       8.94950    
      vertex    2.76940       3.08970       10.8760    
      vertex  -0.418900     -0.522900       13.1420    
    endloop
  endfacet
  facet normal   0.166742      0.697350      0.697065    
    outer loop
      vertex    2.76940       3.08970       10.8760    
      vertex   -1.09530       4.95410       9.93530    
      vertex  -0.676300       2.92540       11.8646    
    endloop
  endfacet
  facet normal  -0.262628     -0.917205      0.299603    
    outer loop
      vertex   -1.19620      -8.99610       8.66900    
      vertex   -4.79480      -8.19840       7.95660    
      vertex   -3.54900      -10.2023       2.91390    
    endloop
  endfacet
  facet normal   0.233830     -0.675697      0.699112    
    outer loop
      vertex  -0.719200      -5.30090       12.0809    
      vertex   -1.19620      -8.99610       8.66900    
      vertex    2.74410      -8.44680       7.88200    
    endloop
  endfacet
  facet normal  -0.352955      0.301737      0.885651    
    outer loop
      vertex  -0.418900     -0.522900       13.1420    
      vertex  -0.676300       2.92540       11.8646    
      vertex   -4.30160       3.07780       10.3679    
    endloop
  endfacet
  facet normal   0.360818     -0.223749      0.905399    
    outer loop
      vertex  -0.418900     -0.522900       13.1420    
      vertex  -0.719200      -5.30090       12.0809    
      vertex    5.45360      -5.07480       9.67680    
    endloop
  endfacet
  facet normal  -0.838771      0.000000E+00  0.544484    
    outer loop
      vertex   -1.11860      -17.7861      -3.16390    
      vertex   -3.24760      -14.9614      -6.44360    
      vertex   -3.24760      -15.8119      -6.44360    
    endloop
  endfacet
  facet normal   0.515346      0.000000E+00  0.856982    
    outer loop
      vertex   0.502900      -20.4255     -0.842300    
      vertex  -0.608100      -20.5486     -0.174200    
      vertex  -0.608100      -21.3991     -0.174200    
    endloop
  endfacet
  facet normal   0.864098      0.000000E+00 -0.503324    
    outer loop
      vertex   -2.37220      -14.9605      -6.87340    
      vertex  -0.420700      -17.7796      -3.52310    
      vertex  -0.420700      -18.6301      -3.52310    
    endloop
  endfacet
  facet normal   0.999797      0.000000E+00  0.201486E-01
    outer loop
      vertex   -2.04860      -15.1872      -22.9308    
      vertex   -2.37220      -14.9605      -6.87340    
      vertex   -2.37220      -15.8110      -6.87340    
    endloop
  endfacet
  facet normal   0.945461      0.000000E+00 -0.325734    
    outer loop
      vertex  -0.420700      -17.7796      -3.52310    
      vertex   0.502900      -20.4255     -0.842300    
      vertex   0.502900      -21.2760     -0.842300    
    endloop
  endfacet
  facet normal  -0.985733      0.000000E+00  0.168317    
    outer loop
      vertex  -0.608100      -20.5486     -0.174200    
      vertex   -1.11860      -17.7861      -3.16390    
      vertex   -1.11860      -18.6366      -3.16390    
    endloop
  endfacet
  facet normal  -0.492697      0.000000E+00  0.870201    
    outer loop
      vertex   -3.24760      -14.9614      -6.44360    
      vertex   -18.2882      -15.3187      -14.9594    
      vertex   -3.24760      -15.8119      -6.44360    
    endloop
  endfacet
  facet normal   0.230830     -0.956384      0.179019    
    outer loop
      vertex   -34.3869      -24.0947      -52.6490    
      vertex   -39.0717      -26.3247      -58.5218    
      vertex   -28.8861      -24.7979      -63.4986    
    endloop
  endfacet
  facet normal   0.197406     -0.947810      0.250374    
    outer loop
      vertex   -9.49680      -17.0263      -45.8673    
      vertex   -23.0115      -18.0887      -39.2335    
      vertex   -28.8621      -21.1393      -46.1689    
    endloop
  endfacet
  facet normal  -0.165326     -0.969729      0.179701    
    outer loop
      vertex   -49.4058      -23.9500      -53.4263    
      vertex   -49.2789      -24.6485      -57.0789    
      vertex   -40.9905      -26.8155      -61.1474    
    endloop
  endfacet
  facet normal  -0.260704     -0.957139      0.126167    
    outer loop
      vertex   -43.9651      -19.6544      -38.7554    
      vertex   -48.3008      -19.6363      -47.5771    
      vertex   -34.3869      -24.0947      -52.6490    
    endloop
  endfacet
  facet normal   0.456258E-01 -0.930157      0.364316    
    outer loop
      vertex   -16.4340      -15.7695      -30.3774    
      vertex   -28.1653      -14.0895      -24.6189    
      vertex   -38.7206      -17.3112      -31.5225    
    endloop
  endfacet
  facet normal  -0.414911E-01 -0.997403      0.588761E-01
    outer loop
      vertex   -16.4340      -15.7695      -30.3774    
      vertex   -13.4955      -15.6125      -25.6469    
      vertex   -23.9738      -14.8730      -20.5035    
    endloop
  endfacet
  facet normal   0.101845     -0.954659     -0.279738    
    outer loop
      vertex   -13.4955      -15.6125      -25.6469    
      vertex   -4.13070      -13.2636      -30.2535    
      vertex   -2.04860      -15.1872      -22.9308    
    endloop
  endfacet
  facet normal  -0.258951     -0.808073     -0.529115    
    outer loop
      vertex   -3.24760      -15.8119      -6.44360    
      vertex   -2.37220      -15.8110      -6.87340    
      vertex  -0.420700      -18.6301      -3.52310    
    endloop
  endfacet
  facet normal  -0.170799     -0.970693      0.169065    
    outer loop
      vertex   -45.1284      -27.0284      -66.5501    
      vertex   -40.9905      -26.8155      -61.1474    
      vertex   -49.2789      -24.6485      -57.0789    
    endloop
  endfacet
  facet normal  -0.974257E-01 -0.963016      0.251215    
    outer loop
      vertex   -40.9905      -26.8155      -61.1474    
      vertex   -39.0717      -26.3247      -58.5218    
      vertex   -49.4058      -23.9500      -53.4263    
    endloop
  endfacet
  facet normal  -0.386540E-01 -0.800705      0.597811    
    outer loop
      vertex   -49.4058      -23.9500      -53.4263    
      vertex   -34.3869      -24.0947      -52.6490    
      vertex   -48.3008      -19.6363      -47.5771    
    endloop
  endfacet
  facet normal   0.824392E-01 -0.931412      0.354506    
    outer loop
      vertex   -34.3869      -24.0947      -52.6490    
      vertex   -28.8621      -21.1393      -46.1689    
      vertex   -43.9651      -19.6544      -38.7554    
    endloop
  endfacet
  facet normal   0.110716     -0.940785      0.320414    
    outer loop
      vertex   -28.8621      -21.1393      -46.1689    
      vertex   -23.0115      -18.0887      -39.2335    
      vertex   -38.7206      -17.3112      -31.5225    
    endloop
  endfacet
  facet normal   0.565016E-01 -0.975319      0.213448    
    outer loop
      vertex   -38.7206      -17.3112      -31.5225    
      vertex   -23.0115      -18.0887      -39.2335    
      vertex   -16.4340      -15.7695      -30.3774    
    endloop
  endfacet
  facet normal  -0.155784     -0.987356     -0.293109E-01
    outer loop
      vertex   -28.1653      -14.0895      -24.6189    
      vertex   -16.4340      -15.7695      -30.3774    
      vertex   -23.9738      -14.8730      -20.5035    
    endloop
  endfacet
  facet normal  -0.661556E-01 -0.997772      0.868171E-02
    outer loop
      vertex   -23.9738      -14.8730      -20.5035    
      vertex   -13.4955      -15.6125      -25.6469    
      vertex   -10.1105      -15.7785      -18.9308    
    endloop
  endfacet
  facet normal  -0.453480E-01 -0.998723      0.222517E-01
    outer loop
      vertex   -18.2882      -15.3187      -14.9594    
      vertex   -10.1105      -15.7785      -18.9308    
      vertex   -3.24760      -15.8119      -6.44360    
    endloop
  endfacet
  facet normal  -0.263113     -0.808861     -0.525847    
    outer loop
      vertex   -3.24760      -15.8119      -6.44360    
      vertex  -0.420700      -18.6301      -3.52310    
      vertex   -1.11860      -18.6366      -3.16390    
    endloop
  endfacet
  facet normal  -0.291556     -0.729118     -0.619178    
    outer loop
      vertex  -0.420700      -18.6301      -3.52310    
      vertex   0.502900      -21.2760     -0.842300    
      vertex  -0.608100      -21.3991     -0.174200    
    endloop
  endfacet
  facet normal   0.544962E-01 -0.997803     -0.376646E-01
    outer loop
      vertex   -10.1105      -15.7785      -18.9308    
      vertex   -2.04860      -15.1872      -22.9308    
      vertex   -2.37220      -15.8110      -6.87340    
    endloop
  endfacet
  facet normal   0.487451E-01 -0.997598     -0.492254E-01
    outer loop
      vertex   -13.4955      -15.6125      -25.6469    
      vertex   -2.04860      -15.1872      -22.9308    
      vertex   -10.1105      -15.7785      -18.9308    
    endloop
  endfacet
  facet normal   0.329517     -0.922873      0.199307    
    outer loop
      vertex   -6.60190      -15.2150      -35.2036    
      vertex   -4.13070      -13.2636      -30.2535    
      vertex   -13.4955      -15.6125      -25.6469    
    endloop
  endfacet
  facet normal   0.148485     -0.978099      0.145859    
    outer loop
      vertex   -23.0115      -18.0887      -39.2335    
      vertex   -9.49680      -17.0263      -45.8673    
      vertex   -16.4340      -15.7695      -30.3774    
    endloop
  endfacet
  facet normal   0.204522     -0.943959     -0.259059    
    outer loop
      vertex   -28.8621      -21.1393      -46.1689    
      vertex   -14.3105      -16.0262      -53.3118    
      vertex   -9.49680      -17.0263      -45.8673    
    endloop
  endfacet
  facet normal   0.459101     -0.816045      0.351136    
    outer loop
      vertex   -21.0367      -22.3405      -59.1920    
      vertex   -14.3105      -16.0262      -53.3118    
      vertex   -28.8621      -21.1393      -46.1689    
    endloop
  endfacet
  facet normal   0.209138     -0.963265      0.168467    
    outer loop
      vertex   -28.8861      -24.7979      -63.4986    
      vertex   -21.0367      -22.3405      -59.1920    
      vertex   -34.3869      -24.0947      -52.6490    
    endloop
  endfacet
  facet normal   0.174741     -0.983018      0.560533E-01
    outer loop
      vertex   -40.9905      -26.8155      -61.1474    
      vertex   -28.8861      -24.7979      -63.4986    
      vertex   -39.0717      -26.3247      -58.5218    
    endloop
  endfacet
  facet normal   0.288016     -0.939870     -0.183553    
    outer loop
      vertex   -45.1284      -27.0284      -66.5501    
      vertex   -33.1896      -23.6826      -64.9487    
      vertex   -40.9905      -26.8155      -61.1474    
    endloop
  endfacet
  facet normal  -0.310315     -0.724032     -0.616022    
    outer loop
      vertex  -0.608100      -21.3991     -0.174200    
      vertex   -1.11860      -18.6366      -3.16390    
      vertex  -0.420700      -18.6301      -3.52310    
    endloop
  endfacet
  facet normal  -0.224315E-03 -0.999997     -0.255149E-02
    outer loop
      vertex   -2.37220      -15.8110      -6.87340    
      vertex   -3.24760      -15.8119      -6.44360    
      vertex   -10.1105      -15.7785      -18.9308    
    endloop
  endfacet
  facet normal   0.556170E-01 -0.998451     -0.141086E-02
    outer loop
      vertex   -13.4955      -15.6125      -25.6469    
      vertex   -16.4340      -15.7695      -30.3774    
      vertex   -6.60190      -15.2150      -35.2036    
    endloop
  endfacet
  facet normal  -0.634595E-01 -0.997870     -0.151413E-01
    outer loop
      vertex   -10.1105      -15.7785      -18.9308    
      vertex   -18.2882      -15.3187      -14.9594    
      vertex   -23.9738      -14.8730      -20.5035    
    endloop
  endfacet
  facet normal   0.429409E-01 -0.959157      0.279596    
    outer loop
      vertex   -38.7206      -17.3112      -31.5225    
      vertex   -43.9651      -19.6544      -38.7554    
      vertex   -28.8621      -21.1393      -46.1689    
    endloop
  endfacet
  facet normal  -0.283115E-01 -0.926793      0.374503    
    outer loop
      vertex   -49.4058      -23.9500      -53.4263    
      vertex   -39.0717      -26.3247      -58.5218    
      vertex   -34.3869      -24.0947      -52.6490    
    endloop
  endfacet
  facet normal   0.236371     -0.944261      0.229127    
    outer loop
      vertex   -28.8621      -21.1393      -46.1689    
      vertex   -34.3869      -24.0947      -52.6490    
      vertex   -21.0367      -22.3405      -59.1920    
    endloop
  endfacet
  facet normal   0.121304     -0.983512      0.134125    
    outer loop
      vertex   -9.49680      -17.0263      -45.8673    
      vertex   -6.60190      -15.2150      -35.2036    
      vertex   -16.4340      -15.7695      -30.3774    
    endloop
  endfacet
  facet normal   0.855551E-02 -0.780207     -0.625463    
    outer loop
      vertex   -40.9905      -26.8155      -61.1474    
      vertex   -33.1896      -23.6826      -64.9487    
      vertex   -28.8861      -24.7979      -63.4986    
    endloop
  endfacet
  facet normal  -0.173779      0.958645     -0.225388    
    outer loop
      vertex   -28.8861      -24.7979      -63.4986    
      vertex   -39.0717      -25.4742      -58.5218    
      vertex   -34.3869      -23.2442      -52.6490    
    endloop
  endfacet
  facet normal  -0.154900      0.945821     -0.285357    
    outer loop
      vertex   -28.8621      -20.2888      -46.1689    
      vertex   -23.0115      -17.2382      -39.2335    
      vertex   -9.49680      -17.0263      -45.8673    
    endloop
  endfacet
  facet normal   0.648078E-01  0.980550     -0.185262    
    outer loop
      vertex   -40.9905      -25.9650      -61.1474    
      vertex   -49.2789      -24.6485      -57.0789    
      vertex   -49.4058      -23.9500      -53.4263    
    endloop
  endfacet
  facet normal   0.214212      0.971311     -0.103288    
    outer loop
      vertex   -34.3869      -23.2442      -52.6490    
      vertex   -48.3008      -19.6363      -47.5771    
      vertex   -43.9651      -19.6544      -38.7554    
    endloop
  endfacet
  facet normal  -0.856367E-01  0.946604     -0.310817    
    outer loop
      vertex   -38.7206      -17.3112      -31.5225    
      vertex   -28.1653      -14.0895      -24.6189    
      vertex   -16.4340      -14.9190      -30.3774    
    endloop
  endfacet
  facet normal  -0.205938E-01  0.999580     -0.203824E-01
    outer loop
      vertex   -23.9738      -14.8730      -20.5035    
      vertex   -13.4955      -14.7620      -25.6469    
      vertex   -16.4340      -14.9190      -30.3774    
    endloop
  endfacet
  facet normal  -0.260624E-01  0.965011      0.260909    
    outer loop
      vertex   -2.04860      -15.1872      -22.9308    
      vertex   -4.13070      -13.2636      -30.2535    
      vertex   -13.4955      -14.7620      -25.6469    
    endloop
  endfacet
  facet normal   0.258951      0.808073      0.529115    
    outer loop
      vertex  -0.420700      -17.7796      -3.52310    
      vertex   -2.37220      -14.9605      -6.87340    
      vertex   -3.24760      -14.9614      -6.44360    
    endloop
  endfacet
  facet normal   0.440124E-01  0.973299     -0.225281    
    outer loop
      vertex   -45.1284      -27.0284      -66.5501    
      vertex   -49.2789      -24.6485      -57.0789    
      vertex   -40.9905      -25.9650      -61.1474    
    endloop
  endfacet
  facet normal   0.397141E-01  0.976556     -0.211570    
    outer loop
      vertex   -49.4058      -23.9500      -53.4263    
      vertex   -39.0717      -25.4742      -58.5218    
      vertex   -40.9905      -25.9650      -61.1474    
    endloop
  endfacet
  facet normal  -0.717871E-02  0.805435     -0.592641    
    outer loop
      vertex   -49.4058      -23.9500      -53.4263    
      vertex   -48.3008      -19.6363      -47.5771    
      vertex   -34.3869      -23.2442      -52.6490    
    endloop
  endfacet
  facet normal  -0.120254      0.937951     -0.325249    
    outer loop
      vertex   -43.9651      -19.6544      -38.7554    
      vertex   -28.8621      -20.2888      -46.1689    
      vertex   -34.3869      -23.2442      -52.6490    
    endloop
  endfacet
  facet normal  -0.147421      0.945179     -0.291383    
    outer loop
      vertex   -38.7206      -17.3112      -31.5225    
      vertex   -23.0115      -17.2382      -39.2335    
      vertex   -28.8621      -20.2888      -46.1689    
    endloop
  endfacet
  facet normal  -0.954648E-01  0.978048     -0.185225    
    outer loop
      vertex   -16.4340      -14.9190      -30.3774    
      vertex   -23.0115      -17.2382      -39.2335    
      vertex   -38.7206      -17.3112      -31.5225    
    endloop
  endfacet
  facet normal   0.108462      0.991020      0.782054E-01
    outer loop
      vertex   -28.1653      -14.0895      -24.6189    
      vertex   -23.9738      -14.8730      -20.5035    
      vertex   -16.4340      -14.9190      -30.3774    
    endloop
  endfacet
  facet normal   0.123357E-02  0.999709      0.240879E-01
    outer loop
      vertex   -10.1105      -14.9280      -18.9308    
      vertex   -13.4955      -14.7620      -25.6469    
      vertex   -23.9738      -14.8730      -20.5035    
    endloop
  endfacet
  facet normal  -0.366515E-01  0.999068      0.228157E-01
    outer loop
      vertex   -3.24760      -14.9614      -6.44360    
      vertex   -10.1105      -14.9280      -18.9308    
      vertex   -18.2882      -15.3187      -14.9594    
    endloop
  endfacet
  facet normal   0.263113      0.808861      0.525847    
    outer loop
      vertex   -1.11860      -17.7861      -3.16390    
      vertex  -0.420700      -17.7796      -3.52310    
      vertex   -3.24760      -14.9614      -6.44360    
    endloop
  endfacet
  facet normal   0.291557      0.729118      0.619178    
    outer loop
      vertex  -0.608100      -20.5486     -0.174200    
      vertex   0.502900      -20.4255     -0.842300    
      vertex  -0.420700      -17.7796      -3.52310    
    endloop
  endfacet
  facet normal   0.253897E-01  0.999585     -0.136006E-01
    outer loop
      vertex   -2.37220      -14.9605      -6.87340    
      vertex   -2.04860      -15.1872      -22.9308    
      vertex   -10.1105      -14.9280      -18.9308    
    endloop
  endfacet
  facet normal   0.355064E-01  0.999346      0.680493E-02
    outer loop
      vertex   -10.1105      -14.9280      -18.9308    
      vertex   -2.04860      -15.1872      -22.9308    
      vertex   -13.4955      -14.7620      -25.6469    
    endloop
  endfacet
  facet normal  -0.265609      0.934774     -0.235903    
    outer loop
      vertex   -13.4955      -14.7620      -25.6469    
      vertex   -4.13070      -13.2636      -30.2535    
      vertex   -6.60190      -15.2150      -35.2036    
    endloop
  endfacet
  facet normal  -0.103401      0.978326     -0.179403    
    outer loop
      vertex   -16.4340      -14.9190      -30.3774    
      vertex   -9.49680      -17.0263      -45.8673    
      vertex   -23.0115      -17.2382      -39.2335    
    endloop
  endfacet
  facet normal  -0.165026      0.957791      0.235378    
    outer loop
      vertex   -9.49680      -17.0263      -45.8673    
      vertex   -14.3105      -16.0262      -53.3118    
      vertex   -28.8621      -20.2888      -46.1689    
    endloop
  endfacet
  facet normal  -0.428847      0.816599     -0.386338    
    outer loop
      vertex   -28.8621      -20.2888      -46.1689    
      vertex   -14.3105      -16.0262      -53.3118    
      vertex   -21.0367      -22.3405      -59.1920    
    endloop
  endfacet
  facet normal  -0.175771      0.958064     -0.226315    
    outer loop
      vertex   -34.3869      -23.2442      -52.6490    
      vertex   -21.0367      -22.3405      -59.1920    
      vertex   -28.8861      -24.7979      -63.4986    
    endloop
  endfacet
  facet normal  -0.114865      0.988255     -0.100790    
    outer loop
      vertex   -39.0717      -25.4742      -58.5218    
      vertex   -28.8861      -24.7979      -63.4986    
      vertex   -40.9905      -25.9650      -61.1474    
    endloop
  endfacet
  facet normal  -0.272175      0.962058      0.190974E-01
    outer loop
      vertex   -40.9905      -25.9650      -61.1474    
      vertex   -33.1896      -23.6826      -64.9487    
      vertex   -45.1284      -27.0284      -66.5501    
    endloop
  endfacet
  facet normal   0.310315      0.724032      0.616022    
    outer loop
      vertex  -0.420700      -17.7796      -3.52310    
      vertex   -1.11860      -17.7861      -3.16390    
      vertex  -0.608100      -20.5486     -0.174200    
    endloop
  endfacet
  facet normal   0.224285E-03  0.999997      0.255143E-02
    outer loop
      vertex   -10.1105      -14.9280      -18.9308    
      vertex   -3.24760      -14.9614      -6.44360    
      vertex   -2.37220      -14.9605      -6.87340    
    endloop
  endfacet
  facet normal   0.105775E-01  0.999154     -0.397313E-01
    outer loop
      vertex   -6.60190      -15.2150      -35.2036    
      vertex   -16.4340      -14.9190      -30.3774    
      vertex   -13.4955      -14.7620      -25.6469    
    endloop
  endfacet
  facet normal  -0.580922E-02  0.996274      0.860497E-01
    outer loop
      vertex   -23.9738      -14.8730      -20.5035    
      vertex   -18.2882      -15.3187      -14.9594    
      vertex   -10.1105      -14.9280      -18.9308    
    endloop
  endfacet
  facet normal  -0.832061E-01  0.964140     -0.252015    
    outer loop
      vertex   -28.8621      -20.2888      -46.1689    
      vertex   -43.9651      -19.6544      -38.7554    
      vertex   -38.7206      -17.3112      -31.5225    
    endloop
  endfacet
  facet normal  -0.268498E-01  0.941455     -0.336068    
    outer loop
      vertex   -34.3869      -23.2442      -52.6490    
      vertex   -39.0717      -25.4742      -58.5218    
      vertex   -49.4058      -23.9500      -53.4263    
    endloop
  endfacet
  facet normal  -0.193980      0.944437     -0.265349    
    outer loop
      vertex   -21.0367      -22.3405      -59.1920    
      vertex   -34.3869      -23.2442      -52.6490    
      vertex   -28.8621      -20.2888      -46.1689    
    endloop
  endfacet
  facet normal  -0.463872E-01  0.986821     -0.155025    
    outer loop
      vertex   -16.4340      -14.9190      -30.3774    
      vertex   -6.60190      -15.2150      -35.2036    
      vertex   -9.49680      -17.0263      -45.8673    
    endloop
  endfacet
  facet normal   0.279149E-01  0.830681      0.556049    
    outer loop
      vertex   -28.8861      -24.7979      -63.4986    
      vertex   -33.1896      -23.6826      -64.9487    
      vertex   -40.9905      -25.9650      -61.1474    
    endloop
  endfacet
  facet normal  -0.302170      0.000000E+00 -0.953254    
    outer loop
      vertex   -3.29530      -13.6029      0.875900    
      vertex   -1.28450      -16.4342      0.238500    
      vertex   -1.28450      -17.4246      0.238500    
    endloop
  endfacet
  facet normal   0.308704E-02  0.000000E+00 -0.999995    
    outer loop
      vertex   -25.4737      -11.3312       2.74100    
      vertex   -7.23620      -10.9945       2.79730    
      vertex   -7.23620      -11.9849       2.79730    
    endloop
  endfacet
  facet normal   0.454498      0.000000E+00  0.890748    
    outer loop
      vertex   -3.18350      -13.7998       1.72650    
      vertex   -6.83940      -11.1948       3.59190    
      vertex   -6.83940      -12.1852       3.59190    
    endloop
  endfacet
  facet normal   0.193958      0.000000E+00  0.981010    
    outer loop
      vertex  -0.796200      -16.5071       1.25450    
      vertex   -3.18350      -13.7998       1.72650    
      vertex   -3.18350      -14.7902       1.72650    
    endloop
  endfacet
  facet normal   0.858145      0.000000E+00  0.513407    
    outer loop
      vertex   -6.83940      -11.1948       3.59190    
      vertex   -12.8325      -11.6090       13.6092    
      vertex   -6.83940      -12.1852       3.59190    
    endloop
  endfacet
  facet normal  -0.438241      0.000000E+00 -0.898857    
    outer loop
      vertex   -7.23620      -10.9945       2.79730    
      vertex   -3.29530      -13.6029      0.875900    
      vertex   -3.29530      -14.5933      0.875900    
    endloop
  endfacet
  facet normal   0.901308      0.000000E+00 -0.433178    
    outer loop
      vertex   -1.28450      -16.4342      0.238500    
      vertex  -0.796200      -16.5071       1.25450    
      vertex  -0.796200      -17.4975       1.25450    
    endloop
  endfacet
  facet normal   0.496365     -0.868026      0.123332E-01
    outer loop
      vertex   -53.2139      -19.7732       33.3687    
      vertex   -48.0953      -16.7006       43.6177    
      vertex   -54.9291      -20.5138       50.2745    
    endloop
  endfacet
  facet normal  -0.268224     -0.955369     -0.123796    
    outer loop
      vertex   -53.2139      -19.7732       33.3687    
      vertex   -60.5125      -15.8304       18.7546    
      vertex   -56.0198      -16.2797       12.4878    
    endloop
  endfacet
  facet normal   0.768297     -0.640079     -0.418504E-02
    outer loop
      vertex   -49.0305      -17.7111       26.4826    
      vertex   -43.0585      -10.6210       38.4405    
      vertex   -48.0953      -16.7006       43.6177    
    endloop
  endfacet
  facet normal   0.376217E-01 -0.975625      0.216196    
    outer loop
      vertex   -25.4380      -13.7425       24.5733    
      vertex   -37.0954      -12.0385       34.2915    
      vertex   -42.1498      -15.3726       20.1253    
    endloop
  endfacet
  facet normal   0.188038     -0.962767     -0.194220    
    outer loop
      vertex   -28.6316      -11.4833       13.9336    
      vertex   -42.1498      -15.3726       20.1253    
      vertex   -49.9354      -14.5645       8.58170    
    endloop
  endfacet
  facet normal  -0.936419E-01 -0.975488     -0.199135    
    outer loop
      vertex   -7.23620      -11.9849       2.79730    
      vertex   -6.83940      -12.1852       3.59190    
      vertex   -20.0680      -12.1534       9.65680    
    endloop
  endfacet
  facet normal  -0.753538     -0.655292     -0.526472E-01
    outer loop
      vertex  -0.796200      -17.4975       1.25450    
      vertex   -3.18350      -14.7902       1.72650    
      vertex   -3.29530      -14.5933      0.875900    
    endloop
  endfacet
  facet normal   0.191878     -0.927157     -0.321811    
    outer loop
      vertex   -65.8992      -27.7642       50.9422    
      vertex   -64.0561      -20.8078       31.9993    
      vertex   -58.5302      -23.5210       43.1110    
    endloop
  endfacet
  facet normal   0.129800     -0.939099     -0.318189    
    outer loop
      vertex   -64.0561      -20.8078       31.9993    
      vertex   -60.5125      -15.8304       18.7546    
      vertex   -53.2139      -19.7732       33.3687    
    endloop
  endfacet
  facet normal   0.172341     -0.967504     -0.185028    
    outer loop
      vertex   -53.2139      -19.7732       33.3687    
      vertex   -56.0198      -16.2797       12.4878    
      vertex   -49.0305      -17.7111       26.4826    
    endloop
  endfacet
  facet normal   0.160590     -0.971149     -0.176294    
    outer loop
      vertex   -56.0198      -16.2797       12.4878    
      vertex   -49.9354      -14.5645       8.58170    
      vertex   -42.1498      -15.3726       20.1253    
    endloop
  endfacet
  facet normal   0.384121     -0.872958     -0.300658    
    outer loop
      vertex   -25.4380      -13.7425       24.5733    
      vertex   -28.6316      -11.4833       13.9336    
      vertex   -19.3157      -9.30410       19.5083    
    endloop
  endfacet
  facet normal   0.633400E-04 -0.931404      0.363988    
    outer loop
      vertex   -19.3157      -9.30410       19.5083    
      vertex   -28.6316      -11.4833       13.9336    
      vertex   -12.8325      -11.6090       13.6092    
    endloop
  endfacet
  facet normal   0.329103E-01 -0.996487      0.770078E-01
    outer loop
      vertex   -12.8325      -11.6090       13.6092    
      vertex   -20.0680      -12.1534       9.65680    
      vertex   -6.83940      -12.1852       3.59190    
    endloop
  endfacet
  facet normal  -0.532958     -0.844463      0.532751E-01
    outer loop
      vertex   -6.83940      -12.1852       3.59190    
      vertex   -7.23620      -11.9849       2.79730    
      vertex   -3.29530      -14.5933      0.875900    
    endloop
  endfacet
  facet normal  -0.739740     -0.595780      0.312779    
    outer loop
      vertex   -3.29530      -14.5933      0.875900    
      vertex   -1.28450      -17.4246      0.238500    
      vertex  -0.796200      -17.4975       1.25450    
    endloop
  endfacet
  facet normal  -0.353938E-01 -0.995253     -0.906576E-01
    outer loop
      vertex   -20.0680      -12.1534       9.65680    
      vertex   -25.4737      -11.3312       2.74100    
      vertex   -7.23620      -11.9849       2.79730    
    endloop
  endfacet
  facet normal  -0.569477     -0.803897     -0.171598    
    outer loop
      vertex   -28.6316      -11.4833       13.9336    
      vertex   -37.0801      -3.69540       5.48690    
      vertex   -25.4737      -11.3312       2.74100    
    endloop
  endfacet
  facet normal   0.277384     -0.551979     -0.786370    
    outer loop
      vertex   -49.9354      -14.5645       8.58170    
      vertex   -37.0801      -3.69540       5.48690    
      vertex   -28.6316      -11.4833       13.9336    
    endloop
  endfacet
  facet normal   0.159860     -0.954770     -0.250716    
    outer loop
      vertex   -42.1498      -15.3726       20.1253    
      vertex   -28.6316      -11.4833       13.9336    
      vertex   -25.4380      -13.7425       24.5733    
    endloop
  endfacet
  facet normal   0.113981     -0.878495      0.463955    
    outer loop
      vertex   -43.0585      -10.6210       38.4405    
      vertex   -49.0305      -17.7111       26.4826    
      vertex   -37.0954      -12.0385       34.2915    
    endloop
  endfacet
  facet normal   0.475916     -0.879110      0.258688E-01
    outer loop
      vertex   -48.0953      -16.7006       43.6177    
      vertex   -53.2139      -19.7732       33.3687    
      vertex   -49.0305      -17.7111       26.4826    
    endloop
  endfacet
  facet normal   0.608553     -0.793054      0.269997E-01
    outer loop
      vertex   -54.9291      -20.5138       50.2745    
      vertex   -58.5302      -23.5210       43.1110    
      vertex   -53.2139      -19.7732       33.3687    
    endloop
  endfacet
  facet normal   0.552990     -0.830198      0.705239E-01
    outer loop
      vertex   -65.8992      -27.7642       50.9422    
      vertex   -58.5302      -23.5210       43.1110    
      vertex   -54.9291      -20.5138       50.2745    
    endloop
  endfacet
  facet normal  -0.611107     -0.785027     -0.101399    
    outer loop
      vertex   -3.29530      -14.5933      0.875900    
      vertex   -3.18350      -14.7902       1.72650    
      vertex   -6.83940      -12.1852       3.59190    
    endloop
  endfacet
  facet normal  -0.984187E-01 -0.994289     -0.412798E-01
    outer loop
      vertex   -25.4737      -11.3312       2.74100    
      vertex   -20.0680      -12.1534       9.65680    
      vertex   -28.6316      -11.4833       13.9336    
    endloop
  endfacet
  facet normal  -0.488974E-02 -0.989386      0.145229    
    outer loop
      vertex   -28.6316      -11.4833       13.9336    
      vertex   -20.0680      -12.1534       9.65680    
      vertex   -12.8325      -11.6090       13.6092    
    endloop
  endfacet
  facet normal   0.385357     -0.919389      0.788911E-01
    outer loop
      vertex   -49.0305      -17.7111       26.4826    
      vertex   -42.1498      -15.3726       20.1253    
      vertex   -37.0954      -12.0385       34.2915    
    endloop
  endfacet
  facet normal   0.162854     -0.969991     -0.180544    
    outer loop
      vertex   -42.1498      -15.3726       20.1253    
      vertex   -49.0305      -17.7111       26.4826    
      vertex   -56.0198      -16.2797       12.4878    
    endloop
  endfacet
  facet normal   0.127590     -0.947036     -0.294694    
    outer loop
      vertex   -53.2139      -19.7732       33.3687    
      vertex   -58.5302      -23.5210       43.1110    
      vertex   -64.0561      -20.8078       31.9993    
    endloop
  endfacet
  facet normal  -0.208196      0.945560      0.250140    
    outer loop
      vertex   -64.0561      -20.8078       31.9993    
      vertex   -58.5302      -22.5306       43.1110    
      vertex   -53.2139      -18.7828       33.3687    
    endloop
  endfacet
  facet normal  -0.206122      0.969378      0.133488    
    outer loop
      vertex   -56.0198      -16.2797       12.4878    
      vertex   -49.0305      -16.7207       26.4826    
      vertex   -42.1498      -14.3822       20.1253    
    endloop
  endfacet
  facet normal  -0.347306      0.937235     -0.311428E-01
    outer loop
      vertex   -37.0954      -12.0385       34.2915    
      vertex   -42.1498      -14.3822       20.1253    
      vertex   -49.0305      -16.7207       26.4826    
    endloop
  endfacet
  facet normal   0.701351E-01  0.997412     -0.158428E-01
    outer loop
      vertex   -12.8325      -11.6090       13.6092    
      vertex   -20.0680      -11.1630       9.65680    
      vertex   -28.6316      -10.4929       13.9336    
    endloop
  endfacet
  facet normal   0.474010E-01  0.996993     -0.612987E-01
    outer loop
      vertex   -28.6316      -10.4929       13.9336    
      vertex   -20.0680      -11.1630       9.65680    
      vertex   -25.4737      -11.3312       2.74100    
    endloop
  endfacet
  facet normal   0.611107      0.785027      0.101399    
    outer loop
      vertex   -6.83940      -11.1948       3.59190    
      vertex   -3.18350      -13.7998       1.72650    
      vertex   -3.29530      -13.6029      0.875900    
    endloop
  endfacet
  facet normal  -0.549173      0.834699      0.410701E-01
    outer loop
      vertex   -65.8992      -27.7642       50.9422    
      vertex   -54.9291      -20.5138       50.2745    
      vertex   -58.5302      -22.5306       43.1110    
    endloop
  endfacet
  facet normal  -0.536069      0.843568      0.319860E-01
    outer loop
      vertex   -53.2139      -18.7828       33.3687    
      vertex   -58.5302      -22.5306       43.1110    
      vertex   -54.9291      -20.5138       50.2745    
    endloop
  endfacet
  facet normal  -0.413343      0.910322      0.214916E-01
    outer loop
      vertex   -49.0305      -16.7207       26.4826    
      vertex   -53.2139      -18.7828       33.3687    
      vertex   -48.0953      -16.7006       43.6177    
    endloop
  endfacet
  facet normal  -0.785758E-01  0.903384     -0.421572    
    outer loop
      vertex   -43.0585      -10.6210       38.4405    
      vertex   -37.0954      -12.0385       34.2915    
      vertex   -49.0305      -16.7207       26.4826    
    endloop
  endfacet
  facet normal  -0.121950      0.938432      0.323223    
    outer loop
      vertex   -25.4380      -13.7425       24.5733    
      vertex   -28.6316      -10.4929       13.9336    
      vertex   -42.1498      -14.3822       20.1253    
    endloop
  endfacet
  facet normal  -0.301010      0.573051      0.762238    
    outer loop
      vertex   -28.6316      -10.4929       13.9336    
      vertex   -37.0801      -3.69540       5.48690    
      vertex   -49.9354      -14.5645       8.58170    
    endloop
  endfacet
  facet normal   0.562981      0.820714      0.973708E-01
    outer loop
      vertex   -25.4737      -11.3312       2.74100    
      vertex   -37.0801      -3.69540       5.48690    
      vertex   -28.6316      -10.4929       13.9336    
    endloop
  endfacet
  facet normal  -0.184273E-01  0.999781     -0.991213E-02
    outer loop
      vertex   -7.23620      -10.9945       2.79730    
      vertex   -25.4737      -11.3312       2.74100    
      vertex   -20.0680      -11.1630       9.65680    
    endloop
  endfacet
  facet normal   0.739740      0.595781     -0.312779    
    outer loop
      vertex  -0.796200      -16.5071       1.25450    
      vertex   -1.28450      -16.4342      0.238500    
      vertex   -3.29530      -13.6029      0.875900    
    endloop
  endfacet
  facet normal   0.532958      0.844463     -0.532744E-01
    outer loop
      vertex   -3.29530      -13.6029      0.875900    
      vertex   -7.23620      -10.9945       2.79730    
      vertex   -6.83940      -11.1948       3.59190    
    endloop
  endfacet
  facet normal   0.293708E-01  0.997836      0.588308E-01
    outer loop
      vertex   -6.83940      -11.1948       3.59190    
      vertex   -20.0680      -11.1630       9.65680    
      vertex   -12.8325      -11.6090       13.6092    
    endloop
  endfacet
  facet normal   0.608996E-01  0.950571     -0.304478    
    outer loop
      vertex   -19.3157      -9.30410       19.5083    
      vertex   -12.8325      -11.6090       13.6092    
      vertex   -28.6316      -10.4929       13.9336    
    endloop
  endfacet
  facet normal  -0.329460      0.870824      0.364859    
    outer loop
      vertex   -25.4380      -13.7425       24.5733    
      vertex   -19.3157      -9.30410       19.5083    
      vertex   -28.6316      -10.4929       13.9336    
    endloop
  endfacet
  facet normal  -0.198289      0.972970      0.118371    
    outer loop
      vertex   -42.1498      -14.3822       20.1253    
      vertex   -49.9354      -14.5645       8.58170    
      vertex   -56.0198      -16.2797       12.4878    
    endloop
  endfacet
  facet normal  -0.232728      0.961441      0.146526    
    outer loop
      vertex   -49.0305      -16.7207       26.4826    
      vertex   -56.0198      -16.2797       12.4878    
      vertex   -53.2139      -18.7828       33.3687    
    endloop
  endfacet
  facet normal  -0.211223      0.932230      0.293823    
    outer loop
      vertex   -53.2139      -18.7828       33.3687    
      vertex   -60.5125      -15.8304       18.7546    
      vertex   -64.0561      -20.8078       31.9993    
    endloop
  endfacet
  facet normal  -0.320735      0.898785      0.298854    
    outer loop
      vertex   -58.5302      -22.5306       43.1110    
      vertex   -64.0561      -20.8078       31.9993    
      vertex   -65.8992      -27.7642       50.9422    
    endloop
  endfacet
  facet normal   0.753538      0.655292      0.526473E-01
    outer loop
      vertex   -3.29530      -13.6029      0.875900    
      vertex   -3.18350      -13.7998       1.72650    
      vertex  -0.796200      -16.5071       1.25450    
    endloop
  endfacet
  facet normal   0.936424E-01  0.975488      0.199136    
    outer loop
      vertex   -20.0680      -11.1630       9.65680    
      vertex   -6.83940      -11.1948       3.59190    
      vertex   -7.23620      -10.9945       2.79730    
    endloop
  endfacet
  facet normal  -0.217906      0.967043      0.131696    
    outer loop
      vertex   -49.9354      -14.5645       8.58170    
      vertex   -42.1498      -14.3822       20.1253    
      vertex   -28.6316      -10.4929       13.9336    
    endloop
  endfacet
  facet normal   0.627211E-02  0.986207     -0.165399    
    outer loop
      vertex   -42.1498      -14.3822       20.1253    
      vertex   -37.0954      -12.0385       34.2915    
      vertex   -25.4380      -13.7425       24.5733    
    endloop
  endfacet
  facet normal  -0.752309      0.657578      0.402882E-01
    outer loop
      vertex   -48.0953      -16.7006       43.6177    
      vertex   -43.0585      -10.6210       38.4405    
      vertex   -49.0305      -16.7207       26.4826    
    endloop
  endfacet
  facet normal   0.218712      0.971893      0.871161E-01
    outer loop
      vertex   -56.0198      -16.2797       12.4878    
      vertex   -60.5125      -15.8304       18.7546    
      vertex   -53.2139      -18.7828       33.3687    
    endloop
  endfacet
  facet normal  -0.452806      0.890461      0.452351E-01
    outer loop
      vertex   -54.9291      -20.5138       50.2745    
      vertex   -48.0953      -16.7006       43.6177    
      vertex   -53.2139      -18.7828       33.3687    
    endloop
  endfacet
  facet normal  -0.980402      0.000000E+00 -0.197010    
    outer loop
      vertex   0.846000      -12.3671      -4.68210    
      vertex    1.40970      -11.1948      -7.48730    
      vertex    1.40970      -12.0857      -7.48730    
    endloop
  endfacet
  facet normal  -0.358885      0.000000E+00  0.933382    
    outer loop
      vertex   0.917600      -16.4342     -0.511200    
      vertex   0.531000E-01  -16.5071     -0.843600    
      vertex   0.531000E-01  -17.3980     -0.843600    
    endloop
  endfacet
  facet normal   0.975047      0.000000E+00  0.222001    
    outer loop
      vertex    2.19530      -11.1939      -7.36760    
      vertex    1.51790      -12.1003      -4.39240    
      vertex    1.51790      -12.9912      -4.39240    
    endloop
  endfacet
  facet normal   0.719370      0.000000E+00  0.694627    
    outer loop
      vertex    8.29290      -10.9959      -13.6824    
      vertex    2.19530      -11.1939      -7.36760    
      vertex    2.19530      -12.0848      -7.36760    
    endloop
  endfacet
  facet normal   0.988249      0.000000E+00  0.152851    
    outer loop
      vertex    1.51790      -12.1003      -4.39240    
      vertex   0.917600      -16.4342     -0.511200    
      vertex   0.917600      -17.3251     -0.511200    
    endloop
  endfacet
  facet normal  -0.979325      0.000000E+00 -0.202294    
    outer loop
      vertex   0.531000E-01  -16.5071     -0.843600    
      vertex   0.846000      -12.3671      -4.68210    
      vertex   0.846000      -13.2580      -4.68210    
    endloop
  endfacet
  facet normal  -0.943039      0.000000E+00  0.332683    
    outer loop
      vertex    1.40970      -11.1948      -7.48730    
      vertex   -2.20140      -11.5592      -17.7235    
      vertex    1.40970      -12.0857      -7.48730    
    endloop
  endfacet
  facet normal  -0.119582      0.977434      0.174132    
    outer loop
      vertex    14.9355      -9.70140      -68.3434    
      vertex    5.20880      -10.6310      -69.8050    
      vertex   0.835300      -12.3586      -63.1111    
    endloop
  endfacet
  facet normal  -0.106617E-01  0.981364     -0.191863    
    outer loop
      vertex   -2.82720      -12.1329      -37.4630    
      vertex    7.73550      -11.7016      -35.8439    
      vertex    11.3464      -14.7111      -51.4379    
    endloop
  endfacet
  facet normal  -0.236904      0.865409      0.441523    
    outer loop
      vertex    23.9906      -16.0567      -49.5110    
      vertex    24.9295      -10.7390      -59.4302    
      vertex    13.4466      -12.9850      -61.1892    
    endloop
  endfacet
  facet normal  -0.177087E-02  0.999990      0.410141E-02
    outer loop
      vertex    3.29200      -11.1630      -14.4280    
      vertex    1.40970      -11.1948      -7.48730    
      vertex    2.19530      -11.1939      -7.36760    
    endloop
  endfacet
  facet normal   0.548909      0.693749     -0.466273    
    outer loop
      vertex   -2.72750      -13.0590      -31.8631    
      vertex   -2.63700      -9.25430      -26.0957    
      vertex    4.44840      -10.7644      -20.0014    
    endloop
  endfacet
  facet normal  -0.409057      0.868268      0.280681    
    outer loop
      vertex    8.29290      -10.9959      -13.6824    
      vertex    11.3427      -7.85240      -18.9619    
      vertex    4.44840      -10.7644      -20.0014    
    endloop
  endfacet
  facet normal  -0.504311      0.637069      0.582935    
    outer loop
      vertex    1.51790      -12.1003      -4.39240    
      vertex   0.846000      -12.3671      -4.68210    
      vertex   0.531000E-01  -16.5071     -0.843600    
    endloop
  endfacet
  facet normal  -0.178858E-01  0.910104      0.413993    
    outer loop
      vertex   0.835300      -12.3586      -63.1111    
      vertex    13.4466      -12.9850      -61.1892    
      vertex    14.9355      -9.70140      -68.3434    
    endloop
  endfacet
  facet normal   0.539530      0.734443      0.411705    
    outer loop
      vertex   -2.82720      -12.1329      -37.4630    
      vertex    11.3464      -14.7111      -51.4379    
      vertex   -2.92590      -3.99920      -51.8434    
    endloop
  endfacet
  facet normal  -0.187843      0.981817     -0.273919E-01
    outer loop
      vertex    13.4466      -12.9850      -61.1892    
      vertex    24.9295      -10.7390      -59.4302    
      vertex    23.6998      -11.1851      -66.9871    
    endloop
  endfacet
  facet normal   0.150058      0.930144     -0.335133    
    outer loop
      vertex    11.3464      -14.7111      -51.4379    
      vertex    18.1713      -9.62400      -34.2630    
      vertex    23.9906      -16.0567      -49.5110    
    endloop
  endfacet
  facet normal  -0.161105      0.982983     -0.882581E-01
    outer loop
      vertex   -2.72750      -13.0590      -31.8631    
      vertex    5.84780      -11.1941      -26.7458    
      vertex    7.73550      -11.7016      -35.8439    
    endloop
  endfacet
  facet normal  -0.156968      0.983005     -0.951988E-01
    outer loop
      vertex    4.44840      -10.7644      -20.0014    
      vertex    5.84780      -11.1941      -26.7458    
      vertex   -2.72750      -13.0590      -31.8631    
    endloop
  endfacet
  facet normal  -0.101636      0.993566      0.499702E-01
    outer loop
      vertex   -2.20140      -11.5592      -17.7235    
      vertex    3.29200      -11.1630      -14.4280    
      vertex    4.44840      -10.7644      -20.0014    
    endloop
  endfacet
  facet normal  -0.642566E-01  0.997851     -0.128544E-01
    outer loop
      vertex    1.40970      -11.1948      -7.48730    
      vertex    3.29200      -11.1630      -14.4280    
      vertex   -2.20140      -11.5592      -17.7235    
    endloop
  endfacet
  facet normal  -0.440586E-01  0.958416      0.281952    
    outer loop
      vertex    1.51790      -12.1003      -4.39240    
      vertex    2.19530      -11.1939      -7.36760    
      vertex    1.40970      -11.1948      -7.48730    
    endloop
  endfacet
  facet normal  -0.318305      0.656518      0.683861    
    outer loop
      vertex   0.531000E-01  -16.5071     -0.843600    
      vertex   0.917600      -16.4342     -0.511200    
      vertex    1.51790      -12.1003      -4.39240    
    endloop
  endfacet
  facet normal  -0.332770E-01  0.999446     -0.794849E-03
    outer loop
      vertex    2.19530      -11.1939      -7.36760    
      vertex    8.29290      -10.9959      -13.6824    
      vertex    3.29200      -11.1630      -14.4280    
    endloop
  endfacet
  facet normal  -0.426318E-01  0.997136      0.624681E-01
    outer loop
      vertex    3.29200      -11.1630      -14.4280    
      vertex    8.29290      -10.9959      -13.6824    
      vertex    4.44840      -10.7644      -20.0014    
    endloop
  endfacet
  facet normal  -0.248366      0.788747     -0.562311    
    outer loop
      vertex    4.44840      -10.7644      -20.0014    
      vertex    11.3427      -7.85240      -18.9619    
      vertex    13.4826      -10.5131      -23.6392    
    endloop
  endfacet
  facet normal  -0.194692      0.980857     -0.383764E-02
    outer loop
      vertex    13.4826      -10.5131      -23.6392    
      vertex    18.1713      -9.62400      -34.2630    
      vertex    7.73550      -11.7016      -35.8439    
    endloop
  endfacet
  facet normal  -0.157877      0.962125     -0.222239    
    outer loop
      vertex    7.73550      -11.7016      -35.8439    
      vertex    18.1713      -9.62400      -34.2630    
      vertex    11.3464      -14.7111      -51.4379    
    endloop
  endfacet
  facet normal   0.753037E-01  0.978987      0.189511    
    outer loop
      vertex    11.3464      -14.7111      -51.4379    
      vertex    23.9906      -16.0567      -49.5110    
      vertex    13.4466      -12.9850      -61.1892    
    endloop
  endfacet
  facet normal   0.163221      0.986292      0.242171E-01
    outer loop
      vertex    14.9355      -9.70140      -68.3434    
      vertex    23.6998      -11.1851      -66.9871    
      vertex    17.2701      -9.85880      -77.6679    
    endloop
  endfacet
  facet normal   0.216136E-01  0.983653      0.178774    
    outer loop
      vertex   0.835300      -12.3586      -63.1111    
      vertex    11.3464      -14.7111      -51.4379    
      vertex    13.4466      -12.9850      -61.1892    
    endloop
  endfacet
  facet normal  -0.892354E-01  0.995241     -0.391421E-01
    outer loop
      vertex    5.20880      -10.6310      -69.8050    
      vertex    14.9355      -9.70140      -68.3434    
      vertex    17.2701      -9.85880      -77.6679    
    endloop
  endfacet
  facet normal  -0.452380      0.851556      0.264962    
    outer loop
      vertex    1.40970      -11.1948      -7.48730    
      vertex   0.846000      -12.3671      -4.68210    
      vertex    1.51790      -12.1003      -4.39240    
    endloop
  endfacet
  facet normal  -0.580812E-01  0.995455     -0.754740E-01
    outer loop
      vertex    13.4826      -10.5131      -23.6392    
      vertex    5.84780      -11.1941      -26.7458    
      vertex    4.44840      -10.7644      -20.0014    
    endloop
  endfacet
  facet normal  -0.238717E-01  0.963537      0.266508    
    outer loop
      vertex    4.44840      -10.7644      -20.0014    
      vertex   -2.63700      -9.25430      -26.0957    
      vertex   -2.20140      -11.5592      -17.7235    
    endloop
  endfacet
  facet normal  -0.610650E-01  0.995800     -0.682165E-01
    outer loop
      vertex    7.73550      -11.7016      -35.8439    
      vertex    5.84780      -11.1941      -26.7458    
      vertex    13.4826      -10.5131      -23.6392    
    endloop
  endfacet
  facet normal   0.855467E-01  0.898643      0.430259    
    outer loop
      vertex    23.6998      -11.1851      -66.9871    
      vertex    14.9355      -9.70140      -68.3434    
      vertex    13.4466      -12.9850      -61.1892    
    endloop
  endfacet
  facet normal   0.566404      0.741010     -0.360681    
    outer loop
      vertex   0.835300      -12.3586      -63.1111    
      vertex   -2.92590      -3.99920      -51.8434    
      vertex    11.3464      -14.7111      -51.4379    
    endloop
  endfacet
  facet normal  -0.599412     -0.725503      0.338158    
    outer loop
      vertex    11.3464      -15.6020      -51.4379    
      vertex   -2.92590      -3.99920      -51.8434    
      vertex   0.835300      -12.3586      -63.1111    
    endloop
  endfacet
  facet normal   0.298543E-02 -0.909075     -0.416622    
    outer loop
      vertex    13.4466      -13.8759      -61.1892    
      vertex    14.9355      -10.5923      -68.3434    
      vertex    23.6998      -11.1851      -66.9871    
    endloop
  endfacet
  facet normal   0.165903     -0.982099      0.892045E-01
    outer loop
      vertex    13.4826      -10.5131      -23.6392    
      vertex    5.84780      -12.0850      -26.7458    
      vertex    7.73550      -12.5925      -35.8439    
    endloop
  endfacet
  facet normal  -0.102621     -0.960394     -0.259061    
    outer loop
      vertex   -2.20140      -11.5592      -17.7235    
      vertex   -2.63700      -9.25430      -26.0957    
      vertex    4.44840      -11.6553      -20.0014    
    endloop
  endfacet
  facet normal   0.162950     -0.981916      0.963705E-01
    outer loop
      vertex    4.44840      -11.6553      -20.0014    
      vertex    5.84780      -12.0850      -26.7458    
      vertex    13.4826      -10.5131      -23.6392    
    endloop
  endfacet
  facet normal   0.452381     -0.851556     -0.264962    
    outer loop
      vertex    1.51790      -12.9912      -4.39240    
      vertex   0.846000      -13.2580      -4.68210    
      vertex    1.40970      -12.0857      -7.48730    
    endloop
  endfacet
  facet normal   0.151821E-01 -0.997095     -0.746341E-01
    outer loop
      vertex    5.20880      -10.6310      -69.8050    
      vertex    17.2701      -9.85880      -77.6679    
      vertex    14.9355      -10.5923      -68.3434    
    endloop
  endfacet
  facet normal  -0.883289E-01 -0.977405     -0.192037    
    outer loop
      vertex    13.4466      -13.8759      -61.1892    
      vertex    11.3464      -15.6020      -51.4379    
      vertex   0.835300      -12.3586      -63.1111    
    endloop
  endfacet
  facet normal  -0.530959E-01 -0.994387     -0.915160E-01
    outer loop
      vertex    17.2701      -9.85880      -77.6679    
      vertex    23.6998      -11.1851      -66.9871    
      vertex    14.9355      -10.5923      -68.3434    
    endloop
  endfacet
  facet normal  -0.856372E-02 -0.984338     -0.176084    
    outer loop
      vertex    13.4466      -13.8759      -61.1892    
      vertex    23.9906      -16.0567      -49.5110    
      vertex    11.3464      -15.6020      -51.4379    
    endloop
  endfacet
  facet normal   0.232639     -0.943506      0.235957    
    outer loop
      vertex    11.3464      -15.6020      -51.4379    
      vertex    18.1713      -9.62400      -34.2630    
      vertex    7.73550      -12.5925      -35.8439    
    endloop
  endfacet
  facet normal   0.268108     -0.962648      0.377631E-01
    outer loop
      vertex    7.73550      -12.5925      -35.8439    
      vertex    18.1713      -9.62400      -34.2630    
      vertex    13.4826      -10.5131      -23.6392    
    endloop
  endfacet
  facet normal   0.326618     -0.749519      0.575797    
    outer loop
      vertex    13.4826      -10.5131      -23.6392    
      vertex    11.3427      -7.85240      -18.9619    
      vertex    4.44840      -11.6553      -20.0014    
    endloop
  endfacet
  facet normal   0.210644     -0.977212     -0.261828E-01
    outer loop
      vertex    4.44840      -11.6553      -20.0014    
      vertex    8.29290      -10.9959      -13.6824    
      vertex    3.29200      -12.0539      -14.4280    
    endloop
  endfacet
  facet normal   0.203013     -0.978797      0.272505E-01
    outer loop
      vertex    3.29200      -12.0539      -14.4280    
      vertex    8.29290      -10.9959      -13.6824    
      vertex    2.19530      -12.0848      -7.36760    
    endloop
  endfacet
  facet normal   0.318307     -0.656517     -0.683861    
    outer loop
      vertex    1.51790      -12.9912      -4.39240    
      vertex   0.917600      -17.3251     -0.511200    
      vertex   0.531000E-01  -17.3980     -0.843600    
    endloop
  endfacet
  facet normal   0.440587E-01 -0.958416     -0.281952    
    outer loop
      vertex    1.40970      -12.0857      -7.48730    
      vertex    2.19530      -12.0848      -7.36760    
      vertex    1.51790      -12.9912      -4.39240    
    endloop
  endfacet
  facet normal  -0.748546E-01 -0.996884     -0.248678E-01
    outer loop
      vertex   -2.20140      -11.5592      -17.7235    
      vertex    3.29200      -12.0539      -14.4280    
      vertex    1.40970      -12.0857      -7.48730    
    endloop
  endfacet
  facet normal  -0.417597E-01 -0.995928     -0.798916E-01
    outer loop
      vertex    4.44840      -11.6553      -20.0014    
      vertex    3.29200      -12.0539      -14.4280    
      vertex   -2.20140      -11.5592      -17.7235    
    endloop
  endfacet
  facet normal   0.668847E-01 -0.994765      0.772565E-01
    outer loop
      vertex   -2.72750      -13.0590      -31.8631    
      vertex    5.84780      -12.0850      -26.7458    
      vertex    4.44840      -11.6553      -20.0014    
    endloop
  endfacet
  facet normal  -0.179653E-01 -0.986492     -0.162824    
    outer loop
      vertex   -2.72750      -13.0590      -31.8631    
      vertex   -2.82720      -12.1329      -37.4630    
      vertex    7.73550      -12.5925      -35.8439    
    endloop
  endfacet
  facet normal  -0.880508E-01 -0.929378      0.358474    
    outer loop
      vertex    23.9906      -16.0567      -49.5110    
      vertex    18.1713      -9.62400      -34.2630    
      vertex    11.3464      -15.6020      -51.4379    
    endloop
  endfacet
  facet normal   0.261439     -0.965112      0.144298E-01
    outer loop
      vertex    23.6998      -11.1851      -66.9871    
      vertex    24.9295      -10.7390      -59.4302    
      vertex    13.4466      -13.8759      -61.1892    
    endloop
  endfacet
  facet normal  -0.570917     -0.716292     -0.401223    
    outer loop
      vertex   -2.82720      -12.1329      -37.4630    
      vertex   -2.92590      -3.99920      -51.8434    
      vertex    11.3464      -15.6020      -51.4379    
    endloop
  endfacet
  facet normal  -0.441539E-01 -0.904442     -0.424306    
    outer loop
      vertex    14.9355      -10.5923      -68.3434    
      vertex    13.4466      -13.8759      -61.1892    
      vertex   0.835300      -12.3586      -63.1111    
    endloop
  endfacet
  facet normal   0.504311     -0.637069     -0.582935    
    outer loop
      vertex   0.531000E-01  -17.3980     -0.843600    
      vertex   0.846000      -13.2580      -4.68210    
      vertex    1.51790      -12.9912      -4.39240    
    endloop
  endfacet
  facet normal   0.496348     -0.841285     -0.214190    
    outer loop
      vertex    4.44840      -11.6553      -20.0014    
      vertex    11.3427      -7.85240      -18.9619    
      vertex    8.29290      -10.9959      -13.6824    
    endloop
  endfacet
  facet normal  -0.605971     -0.659612      0.444648    
    outer loop
      vertex    4.44840      -11.6553      -20.0014    
      vertex   -2.63700      -9.25430      -26.0957    
      vertex   -2.72750      -13.0590      -31.8631    
    endloop
  endfacet
  facet normal   0.177087E-02 -0.999990     -0.410141E-02
    outer loop
      vertex    2.19530      -12.0848      -7.36760    
      vertex    1.40970      -12.0857      -7.48730    
      vertex    3.29200      -12.0539      -14.4280    
    endloop
  endfacet
  facet normal   0.298605     -0.852612     -0.428822    
    outer loop
      vertex    13.4466      -13.8759      -61.1892    
      vertex    24.9295      -10.7390      -59.4302    
      vertex    23.9906      -16.0567      -49.5110    
    endloop
  endfacet
  facet normal  -0.693452E-01 -0.982383      0.173534    
    outer loop
      vertex    11.3464      -15.6020      -51.4379    
      vertex    7.73550      -12.5925      -35.8439    
      vertex   -2.82720      -12.1329      -37.4630    
    endloop
  endfacet
  facet normal   0.378975E-01 -0.973289     -0.226432    
    outer loop
      vertex   0.835300      -12.3586      -63.1111    
      vertex    5.20880      -10.6310      -69.8050    
      vertex    14.9355      -10.5923      -68.3434    
    endloop
  endfacet
  facet normal   0.966259      0.000000E+00 -0.257573    
    outer loop
      vertex    1.62030      -13.3751       3.64780    
      vertex    2.63760      -11.3773       7.46410    
      vertex    2.63760      -12.5328       7.46410    
    endloop
  endfacet
  facet normal  -0.102243      0.000000E+00 -0.994760    
    outer loop
      vertex  -0.967000E-01  -20.1064       1.11860    
      vertex   0.974500      -19.4506       1.00850    
      vertex   0.974500      -20.6061       1.00850    
    endloop
  endfacet
  facet normal  -0.971784      0.000000E+00  0.235871    
    outer loop
      vertex    1.75530      -11.3782       7.58940    
      vertex   0.886900      -13.6277       4.01160    
      vertex   0.886900      -14.7832       4.01160    
    endloop
  endfacet
  facet normal  -0.940631      0.000000E+00 -0.339430    
    outer loop
      vertex   -2.07350      -12.0377       18.1998    
      vertex    1.75530      -11.3782       7.58940    
      vertex    1.75530      -12.5337       7.58940    
    endloop
  endfacet
  facet normal  -0.946775      0.000000E+00  0.321897    
    outer loop
      vertex   0.886900      -13.6277       4.01160    
      vertex  -0.967000E-01  -20.1064       1.11860    
      vertex  -0.967000E-01  -21.2619       1.11860    
    endloop
  endfacet
  facet normal   0.971345      0.000000E+00 -0.237675    
    outer loop
      vertex   0.974500      -19.4506       1.00850    
      vertex    1.62030      -13.3751       3.64780    
      vertex    1.62030      -14.5306       3.64780    
    endloop
  endfacet
  facet normal   0.712789      0.000000E+00 -0.701378    
    outer loop
      vertex    2.63760      -11.3773       7.46410    
      vertex    11.3407      -11.9662       16.3088    
      vertex    2.63760      -12.5328       7.46410    
    endloop
  endfacet
  facet normal   0.311250      0.878366      0.362762    
    outer loop
      vertex    16.2227      -21.1206       62.8673    
      vertex    14.7262      -17.3029       54.9074    
      vertex   0.721900      -14.6831       60.5797    
    endloop
  endfacet
  facet normal  -0.728830E-01  0.684580      0.725285    
    outer loop
      vertex    27.1672      -27.4192       69.9122    
      vertex    28.8080      -16.6319       59.8952    
      vertex    16.2227      -21.1206       62.8673    
    endloop
  endfacet
  facet normal   0.887119E-01  0.969158      0.229918    
    outer loop
      vertex   -2.06650      -13.1177       44.3783    
      vertex    11.0766      -13.8757       42.5023    
      vertex    9.21940      -11.4918       33.1702    
    endloop
  endfacet
  facet normal  -0.211655      0.690133      0.692040    
    outer loop
      vertex    28.8949      -16.8839       52.8949    
      vertex    24.9299      -9.42030       44.2392    
      vertex    12.4774      -15.0130       46.0080    
    endloop
  endfacet
  facet normal   0.141250      0.982994     -0.117354    
    outer loop
      vertex   -2.06650      -13.1177       44.3783    
      vertex   -1.85100      -12.4900       49.8955    
      vertex    12.4774      -15.0130       46.0080    
    endloop
  endfacet
  facet normal  -0.159030      0.976469     -0.145667    
    outer loop
      vertex    9.21940      -11.4918       33.1702    
      vertex    19.5318      -10.0284       31.7216    
      vertex    15.8136      -11.7384       24.3180    
    endloop
  endfacet
  facet normal   0.238679      0.841886      0.484004    
    outer loop
      vertex    6.80250      -11.4951       25.5886    
      vertex   -2.32910      -9.65190       26.8856    
      vertex   -2.17760      -14.2424       34.7957    
    endloop
  endfacet
  facet normal  -0.446169      0.836231     -0.318826    
    outer loop
      vertex    2.63760      -11.3773       7.46410    
      vertex    1.62030      -13.3751       3.64780    
      vertex   0.886900      -13.6277       4.01160    
    endloop
  endfacet
  facet normal  -0.297878      0.722366      0.624064    
    outer loop
      vertex    27.1672      -27.4192       69.9122    
      vertex    18.6271      -31.3143       70.3445    
      vertex    19.8996      -36.9004       77.4179    
    endloop
  endfacet
  facet normal  -0.208018      0.546144      0.811452    
    outer loop
      vertex    16.2227      -21.1206       62.8673    
      vertex    18.6271      -31.3143       70.3445    
      vertex    27.1672      -27.4192       69.9122    
    endloop
  endfacet
  facet normal   0.339296E-01  0.903611      0.427008    
    outer loop
      vertex    28.8949      -16.8839       52.8949    
      vertex    14.7262      -17.3029       54.9074    
      vertex    16.2227      -21.1206       62.8673    
    endloop
  endfacet
  facet normal   0.652395E-02  0.968830      0.247641    
    outer loop
      vertex    12.4774      -15.0130       46.0080    
      vertex    14.7262      -17.3029       54.9074    
      vertex    28.8949      -16.8839       52.8949    
    endloop
  endfacet
  facet normal  -0.128236      0.927164      0.352026    
    outer loop
      vertex    22.3380      -10.2769       37.1261    
      vertex    11.0766      -13.8757       42.5023    
      vertex    12.4774      -15.0130       46.0080    
    endloop
  endfacet
  facet normal  -0.124486      0.986107      0.109979    
    outer loop
      vertex    19.5318      -10.0284       31.7216    
      vertex    9.21940      -11.4918       33.1702    
      vertex    22.3380      -10.2769       37.1261    
    endloop
  endfacet
  facet normal   0.257704E-01  0.999630     -0.865028E-02
    outer loop
      vertex    15.8136      -11.7384       24.3180    
      vertex    6.80250      -11.4951       25.5886    
      vertex    9.21940      -11.4918       33.1702    
    endloop
  endfacet
  facet normal   0.591865E-01  0.998011     -0.217206E-01
    outer loop
      vertex    11.3407      -11.9662       16.3088    
      vertex    4.69260      -11.5517       17.2387    
      vertex    6.80250      -11.4951       25.5886    
    endloop
  endfacet
  facet normal   0.628667E-01  0.998011      0.458961E-02
    outer loop
      vertex    2.63760      -11.3773       7.46410    
      vertex    4.69260      -11.5517       17.2387    
      vertex    11.3407      -11.9662       16.3088    
    endloop
  endfacet
  facet normal  -0.744031E-01  0.852265     -0.517793    
    outer loop
      vertex   0.886900      -13.6277       4.01160    
      vertex    1.75530      -11.3782       7.58940    
      vertex    2.63760      -11.3773       7.46410    
    endloop
  endfacet
  facet normal  -0.346602      0.425832     -0.835783    
    outer loop
      vertex   0.974500      -19.4506       1.00850    
      vertex  -0.967000E-01  -20.1064       1.11860    
      vertex   0.886900      -13.6277       4.01160    
    endloop
  endfacet
  facet normal   0.147043E-02  0.999845      0.175302E-01
    outer loop
      vertex    2.63760      -11.3773       7.46410    
      vertex    1.75530      -11.3782       7.58940    
      vertex    4.69260      -11.5517       17.2387    
    endloop
  endfacet
  facet normal   0.155939      0.953651     -0.257358    
    outer loop
      vertex   -2.07350      -12.0377       18.1998    
      vertex   -2.32910      -9.65190       26.8856    
      vertex    6.80250      -11.4951       25.5886    
    endloop
  endfacet
  facet normal  -0.224418      0.971895      0.711181E-01
    outer loop
      vertex    6.80250      -11.4951       25.5886    
      vertex   -2.17760      -14.2424       34.7957    
      vertex    9.21940      -11.4918       33.1702    
    endloop
  endfacet
  facet normal  -0.247992      0.962486     -0.110091    
    outer loop
      vertex    9.21940      -11.4918       33.1702    
      vertex   -2.17760      -14.2424       34.7957    
      vertex   -2.06650      -13.1177       44.3783    
    endloop
  endfacet
  facet normal   0.941781E-01  0.957403      0.272964    
    outer loop
      vertex    11.0766      -13.8757       42.5023    
      vertex   -2.06650      -13.1177       44.3783    
      vertex    12.4774      -15.0130       46.0080    
    endloop
  endfacet
  facet normal   0.210255      0.966419      0.147740    
    outer loop
      vertex    12.4774      -15.0130       46.0080    
      vertex   -1.85100      -12.4900       49.8955    
      vertex   0.721900      -14.6831       60.5797    
    endloop
  endfacet
  facet normal   0.398918      0.902128     -0.164405    
    outer loop
      vertex   0.721900      -14.6831       60.5797    
      vertex    3.63460      -14.8649       66.6496    
      vertex    16.2227      -21.1206       62.8673    
    endloop
  endfacet
  facet normal   0.484538      0.578040      0.656576    
    outer loop
      vertex    16.2227      -21.1206       62.8673    
      vertex    3.63460      -14.8649       66.6496    
      vertex    9.44120      -26.5036       72.6110    
    endloop
  endfacet
  facet normal   0.496942      0.722276      0.481006    
    outer loop
      vertex    18.6271      -31.3143       70.3445    
      vertex    9.44120      -26.5036       72.6110    
      vertex    19.8996      -36.9004       77.4179    
    endloop
  endfacet
  facet normal  -0.513290      0.387268     -0.765870    
    outer loop
      vertex   0.886900      -13.6277       4.01160    
      vertex    1.62030      -13.3751       3.64780    
      vertex   0.974500      -19.4506       1.00850    
    endloop
  endfacet
  facet normal  -0.700923E-01  0.997480      0.109499E-01
    outer loop
      vertex    6.80250      -11.4951       25.5886    
      vertex    4.69260      -11.5517       17.2387    
      vertex   -2.07350      -12.0377       18.1998    
    endloop
  endfacet
  facet normal  -0.170722      0.945983      0.275628    
    outer loop
      vertex    9.21940      -11.4918       33.1702    
      vertex    11.0766      -13.8757       42.5023    
      vertex    22.3380      -10.2769       37.1261    
    endloop
  endfacet
  facet normal   0.212893E-01  0.998961     -0.403021E-01
    outer loop
      vertex    6.80250      -11.4951       25.5886    
      vertex    15.8136      -11.7384       24.3180    
      vertex    11.3407      -11.9662       16.3088    
    endloop
  endfacet
  facet normal   0.251250      0.950817      0.181166    
    outer loop
      vertex   0.721900      -14.6831       60.5797    
      vertex    14.7262      -17.3029       54.9074    
      vertex    12.4774      -15.0130       46.0080    
    endloop
  endfacet
  facet normal  -0.404967      0.913560      0.375474E-01
    outer loop
      vertex    12.4774      -15.0130       46.0080    
      vertex    24.9299      -9.42030       44.2392    
      vertex    22.3380      -10.2769       37.1261    
    endloop
  endfacet
  facet normal  -0.343650      0.938327     -0.380441E-01
    outer loop
      vertex    16.2227      -21.1206       62.8673    
      vertex    28.8080      -16.6319       59.8952    
      vertex    28.8949      -16.8839       52.8949    
    endloop
  endfacet
  facet normal   0.471145      0.591253      0.654555    
    outer loop
      vertex    9.44120      -26.5036       72.6110    
      vertex    18.6271      -31.3143       70.3445    
      vertex    16.2227      -21.1206       62.8673    
    endloop
  endfacet
  facet normal  -0.662094E-01  0.997079      0.380825E-01
    outer loop
      vertex    1.75530      -11.3782       7.58940    
      vertex   -2.07350      -12.0377       18.1998    
      vertex    4.69260      -11.5517       17.2387    
    endloop
  endfacet
  facet normal  -0.489695     -0.587836     -0.643931    
    outer loop
      vertex    16.2227      -21.4794       62.8673    
      vertex    18.6271      -31.6731       70.3445    
      vertex    9.44120      -26.5036       72.6110    
    endloop
  endfacet
  facet normal   0.366976     -0.929453      0.380142E-01
    outer loop
      vertex    28.8949      -16.8839       52.8949    
      vertex    28.8080      -16.6319       59.8952    
      vertex    16.2227      -21.4794       62.8673    
    endloop
  endfacet
  facet normal   0.425411     -0.903822     -0.461695E-01
    outer loop
      vertex    22.3380      -10.2769       37.1261    
      vertex    24.9299      -9.42030       44.2392    
      vertex    12.4774      -15.3718       46.0080    
    endloop
  endfacet
  facet normal  -0.272046     -0.946285     -0.174745    
    outer loop
      vertex    12.4774      -15.3718       46.0080    
      vertex    14.7262      -17.6617       54.9074    
      vertex   0.721900      -14.6831       60.5797    
    endloop
  endfacet
  facet normal   0.155946E-01 -0.999684      0.197241E-01
    outer loop
      vertex    11.3407      -11.9662       16.3088    
      vertex    15.8136      -11.7384       24.3180    
      vertex    6.80250      -11.8539       25.5886    
    endloop
  endfacet
  facet normal   0.196951     -0.939798     -0.279268    
    outer loop
      vertex    22.3380      -10.2769       37.1261    
      vertex    11.0766      -14.2345       42.5023    
      vertex    9.21940      -11.8506       33.1702    
    endloop
  endfacet
  facet normal   0.190742E-01 -0.999816      0.195745E-02
    outer loop
      vertex   -2.07350      -12.0377       18.1998    
      vertex    4.69260      -11.9105       17.2387    
      vertex    6.80250      -11.8539       25.5886    
    endloop
  endfacet
  facet normal   0.513291     -0.387267      0.765870    
    outer loop
      vertex   0.974500      -20.6061       1.00850    
      vertex    1.62030      -14.5306       3.64780    
      vertex   0.886900      -14.7832       4.01160    
    endloop
  endfacet
  facet normal  -0.520065     -0.728957     -0.445145    
    outer loop
      vertex    19.8996      -36.9004       77.4179    
      vertex    9.44120      -26.5036       72.6110    
      vertex    18.6271      -31.6731       70.3445    
    endloop
  endfacet
  facet normal  -0.498190     -0.579093     -0.645335    
    outer loop
      vertex    9.44120      -26.5036       72.6110    
      vertex    3.63460      -14.8649       66.6496    
      vertex    16.2227      -21.4794       62.8673    
    endloop
  endfacet
  facet normal  -0.416811     -0.892323      0.173285    
    outer loop
      vertex    16.2227      -21.4794       62.8673    
      vertex    3.63460      -14.8649       66.6496    
      vertex   0.721900      -14.6831       60.5797    
    endloop
  endfacet
  facet normal  -0.231989     -0.962346     -0.141671    
    outer loop
      vertex   0.721900      -14.6831       60.5797    
      vertex   -1.85100      -12.4900       49.8955    
      vertex    12.4774      -15.3718       46.0080    
    endloop
  endfacet
  facet normal  -0.118906     -0.957416     -0.263088    
    outer loop
      vertex    12.4774      -15.3718       46.0080    
      vertex   -2.06650      -13.1177       44.3783    
      vertex    11.0766      -14.2345       42.5023    
    endloop
  endfacet
  facet normal   0.219283     -0.969301      0.111224    
    outer loop
      vertex   -2.06650      -13.1177       44.3783    
      vertex   -2.17760      -14.2424       34.7957    
      vertex    9.21940      -11.8506       33.1702    
    endloop
  endfacet
  facet normal   0.196484     -0.978531     -0.622103E-01
    outer loop
      vertex    9.21940      -11.8506       33.1702    
      vertex   -2.17760      -14.2424       34.7957    
      vertex    6.80250      -11.8539       25.5886    
    endloop
  endfacet
  facet normal  -0.192361     -0.947707      0.254654    
    outer loop
      vertex    6.80250      -11.8539       25.5886    
      vertex   -2.32910      -9.65190       26.8856    
      vertex   -2.07350      -12.0377       18.1998    
    endloop
  endfacet
  facet normal   0.975110E-02 -0.998060      0.614915E-01
    outer loop
      vertex    4.69260      -11.9105       17.2387    
      vertex    1.75530      -12.5337       7.58940    
      vertex    2.63760      -12.5328       7.46410    
    endloop
  endfacet
  facet normal   0.346602     -0.425832      0.835783    
    outer loop
      vertex   0.886900      -14.7832       4.01160    
      vertex  -0.967000E-01  -21.2619       1.11860    
      vertex   0.974500      -20.6061       1.00850    
    endloop
  endfacet
  facet normal   0.744040E-01 -0.852265      0.517792    
    outer loop
      vertex    2.63760      -12.5328       7.46410    
      vertex    1.75530      -12.5337       7.58940    
      vertex   0.886900      -14.7832       4.01160    
    endloop
  endfacet
  facet normal   0.510669E-03 -0.997986      0.634294E-01
    outer loop
      vertex    11.3407      -11.9662       16.3088    
      vertex    4.69260      -11.9105       17.2387    
      vertex    2.63760      -12.5328       7.46410    
    endloop
  endfacet
  facet normal  -0.717614E-02 -0.999937      0.859136E-02
    outer loop
      vertex    6.80250      -11.8539       25.5886    
      vertex    4.69260      -11.9105       17.2387    
      vertex    11.3407      -11.9662       16.3088    
    endloop
  endfacet
  facet normal   0.123238E-01 -0.999918     -0.349346E-02
    outer loop
      vertex    9.21940      -11.8506       33.1702    
      vertex    6.80250      -11.8539       25.5886    
      vertex    15.8136      -11.7384       24.3180    
    endloop
  endfacet
  facet normal   0.155463     -0.979802     -0.125773    
    outer loop
      vertex    19.5318      -10.0284       31.7216    
      vertex    22.3380      -10.2769       37.1261    
      vertex    9.21940      -11.8506       33.1702    
    endloop
  endfacet
  facet normal   0.151980     -0.920716     -0.359422    
    outer loop
      vertex    12.4774      -15.3718       46.0080    
      vertex    11.0766      -14.2345       42.5023    
      vertex    22.3380      -10.2769       37.1261    
    endloop
  endfacet
  facet normal   0.171322E-01 -0.967259     -0.253214    
    outer loop
      vertex    28.8949      -16.8839       52.8949    
      vertex    14.7262      -17.6617       54.9074    
      vertex    12.4774      -15.3718       46.0080    
    endloop
  endfacet
  facet normal  -0.116273E-01 -0.902447     -0.430643    
    outer loop
      vertex    16.2227      -21.4794       62.8673    
      vertex    14.7262      -17.6617       54.9074    
      vertex    28.8949      -16.8839       52.8949    
    endloop
  endfacet
  facet normal   0.228130     -0.540303     -0.809956    
    outer loop
      vertex    27.1672      -27.4192       69.9122    
      vertex    18.6271      -31.6731       70.3445    
      vertex    16.2227      -21.4794       62.8673    
    endloop
  endfacet
  facet normal   0.332729     -0.728802     -0.598448    
    outer loop
      vertex    27.1672      -27.4192       69.9122    
      vertex    19.8996      -36.9004       77.4179    
      vertex    18.6271      -31.6731       70.3445    
    endloop
  endfacet
  facet normal   0.446170     -0.836231      0.318825    
    outer loop
      vertex   0.886900      -14.7832       4.01160    
      vertex    1.62030      -14.5306       3.64780    
      vertex    2.63760      -12.5328       7.46410    
    endloop
  endfacet
  facet normal  -0.269491     -0.835139     -0.479498    
    outer loop
      vertex   -2.17760      -14.2424       34.7957    
      vertex   -2.32910      -9.65190       26.8856    
      vertex    6.80250      -11.8539       25.5886    
    endloop
  endfacet
  facet normal   0.190128     -0.973208      0.129295    
    outer loop
      vertex    15.8136      -11.7384       24.3180    
      vertex    19.5318      -10.0284       31.7216    
      vertex    9.21940      -11.8506       33.1702    
    endloop
  endfacet
  facet normal  -0.164973     -0.979232      0.117852    
    outer loop
      vertex    12.4774      -15.3718       46.0080    
      vertex   -1.85100      -12.4900       49.8955    
      vertex   -2.06650      -13.1177       44.3783    
    endloop
  endfacet
  facet normal   0.228038     -0.683279     -0.693634    
    outer loop
      vertex    12.4774      -15.3718       46.0080    
      vertex    24.9299      -9.42030       44.2392    
      vertex    28.8949      -16.8839       52.8949    
    endloop
  endfacet
  facet normal  -0.114273     -0.967757     -0.224473    
    outer loop
      vertex    9.21940      -11.8506       33.1702    
      vertex    11.0766      -14.2345       42.5023    
      vertex   -2.06650      -13.1177       44.3783    
    endloop
  endfacet
  facet normal   0.932526E-01 -0.685074     -0.722480    
    outer loop
      vertex    16.2227      -21.4794       62.8673    
      vertex    28.8080      -16.6319       59.8952    
      vertex    27.1672      -27.4192       69.9122    
    endloop
  endfacet
  facet normal  -0.330413     -0.873740     -0.356941    
    outer loop
      vertex   0.721900      -14.6831       60.5797    
      vertex    14.7262      -17.6617       54.9074    
      vertex    16.2227      -21.4794       62.8673    
    endloop
  endfacet
  facet normal   0.267621E-01 -0.998054      0.563129E-01
    outer loop
      vertex    4.69260      -11.9105       17.2387    
      vertex   -2.07350      -12.0377       18.1998    
      vertex    1.75530      -12.5337       7.58940    
    endloop
  endfacet
  facet normal  -0.151542      0.000000E+00  0.988451    
    outer loop
      vertex   -3.33570      -13.1691     -0.694900    
      vertex   -7.56430      -10.9953      -1.34320    
      vertex   -7.56430      -11.7845      -1.34320    
    endloop
  endfacet
  facet normal   0.791371      0.000000E+00  0.611337    
    outer loop
      vertex  -0.549900      -16.3901      -1.08500    
      vertex   -1.08370      -16.5071     -0.394000    
      vertex   -1.08370      -17.2963     -0.394000    
    endloop
  endfacet
  facet normal   0.168113      0.000000E+00 -0.985768    
    outer loop
      vertex   -7.42050      -10.9945      -2.07850    
      vertex   -3.31530      -13.2650      -1.37840    
      vertex   -3.31530      -14.0542      -1.37840    
    endloop
  endfacet
  facet normal   0.567054      0.000000E+00 -0.823680    
    outer loop
      vertex   -21.7118      -11.3943      -11.9172    
      vertex   -7.42050      -10.9945      -2.07850    
      vertex   -7.42050      -11.7837      -2.07850    
    endloop
  endfacet
  facet normal   0.105505      0.000000E+00 -0.994419    
    outer loop
      vertex   -3.31530      -13.2650      -1.37840    
      vertex  -0.549900      -16.3901      -1.08500    
      vertex  -0.549900      -17.1793      -1.08500    
    endloop
  endfacet
  facet normal  -0.132438      0.000000E+00  0.991191    
    outer loop
      vertex   -1.08370      -16.5071     -0.394000    
      vertex   -3.33570      -13.1691     -0.694900    
      vertex   -3.33570      -13.9583     -0.694900    
    endloop
  endfacet
  facet normal   0.464803      0.000000E+00  0.885414    
    outer loop
      vertex   -7.56430      -10.9953      -1.34320    
      vertex   -10.8863      -11.3998      0.400700    
      vertex   -7.56430      -11.7845      -1.34320    
    endloop
  endfacet
  facet normal  -0.403567      0.871112     -0.279818    
    outer loop
      vertex   -73.4149      -22.0069      -6.51390    
      vertex   -66.7273      -17.6107      -2.47310    
      vertex   -64.6571      -20.0526      -13.0608    
    endloop
  endfacet
  facet normal  -0.208606      0.965339     -0.156858    
    outer loop
      vertex   -43.5367      -12.1515       2.62020    
      vertex   -44.7721      -14.3822      -9.46510    
      vertex   -48.2280      -15.2388      -10.1408    
    endloop
  endfacet
  facet normal  -0.274570      0.956974      0.938712E-01
    outer loop
      vertex   -62.6445      -18.4728      -23.2794    
      vertex   -64.6571      -20.0526      -13.0608    
      vertex   -58.3885      -18.3456      -12.1275    
    endloop
  endfacet
  facet normal  -0.162938      0.984720     -0.614635E-01
    outer loop
      vertex   -42.5971      -14.9592      -20.5886    
      vertex   -49.3755      -16.2044      -22.5689    
      vertex   -48.2280      -15.2388      -10.1408    
    endloop
  endfacet
  facet normal  -0.118856E-01  0.999461     -0.305957E-01
    outer loop
      vertex   -32.4155      -11.3594      -6.61900    
      vertex   -21.4296      -11.1630      -4.47100    
      vertex   -21.7118      -11.3943      -11.9172    
    endloop
  endfacet
  facet normal   0.150846      0.969269     -0.194327    
    outer loop
      vertex   -44.7721      -14.3822      -9.46510    
      vertex   -43.5367      -12.1515       2.62020    
      vertex   -34.1959      -13.6419       2.43710    
    endloop
  endfacet
  facet normal  -0.118181E-01  0.999929     -0.122315E-02
    outer loop
      vertex   -21.4296      -11.1630      -4.47100    
      vertex   -7.56430      -10.9953      -1.34320    
      vertex   -7.42050      -10.9945      -2.07850    
    endloop
  endfacet
  facet normal   0.830024      0.555192     -0.531246E-01
    outer loop
      vertex   -3.31530      -13.2650      -1.37840    
      vertex   -3.33570      -13.1691     -0.694900    
      vertex   -1.08370      -16.5071     -0.394000    
    endloop
  endfacet
  facet normal  -0.431650      0.890087      0.146364    
    outer loop
      vertex   -72.1679      -24.8176      -12.8920    
      vertex   -70.7725      -22.9888      -19.8983    
      vertex   -78.0177      -27.5765      -13.3662    
    endloop
  endfacet
  facet normal  -0.433456      0.889302      0.145799    
    outer loop
      vertex   -62.6445      -18.4728      -23.2794    
      vertex   -70.7725      -22.9888      -19.8983    
      vertex   -72.1679      -24.8176      -12.8920    
    endloop
  endfacet
  facet normal  -0.646152      0.725044      0.238327    
    outer loop
      vertex   -58.3885      -18.3456      -12.1275    
      vertex   -56.1802      -12.6652      -23.4214    
      vertex   -62.6445      -18.4728      -23.2794    
    endloop
  endfacet
  facet normal  -0.283429      0.957779     -0.482452E-01
    outer loop
      vertex   -48.2280      -15.2388      -10.1408    
      vertex   -49.3755      -16.2044      -22.5689    
      vertex   -58.3885      -18.3456      -12.1275    
    endloop
  endfacet
  facet normal  -0.222210      0.970477     -0.937899E-01
    outer loop
      vertex   -44.7721      -14.3822      -9.46510    
      vertex   -42.5971      -14.9592      -20.5886    
      vertex   -48.2280      -15.2388      -10.1408    
    endloop
  endfacet
  facet normal  -0.494853      0.860701      0.119645    
    outer loop
      vertex   -26.4847      -9.20350       2.40180    
      vertex   -32.4155      -11.3594      -6.61900    
      vertex   -34.1959      -13.6419       2.43710    
    endloop
  endfacet
  facet normal   0.228618      0.902133     -0.365909    
    outer loop
      vertex   -18.0121      -11.5084       2.01280    
      vertex   -32.4155      -11.3594      -6.61900    
      vertex   -26.4847      -9.20350       2.40180    
    endloop
  endfacet
  facet normal  -0.445398E-01  0.988510      0.144441    
    outer loop
      vertex   -7.56430      -10.9953      -1.34320    
      vertex   -21.4296      -11.1630      -4.47100    
      vertex   -10.8863      -11.3998      0.400700    
    endloop
  endfacet
  facet normal   0.469729      0.877918      0.928184E-01
    outer loop
      vertex   -3.31530      -13.2650      -1.37840    
      vertex   -7.42050      -10.9945      -2.07850    
      vertex   -7.56430      -10.9953      -1.34320    
    endloop
  endfacet
  facet normal   0.594972      0.578844      0.557627    
    outer loop
      vertex   -1.08370      -16.5071     -0.394000    
      vertex  -0.549900      -16.3901      -1.08500    
      vertex   -3.31530      -13.2650      -1.37840    
    endloop
  endfacet
  facet normal  -0.676335E-02  0.999503     -0.307911E-01
    outer loop
      vertex   -7.42050      -10.9945      -2.07850    
      vertex   -21.7118      -11.3943      -11.9172    
      vertex   -21.4296      -11.1630      -4.47100    
    endloop
  endfacet
  facet normal   0.798713E-01  0.984700      0.154874    
    outer loop
      vertex   -21.7118      -11.3943      -11.9172    
      vertex   -34.1359      -9.57310      -17.0892    
      vertex   -32.4155      -11.3594      -6.61900    
    endloop
  endfacet
  facet normal  -0.588359      0.775501      0.228982    
    outer loop
      vertex   -32.4155      -11.3594      -6.61900    
      vertex   -34.1359      -9.57310      -17.0892    
      vertex   -42.5971      -14.9592      -20.5886    
    endloop
  endfacet
  facet normal  -0.273384      0.944102      0.184205    
    outer loop
      vertex   -34.1959      -13.6419       2.43710    
      vertex   -32.4155      -11.3594      -6.61900    
      vertex   -44.7721      -14.3822      -9.46510    
    endloop
  endfacet
  facet normal   0.333382      0.881000     -0.335703    
    outer loop
      vertex   -43.5367      -12.1515       2.62020    
      vertex   -48.2280      -15.2388      -10.1408    
      vertex   -50.6710      -9.55330       2.35380    
    endloop
  endfacet
  facet normal  -0.244911      0.943554     -0.222990    
    outer loop
      vertex   -48.2280      -15.2388      -10.1408    
      vertex   -58.3885      -18.3456      -12.1275    
      vertex   -62.2715      -16.6000     -0.476500    
    endloop
  endfacet
  facet normal  -0.226150      0.949472     -0.217624    
    outer loop
      vertex   -62.2715      -16.6000     -0.476500    
      vertex   -58.3885      -18.3456      -12.1275    
      vertex   -64.6571      -20.0526      -13.0608    
    endloop
  endfacet
  facet normal  -0.490538      0.757978     -0.429932    
    outer loop
      vertex   -64.6571      -20.0526      -13.0608    
      vertex   -72.1679      -24.8176      -12.8920    
      vertex   -73.4149      -22.0069      -6.51390    
    endloop
  endfacet
  facet normal  -0.355210      0.827803     -0.434244    
    outer loop
      vertex   -73.4149      -22.0069      -6.51390    
      vertex   -72.1679      -24.8176      -12.8920    
      vertex   -78.0177      -27.5765      -13.3662    
    endloop
  endfacet
  facet normal   0.467648      0.877154     -0.109114    
    outer loop
      vertex   -7.56430      -10.9953      -1.34320    
      vertex   -3.33570      -13.1691     -0.694900    
      vertex   -3.31530      -13.2650      -1.37840    
    endloop
  endfacet
  facet normal  -0.284459E-02  0.998499      0.546906E-01
    outer loop
      vertex   -21.4296      -11.1630      -4.47100    
      vertex   -18.0121      -11.5084       2.01280    
      vertex   -10.8863      -11.3998      0.400700    
    endloop
  endfacet
  facet normal  -0.314517E-01  0.997073      0.696929E-01
    outer loop
      vertex   -18.0121      -11.5084       2.01280    
      vertex   -21.4296      -11.1630      -4.47100    
      vertex   -32.4155      -11.3594      -6.61900    
    endloop
  endfacet
  facet normal  -0.216397      0.971892     -0.927266E-01
    outer loop
      vertex   -42.5971      -14.9592      -20.5886    
      vertex   -44.7721      -14.3822      -9.46510    
      vertex   -32.4155      -11.3594      -6.61900    
    endloop
  endfacet
  facet normal   0.358673      0.803892      0.474459    
    outer loop
      vertex   -49.3755      -16.2044      -22.5689    
      vertex   -56.1802      -12.6652      -23.4214    
      vertex   -58.3885      -18.3456      -12.1275    
    endloop
  endfacet
  facet normal  -0.383759      0.809919     -0.443577    
    outer loop
      vertex   -62.2715      -16.6000     -0.476500    
      vertex   -50.6710      -9.55330       2.35380    
      vertex   -48.2280      -15.2388      -10.1408    
    endloop
  endfacet
  facet normal  -0.109411      0.963672     -0.243650    
    outer loop
      vertex   -64.6571      -20.0526      -13.0608    
      vertex   -66.7273      -17.6107      -2.47310    
      vertex   -62.2715      -16.6000     -0.476500    
    endloop
  endfacet
  facet normal  -0.535134      0.844393      0.251467E-01
    outer loop
      vertex   -72.1679      -24.8176      -12.8920    
      vertex   -64.6571      -20.0526      -13.0608    
      vertex   -62.6445      -18.4728      -23.2794    
    endloop
  endfacet
  facet normal   0.366871     -0.867312      0.336416    
    outer loop
      vertex   -64.6571      -20.8418      -13.0608    
      vertex   -66.7273      -17.6107      -2.47310    
      vertex   -73.4149      -22.0069      -6.51390    
    endloop
  endfacet
  facet normal   0.194171     -0.956190      0.219086    
    outer loop
      vertex   -48.2280      -16.0280      -10.1408    
      vertex   -44.7721      -15.1714      -9.46510    
      vertex   -43.5367      -12.1515       2.62020    
    endloop
  endfacet
  facet normal   0.281812     -0.945407     -0.163672    
    outer loop
      vertex   -58.3885      -19.1348      -12.1275    
      vertex   -64.6571      -20.8418      -13.0608    
      vertex   -62.6445      -18.4728      -23.2794    
    endloop
  endfacet
  facet normal   0.181468     -0.983393     -0.279721E-02
    outer loop
      vertex   -48.2280      -16.0280      -10.1408    
      vertex   -49.3755      -16.2044      -22.5689    
      vertex   -42.5971      -14.9592      -20.5886    
    endloop
  endfacet
  facet normal   0.326576E-01 -0.996580     -0.759055E-01
    outer loop
      vertex   -21.7118      -11.3943      -11.9172    
      vertex   -21.4296      -11.9522      -4.47100    
      vertex   -32.4155      -12.1486      -6.61900    
    endloop
  endfacet
  facet normal  -0.147544     -0.955899      0.253944    
    outer loop
      vertex   -34.1959      -13.6419       2.43710    
      vertex   -43.5367      -12.1515       2.62020    
      vertex   -44.7721      -15.1714      -9.46510    
    endloop
  endfacet
  facet normal   0.118182E-01 -0.999929      0.122314E-02
    outer loop
      vertex   -7.42050      -11.7837      -2.07850    
      vertex   -7.56430      -11.7845      -1.34320    
      vertex   -21.4296      -11.9522      -4.47100    
    endloop
  endfacet
  facet normal  -0.830024     -0.555191      0.531246E-01
    outer loop
      vertex   -1.08370      -17.2963     -0.394000    
      vertex   -3.33570      -13.9583     -0.694900    
      vertex   -3.31530      -14.0542      -1.37840    
    endloop
  endfacet
  facet normal   0.326790     -0.904806     -0.273009    
    outer loop
      vertex   -78.0177      -27.5765      -13.3662    
      vertex   -70.7725      -22.9888      -19.8983    
      vertex   -72.1679      -25.6068      -12.8920    
    endloop
  endfacet
  facet normal   0.386776     -0.886446     -0.254201    
    outer loop
      vertex   -72.1679      -25.6068      -12.8920    
      vertex   -70.7725      -22.9888      -19.8983    
      vertex   -62.6445      -18.4728      -23.2794    
    endloop
  endfacet
  facet normal   0.636995     -0.716007     -0.285606    
    outer loop
      vertex   -62.6445      -18.4728      -23.2794    
      vertex   -56.1802      -12.6652      -23.4214    
      vertex   -58.3885      -19.1348      -12.1275    
    endloop
  endfacet
  facet normal   0.294823     -0.955454     -0.136599E-01
    outer loop
      vertex   -58.3885      -19.1348      -12.1275    
      vertex   -49.3755      -16.2044      -22.5689    
      vertex   -48.2280      -16.0280      -10.1408    
    endloop
  endfacet
  facet normal   0.235426     -0.971503      0.275001E-01
    outer loop
      vertex   -48.2280      -16.0280      -10.1408    
      vertex   -42.5971      -14.9592      -20.5886    
      vertex   -44.7721      -15.1714      -9.46510    
    endloop
  endfacet
  facet normal   0.498192     -0.865907     -0.448403E-01
    outer loop
      vertex   -26.4847      -9.20350       2.40180    
      vertex   -34.1959      -13.6419       2.43710    
      vertex   -32.4155      -12.1486      -6.61900    
    endloop
  endfacet
  facet normal  -0.218602     -0.876089      0.429746    
    outer loop
      vertex   -18.0121      -11.5084       2.01280    
      vertex   -26.4847      -9.20350       2.40180    
      vertex   -32.4155      -12.1486      -6.61900    
    endloop
  endfacet
  facet normal  -0.259636E-01 -0.985457      0.167931    
    outer loop
      vertex   -10.8863      -11.3998      0.400700    
      vertex   -21.4296      -11.9522      -4.47100    
      vertex   -7.56430      -11.7845      -1.34320    
    endloop
  endfacet
  facet normal  -0.469729     -0.877918     -0.928186E-01
    outer loop
      vertex   -7.56430      -11.7845      -1.34320    
      vertex   -7.42050      -11.7837      -2.07850    
      vertex   -3.31530      -14.0542      -1.37840    
    endloop
  endfacet
  facet normal  -0.594972     -0.578843     -0.557628    
    outer loop
      vertex   -3.31530      -14.0542      -1.37840    
      vertex  -0.549900      -17.1793      -1.08500    
      vertex   -1.08370      -17.2963     -0.394000    
    endloop
  endfacet
  facet normal   0.249059E-01 -0.996825     -0.756301E-01
    outer loop
      vertex   -21.4296      -11.9522      -4.47100    
      vertex   -21.7118      -11.3943      -11.9172    
      vertex   -7.42050      -11.7837      -2.07850    
    endloop
  endfacet
  facet normal  -0.460906E-01 -0.971752     -0.231462    
    outer loop
      vertex   -32.4155      -12.1486      -6.61900    
      vertex   -34.1359      -9.57310      -17.0892    
      vertex   -21.7118      -11.3943      -11.9172    
    endloop
  endfacet
  facet normal   0.595578     -0.751869     -0.282809    
    outer loop
      vertex   -42.5971      -14.9592      -20.5886    
      vertex   -34.1359      -9.57310      -17.0892    
      vertex   -32.4155      -12.1486      -6.61900    
    endloop
  endfacet
  facet normal   0.259492     -0.959772     -0.107246    
    outer loop
      vertex   -44.7721      -15.1714      -9.46510    
      vertex   -32.4155      -12.1486      -6.61900    
      vertex   -34.1959      -13.6419       2.43710    
    endloop
  endfacet
  facet normal  -0.328690     -0.863260      0.383074    
    outer loop
      vertex   -43.5367      -12.1515       2.62020    
      vertex   -50.6710      -9.55330       2.35380    
      vertex   -48.2280      -16.0280      -10.1408    
    endloop
  endfacet
  facet normal   0.230345     -0.932089      0.279555    
    outer loop
      vertex   -62.2715      -16.6000     -0.476500    
      vertex   -58.3885      -19.1348      -12.1275    
      vertex   -48.2280      -16.0280      -10.1408    
    endloop
  endfacet
  facet normal   0.214220     -0.937190      0.275290    
    outer loop
      vertex   -64.6571      -20.8418      -13.0608    
      vertex   -58.3885      -19.1348      -12.1275    
      vertex   -62.2715      -16.6000     -0.476500    
    endloop
  endfacet
  facet normal   0.471455     -0.725360      0.501580    
    outer loop
      vertex   -73.4149      -22.0069      -6.51390    
      vertex   -72.1679      -25.6068      -12.8920    
      vertex   -64.6571      -20.8418      -13.0608    
    endloop
  endfacet
  facet normal   0.236481     -0.825643      0.512241    
    outer loop
      vertex   -73.4149      -22.0069      -6.51390    
      vertex   -78.0177      -27.5765      -13.3662    
      vertex   -72.1679      -25.6068      -12.8920    
    endloop
  endfacet
  facet normal  -0.467648     -0.877154      0.109114    
    outer loop
      vertex   -3.31530      -14.0542      -1.37840    
      vertex   -3.33570      -13.9583     -0.694900    
      vertex   -7.56430      -11.7845      -1.34320    
    endloop
  endfacet
  facet normal   0.274018E-01 -0.998171      0.538793E-01
    outer loop
      vertex   -10.8863      -11.3998      0.400700    
      vertex   -18.0121      -11.5084       2.01280    
      vertex   -21.4296      -11.9522      -4.47100    
    endloop
  endfacet
  facet normal   0.499986E-02 -0.997829      0.656636E-01
    outer loop
      vertex   -32.4155      -12.1486      -6.61900    
      vertex   -21.4296      -11.9522      -4.47100    
      vertex   -18.0121      -11.5084       2.01280    
    endloop
  endfacet
  facet normal   0.231719     -0.972415      0.267580E-01
    outer loop
      vertex   -32.4155      -12.1486      -6.61900    
      vertex   -44.7721      -15.1714      -9.46510    
      vertex   -42.5971      -14.9592      -20.5886    
    endloop
  endfacet
  facet normal  -0.343299     -0.784460     -0.516496    
    outer loop
      vertex   -58.3885      -19.1348      -12.1275    
      vertex   -56.1802      -12.6652      -23.4214    
      vertex   -49.3755      -16.2044      -22.5689    
    endloop
  endfacet
  facet normal   0.365205     -0.795453      0.483610    
    outer loop
      vertex   -48.2280      -16.0280      -10.1408    
      vertex   -50.6710      -9.55330       2.35380    
      vertex   -62.2715      -16.6000     -0.476500    
    endloop
  endfacet
  facet normal   0.786095E-01 -0.949099      0.305012    
    outer loop
      vertex   -62.2715      -16.6000     -0.476500    
      vertex   -66.7273      -17.6107      -2.47310    
      vertex   -64.6571      -20.8418      -13.0608    
    endloop
  endfacet
  facet normal   0.532065     -0.841866     -0.903793E-01
    outer loop
      vertex   -62.6445      -18.4728      -23.2794    
      vertex   -64.6571      -20.8418      -13.0608    
      vertex   -72.1679      -25.6068      -12.8920    
    endloop
  endfacet
  facet normal  -0.305852E-01  0.000000E+00 -0.999532    
    outer loop
      vertex    1.31590      -16.5521     -0.304000E-01
      vertex    8.74740      -11.0052     -0.257800    
      vertex    8.74740      -11.8048     -0.257800    
    endloop
  endfacet
  facet normal  -0.581180E-02  0.000000E+00  0.999983    
    outer loop
      vertex    8.74740      -11.0052      0.850300    
      vertex    1.38320      -16.5435      0.807500    
      vertex    1.38320      -17.3431      0.807500    
    endloop
  endfacet
  facet normal  -0.460635      0.000000E+00  0.887590    
    outer loop
      vertex    24.7862      -11.5467       9.17400    
      vertex    8.74740      -11.0052      0.850300    
      vertex    8.74740      -11.8048      0.850300    
    endloop
  endfacet
  facet normal  -0.996790      0.000000E+00  0.800621E-01
    outer loop
      vertex    1.38320      -16.5435      0.807500    
      vertex    1.31590      -16.5521     -0.304000E-01
      vertex    1.31590      -17.3517     -0.304000E-01
    endloop
  endfacet
  facet normal  -0.668622      0.000000E+00 -0.743603    
    outer loop
      vertex    8.74740      -11.0052     -0.257800    
      vertex    13.3024      -11.6818      -4.35350    
      vertex    8.74740      -11.8048     -0.257800    
    endloop
  endfacet
  facet normal  -0.779885E-01 -0.975407     -0.206154    
    outer loop
      vertex    73.6133      -22.1688      -3.88560    
      vertex    73.5918      -19.8886      -14.6661    
      vertex    76.9694      -20.5527      -12.8017    
    endloop
  endfacet
  facet normal  -0.235439     -0.964265      0.121501    
    outer loop
      vertex    65.9253      -18.5470       9.96050    
      vertex    65.9253      -20.1733      -2.94620    
      vertex    73.6133      -22.1688      -3.88560    
    endloop
  endfacet
  facet normal  -0.406622     -0.867327     -0.287059    
    outer loop
      vertex    65.9253      -20.1733      -2.94620    
      vertex    65.9253      -15.5997      -16.7650    
      vertex    73.5918      -19.8886      -14.6661    
    endloop
  endfacet
  facet normal  -0.235915     -0.970102     -0.569804E-01
    outer loop
      vertex    49.9059      -14.9981     -0.510000    
      vertex    49.9059      -14.0102      -17.3292    
      vertex    59.1212      -16.2650      -17.0947    
    endloop
  endfacet
  facet normal   0.131301     -0.988350     -0.769689E-01
    outer loop
      vertex    30.8765      -12.1084      0.850300    
      vertex    30.8765      -11.2580      -10.0696    
      vertex    34.7573      -10.6770      -10.9099    
    endloop
  endfacet
  facet normal  -0.174281     -0.977823      0.116138    
    outer loop
      vertex    34.7411      -12.1369      0.823000    
      vertex    49.9059      -14.9981     -0.510000    
      vertex    49.9059      -13.2747       14.0002    
    endloop
  endfacet
  facet normal  -0.653659E-02 -0.993684      0.112025    
    outer loop
      vertex    30.8765      -12.1084      0.850300    
      vertex    34.7411      -12.1369      0.823000    
      vertex    34.7573      -10.9333       11.5001    
    endloop
  endfacet
  facet normal  -0.203539E-01 -0.997017     -0.744446E-01
    outer loop
      vertex    13.3024      -11.6818      -4.35350    
      vertex    24.7768      -11.5968      -8.62910    
      vertex    24.7768      -12.2662      0.336000    
    endloop
  endfacet
  facet normal   0.598154     -0.801381      0.000000E+00
    outer loop
      vertex    1.31590      -17.3517     -0.304000E-01
      vertex    8.74740      -11.8048     -0.257800    
      vertex    8.74740      -11.8048      0.850300    
    endloop
  endfacet
  facet normal   0.509948E-01 -0.940392      0.336247    
    outer loop
      vertex    83.9627      -22.8155      -4.88970    
      vertex    78.0016      -20.3417       2.93290    
      vertex    78.0290      -22.9016      -4.23060    
    endloop
  endfacet
  facet normal   0.194054     -0.971593      0.135459    
    outer loop
      vertex    78.0016      -20.3417       2.93290    
      vertex    73.5918      -20.6947       6.71830    
      vertex    73.6133      -22.1688      -3.88560    
    endloop
  endfacet
  facet normal  -0.214344     -0.967514      0.134064    
    outer loop
      vertex    73.6133      -22.1688      -3.88560    
      vertex    73.5918      -20.6947       6.71830    
      vertex    65.9253      -18.5470       9.96050    
    endloop
  endfacet
  facet normal  -0.488501     -0.826344      0.280219    
    outer loop
      vertex    65.9253      -18.5470       9.96050    
      vertex    57.2781      -12.5545       12.5574    
      vertex    57.2781      -17.3633      -1.62340    
    endloop
  endfacet
  facet normal   0.153525     -0.935803      0.317337    
    outer loop
      vertex    57.2781      -17.3633      -1.62340    
      vertex    57.2781      -12.5545       12.5574    
      vertex    49.9059      -13.2747       14.0002    
    endloop
  endfacet
  facet normal  -0.169621     -0.979278      0.110649    
    outer loop
      vertex    49.9059      -13.2747       14.0002    
      vertex    34.7573      -10.9333       11.5001    
      vertex    34.7411      -12.1369      0.823000    
    endloop
  endfacet
  facet normal  -0.336005     -0.914983      0.223400    
    outer loop
      vertex    34.7573      -10.9333       11.5001    
      vertex    30.8857      -9.72780       10.6144    
      vertex    30.8765      -12.1084      0.850300    
    endloop
  endfacet
  facet normal   0.189416E-01 -0.996525      0.811069E-01
    outer loop
      vertex    30.8765      -12.1084      0.850300    
      vertex    24.7862      -11.5467       9.17400    
      vertex    24.7768      -12.2662      0.336000    
    endloop
  endfacet
  facet normal  -0.287727E-01 -0.999586      0.000000E+00
    outer loop
      vertex    24.7768      -12.2662      0.336000    
      vertex    8.74740      -11.8048      0.850300    
      vertex    8.74740      -11.8048     -0.257800    
    endloop
  endfacet
  facet normal   0.600718     -0.798457     -0.400543E-01
    outer loop
      vertex    8.74740      -11.8048      0.850300    
      vertex    1.38320      -17.3431      0.807500    
      vertex    1.31590      -17.3517     -0.304000E-01
    endloop
  endfacet
  facet normal  -0.265208E-01 -0.997878     -0.594627E-01
    outer loop
      vertex    13.3024      -11.6818      -4.35350    
      vertex    24.7768      -12.2662      0.336000    
      vertex    8.74740      -11.8048     -0.257800    
    endloop
  endfacet
  facet normal   0.377780E-01 -0.996512     -0.744069E-01
    outer loop
      vertex    30.8765      -11.2580      -10.0696    
      vertex    24.7768      -12.2662      0.336000    
      vertex    24.7768      -11.5968      -8.62910    
    endloop
  endfacet
  facet normal  -0.819015E-02 -0.992313     -0.123483    
    outer loop
      vertex    34.7573      -10.6770      -10.9099    
      vertex    34.7411      -12.1369      0.823000    
      vertex    30.8765      -12.1084      0.850300    
    endloop
  endfacet
  facet normal  -0.237506     -0.969715     -0.569576E-01
    outer loop
      vertex    49.9059      -14.0102      -17.3292    
      vertex    49.9059      -14.9981     -0.510000    
      vertex    34.7573      -10.6770      -10.9099    
    endloop
  endfacet
  facet normal  -0.318122     -0.942241     -0.104787    
    outer loop
      vertex    59.1212      -16.2650      -17.0947    
      vertex    57.2781      -17.3633      -1.62340    
      vertex    49.9059      -14.9981     -0.510000    
    endloop
  endfacet
  facet normal  -0.321850     -0.940935     -0.105139    
    outer loop
      vertex    65.9253      -20.1733      -2.94620    
      vertex    57.2781      -17.3633      -1.62340    
      vertex    59.1212      -16.2650      -17.0947    
    endloop
  endfacet
  facet normal  -0.268908     -0.942427     -0.198798    
    outer loop
      vertex    73.5918      -19.8886      -14.6661    
      vertex    73.6133      -22.1688      -3.88560    
      vertex    65.9253      -20.1733      -2.94620    
    endloop
  endfacet
  facet normal  -0.177138     -0.954551     -0.239695    
    outer loop
      vertex    76.9694      -20.5527      -12.8017    
      vertex    78.0290      -22.9016      -4.23060    
      vertex    73.6133      -22.1688      -3.88560    
    endloop
  endfacet
  facet normal  -0.151615E-01 -0.964805     -0.262529    
    outer loop
      vertex    83.9627      -22.8155      -4.88970    
      vertex    78.0290      -22.9016      -4.23060    
      vertex    76.9694      -20.5527      -12.8017    
    endloop
  endfacet
  facet normal  -0.260765E-01 -0.996361      0.811414E-01
    outer loop
      vertex    24.7768      -12.2662      0.336000    
      vertex    24.7862      -11.5467       9.17400    
      vertex    8.74740      -11.8048      0.850300    
    endloop
  endfacet
  facet normal   0.227702     -0.946069      0.230448    
    outer loop
      vertex    30.8765      -12.1084      0.850300    
      vertex    30.8857      -9.72780       10.6144    
      vertex    24.7862      -11.5467       9.17400    
    endloop
  endfacet
  facet normal  -0.288029     -0.950938      0.112944    
    outer loop
      vertex    49.9059      -13.2747       14.0002    
      vertex    49.9059      -14.9981     -0.510000    
      vertex    57.2781      -17.3633      -1.62340    
    endloop
  endfacet
  facet normal  -0.194325     -0.973398     -0.121386    
    outer loop
      vertex    49.9059      -14.9981     -0.510000    
      vertex    34.7411      -12.1369      0.823000    
      vertex    34.7573      -10.6770      -10.9099    
    endloop
  endfacet
  facet normal   0.323214E-01 -0.996460     -0.776005E-01
    outer loop
      vertex    30.8765      -11.2580      -10.0696    
      vertex    30.8765      -12.1084      0.850300    
      vertex    24.7768      -12.2662      0.336000    
    endloop
  endfacet
  facet normal   0.107427     -0.943860     -0.312389    
    outer loop
      vertex    59.1212      -16.2650      -17.0947    
      vertex    65.9253      -15.5997      -16.7650    
      vertex    65.9253      -20.1733      -2.94620    
    endloop
  endfacet
  facet normal  -0.290232     -0.949449      0.119635    
    outer loop
      vertex    57.2781      -17.3633      -1.62340    
      vertex    65.9253      -20.1733      -2.94620    
      vertex    65.9253      -18.5470       9.96050    
    endloop
  endfacet
  facet normal  -0.128958     -0.933972      0.333265    
    outer loop
      vertex    73.6133      -22.1688      -3.88560    
      vertex    78.0290      -22.9016      -4.23060    
      vertex    78.0016      -20.3417       2.93290    
    endloop
  endfacet
  facet normal   0.145550      0.969617     -0.196615    
    outer loop
      vertex    78.0016      -20.3417       2.93290    
      vertex    78.0290      -21.7984      -4.23060    
      vertex    73.6133      -21.0656      -3.88560    
    endloop
  endfacet
  facet normal   0.303478      0.952057     -0.385862E-01
    outer loop
      vertex    65.9253      -18.5470       9.96050    
      vertex    65.9253      -19.0701      -2.94620    
      vertex    57.2781      -16.2601      -1.62340    
    endloop
  endfacet
  facet normal  -0.106036      0.964415      0.242199    
    outer loop
      vertex    65.9253      -19.0701      -2.94620    
      vertex    65.9253      -15.5997      -16.7650    
      vertex    59.1212      -16.2650      -17.0947    
    endloop
  endfacet
  facet normal  -0.239049E-01  0.999446     -0.231376E-01
    outer loop
      vertex    24.7768      -11.1630      0.336000    
      vertex    30.8765      -11.0052      0.850300    
      vertex    30.8765      -11.2580      -10.0696    
    endloop
  endfacet
  facet normal   0.187873      0.981732      0.301057E-01
    outer loop
      vertex    34.7573      -10.6770      -10.9099    
      vertex    34.7411      -11.0337      0.823000    
      vertex    49.9059      -13.8949     -0.510000    
    endloop
  endfacet
  facet normal   0.299652      0.953178     -0.407411E-01
    outer loop
      vertex    57.2781      -16.2601      -1.62340    
      vertex    49.9059      -13.8949     -0.510000    
      vertex    49.9059      -13.2747       14.0002    
    endloop
  endfacet
  facet normal  -0.256266      0.958470     -0.125152    
    outer loop
      vertex    24.7862      -11.5467       9.17400    
      vertex    30.8857      -9.72780       10.6144    
      vertex    30.8765      -11.0052      0.850300    
    endloop
  endfacet
  facet normal   0.112257E-01  0.998996      0.433592E-01
    outer loop
      vertex    8.74740      -11.0052      0.850300    
      vertex    24.7862      -11.5467       9.17400    
      vertex    24.7768      -11.1630      0.336000    
    endloop
  endfacet
  facet normal   0.180621      0.976259      0.119558    
    outer loop
      vertex    83.9627      -22.8155      -4.88970    
      vertex    76.9694      -20.5527      -12.8017    
      vertex    78.0290      -21.7984      -4.23060    
    endloop
  endfacet
  facet normal   0.171698      0.977707      0.120871    
    outer loop
      vertex    73.6133      -21.0656      -3.88560    
      vertex    78.0290      -21.7984      -4.23060    
      vertex    76.9694      -20.5527      -12.8017    
    endloop
  endfacet
  facet normal   0.261780      0.959483      0.104233    
    outer loop
      vertex    65.9253      -19.0701      -2.94620    
      vertex    73.6133      -21.0656      -3.88560    
      vertex    73.5918      -19.8886      -14.6661    
    endloop
  endfacet
  facet normal   0.313969      0.948708      0.371027E-01
    outer loop
      vertex    59.1212      -16.2650      -17.0947    
      vertex    57.2781      -16.2601      -1.62340    
      vertex    65.9253      -19.0701      -2.94620    
    endloop
  endfacet
  facet normal   0.310301      0.949931      0.366654E-01
    outer loop
      vertex    49.9059      -13.8949     -0.510000    
      vertex    57.2781      -16.2601      -1.62340    
      vertex    59.1212      -16.2650      -17.0947    
    endloop
  endfacet
  facet normal   0.212180      0.977208     -0.669897E-02
    outer loop
      vertex    49.9059      -14.0102      -17.3292    
      vertex    34.7573      -10.6770      -10.9099    
      vertex    49.9059      -13.8949     -0.510000    
    endloop
  endfacet
  facet normal   0.758564E-02  0.999509      0.303972E-01
    outer loop
      vertex    30.8765      -11.0052      0.850300    
      vertex    34.7411      -11.0337      0.823000    
      vertex    34.7573      -10.6770      -10.9099    
    endloop
  endfacet
  facet normal  -0.667434E-01  0.996604     -0.482233E-01
    outer loop
      vertex    30.8765      -11.2580      -10.0696    
      vertex    24.7768      -11.5968      -8.62910    
      vertex    24.7768      -11.1630      0.336000    
    endloop
  endfacet
  facet normal   0.151651E-01  0.989090     -0.146529    
    outer loop
      vertex    8.74740      -11.0052     -0.257800    
      vertex    24.7768      -11.1630      0.336000    
      vertex    13.3024      -11.6818      -4.35350    
    endloop
  endfacet
  facet normal  -0.600718      0.798457      0.400561E-01
    outer loop
      vertex    1.31590      -16.5521     -0.304000E-01
      vertex    1.38320      -16.5435      0.807500    
      vertex    8.74740      -11.0052      0.850300    
    endloop
  endfacet
  facet normal   0.984392E-02  0.999952      0.000000E+00
    outer loop
      vertex    8.74740      -11.0052     -0.257800    
      vertex    8.74740      -11.0052      0.850300    
      vertex    24.7768      -11.1630      0.336000    
    endloop
  endfacet
  facet normal  -0.294926E-01  0.998623      0.433863E-01
    outer loop
      vertex    24.7768      -11.1630      0.336000    
      vertex    24.7862      -11.5467       9.17400    
      vertex    30.8765      -11.0052      0.850300    
    endloop
  endfacet
  facet normal   0.320607      0.939170     -0.123170    
    outer loop
      vertex    30.8765      -11.0052      0.850300    
      vertex    30.8857      -9.72780       10.6144    
      vertex    34.7573      -10.9333       11.5001    
    endloop
  endfacet
  facet normal   0.154277      0.987982     -0.952438E-02
    outer loop
      vertex    34.7411      -11.0337      0.823000    
      vertex    34.7573      -10.9333       11.5001    
      vertex    49.9059      -13.2747       14.0002    
    endloop
  endfacet
  facet normal  -0.142527      0.957635     -0.250241    
    outer loop
      vertex    49.9059      -13.2747       14.0002    
      vertex    57.2781      -12.5545       12.5574    
      vertex    57.2781      -16.2601      -1.62340    
    endloop
  endfacet
  facet normal   0.511053      0.831625     -0.217313    
    outer loop
      vertex    57.2781      -16.2601      -1.62340    
      vertex    57.2781      -12.5545       12.5574    
      vertex    65.9253      -18.5470       9.96050    
    endloop
  endfacet
  facet normal   0.256537      0.965962     -0.332669E-01
    outer loop
      vertex    65.9253      -18.5470       9.96050    
      vertex    73.5918      -20.6947       6.71830    
      vertex    73.6133      -21.0656      -3.88560    
    endloop
  endfacet
  facet normal  -0.109535      0.993368     -0.349677E-01
    outer loop
      vertex    73.6133      -21.0656      -3.88560    
      vertex    73.5918      -20.6947       6.71830    
      vertex    78.0016      -20.3417       2.93290    
    endloop
  endfacet
  facet normal   0.144387      0.969783     -0.196654    
    outer loop
      vertex    78.0290      -21.7984      -4.23060    
      vertex    78.0016      -20.3417       2.93290    
      vertex    83.9627      -22.8155      -4.88970    
    endloop
  endfacet
  facet normal  -0.598154      0.801381      0.000000E+00
    outer loop
      vertex    8.74740      -11.0052      0.850300    
      vertex    8.74740      -11.0052     -0.257800    
      vertex    1.31590      -16.5521     -0.304000E-01
    endloop
  endfacet
  facet normal  -0.254001E-01  0.998509     -0.483155E-01
    outer loop
      vertex    24.7768      -11.1630      0.336000    
      vertex    24.7768      -11.5968      -8.62910    
      vertex    13.3024      -11.6818      -4.35350    
    endloop
  endfacet
  facet normal   0.730750E-02  0.999929     -0.941372E-02
    outer loop
      vertex    34.7573      -10.9333       11.5001    
      vertex    34.7411      -11.0337      0.823000    
      vertex    30.8765      -11.0052      0.850300    
    endloop
  endfacet
  facet normal   0.181674      0.982462     -0.419927E-01
    outer loop
      vertex    49.9059      -13.2747       14.0002    
      vertex    49.9059      -13.8949     -0.510000    
      vertex    34.7411      -11.0337      0.823000    
    endloop
  endfacet
  facet normal  -0.152865      0.987982     -0.228722E-01
    outer loop
      vertex    34.7573      -10.6770      -10.9099    
      vertex    30.8765      -11.2580      -10.0696    
      vertex    30.8765      -11.0052      0.850300    
    endloop
  endfacet
  facet normal   0.237824      0.971286     -0.665837E-02
    outer loop
      vertex    59.1212      -16.2650      -17.0947    
      vertex    49.9059      -14.0102      -17.3292    
      vertex    49.9059      -13.8949     -0.510000    
    endloop
  endfacet
  facet normal   0.429721      0.875767      0.219937    
    outer loop
      vertex    73.5918      -19.8886      -14.6661    
      vertex    65.9253      -15.5997      -16.7650    
      vertex    65.9253      -19.0701      -2.94620    
    endloop
  endfacet
  facet normal   0.246546      0.968336     -0.392460E-01
    outer loop
      vertex    73.6133      -21.0656      -3.88560    
      vertex    65.9253      -19.0701      -2.94620    
      vertex    65.9253      -18.5470       9.96050    
    endloop
  endfacet
  facet normal   0.134469      0.985093      0.107283    
    outer loop
      vertex    76.9694      -20.5527      -12.8017    
      vertex    73.5918      -19.8886      -14.6661    
      vertex    73.6133      -21.0656      -3.88560    
    endloop
  endfacet
  facet normal   0.874118      0.000000E+00  0.485714    
    outer loop
      vertex  -0.420700      -17.7796       3.52410    
      vertex   -2.50610      -14.7620       7.27710    
      vertex   -2.50610      -15.5606       7.27710    
    endloop
  endfacet
  facet normal  -0.786621E-01  0.000000E+00 -0.996901    
    outer loop
      vertex  -0.594600      -20.5959      0.504700    
      vertex   0.502900      -20.4255      0.418100    
      vertex   0.502900      -21.2240      0.418100    
    endloop
  endfacet
  facet normal  -0.828751      0.000000E+00 -0.559617    
    outer loop
      vertex   -3.54310      -14.8935       6.76760    
      vertex   -1.11860      -17.7861       3.17710    
      vertex   -1.11860      -18.5846       3.17710    
    endloop
  endfacet
  facet normal  -0.526592      0.000000E+00 -0.850118    
    outer loop
      vertex   -21.0536      -15.2508       17.6142    
      vertex   -3.54310      -14.8935       6.76760    
      vertex   -3.54310      -15.6921       6.76760    
    endloop
  endfacet
  facet normal  -0.981314      0.000000E+00 -0.192414    
    outer loop
      vertex   -1.11860      -17.7861       3.17710    
      vertex  -0.594600      -20.5959      0.504700    
      vertex  -0.594600      -21.3944      0.504700    
    endloop
  endfacet
  facet normal   0.958520      0.000000E+00  0.285025    
    outer loop
      vertex   0.502900      -20.4255      0.418100    
      vertex  -0.420700      -17.7796       3.52410    
      vertex  -0.420700      -18.5781       3.52410    
    endloop
  endfacet
  facet normal   0.977024      0.000000E+00 -0.213130    
    outer loop
      vertex   -2.50610      -14.7620       7.27710    
      vertex  -0.881400      -15.1613       14.7250    
      vertex   -2.50610      -15.5606       7.27710    
    endloop
  endfacet
  facet normal   0.187145     -0.972647     -0.137606    
    outer loop
      vertex   -23.5046      -18.2016       38.9914    
      vertex   -17.9604      -16.1013       31.6859    
      vertex   -4.13070      -13.2377       30.2535    
    endloop
  endfacet
  facet normal   0.509793E-01 -0.972207     -0.228503    
    outer loop
      vertex   -45.4296      -20.0478       41.9549    
      vertex   -38.6730      -17.2470       31.5458    
      vertex   -23.5046      -18.2016       38.9914    
    endloop
  endfacet
  facet normal   0.412620     -0.816186     -0.404456    
    outer loop
      vertex   -31.2315      -22.3804       48.9242    
      vertex   -14.3105      -16.0003       53.3118    
      vertex   -21.0367      -22.3146       59.1920    
    endloop
  endfacet
  facet normal  -0.176142E-01 -0.945140     -0.326190    
    outer loop
      vertex   -35.4210      -24.5555       53.8993    
      vertex   -39.7387      -26.3786       59.4149    
      vertex   -49.4545      -24.5516       54.6458    
    endloop
  endfacet
  facet normal  -0.393621E-01 -0.944914      0.324944    
    outer loop
      vertex   -11.9877      -15.7266       22.0642    
      vertex   -3.04840      -14.5866       26.4621    
      vertex   -4.13070      -13.2377       30.2535    
    endloop
  endfacet
  facet normal   0.941949E-01 -0.993362      0.660303E-01
    outer loop
      vertex  -0.881400      -15.1613       14.7250    
      vertex   -3.04840      -14.5866       26.4621    
      vertex   -11.9877      -15.7266       22.0642    
    endloop
  endfacet
  facet normal  -0.171112     -0.812100      0.557867    
    outer loop
      vertex  -0.420700      -18.5781       3.52410    
      vertex   -2.50610      -15.5606       7.27710    
      vertex   -3.54310      -15.6921       6.76760    
    endloop
  endfacet
  facet normal   0.283806     -0.949847      0.131323    
    outer loop
      vertex   -45.1284      -27.0025       66.5501    
      vertex   -39.7387      -26.3786       59.4149    
      vertex   -33.1896      -23.6567       64.9487    
    endloop
  endfacet
  facet normal   0.207955     -0.965560     -0.156361    
    outer loop
      vertex   -39.7387      -26.3786       59.4149    
      vertex   -35.4210      -24.5555       53.8993    
      vertex   -21.0367      -22.3146       59.1920    
    endloop
  endfacet
  facet normal   0.229146     -0.947869     -0.221443    
    outer loop
      vertex   -21.0367      -22.3146       59.1920    
      vertex   -35.4210      -24.5555       53.8993    
      vertex   -31.2315      -22.3804       48.9242    
    endloop
  endfacet
  facet normal   0.200714     -0.949004     -0.243114    
    outer loop
      vertex   -31.2315      -22.3804       48.9242    
      vertex   -23.5046      -18.2016       38.9914    
      vertex   -9.49680      -17.0004       45.8673    
    endloop
  endfacet
  facet normal   0.169318     -0.969806     -0.175519    
    outer loop
      vertex   -9.49680      -17.0004       45.8673    
      vertex   -23.5046      -18.2016       38.9914    
      vertex   -4.13070      -13.2377       30.2535    
    endloop
  endfacet
  facet normal   0.211122     -0.973010      0.931626E-01
    outer loop
      vertex   -4.13070      -13.2377       30.2535    
      vertex   -17.9604      -16.1013       31.6859    
      vertex   -11.9877      -15.7266       22.0642    
    endloop
  endfacet
  facet normal   0.751852E-01 -0.996482      0.370228E-01
    outer loop
      vertex  -0.881400      -15.1613       14.7250    
      vertex   -11.9877      -15.7266       22.0642    
      vertex   -2.50610      -15.5606       7.27710    
    endloop
  endfacet
  facet normal  -0.242800     -0.828961      0.503858    
    outer loop
      vertex   -3.54310      -15.6921       6.76760    
      vertex   -1.11860      -18.5846       3.17710    
      vertex  -0.420700      -18.5781       3.52410    
    endloop
  endfacet
  facet normal   0.160740     -0.664303      0.729975    
    outer loop
      vertex   -1.11860      -18.5846       3.17710    
      vertex  -0.594600      -21.3944      0.504700    
      vertex   0.502900      -21.2240      0.418100    
    endloop
  endfacet
  facet normal   0.999768E-01 -0.993580      0.529520E-01
    outer loop
      vertex   -11.9877      -15.7266       22.0642    
      vertex   -3.54310      -15.6921       6.76760    
      vertex   -2.50610      -15.5606       7.27710    
    endloop
  endfacet
  facet normal  -0.255279E-01 -0.998175     -0.547187E-01
    outer loop
      vertex   -17.9604      -16.1013       31.6859    
      vertex   -21.0536      -15.2508       17.6142    
      vertex   -11.9877      -15.7266       22.0642    
    endloop
  endfacet
  facet normal   0.535871E-01 -0.921838     -0.383852    
    outer loop
      vertex   -38.6730      -17.2470       31.5458    
      vertex   -29.6346      -14.3938       25.9555    
      vertex   -17.9604      -16.1013       31.6859    
    endloop
  endfacet
  facet normal   0.283860E-01 -0.929080     -0.368789    
    outer loop
      vertex   -31.2315      -22.3804       48.9242    
      vertex   -45.4296      -20.0478       41.9549    
      vertex   -23.5046      -18.2016       38.9914    
    endloop
  endfacet
  facet normal  -0.324601     -0.942152     -0.835651E-01
    outer loop
      vertex   -35.4210      -24.5555       53.8993    
      vertex   -48.2525      -19.5749       47.5885    
      vertex   -45.4296      -20.0478       41.9549    
    endloop
  endfacet
  facet normal  -0.310552E-01 -0.814343     -0.579552    
    outer loop
      vertex   -49.4545      -24.5516       54.6458    
      vertex   -48.2525      -19.5749       47.5885    
      vertex   -35.4210      -24.5555       53.8993    
    endloop
  endfacet
  facet normal  -0.103852     -0.980942     -0.164220    
    outer loop
      vertex   -45.1284      -27.0025       66.5501    
      vertex   -49.4545      -24.5516       54.6458    
      vertex   -39.7387      -26.3786       59.4149    
    endloop
  endfacet
  facet normal  -0.278047     -0.770463      0.573652    
    outer loop
      vertex   0.502900      -21.2240      0.418100    
      vertex  -0.420700      -18.5781       3.52410    
      vertex   -1.11860      -18.5846       3.17710    
    endloop
  endfacet
  facet normal  -0.403767E-01 -0.998883     -0.245431E-01
    outer loop
      vertex   -11.9877      -15.7266       22.0642    
      vertex   -21.0536      -15.2508       17.6142    
      vertex   -3.54310      -15.6921       6.76760    
    endloop
  endfacet
  facet normal  -0.129531     -0.991077     -0.314280E-01
    outer loop
      vertex   -17.9604      -16.1013       31.6859    
      vertex   -29.6346      -14.3938       25.9555    
      vertex   -21.0536      -15.2508       17.6142    
    endloop
  endfacet
  facet normal   0.329521E-01 -0.925650     -0.376943    
    outer loop
      vertex   -45.4296      -20.0478       41.9549    
      vertex   -31.2315      -22.3804       48.9242    
      vertex   -35.4210      -24.5555       53.8993    
    endloop
  endfacet
  facet normal   0.209631     -0.952602      0.220462    
    outer loop
      vertex   -21.0367      -22.3146       59.1920    
      vertex   -33.1896      -23.6567       64.9487    
      vertex   -39.7387      -26.3786       59.4149    
    endloop
  endfacet
  facet normal   0.268577     -0.916401      0.296775    
    outer loop
      vertex   -9.49680      -17.0004       45.8673    
      vertex   -14.3105      -16.0003       53.3118    
      vertex   -31.2315      -22.3804       48.9242    
    endloop
  endfacet
  facet normal   0.552549E-01 -0.969956     -0.236925    
    outer loop
      vertex   -17.9604      -16.1013       31.6859    
      vertex   -23.5046      -18.2016       38.9914    
      vertex   -38.6730      -17.2470       31.5458    
    endloop
  endfacet
  facet normal  -0.927863E-01  0.973410      0.209435    
    outer loop
      vertex   -38.6730      -17.2470       31.5458    
      vertex   -23.5046      -17.4031       38.9914    
      vertex   -17.9604      -15.3028       31.6859    
    endloop
  endfacet
  facet normal  -0.235358      0.931503     -0.277324    
    outer loop
      vertex   -31.2315      -21.5819       48.9242    
      vertex   -14.3105      -16.0003       53.3118    
      vertex   -9.49680      -17.0004       45.8673    
    endloop
  endfacet
  facet normal  -0.171984      0.975723     -0.135596    
    outer loop
      vertex   -39.7387      -25.5801       59.4149    
      vertex   -33.1896      -23.6567       64.9487    
      vertex   -21.0367      -22.3146       59.1920    
    endloop
  endfacet
  facet normal  -0.704450E-01  0.934398      0.349195    
    outer loop
      vertex   -35.4210      -23.7570       53.8993    
      vertex   -31.2315      -21.5819       48.9242    
      vertex   -45.4296      -20.0478       41.9549    
    endloop
  endfacet
  facet normal   0.849308E-01  0.996274     -0.149876E-01
    outer loop
      vertex   -21.0536      -15.2508       17.6142    
      vertex   -29.6346      -14.3938       25.9555    
      vertex   -17.9604      -15.3028       31.6859    
    endloop
  endfacet
  facet normal  -0.288709E-01  0.999489     -0.136841E-01
    outer loop
      vertex   -3.54310      -14.8935       6.76760    
      vertex   -21.0536      -15.2508       17.6142    
      vertex   -11.9877      -14.9280       22.0642    
    endloop
  endfacet
  facet normal   0.278047      0.770463     -0.573652    
    outer loop
      vertex   -1.11860      -17.7861       3.17710    
      vertex  -0.420700      -17.7796       3.52410    
      vertex   0.502900      -20.4255      0.418100    
    endloop
  endfacet
  facet normal   0.572244E-02  0.979849      0.199655    
    outer loop
      vertex   -39.7387      -25.5801       59.4149    
      vertex   -49.4545      -24.5516       54.6458    
      vertex   -45.1284      -27.0025       66.5501    
    endloop
  endfacet
  facet normal  -0.157825E-01  0.818399      0.574434    
    outer loop
      vertex   -35.4210      -23.7570       53.8993    
      vertex   -48.2525      -19.5749       47.5885    
      vertex   -49.4545      -24.5516       54.6458    
    endloop
  endfacet
  facet normal   0.282072      0.957454      0.609697E-01
    outer loop
      vertex   -45.4296      -20.0478       41.9549    
      vertex   -48.2525      -19.5749       47.5885    
      vertex   -35.4210      -23.7570       53.8993    
    endloop
  endfacet
  facet normal  -0.667773E-01  0.937200      0.342340    
    outer loop
      vertex   -23.5046      -17.4031       38.9914    
      vertex   -45.4296      -20.0478       41.9549    
      vertex   -31.2315      -21.5819       48.9242    
    endloop
  endfacet
  facet normal  -0.903545E-01  0.938601      0.332962    
    outer loop
      vertex   -17.9604      -15.3028       31.6859    
      vertex   -29.6346      -14.3938       25.9555    
      vertex   -38.6730      -17.2470       31.5458    
    endloop
  endfacet
  facet normal  -0.419053E-01  0.999038      0.129033E-01
    outer loop
      vertex   -11.9877      -14.9280       22.0642    
      vertex   -21.0536      -15.2508       17.6142    
      vertex   -17.9604      -15.3028       31.6859    
    endloop
  endfacet
  facet normal  -0.999775E-01  0.993580     -0.529524E-01
    outer loop
      vertex   -2.50610      -14.7620       7.27710    
      vertex   -3.54310      -14.8935       6.76760    
      vertex   -11.9877      -14.9280       22.0642    
    endloop
  endfacet
  facet normal  -0.160740      0.664303     -0.729975    
    outer loop
      vertex   0.502900      -20.4255      0.418100    
      vertex  -0.594600      -20.5959      0.504700    
      vertex   -1.11860      -17.7861       3.17710    
    endloop
  endfacet
  facet normal   0.242806      0.828952     -0.503869    
    outer loop
      vertex  -0.420700      -17.7796       3.52410    
      vertex   -1.11860      -17.7861       3.17710    
      vertex   -3.54310      -14.8935       6.76760    
    endloop
  endfacet
  facet normal   0.492188E-01  0.997872      0.427616E-01
    outer loop
      vertex   -2.50610      -14.7620       7.27710    
      vertex   -11.9877      -14.9280       22.0642    
      vertex  -0.881400      -15.1613       14.7250    
    endloop
  endfacet
  facet normal  -0.153187      0.986571     -0.566608E-01
    outer loop
      vertex   -11.9877      -14.9280       22.0642    
      vertex   -17.9604      -15.3028       31.6859    
      vertex   -4.13070      -13.2377       30.2535    
    endloop
  endfacet
  facet normal  -0.122495      0.973616      0.192529    
    outer loop
      vertex   -9.49680      -17.0004       45.8673    
      vertex   -4.13070      -13.2377       30.2535    
      vertex   -23.5046      -17.4031       38.9914    
    endloop
  endfacet
  facet normal  -0.161441      0.948269      0.273356    
    outer loop
      vertex   -9.49680      -17.0004       45.8673    
      vertex   -23.5046      -17.4031       38.9914    
      vertex   -31.2315      -21.5819       48.9242    
    endloop
  endfacet
  facet normal  -0.189039      0.948186      0.255356    
    outer loop
      vertex   -31.2315      -21.5819       48.9242    
      vertex   -35.4210      -23.7570       53.8993    
      vertex   -21.0367      -22.3146       59.1920    
    endloop
  endfacet
  facet normal  -0.166703      0.967656      0.189347    
    outer loop
      vertex   -21.0367      -22.3146       59.1920    
      vertex   -35.4210      -23.7570       53.8993    
      vertex   -39.7387      -25.5801       59.4149    
    endloop
  endfacet
  facet normal  -0.271469      0.962357     -0.132131E-01
    outer loop
      vertex   -45.1284      -27.0025       66.5501    
      vertex   -33.1896      -23.6567       64.9487    
      vertex   -39.7387      -25.5801       59.4149    
    endloop
  endfacet
  facet normal   0.171117      0.812090     -0.557878    
    outer loop
      vertex   -3.54310      -14.8935       6.76760    
      vertex   -2.50610      -14.7620       7.27710    
      vertex  -0.420700      -17.7796       3.52410    
    endloop
  endfacet
  facet normal  -0.129094E-01  0.998601     -0.512793E-01
    outer loop
      vertex   -11.9877      -14.9280       22.0642    
      vertex   -3.04840      -14.5866       26.4621    
      vertex  -0.881400      -15.1613       14.7250    
    endloop
  endfacet
  facet normal   0.113494      0.945850     -0.304115    
    outer loop
      vertex   -4.13070      -13.2377       30.2535    
      vertex   -3.04840      -14.5866       26.4621    
      vertex   -11.9877      -14.9280       22.0642    
    endloop
  endfacet
  facet normal  -0.390022E-01  0.957453      0.285940    
    outer loop
      vertex   -49.4545      -24.5516       54.6458    
      vertex   -39.7387      -25.5801       59.4149    
      vertex   -35.4210      -23.7570       53.8993    
    endloop
  endfacet
  facet normal  -0.381959      0.814150      0.437341    
    outer loop
      vertex   -21.0367      -22.3146       59.1920    
      vertex   -14.3105      -16.0003       53.3118    
      vertex   -31.2315      -21.5819       48.9242    
    endloop
  endfacet
  facet normal  -0.900362E-01  0.974851      0.203862    
    outer loop
      vertex   -23.5046      -17.4031       38.9914    
      vertex   -38.6730      -17.2470       31.5458    
      vertex   -45.4296      -20.0478       41.9549    
    endloop
  endfacet
  facet normal  -0.126463      0.974710      0.184251    
    outer loop
      vertex   -4.13070      -13.2377       30.2535    
      vertex   -17.9604      -15.3028       31.6859    
      vertex   -23.5046      -17.4031       38.9914    
    endloop
  endfacet
  facet normal   0.599057      0.000000E+00 -0.800706    
    outer loop
      vertex    3.16070      -13.7638       3.68400    
      vertex    6.23210      -11.5424       5.98190    
      vertex    6.23210      -12.3483       5.98190    
    endloop
  endfacet
  facet normal  -0.856298      0.000000E+00 -0.516482    
    outer loop
      vertex   0.441800      -17.2667       1.92030    
      vertex   0.866000      -17.2759       1.21700    
      vertex   0.866000      -18.0818       1.21700    
    endloop
  endfacet
  facet normal  -0.617174      0.000000E+00  0.786827    
    outer loop
      vertex    5.75760      -11.1775       6.59210    
      vertex    2.74300      -13.7580       4.22750    
      vertex    2.74300      -14.5639       4.22750    
    endloop
  endfacet
  facet normal  -0.920422      0.000000E+00  0.390926    
    outer loop
      vertex    11.1277      -11.7425       19.2358    
      vertex    5.75760      -11.1775       6.59210    
      vertex    5.75760      -11.9834       6.59210    
    endloop
  endfacet
  facet normal  -0.708027      0.000000E+00  0.706186    
    outer loop
      vertex    2.74300      -13.7580       4.22750    
      vertex   0.441800      -17.2667       1.92030    
      vertex   0.441800      -18.0726       1.92030    
    endloop
  endfacet
  facet normal   0.732214      0.000000E+00 -0.681075    
    outer loop
      vertex   0.866000      -17.2759       1.21700    
      vertex    3.16070      -13.7638       3.68400    
      vertex    3.16070      -14.5697       3.68400    
    endloop
  endfacet
  facet normal   0.157242      0.000000E+00 -0.987560    
    outer loop
      vertex    6.23210      -11.5424       5.98190    
      vertex    18.3792      -11.8588       7.91600    
      vertex    6.23210      -12.3483       5.98190    
    endloop
  endfacet
  facet normal   0.250334      0.907841      0.336389    
    outer loop
      vertex    68.7171      -24.5531       47.3450    
      vertex    65.4912      -20.6368       39.1764    
      vertex    58.4379      -22.0528       48.2468    
    endloop
  endfacet
  facet normal   0.554718      0.816863      0.158185    
    outer loop
      vertex    60.0237      -25.1107       58.4767    
      vertex    64.3479      -26.9796       52.9637    
      vertex    58.4379      -22.0528       48.2468    
    endloop
  endfacet
  facet normal   0.227097      0.960310      0.161961    
    outer loop
      vertex    52.5648      -19.6632       44.1776    
      vertex    43.6481      -16.3543       37.0610    
      vertex    35.2697      -16.1901       47.8354    
    endloop
  endfacet
  facet normal   0.377663      0.923818     -0.626931E-01
    outer loop
      vertex    34.7051      -14.1420       15.7879    
      vertex    31.1471      -11.9209       27.0837    
      vertex    43.6481      -16.3543       37.0610    
    endloop
  endfacet
  facet normal   0.218087      0.963557      0.154905    
    outer loop
      vertex    35.2697      -16.1901       47.8354    
      vertex    43.6481      -16.3543       37.0610    
      vertex    31.1471      -11.9209       27.0837    
    endloop
  endfacet
  facet normal  -0.982284E-02  0.999952      0.616719E-03
    outer loop
      vertex    16.2156      -11.5069       25.7523    
      vertex    21.5837      -11.4499       18.8328    
      vertex    15.3143      -11.5084       13.8291    
    endloop
  endfacet
  facet normal  -0.392961      0.865282     -0.311238    
    outer loop
      vertex    6.23210      -11.5424       5.98190    
      vertex    3.16070      -13.7638       3.68400    
      vertex    2.74300      -13.7580       4.22750    
    endloop
  endfacet
  facet normal   0.517659E-01  0.901537      0.429594    
    outer loop
      vertex    68.7171      -24.5531       47.3450    
      vertex    64.3479      -26.9796       52.9637    
      vertex    69.3021      -29.1482       56.9177    
    endloop
  endfacet
  facet normal   0.243502      0.807077      0.537897    
    outer loop
      vertex    58.4379      -22.0528       48.2468    
      vertex    64.3479      -26.9796       52.9637    
      vertex    68.7171      -24.5531       47.3450    
    endloop
  endfacet
  facet normal   0.182455      0.939901      0.288610    
    outer loop
      vertex    52.5648      -19.6632       44.1776    
      vertex    58.4379      -22.0528       48.2468    
      vertex    65.4912      -20.6368       39.1764    
    endloop
  endfacet
  facet normal   0.117232      0.948544      0.294145    
    outer loop
      vertex    43.6481      -16.3543       37.0610    
      vertex    52.5648      -19.6632       44.1776    
      vertex    61.1239      -17.3078       33.1708    
    endloop
  endfacet
  facet normal  -0.193293      0.964202      0.181531    
    outer loop
      vertex    34.7051      -14.1420       15.7879    
      vertex    43.6481      -16.3543       37.0610    
      vertex    52.6937      -12.3509       25.4286    
    endloop
  endfacet
  facet normal   0.167980      0.975943     -0.138989    
    outer loop
      vertex    21.5837      -11.4499       18.8328    
      vertex    31.1471      -11.9209       27.0837    
      vertex    34.7051      -14.1420       15.7879    
    endloop
  endfacet
  facet normal   0.268173E-01  0.998614     -0.452761E-01
    outer loop
      vertex    18.3792      -11.8588       7.91600    
      vertex    15.3143      -11.5084       13.8291    
      vertex    21.5837      -11.4499       18.8328    
    endloop
  endfacet
  facet normal   0.327307E-01  0.998573     -0.422085E-01
    outer loop
      vertex    6.23210      -11.5424       5.98190    
      vertex    15.3143      -11.5084       13.8291    
      vertex    18.3792      -11.8588       7.91600    
    endloop
  endfacet
  facet normal  -0.185770      0.772938     -0.606676    
    outer loop
      vertex    2.74300      -13.7580       4.22750    
      vertex    5.75760      -11.1775       6.59210    
      vertex    6.23210      -11.5424       5.98190    
    endloop
  endfacet
  facet normal  -0.631479      0.670379     -0.389649    
    outer loop
      vertex   0.866000      -17.2759       1.21700    
      vertex   0.441800      -17.2667       1.92030    
      vertex    2.74300      -13.7580       4.22750    
    endloop
  endfacet
  facet normal   0.465431      0.870727     -0.158771    
    outer loop
      vertex    6.23210      -11.5424       5.98190    
      vertex    5.75760      -11.1775       6.59210    
      vertex    11.1277      -11.7425       19.2358    
    endloop
  endfacet
  facet normal  -0.510245E-01  0.998690      0.373140E-02
    outer loop
      vertex    15.3143      -11.5084       13.8291    
      vertex    11.1277      -11.7425       19.2358    
      vertex    16.2156      -11.5069       25.7523    
    endloop
  endfacet
  facet normal   0.455326E-01  0.977336     -0.206739    
    outer loop
      vertex    16.2156      -11.5069       25.7523    
      vertex    24.4628      -9.78760       35.6965    
      vertex    31.1471      -11.9209       27.0837    
    endloop
  endfacet
  facet normal   0.419556      0.901957      0.102207    
    outer loop
      vertex    31.1471      -11.9209       27.0837    
      vertex    24.4628      -9.78760       35.6965    
      vertex    35.2697      -16.1901       47.8354    
    endloop
  endfacet
  facet normal   0.153747      0.969047     -0.193158    
    outer loop
      vertex    35.2697      -16.1901       47.8354    
      vertex    44.6448      -16.3765       54.3625    
      vertex    52.5648      -19.6632       44.1776    
    endloop
  endfacet
  facet normal   0.482312      0.870941      0.940006E-01
    outer loop
      vertex    52.5648      -19.6632       44.1776    
      vertex    44.6448      -16.3765       54.3625    
      vertex    51.4417      -20.4482       57.2134    
    endloop
  endfacet
  facet normal   0.446528      0.873924      0.192013    
    outer loop
      vertex    58.4379      -22.0528       48.2468    
      vertex    51.4417      -20.4482       57.2134    
      vertex    60.0237      -25.1107       58.4767    
    endloop
  endfacet
  facet normal   0.399354      0.916793      0.244719E-02
    outer loop
      vertex    64.3479      -26.9796       52.9637    
      vertex    60.0237      -25.1107       58.4767    
      vertex    69.3021      -29.1482       56.9177    
    endloop
  endfacet
  facet normal  -0.572048      0.687729     -0.446978    
    outer loop
      vertex    2.74300      -13.7580       4.22750    
      vertex    3.16070      -13.7638       3.68400    
      vertex   0.866000      -17.2759       1.21700    
    endloop
  endfacet
  facet normal  -0.295931      0.953839      0.511401E-01
    outer loop
      vertex    21.5837      -11.4499       18.8328    
      vertex    27.0132      -9.39190       11.8668    
      vertex    18.3792      -11.8588       7.91600    
    endloop
  endfacet
  facet normal   0.252279E-01  0.999295      0.278035E-01
    outer loop
      vertex    31.1471      -11.9209       27.0837    
      vertex    21.5837      -11.4499       18.8328    
      vertex    16.2156      -11.5069       25.7523    
    endloop
  endfacet
  facet normal   0.280359      0.838979      0.466384    
    outer loop
      vertex    34.7051      -14.1420       15.7879    
      vertex    27.0132      -9.39190       11.8668    
      vertex    21.5837      -11.4499       18.8328    
    endloop
  endfacet
  facet normal   0.142242      0.896677      0.419210    
    outer loop
      vertex    61.1239      -17.3078       33.1708    
      vertex    52.6937      -12.3509       25.4286    
      vertex    43.6481      -16.3543       37.0610    
    endloop
  endfacet
  facet normal   0.324611      0.942048      0.846958E-01
    outer loop
      vertex    51.4417      -20.4482       57.2134    
      vertex    58.4379      -22.0528       48.2468    
      vertex    52.5648      -19.6632       44.1776    
    endloop
  endfacet
  facet normal   0.206180      0.911682      0.355425    
    outer loop
      vertex    65.4912      -20.6368       39.1764    
      vertex    61.1239      -17.3078       33.1708    
      vertex    52.5648      -19.6632       44.1776    
    endloop
  endfacet
  facet normal  -0.161206     -0.908216     -0.386209    
    outer loop
      vertex    52.5648      -20.4691       44.1776    
      vertex    61.1239      -17.3078       33.1708    
      vertex    65.4912      -20.6368       39.1764    
    endloop
  endfacet
  facet normal  -0.359137     -0.932820     -0.294458E-01
    outer loop
      vertex    52.5648      -20.4691       44.1776    
      vertex    58.4379      -22.8587       48.2468    
      vertex    51.4417      -20.4482       57.2134    
    endloop
  endfacet
  facet normal  -0.107709     -0.886394     -0.450228    
    outer loop
      vertex    43.6481      -17.1602       37.0610    
      vertex    52.6937      -12.3509       25.4286    
      vertex    61.1239      -17.3078       33.1708    
    endloop
  endfacet
  facet normal  -0.238931     -0.818363     -0.522679    
    outer loop
      vertex    21.5837      -12.2558       18.8328    
      vertex    27.0132      -9.39190       11.8668    
      vertex    34.7051      -14.1420       15.7879    
    endloop
  endfacet
  facet normal  -0.850556E-01 -0.995501      0.417579E-01
    outer loop
      vertex    16.2156      -11.5069       25.7523    
      vertex    21.5837      -12.2558       18.8328    
      vertex    31.1471      -12.7268       27.0837    
    endloop
  endfacet
  facet normal   0.326941     -0.936059     -0.130011    
    outer loop
      vertex    18.3792      -11.8588       7.91600    
      vertex    27.0132      -9.39190       11.8668    
      vertex    21.5837      -12.2558       18.8328    
    endloop
  endfacet
  facet normal   0.572047     -0.687729      0.446979    
    outer loop
      vertex   0.866000      -18.0818       1.21700    
      vertex    3.16070      -14.5697       3.68400    
      vertex    2.74300      -14.5639       4.22750    
    endloop
  endfacet
  facet normal  -0.372853     -0.915408      0.151685    
    outer loop
      vertex    69.3021      -29.1482       56.9177    
      vertex    60.0237      -25.1107       58.4767    
      vertex    64.3479      -27.7855       52.9637    
    endloop
  endfacet
  facet normal  -0.459834     -0.879537     -0.122339    
    outer loop
      vertex    60.0237      -25.1107       58.4767    
      vertex    51.4417      -20.4482       57.2134    
      vertex    58.4379      -22.8587       48.2468    
    endloop
  endfacet
  facet normal  -0.500510     -0.864724     -0.417350E-01
    outer loop
      vertex    51.4417      -20.4482       57.2134    
      vertex    44.6448      -16.3765       54.3625    
      vertex    52.5648      -20.4691       44.1776    
    endloop
  endfacet
  facet normal  -0.185299     -0.953193      0.238930    
    outer loop
      vertex    52.5648      -20.4691       44.1776    
      vertex    44.6448      -16.3765       54.3625    
      vertex    35.2697      -16.1901       47.8354    
    endloop
  endfacet
  facet normal  -0.461542     -0.885345     -0.560658E-01
    outer loop
      vertex    35.2697      -16.1901       47.8354    
      vertex    24.4628      -9.78760       35.6965    
      vertex    31.1471      -12.7268       27.0837    
    endloop
  endfacet
  facet normal  -0.100981     -0.962906      0.250230    
    outer loop
      vertex    31.1471      -12.7268       27.0837    
      vertex    24.4628      -9.78760       35.6965    
      vertex    16.2156      -11.5069       25.7523    
    endloop
  endfacet
  facet normal  -0.446006E-01 -0.996489      0.708504E-01
    outer loop
      vertex    16.2156      -11.5069       25.7523    
      vertex    11.1277      -11.7425       19.2358    
      vertex    15.3143      -12.3143       13.8291    
    endloop
  endfacet
  facet normal  -0.720334E-01 -0.996169      0.495744E-01
    outer loop
      vertex    15.3143      -12.3143       13.8291    
      vertex    11.1277      -11.7425       19.2358    
      vertex    5.75760      -11.9834       6.59210    
    endloop
  endfacet
  facet normal   0.631478     -0.670379      0.389650    
    outer loop
      vertex    2.74300      -14.5639       4.22750    
      vertex   0.441800      -18.0726       1.92030    
      vertex   0.866000      -18.0818       1.21700    
    endloop
  endfacet
  facet normal   0.185771     -0.772939      0.606675    
    outer loop
      vertex    6.23210      -12.3483       5.98190    
      vertex    5.75760      -11.9834       6.59210    
      vertex    2.74300      -14.5639       4.22750    
    endloop
  endfacet
  facet normal   0.484337E-01 -0.997486     -0.517343E-01
    outer loop
      vertex    18.3792      -11.8588       7.91600    
      vertex    15.3143      -12.3143       13.8291    
      vertex    6.23210      -12.3483       5.98190    
    endloop
  endfacet
  facet normal   0.499625E-01 -0.997451     -0.509392E-01
    outer loop
      vertex    21.5837      -12.2558       18.8328    
      vertex    15.3143      -12.3143       13.8291    
      vertex    18.3792      -11.8588       7.91600    
    endloop
  endfacet
  facet normal  -0.122336     -0.988812      0.853500E-01
    outer loop
      vertex    34.7051      -14.1420       15.7879    
      vertex    31.1471      -12.7268       27.0837    
      vertex    21.5837      -12.2558       18.8328    
    endloop
  endfacet
  facet normal   0.215382     -0.950172     -0.225354    
    outer loop
      vertex    34.7051      -14.1420       15.7879    
      vertex    52.6937      -12.3509       25.4286    
      vertex    43.6481      -17.1602       37.0610    
    endloop
  endfacet
  facet normal  -0.822032E-01 -0.939107     -0.333647    
    outer loop
      vertex    61.1239      -17.3078       33.1708    
      vertex    52.5648      -20.4691       44.1776    
      vertex    43.6481      -17.1602       37.0610    
    endloop
  endfacet
  facet normal  -0.143288     -0.929746     -0.339176    
    outer loop
      vertex    65.4912      -20.6368       39.1764    
      vertex    58.4379      -22.8587       48.2468    
      vertex    52.5648      -20.4691       44.1776    
    endloop
  endfacet
  facet normal  -0.181358     -0.784854     -0.592548    
    outer loop
      vertex    68.7171      -24.5531       47.3450    
      vertex    64.3479      -27.7855       52.9637    
      vertex    58.4379      -22.8587       48.2468    
    endloop
  endfacet
  facet normal   0.101597     -0.894414     -0.435547    
    outer loop
      vertex    68.7171      -24.5531       47.3450    
      vertex    69.3021      -29.1482       56.9177    
      vertex    64.3479      -27.7855       52.9637    
    endloop
  endfacet
  facet normal   0.392961     -0.865281      0.311239    
    outer loop
      vertex    2.74300      -14.5639       4.22750    
      vertex    3.16070      -14.5697       3.68400    
      vertex    6.23210      -12.3483       5.98190    
    endloop
  endfacet
  facet normal  -0.474117E-01 -0.996345      0.710532E-01
    outer loop
      vertex    15.3143      -12.3143       13.8291    
      vertex    21.5837      -12.2558       18.8328    
      vertex    16.2156      -11.5069       25.7523    
    endloop
  endfacet
  facet normal  -0.252956     -0.961186     -0.110161    
    outer loop
      vertex    31.1471      -12.7268       27.0837    
      vertex    43.6481      -17.1602       37.0610    
      vertex    35.2697      -16.1901       47.8354    
    endloop
  endfacet
  facet normal  -0.341449     -0.939845      0.101978E-01
    outer loop
      vertex    43.6481      -17.1602       37.0610    
      vertex    31.1471      -12.7268       27.0837    
      vertex    34.7051      -14.1420       15.7879    
    endloop
  endfacet
  facet normal  -0.261827     -0.957954     -0.117351    
    outer loop
      vertex    35.2697      -16.1901       47.8354    
      vertex    43.6481      -17.1602       37.0610    
      vertex    52.5648      -20.4691       44.1776    
    endloop
  endfacet
  facet normal  -0.598371     -0.796942     -0.826807E-01
    outer loop
      vertex    58.4379      -22.8587       48.2468    
      vertex    64.3479      -27.7855       52.9637    
      vertex    60.0237      -25.1107       58.4767    
    endloop
  endfacet
  facet normal  -0.182520     -0.912735     -0.365516    
    outer loop
      vertex    58.4379      -22.8587       48.2468    
      vertex    65.4912      -20.6368       39.1764    
      vertex    68.7171      -24.5531       47.3450    
    endloop
  endfacet
  facet normal  -0.610190      0.000000E+00 -0.792255    
    outer loop
      vertex    4.06530      -12.9913      -3.25330    
      vertex    6.36420      -11.5503      -5.02390    
      vertex    6.36420      -12.3552      -5.02390    
    endloop
  endfacet
  facet normal  -0.884240      0.000000E+00  0.467034    
    outer loop
      vertex    1.40140      -17.2636      0.809000E-01
      vertex   0.936500      -17.3403     -0.799300    
      vertex   0.936500      -18.1452     -0.799300    
    endloop
  endfacet
  facet normal   0.588367      0.000000E+00  0.808594    
    outer loop
      vertex    6.79960      -11.5494      -4.27430    
      vertex    4.26800      -12.7110      -2.43220    
      vertex    4.26800      -13.5159      -2.43220    
    endloop
  endfacet
  facet normal   0.129245      0.000000E+00  0.991613    
    outer loop
      vertex    20.4188      -11.9630      -6.04940    
      vertex    6.79960      -11.5494      -4.27430    
      vertex    6.79960      -12.3543      -4.27430    
    endloop
  endfacet
  facet normal   0.659221      0.000000E+00  0.751949    
    outer loop
      vertex    4.26800      -12.7110      -2.43220    
      vertex    1.40140      -17.2636      0.809000E-01
      vertex    1.40140      -18.0685      0.809000E-01
    endloop
  endfacet
  facet normal  -0.617146      0.000000E+00 -0.786849    
    outer loop
      vertex   0.936500      -17.3403     -0.799300    
      vertex    4.06530      -12.9913      -3.25330    
      vertex    4.06530      -13.7962      -3.25330    
    endloop
  endfacet
  facet normal  -0.905902      0.000000E+00 -0.423487    
    outer loop
      vertex    6.36420      -11.5503      -5.02390    
      vertex    12.2852      -11.7715      -17.6898    
      vertex    6.36420      -12.3552      -5.02390    
    endloop
  endfacet
  facet normal  -0.136266      0.990640     -0.803826E-02
    outer loop
      vertex    32.5316      -12.7185      -41.4011    
      vertex    27.1963      -13.4030      -35.3145    
      vertex    33.8943      -12.3881      -23.7830    
    endloop
  endfacet
  facet normal   0.476824      0.878973     -0.681244E-02
    outer loop
      vertex    39.7253      -13.5854      -47.8103    
      vertex    47.2455      -17.5646      -34.8633    
      vertex    53.9697      -21.2519      -39.9683    
    endloop
  endfacet
  facet normal   0.442852      0.604451     -0.662209    
    outer loop
      vertex    64.8510      -26.0413      -37.0631    
      vertex    59.6673      -30.1653      -44.2940    
      vertex    53.9697      -21.2519      -39.9683    
    endloop
  endfacet
  facet normal   0.192034      0.968164     -0.160564    
    outer loop
      vertex    54.2372      -16.9551      -22.8261    
      vertex    47.2455      -17.5646      -34.8633    
      vertex    39.6698      -15.1081      -29.1117    
    endloop
  endfacet
  facet normal   0.557185E-02  0.973626     -0.228081    
    outer loop
      vertex    39.2883      -10.2482      -14.5165    
      vertex    33.8943      -12.3881      -23.7830    
      vertex    28.7332      -11.6656      -20.8249    
    endloop
  endfacet
  facet normal  -0.234671      0.970865     -0.484834E-01
    outer loop
      vertex    25.9854      -11.7592      -9.39920    
      vertex    33.8333      -9.99600      -12.0774    
      vertex    28.7332      -11.6656      -20.8249    
    endloop
  endfacet
  facet normal  -0.694354E-01  0.961918      0.264372    
    outer loop
      vertex    22.2274      -11.5542      -15.8692    
      vertex    17.5064      -9.65590      -24.0161    
      vertex    12.2852      -11.7715      -17.6898    
    endloop
  endfacet
  facet normal  -0.594101      0.794679     -0.124617    
    outer loop
      vertex    6.36420      -11.5503      -5.02390    
      vertex    4.06530      -12.9913      -3.25330    
      vertex    4.26800      -12.7110      -2.43220    
    endloop
  endfacet
  facet normal   0.750329      0.660627      0.240467E-01
    outer loop
      vertex    55.4572      -25.0457      -53.5752    
      vertex    59.6673      -30.1653      -44.2940    
      vertex    66.0132      -37.1975      -49.1119    
    endloop
  endfacet
  facet normal   0.825943      0.559898     -0.658160E-01
    outer loop
      vertex    53.9697      -21.2519      -39.9683    
      vertex    59.6673      -30.1653      -44.2940    
      vertex    55.4572      -25.0457      -53.5752    
    endloop
  endfacet
  facet normal   0.282536      0.890287      0.357158    
    outer loop
      vertex    39.7253      -13.5854      -47.8103    
      vertex    53.9697      -21.2519      -39.9683    
      vertex    47.4230      -14.2907      -52.1416    
    endloop
  endfacet
  facet normal   0.248673      0.956953      0.149675    
    outer loop
      vertex    32.5316      -12.7185      -41.4011    
      vertex    47.2455      -17.5646      -34.8633    
      vertex    39.7253      -13.5854      -47.8103    
    endloop
  endfacet
  facet normal   0.389482      0.919815     -0.473747E-01
    outer loop
      vertex    33.8943      -12.3881      -23.7830    
      vertex    39.6698      -15.1081      -29.1117    
      vertex    32.5316      -12.7185      -41.4011    
    endloop
  endfacet
  facet normal  -0.191763      0.981122      0.250347E-01
    outer loop
      vertex    23.1445      -14.3183      -30.4798    
      vertex    33.8943      -12.3881      -23.7830    
      vertex    27.1963      -13.4030      -35.3145    
    endloop
  endfacet
  facet normal   0.545157      0.829310     -0.122673    
    outer loop
      vertex    17.5064      -9.65590      -24.0161    
      vertex    22.2274      -11.5542      -15.8692    
      vertex    23.1445      -14.3183      -30.4798    
    endloop
  endfacet
  facet normal  -0.239700E-01  0.999646      0.115854E-01
    outer loop
      vertex    12.2852      -11.7715      -17.6898    
      vertex    16.7586      -11.7264      -12.3258    
      vertex    22.2274      -11.5542      -15.8692    
    endloop
  endfacet
  facet normal   0.695790E-02  0.999875     -0.142094E-01
    outer loop
      vertex    6.36420      -11.5503      -5.02390    
      vertex    16.7586      -11.7264      -12.3258    
      vertex    12.2852      -11.7715      -17.6898    
    endloop
  endfacet
  facet normal  -0.302754      0.936915      0.174729    
    outer loop
      vertex    4.26800      -12.7110      -2.43220    
      vertex    6.79960      -11.5494      -4.27430    
      vertex    6.36420      -11.5503      -5.02390    
    endloop
  endfacet
  facet normal  -0.711303      0.625196      0.321214    
    outer loop
      vertex   0.936500      -17.3403     -0.799300    
      vertex    1.40140      -17.2636      0.809000E-01
      vertex    4.26800      -12.7110      -2.43220    
    endloop
  endfacet
  facet normal   0.327666E-01  0.999291      0.185615E-01
    outer loop
      vertex    6.79960      -11.5494      -4.27430    
      vertex    20.4188      -11.9630      -6.04940    
      vertex    16.7586      -11.7264      -12.3258    
    endloop
  endfacet
  facet normal  -0.795641E-02  0.999310      0.362842E-01
    outer loop
      vertex    16.7586      -11.7264      -12.3258    
      vertex    25.9854      -11.7592      -9.39920    
      vertex    22.2274      -11.5542      -15.8692    
    endloop
  endfacet
  facet normal   0.285883E-01  0.999478      0.150631E-01
    outer loop
      vertex    22.2274      -11.5542      -15.8692    
      vertex    25.9854      -11.7592      -9.39920    
      vertex    28.7332      -11.6656      -20.8249    
    endloop
  endfacet
  facet normal  -0.305548E-01  0.984940     -0.170177    
    outer loop
      vertex    28.7332      -11.6656      -20.8249    
      vertex    33.8333      -9.99600      -12.0774    
      vertex    39.2883      -10.2482      -14.5165    
    endloop
  endfacet
  facet normal  -0.273305      0.910497     -0.310321    
    outer loop
      vertex    39.2883      -10.2482      -14.5165    
      vertex    46.2563      -9.26620      -17.7721    
      vertex    39.6698      -15.1081      -29.1117    
    endloop
  endfacet
  facet normal   0.343937      0.738335     -0.580146    
    outer loop
      vertex    39.6698      -15.1081      -29.1117    
      vertex    46.2563      -9.26620      -17.7721    
      vertex    54.2372      -16.9551      -22.8261    
    endloop
  endfacet
  facet normal  -0.196578      0.951785     -0.235503    
    outer loop
      vertex    54.2372      -16.9551      -22.8261    
      vertex    60.6861      -17.2229      -29.2914    
      vertex    53.9697      -21.2519      -39.9683    
    endloop
  endfacet
  facet normal   0.455052      0.699990     -0.550401    
    outer loop
      vertex    53.9697      -21.2519      -39.9683    
      vertex    60.6861      -17.2229      -29.2914    
      vertex    64.8510      -26.0413      -37.0631    
    endloop
  endfacet
  facet normal   0.311319      0.712082     -0.629301    
    outer loop
      vertex    59.6673      -30.1653      -44.2940    
      vertex    64.8510      -26.0413      -37.0631    
      vertex    66.0132      -37.1975      -49.1119    
    endloop
  endfacet
  facet normal  -0.811522      0.584321      0.865640E-03
    outer loop
      vertex    4.26800      -12.7110      -2.43220    
      vertex    4.06530      -12.9913      -3.25330    
      vertex   0.936500      -17.3403     -0.799300    
    endloop
  endfacet
  facet normal   0.114327E-01  0.999904     -0.784018E-02
    outer loop
      vertex    16.7586      -11.7264      -12.3258    
      vertex    6.36420      -11.5503      -5.02390    
      vertex    6.79960      -11.5494      -4.27430    
    endloop
  endfacet
  facet normal  -0.129728      0.972749     -0.192172    
    outer loop
      vertex    22.2274      -11.5542      -15.8692    
      vertex    28.7332      -11.6656      -20.8249    
      vertex    23.1445      -14.3183      -30.4798    
    endloop
  endfacet
  facet normal  -0.102985E-01  0.998993      0.436645E-01
    outer loop
      vertex    16.7586      -11.7264      -12.3258    
      vertex    20.4188      -11.9630      -6.04940    
      vertex    25.9854      -11.7592      -9.39920    
    endloop
  endfacet
  facet normal   0.157410      0.938182     -0.308281    
    outer loop
      vertex    39.6698      -15.1081      -29.1117    
      vertex    33.8943      -12.3881      -23.7830    
      vertex    39.2883      -10.2482      -14.5165    
    endloop
  endfacet
  facet normal   0.324278      0.916370     -0.234754    
    outer loop
      vertex    53.9697      -21.2519      -39.9683    
      vertex    47.2455      -17.5646      -34.8633    
      vertex    54.2372      -16.9551      -22.8261    
    endloop
  endfacet
  facet normal   0.793236      0.603431     -0.815291E-01
    outer loop
      vertex    55.4572      -25.0457      -53.5752    
      vertex    47.4230      -14.2907      -52.1416    
      vertex    53.9697      -21.2519      -39.9683    
    endloop
  endfacet
  facet normal  -0.126836E-01  0.966040     -0.258079    
    outer loop
      vertex    23.1445      -14.3183      -30.4798    
      vertex    28.7332      -11.6656      -20.8249    
      vertex    33.8943      -12.3881      -23.7830    
    endloop
  endfacet
  facet normal   0.311210      0.950333      0.402287E-02
    outer loop
      vertex    32.5316      -12.7185      -41.4011    
      vertex    39.6698      -15.1081      -29.1117    
      vertex    47.2455      -17.5646      -34.8633    
    endloop
  endfacet
  facet normal   0.892509E-01 -0.995438     -0.337129E-01
    outer loop
      vertex    33.8943      -13.1930      -23.7830    
      vertex    27.1963      -13.4030      -35.3145    
      vertex    32.5316      -12.7185      -41.4011    
    endloop
  endfacet
  facet normal  -0.498388     -0.866411     -0.306649E-01
    outer loop
      vertex    53.9697      -22.0568      -39.9683    
      vertex    47.2455      -18.3695      -34.8633    
      vertex    39.7253      -13.5854      -47.8103    
    endloop
  endfacet
  facet normal  -0.403488     -0.595179      0.694953    
    outer loop
      vertex    53.9697      -22.0568      -39.9683    
      vertex    59.6673      -30.9702      -44.2940    
      vertex    64.8510      -26.0413      -37.0631    
    endloop
  endfacet
  facet normal  -0.157570     -0.965989      0.205029    
    outer loop
      vertex    39.6698      -15.9130      -29.1117    
      vertex    47.2455      -18.3695      -34.8633    
      vertex    54.2372      -16.9551      -22.8261    
    endloop
  endfacet
  facet normal   0.302657E-01 -0.957548      0.286681    
    outer loop
      vertex    28.7332      -12.4705      -20.8249    
      vertex    33.8943      -13.1930      -23.7830    
      vertex    39.2883      -10.2482      -14.5165    
    endloop
  endfacet
  facet normal   0.256862     -0.958785      0.121462    
    outer loop
      vertex    28.7332      -12.4705      -20.8249    
      vertex    33.8333      -9.99600      -12.0774    
      vertex    25.9854      -11.7592      -9.39920    
    endloop
  endfacet
  facet normal   0.176025E-02 -0.948810     -0.315842    
    outer loop
      vertex    12.2852      -11.7715      -17.6898    
      vertex    17.5064      -9.65590      -24.0161    
      vertex    22.2274      -12.3591      -15.8692    
    endloop
  endfacet
  facet normal   0.594102     -0.794678      0.124618    
    outer loop
      vertex    4.26800      -13.5159      -2.43220    
      vertex    4.06530      -13.7962      -3.25330    
      vertex    6.36420      -12.3552      -5.02390    
    endloop
  endfacet
  facet normal  -0.733549     -0.672726     -0.966735E-01
    outer loop
      vertex    55.4572      -25.0457      -53.5752    
      vertex    66.0132      -37.1975      -49.1119    
      vertex    59.6673      -30.9702      -44.2940    
    endloop
  endfacet
  facet normal  -0.835749     -0.548341      0.290852E-01
    outer loop
      vertex    55.4572      -25.0457      -53.5752    
      vertex    59.6673      -30.9702      -44.2940    
      vertex    53.9697      -22.0568      -39.9683    
    endloop
  endfacet
  facet normal  -0.300637     -0.869106     -0.392776    
    outer loop
      vertex    39.7253      -13.5854      -47.8103    
      vertex    47.4230      -14.2907      -52.1416    
      vertex    53.9697      -22.0568      -39.9683    
    endloop
  endfacet
  facet normal  -0.279189     -0.942062     -0.185940    
    outer loop
      vertex    32.5316      -12.7185      -41.4011    
      vertex    39.7253      -13.5854      -47.8103    
      vertex    47.2455      -18.3695      -34.8633    
    endloop
  endfacet
  facet normal  -0.419972     -0.907501      0.804207E-02
    outer loop
      vertex    32.5316      -12.7185      -41.4011    
      vertex    39.6698      -15.9130      -29.1117    
      vertex    33.8943      -13.1930      -23.7830    
    endloop
  endfacet
  facet normal   0.144406     -0.987322     -0.658971E-01
    outer loop
      vertex    23.1445      -14.3183      -30.4798    
      vertex    27.1963      -13.4030      -35.3145    
      vertex    33.8943      -13.1930      -23.7830    
    endloop
  endfacet
  facet normal  -0.585686     -0.807378      0.715017E-01
    outer loop
      vertex    17.5064      -9.65590      -24.0161    
      vertex    23.1445      -14.3183      -30.4798    
      vertex    22.2274      -12.3591      -15.8692    
    endloop
  endfacet
  facet normal  -0.388808E-01 -0.993360     -0.108282    
    outer loop
      vertex    22.2274      -12.3591      -15.8692    
      vertex    16.7586      -12.5313      -12.3258    
      vertex    12.2852      -11.7715      -17.6898    
    endloop
  endfacet
  facet normal  -0.729975E-01 -0.994123     -0.799381E-01
    outer loop
      vertex    12.2852      -11.7715      -17.6898    
      vertex    16.7586      -12.5313      -12.3258    
      vertex    6.36420      -12.3552      -5.02390    
    endloop
  endfacet
  facet normal   0.302755     -0.936915     -0.174728    
    outer loop
      vertex    6.36420      -12.3552      -5.02390    
      vertex    6.79960      -12.3543      -4.27430    
      vertex    4.26800      -13.5159      -2.43220    
    endloop
  endfacet
  facet normal   0.711303     -0.625195     -0.321214    
    outer loop
      vertex    4.26800      -13.5159      -2.43220    
      vertex    1.40140      -18.0685      0.809000E-01
      vertex   0.936500      -18.1452     -0.799300    
    endloop
  endfacet
  facet normal   0.375549E-01 -0.996953      0.683687E-01
    outer loop
      vertex    16.7586      -12.5313      -12.3258    
      vertex    20.4188      -11.9630      -6.04940    
      vertex    6.79960      -12.3543      -4.27430    
    endloop
  endfacet
  facet normal   0.662839E-01 -0.996345      0.538814E-01
    outer loop
      vertex    22.2274      -12.3591      -15.8692    
      vertex    25.9854      -11.7592      -9.39920    
      vertex    16.7586      -12.5313      -12.3258    
    endloop
  endfacet
  facet normal   0.369746E-01 -0.996795      0.709470E-01
    outer loop
      vertex    28.7332      -12.4705      -20.8249    
      vertex    25.9854      -11.7592      -9.39920    
      vertex    22.2274      -12.3591      -15.8692    
    endloop
  endfacet
  facet normal   0.616997E-01 -0.969252      0.238210    
    outer loop
      vertex    39.2883      -10.2482      -14.5165    
      vertex    33.8333      -9.99600      -12.0774    
      vertex    28.7332      -12.4705      -20.8249    
    endloop
  endfacet
  facet normal   0.290217     -0.889538      0.352840    
    outer loop
      vertex    39.6698      -15.9130      -29.1117    
      vertex    46.2563      -9.26620      -17.7721    
      vertex    39.2883      -10.2482      -14.5165    
    endloop
  endfacet
  facet normal  -0.315011     -0.727565      0.609440    
    outer loop
      vertex    54.2372      -16.9551      -22.8261    
      vertex    46.2563      -9.26620      -17.7721    
      vertex    39.6698      -15.9130      -29.1117    
    endloop
  endfacet
  facet normal   0.235797     -0.932428      0.273821    
    outer loop
      vertex    53.9697      -22.0568      -39.9683    
      vertex    60.6861      -17.2229      -29.2914    
      vertex    54.2372      -16.9551      -22.8261    
    endloop
  endfacet
  facet normal  -0.412207     -0.704179      0.578115    
    outer loop
      vertex    64.8510      -26.0413      -37.0631    
      vertex    60.6861      -17.2229      -29.2914    
      vertex    53.9697      -22.0568      -39.9683    
    endloop
  endfacet
  facet normal  -0.218189     -0.726487      0.651621    
    outer loop
      vertex    66.0132      -37.1975      -49.1119    
      vertex    64.8510      -26.0413      -37.0631    
      vertex    59.6673      -30.9702      -44.2940    
    endloop
  endfacet
  facet normal   0.811522     -0.584321     -0.865185E-03
    outer loop
      vertex   0.936500      -18.1452     -0.799300    
      vertex    4.06530      -13.7962      -3.25330    
      vertex    4.26800      -13.5159      -2.43220    
    endloop
  endfacet
  facet normal  -0.114320E-01 -0.999904      0.784105E-02
    outer loop
      vertex    6.79960      -12.3543      -4.27430    
      vertex    6.36420      -12.3552      -5.02390    
      vertex    16.7586      -12.5313      -12.3258    
    endloop
  endfacet
  facet normal   0.880882E-01 -0.986533      0.137818    
    outer loop
      vertex    23.1445      -14.3183      -30.4798    
      vertex    28.7332      -12.4705      -20.8249    
      vertex    22.2274      -12.3591      -15.8692    
    endloop
  endfacet
  facet normal   0.671934E-01 -0.996434      0.510374E-01
    outer loop
      vertex    25.9854      -11.7592      -9.39920    
      vertex    20.4188      -11.9630      -6.04940    
      vertex    16.7586      -12.5313      -12.3258    
    endloop
  endfacet
  facet normal  -0.107294     -0.927805      0.357302    
    outer loop
      vertex    39.2883      -10.2482      -14.5165    
      vertex    33.8943      -13.1930      -23.7830    
      vertex    39.6698      -15.9130      -29.1117    
    endloop
  endfacet
  facet normal  -0.291721     -0.915511      0.277018    
    outer loop
      vertex    54.2372      -16.9551      -22.8261    
      vertex    47.2455      -18.3695      -34.8633    
      vertex    53.9697      -22.0568      -39.9683    
    endloop
  endfacet
  facet normal  -0.797448     -0.601707      0.449947E-01
    outer loop
      vertex    53.9697      -22.0568      -39.9683    
      vertex    47.4230      -14.2907      -52.1416    
      vertex    55.4572      -25.0457      -53.5752    
    endloop
  endfacet
  facet normal  -0.222822E-01 -0.979470      0.200354    
    outer loop
      vertex    33.8943      -13.1930      -23.7830    
      vertex    28.7332      -12.4705      -20.8249    
      vertex    23.1445      -14.3183      -30.4798    
    endloop
  endfacet
  facet normal  -0.339998     -0.939268     -0.466676E-01
    outer loop
      vertex    47.2455      -18.3695      -34.8633    
      vertex    39.6698      -15.9130      -29.1117    
      vertex    32.5316      -12.7185      -41.4011    
    endloop
  endfacet
  facet normal   0.696542      0.356315      0.622791    
    outer loop
      vertex  -0.679500      -9.47260     -0.378600    
      vertex   -2.68640      -3.48990      -1.55690    
      vertex   -3.00270      -3.53210      -1.17900    
    endloop
  endfacet
  facet normal   0.241014     -0.109086     -0.964372    
    outer loop
      vertex  -0.679500      -9.47260     -0.378600    
      vertex   -3.16070      -3.69090      -1.65270    
      vertex   -2.68640      -3.48990      -1.55690    
    endloop
  endfacet
  facet normal   0.862922      0.356302      0.358349    
    outer loop
      vertex  -0.766400      -9.47260     -0.133300    
      vertex   -3.04950      -3.48990     -0.584000    
      vertex   -3.22360      -3.53210     -0.122800    
    endloop
  endfacet
  facet normal  -0.907058E-01 -0.109186     -0.989874    
    outer loop
      vertex  -0.766400      -9.47260     -0.133300    
      vertex   -3.52890      -3.69090     -0.517900    
      vertex   -3.04950      -3.48990     -0.584000    
    endloop
  endfacet
  facet normal   0.931472      0.356307     -0.735172E-01
    outer loop
      vertex  -0.743100      -9.47260      0.229900    
      vertex   -2.98130      -3.48990      0.867300    
      vertex   -2.92650      -3.53210       1.35710    
    endloop
  endfacet
  facet normal  -0.530993     -0.109123     -0.840321    
    outer loop
      vertex  -0.743100      -9.47260      0.229900    
      vertex   -3.37820      -3.69090       1.14420    
      vertex   -2.98130      -3.48990      0.867300    
    endloop
  endfacet
  facet normal   0.859328      0.356329     -0.366857    
    outer loop
      vertex  -0.631000      -9.47260      0.454900    
      vertex   -2.54920      -3.48990       1.77270    
      vertex   -2.34100      -3.53210       2.21940    
    endloop
  endfacet
  facet normal  -0.771141     -0.109084     -0.627249    
    outer loop
      vertex  -0.631000      -9.47260      0.454900    
      vertex   -2.83710      -3.69090       2.16160    
      vertex   -2.54920      -3.48990       1.77270    
    endloop
  endfacet
  facet normal   0.652158      0.356326     -0.669120    
    outer loop
      vertex  -0.407600      -9.47260      0.662600    
      vertex   -1.67150      -3.48990       2.61670    
      vertex   -1.30750      -3.53210       2.94900    
    endloop
  endfacet
  facet normal  -0.953099     -0.109147     -0.282294    
    outer loop
      vertex  -0.407600      -9.47260      0.662600    
      vertex   -1.78760      -3.69090       3.08640    
      vertex   -1.67150      -3.48990       2.61670    
    endloop
  endfacet
  facet normal   0.358415      0.356318     -0.862888    
    outer loop
      vertex  -0.133500      -9.47260      0.766300    
      vertex  -0.584600      -3.48990       3.04940    
      vertex  -0.123500      -3.53210       3.22350    
    endloop
  endfacet
  facet normal  -0.989917     -0.109112      0.903297E-01
    outer loop
      vertex  -0.133500      -9.47260      0.766300    
      vertex  -0.518700      -3.69090       3.52880    
      vertex  -0.584600      -3.48990       3.04940    
    endloop
  endfacet
  facet normal  -0.298266      0.356310     -0.885483    
    outer loop
      vertex   0.404000      -9.47260      0.664800    
      vertex    1.56740      -3.48990       2.68030    
      vertex    2.02910      -3.53210       2.50780    
    endloop
  endfacet
  facet normal  -0.685706     -0.109100      0.719656    
    outer loop
      vertex   0.404000      -9.47260      0.664800    
      vertex    1.93260      -3.69090       2.99780    
      vertex    1.56740      -3.48990       2.68030    
    endloop
  endfacet
  facet normal  -0.764550      0.356289     -0.537142    
    outer loop
      vertex   0.719200      -9.47260      0.296500    
      vertex    2.85010      -3.48990       1.23180    
      vertex    3.12010      -3.53210      0.819500    
    endloop
  endfacet
  facet normal  -0.126425     -0.109109      0.985957    
    outer loop
      vertex   0.719200      -9.47260      0.296500    
      vertex    3.33240      -3.69090       1.27140    
      vertex    2.85010      -3.48990       1.23180    
    endloop
  endfacet
  facet normal  -0.931443      0.356311     -0.738701E-01
    outer loop
      vertex   0.770100      -9.47260     -0.110100    
      vertex    3.08070      -3.48990     -0.387500    
      vertex    3.10360      -3.53210     -0.879800    
    endloop
  endfacet
  facet normal   0.392243     -0.109140      0.913364    
    outer loop
      vertex   0.770100      -9.47260     -0.110100    
      vertex    3.51610      -3.69090     -0.598500    
      vertex    3.08070      -3.48990     -0.387500    
    endloop
  endfacet
  facet normal  -0.844985      0.356303      0.398808    
    outer loop
      vertex   0.613500      -9.47260     -0.478300    
      vertex    2.48060      -3.48990      -1.86740    
      vertex    2.25580      -3.53210      -2.30600    
    endloop
  endfacet
  facet normal   0.794342     -0.109150      0.597584    
    outer loop
      vertex   0.613500      -9.47260     -0.478300    
      vertex    2.75360      -3.69090      -2.26700    
      vertex    2.48060      -3.48990      -1.86740    
    endloop
  endfacet
  facet normal  -0.458508      0.356314      0.814132    
    outer loop
      vertex   0.223700      -9.47260     -0.745000    
      vertex   0.943000      -3.48990      -2.95830    
      vertex   0.505900      -3.53210      -3.18600    
    endloop
  endfacet
  facet normal   0.993634     -0.109147      0.278888E-01
    outer loop
      vertex   0.223700      -9.47260     -0.745000    
      vertex   0.934500      -3.69090      -3.44210    
      vertex   0.943000      -3.48990      -2.95830    
    endloop
  endfacet
  facet normal  -0.992100E-01  0.356293      0.929093    
    outer loop
      vertex  -0.893000E-01  -9.47260     -0.772800    
      vertex  -0.304000      -3.48990      -3.09000    
      vertex  -0.795500      -3.53210      -3.12630    
    endloop
  endfacet
  facet normal   0.923712     -0.109085     -0.367229    
    outer loop
      vertex  -0.893000E-01  -9.47260     -0.772800    
      vertex  -0.503100      -3.69090      -3.53110    
      vertex  -0.304000      -3.48990      -3.09000    
    endloop
  endfacet
  facet normal   0.159793      0.356311      0.920602    
    outer loop
      vertex  -0.297900      -9.47260     -0.718600    
      vertex   -1.14050      -3.48990      -2.88790    
      vertex   -1.62310      -3.53210      -2.78780    
    endloop
  endfacet
  facet normal   0.787382     -0.109104     -0.606733    
    outer loop
      vertex  -0.297900      -9.47260     -0.718600    
      vertex   -1.45300      -3.69090      -3.25730    
      vertex   -1.14050      -3.48990      -2.88790    
    endloop
  endfacet
  facet normal  -0.927085     -0.289680     -0.237904    
    outer loop
      vertex  -0.297900      -9.47260     -0.718600    
      vertex   -1.62310      -3.53210      -2.78780    
      vertex   -1.45300      -3.69090      -3.25730    
    endloop
  endfacet
  facet normal  -0.156274      0.917079     -0.366804    
    outer loop
      vertex   -1.14050      -3.48990      -2.88790    
      vertex   -1.45300      -3.69090      -3.25730    
      vertex   -1.62310      -3.53210      -2.78780    
    endloop
  endfacet
  facet normal  -0.826222     -0.289646     -0.483180    
    outer loop
      vertex  -0.893000E-01  -9.47260     -0.772800    
      vertex  -0.795500      -3.53210      -3.12630    
      vertex  -0.503100      -3.69090      -3.53110    
    endloop
  endfacet
  facet normal  -0.495285E-01  0.917108     -0.395551    
    outer loop
      vertex  -0.304000      -3.48990      -3.09000    
      vertex  -0.503100      -3.69090      -3.53110    
      vertex  -0.795500      -3.53210      -3.12630    
    endloop
  endfacet
  facet normal  -0.567750     -0.289658     -0.770557    
    outer loop
      vertex   0.223700      -9.47260     -0.745000    
      vertex   0.505900      -3.53210      -3.18600    
      vertex   0.934500      -3.69090      -3.44210    
    endloop
  endfacet
  facet normal   0.110957      0.917077     -0.382959    
    outer loop
      vertex   0.943000      -3.48990      -2.95830    
      vertex   0.934500      -3.69090      -3.44210    
      vertex   0.505900      -3.53210      -3.18600    
    endloop
  endfacet
  facet normal  -0.174148E-01 -0.289619     -0.956984    
    outer loop
      vertex   0.613500      -9.47260     -0.478300    
      vertex    2.25580      -3.53210      -2.30600    
      vertex    2.75360      -3.69090      -2.26700    
    endloop
  endfacet
  facet normal   0.312001      0.917102     -0.248152    
    outer loop
      vertex    2.48060      -3.48990      -1.86740    
      vertex    2.75360      -3.69090      -2.26700    
      vertex    2.25580      -3.53210      -2.30600    
    endloop
  endfacet
  facet normal   0.460638     -0.289651     -0.838996    
    outer loop
      vertex   0.770100      -9.47260     -0.110100    
      vertex    3.10360      -3.53210     -0.879800    
      vertex    3.51610      -3.69090     -0.598500    
    endloop
  endfacet
  facet normal   0.394149      0.917068     -0.602764E-01
    outer loop
      vertex    3.08070      -3.48990     -0.387500    
      vertex    3.51610      -3.69090     -0.598500    
      vertex    3.10360      -3.53210     -0.879800    
    endloop
  endfacet
  facet normal   0.823099     -0.289657     -0.488475    
    outer loop
      vertex   0.719200      -9.47260      0.296500    
      vertex    3.12010      -3.53210      0.819500    
      vertex    3.33240      -3.69090       1.27140    
    endloop
  endfacet
  facet normal   0.370012      0.917091      0.148441    
    outer loop
      vertex    2.85010      -3.48990       1.23180    
      vertex    3.33240      -3.69090       1.27140    
      vertex    3.12010      -3.53210      0.819500    
    endloop
  endfacet
  facet normal   0.952532     -0.289653      0.937192E-01
    outer loop
      vertex   0.404000      -9.47260      0.664800    
      vertex    2.02910      -3.53210       2.50780    
      vertex    1.93260      -3.69090       2.99780    
    endloop
  endfacet
  facet normal   0.210347      0.917102      0.338642    
    outer loop
      vertex    1.56740      -3.48990       2.68030    
      vertex    1.93260      -3.69090       2.99780    
      vertex    2.02910      -3.53210       2.50780    
    endloop
  endfacet
  facet normal   0.655312     -0.289660      0.697613    
    outer loop
      vertex  -0.133500      -9.47260      0.766300    
      vertex  -0.123500      -3.53210       3.22350    
      vertex  -0.518700      -3.69090       3.52880    
    endloop
  endfacet
  facet normal  -0.646038E-01  0.917097      0.393396    
    outer loop
      vertex  -0.584600      -3.48990       3.04940    
      vertex  -0.518700      -3.69090       3.52880    
      vertex  -0.123500      -3.53210       3.22350    
    endloop
  endfacet
  facet normal   0.350680     -0.289646      0.890578    
    outer loop
      vertex  -0.407600      -9.47260      0.662600    
      vertex   -1.30750      -3.53210       2.94900    
      vertex   -1.78760      -3.69090       3.08640    
    endloop
  endfacet
  facet normal  -0.205563      0.917076      0.341636    
    outer loop
      vertex   -1.67150      -3.48990       2.61670    
      vertex   -1.78760      -3.69090       3.08640    
      vertex   -1.30750      -3.53210       2.94900    
    endloop
  endfacet
  facet normal  -0.187776E-01 -0.289647      0.956949    
    outer loop
      vertex  -0.631000      -9.47260      0.454900    
      vertex   -2.34100      -3.53210       2.21940    
      vertex   -2.83710      -3.69090       2.16160    
    endloop
  endfacet
  facet normal  -0.321090      0.917097      0.236294    
    outer loop
      vertex   -2.54920      -3.48990       1.77270    
      vertex   -2.83710      -3.69090       2.16160    
      vertex   -2.34100      -3.53210       2.21940    
    endloop
  endfacet
  facet normal  -0.322862     -0.289637      0.901039    
    outer loop
      vertex  -0.743100      -9.47260      0.229900    
      vertex   -2.92650      -3.53210       1.35710    
      vertex   -3.37820      -3.69090       1.14420    
    endloop
  endfacet
  facet normal  -0.379682      0.917104      0.121495    
    outer loop
      vertex   -2.98130      -3.48990      0.867300    
      vertex   -3.37820      -3.69090       1.14420    
      vertex   -2.92650      -3.53210       1.35710    
    endloop
  endfacet
  facet normal  -0.697516     -0.289675      0.655408    
    outer loop
      vertex  -0.766400      -9.47260     -0.133300    
      vertex   -3.22360      -3.53210     -0.122800    
      vertex   -3.52890      -3.69090     -0.517900    
    endloop
  endfacet
  facet normal  -0.393418      0.917087     -0.645991E-01
    outer loop
      vertex   -3.04950      -3.48990     -0.584000    
      vertex   -3.52890      -3.69090     -0.517900    
      vertex   -3.22360      -3.53210     -0.122800    
    endloop
  endfacet
  facet normal  -0.874599     -0.289649      0.388818    
    outer loop
      vertex  -0.679500      -9.47260     -0.378600    
      vertex   -3.00270      -3.53210      -1.17900    
      vertex   -3.16070      -3.69090      -1.65270    
    endloop
  endfacet
  facet normal  -0.350138      0.917090     -0.190653    
    outer loop
      vertex   -2.68640      -3.48990      -1.55690    
      vertex   -3.16070      -3.69090      -1.65270    
      vertex   -3.00270      -3.53210      -1.17900    
    endloop
  endfacet
  facet normal  -0.603032      0.749030     -0.274420    
    outer loop
      vertex   -3.72230      -2.89420      -4.27070    
      vertex   -4.44630      -3.58340      -4.56090    
      vertex   -4.16380      -3.04620      -3.71540    
    endloop
  endfacet
  facet normal  -0.858929     -0.250917      0.446410    
    outer loop
      vertex  -0.456600      -9.90210     -0.436000    
      vertex   -4.16380      -3.04620      -3.71540    
      vertex   -4.44630      -3.58340      -4.56090    
    endloop
  endfacet
  facet normal  -0.658697      0.749024      0.712821E-01
    outer loop
      vertex   -5.37930      -2.89420      -1.77700    
      vertex   -6.15010      -3.58340      -1.65770    
      vertex   -5.47610      -3.04620      -1.07430    
    endloop
  endfacet
  facet normal  -0.511425     -0.250905      0.821883    
    outer loop
      vertex  -0.615000      -9.90210     -0.142400    
      vertex   -5.47610      -3.04620      -1.07430    
      vertex   -6.15010      -3.58340      -1.65770    
    endloop
  endfacet
  facet normal  -0.535913      0.749005      0.389601    
    outer loop
      vertex   -5.55020      -2.89420       1.13560    
      vertex   -6.15940      -3.58340       1.62260    
      vertex   -5.28450      -3.04620       1.79330    
    endloop
  endfacet
  facet normal  -0.346589E-01 -0.250947      0.967380    
    outer loop
      vertex  -0.604300      -9.90210      0.182500    
      vertex   -5.28450      -3.04620       1.79330    
      vertex   -6.15940      -3.58340       1.62260    
    endloop
  endfacet
  facet normal  -0.204224      0.749026      0.630280    
    outer loop
      vertex   -3.82070      -2.89420       4.18290    
      vertex   -4.02700      -3.58340       4.93510    
      vertex   -3.21900      -3.04620       4.55850    
    endloop
  endfacet
  facet normal   0.540975     -0.250928      0.802733    
    outer loop
      vertex  -0.381400      -9.90210      0.503100    
      vertex   -3.21900      -3.04620       4.55850    
      vertex   -4.02700      -3.58340       4.93510    
    endloop
  endfacet
  facet normal   0.250316      0.749010      0.613454    
    outer loop
      vertex  -0.223200      -2.89420       5.66080    
      vertex   0.104200      -3.58340       6.36870    
      vertex   0.478900      -3.04620       5.55990    
    endloop
  endfacet
  facet normal   0.931114     -0.250904      0.264717    
    outer loop
      vertex   0.329000E-01  -9.90210      0.630500    
      vertex   0.478900      -3.04620       5.55990    
      vertex   0.104200      -3.58340       6.36870    
    endloop
  endfacet
  facet normal   0.599545      0.749037      0.281939    
    outer loop
      vertex    3.66840      -2.89420       4.31710    
      vertex    4.38870      -3.58340       4.61640    
      vertex    4.11680      -3.04620       3.76740    
    endloop
  endfacet
  facet normal   0.864457     -0.250910     -0.435612    
    outer loop
      vertex   0.451000      -9.90210      0.441700    
      vertex    4.11680      -3.04620       3.76740    
      vertex    4.38870      -3.58340       4.61640    
    endloop
  endfacet
  facet normal   0.644829      0.749012     -0.152237    
    outer loop
      vertex    5.55780      -2.89420       1.09790    
      vertex    6.30790      -3.58340      0.884200    
      vertex    5.56690      -3.04620      0.388600    
    endloop
  endfacet
  facet normal   0.405860     -0.250927     -0.878814    
    outer loop
      vertex   0.627900      -9.90210      0.652000E-01
      vertex    5.56690      -3.04620      0.388600    
      vertex    6.30790      -3.58340      0.884200    
    endloop
  endfacet
  facet normal   0.504853      0.749000     -0.429095    
    outer loop
      vertex    5.44830      -2.89420      -1.55270    
      vertex    6.01880      -3.58340      -2.08450    
      vertex    5.13350      -3.04620      -2.18840    
    endloop
  endfacet
  facet normal  -0.387425E-01 -0.250920     -0.967232    
    outer loop
      vertex   0.588800      -9.90210     -0.227800    
      vertex    5.13350      -3.04620      -2.18840    
      vertex    6.01880      -3.58340      -2.08450    
    endloop
  endfacet
  facet normal   0.253492      0.749006     -0.612153    
    outer loop
      vertex    4.14000      -2.89420      -3.86720    
      vertex    4.40510      -3.58340      -4.60070    
      vertex    3.56980      -3.04620      -4.28930    
    endloop
  endfacet
  facet normal  -0.475684     -0.250950     -0.843059    
    outer loop
      vertex   0.420000      -9.90210     -0.471300    
      vertex    3.56980      -3.04620      -4.28930    
      vertex    4.40510      -3.58340      -4.60070    
    endloop
  endfacet
  facet normal   0.603297E-01  0.749035     -0.659778    
    outer loop
      vertex    2.80500      -2.89420      -4.92200    
      vertex    2.84040      -3.58340      -5.70120    
      vertex    2.13530      -3.04620      -5.15580    
    endloop
  endfacet
  facet normal  -0.704595     -0.250914     -0.663768    
    outer loop
      vertex   0.261200      -9.90210     -0.574800    
      vertex    2.13530      -3.04620      -5.15580    
      vertex    2.84040      -3.58340      -5.70120    
    endloop
  endfacet
  facet normal  -0.178100      0.748985     -0.638202    
    outer loop
      vertex   0.872800      -2.89420      -5.59760    
      vertex   0.629000      -3.58340      -6.33840    
      vertex   0.163700      -3.04620      -5.57810    
    endloop
  endfacet
  facet normal  -0.894458     -0.250950     -0.370093    
    outer loop
      vertex   0.399000E-01  -9.90210     -0.630100    
      vertex   0.163700      -3.04620      -5.57810    
      vertex   0.629000      -3.58340      -6.33840    
    endloop
  endfacet
  facet normal  -0.415652      0.749007     -0.515967    
    outer loop
      vertex   -1.40850      -2.89420      -5.48730    
      vertex   -1.92500      -3.58340      -6.07170    
      vertex   -2.05220      -3.04620      -5.18940    
    endloop
  endfacet
  facet normal  -0.967920     -0.250909      0.132253E-01
    outer loop
      vertex  -0.212200      -9.90210     -0.594600    
      vertex   -2.05220      -3.04620      -5.18940    
      vertex   -1.92500      -3.58340      -6.07170    
    endloop
  endfacet
  facet normal   0.840932     -0.205852     -0.500459    
    outer loop
      vertex  -0.212200      -9.90210     -0.594600    
      vertex   -1.92500      -3.58340      -6.07170    
      vertex   -1.40850      -2.89420      -5.48730    
    endloop
  endfacet
  facet normal   0.223623      0.583334      0.780842    
    outer loop
      vertex  -0.212200      -9.90210     -0.594600    
      vertex   -1.40850      -2.89420      -5.48730    
      vertex   -2.05220      -3.04620      -5.18940    
    endloop
  endfacet
  facet normal   0.970202     -0.205874     -0.127763    
    outer loop
      vertex   0.399000E-01  -9.90210     -0.630100    
      vertex   0.629000      -3.58340      -6.33840    
      vertex   0.872800      -2.89420      -5.59760    
    endloop
  endfacet
  facet normal  -0.102886      0.583335      0.805689    
    outer loop
      vertex   0.399000E-01  -9.90210     -0.630100    
      vertex   0.872800      -2.89420      -5.59760    
      vertex   0.163700      -3.04620      -5.57810    
    endloop
  endfacet
  facet normal   0.952277     -0.205872      0.225356    
    outer loop
      vertex   0.261200      -9.90210     -0.574800    
      vertex    2.84040      -3.58340      -5.70120    
      vertex    2.80500      -2.89420      -4.92200    
    endloop
  endfacet
  facet normal  -0.382539      0.583331      0.716512    
    outer loop
      vertex   0.261200      -9.90210     -0.574800    
      vertex    2.80500      -2.89420      -4.92200    
      vertex    2.13530      -3.04620      -5.15580    
    endloop
  endfacet
  facet normal   0.842422     -0.205896      0.497927    
    outer loop
      vertex   0.420000      -9.90210     -0.471300    
      vertex    4.40510      -3.58340      -4.60070    
      vertex    4.14000      -2.89420      -3.86720    
    endloop
  endfacet
  facet normal  -0.577959      0.583340      0.570682    
    outer loop
      vertex   0.420000      -9.90210     -0.471300    
      vertex    4.14000      -2.89420      -3.86720    
      vertex    3.56980      -3.04620      -4.28930    
    endloop
  endfacet
  facet normal   0.522519     -0.205906      0.827392    
    outer loop
      vertex   0.588800      -9.90210     -0.227800    
      vertex    6.01880      -3.58340      -2.08450    
      vertex    5.44830      -2.89420      -1.55270    
    endloop
  endfacet
  facet normal  -0.774670      0.583337      0.244139    
    outer loop
      vertex   0.588800      -9.90210     -0.227800    
      vertex    5.44830      -2.89420      -1.55270    
      vertex    5.13350      -3.04620      -2.18840    
    endloop
  endfacet
  facet normal   0.884955E-01 -0.205869      0.974570    
    outer loop
      vertex   0.627900      -9.90210      0.652000E-01
      vertex    6.30790      -3.58340      0.884200    
      vertex    5.55780      -2.89420       1.09790    
    endloop
  endfacet
  facet normal  -0.800884      0.583339     -0.135282    
    outer loop
      vertex   0.627900      -9.90210      0.652000E-01
      vertex    5.55780      -2.89420       1.09790    
      vertex    5.56690      -3.04620      0.388600    
    endloop
  endfacet
  facet normal  -0.536947     -0.205897      0.818104    
    outer loop
      vertex   0.451000      -9.90210      0.441700    
      vertex    4.38870      -3.58340       4.61640    
      vertex    3.66840      -2.89420       4.31710    
    endloop
  endfacet
  facet normal  -0.542887      0.583339     -0.604143    
    outer loop
      vertex   0.451000      -9.90210      0.441700    
      vertex    3.66840      -2.89420       4.31710    
      vertex    4.11680      -3.04620       3.76740    
    endloop
  endfacet
  facet normal  -0.949069     -0.205879      0.238499    
    outer loop
      vertex   0.329000E-01  -9.90210      0.630500    
      vertex   0.104200      -3.58340       6.36870    
      vertex  -0.223200      -2.89420       5.66080    
    endloop
  endfacet
  facet normal   0.956821E-02  0.583333     -0.812176    
    outer loop
      vertex   0.329000E-01  -9.90210      0.630500    
      vertex  -0.223200      -2.89420       5.66080    
      vertex   0.478900      -3.04620       5.55990    
    endloop
  endfacet
  facet normal  -0.879186     -0.205837     -0.429724    
    outer loop
      vertex  -0.381400      -9.90210      0.503100    
      vertex   -4.02700      -3.58340       4.93510    
      vertex   -3.82070      -2.89420       4.18290    
    endloop
  endfacet
  facet normal   0.531017      0.583335     -0.614606    
    outer loop
      vertex  -0.381400      -9.90210      0.503100    
      vertex   -3.82070      -2.89420       4.18290    
      vertex   -3.21900      -3.04620       4.55850    
    endloop
  endfacet
  facet normal  -0.458301     -0.205858     -0.864629    
    outer loop
      vertex  -0.604300      -9.90210      0.182500    
      vertex   -6.15940      -3.58340       1.62260    
      vertex   -5.55020      -2.89420       1.13560    
    endloop
  endfacet
  facet normal   0.790946      0.583340     -0.184715    
    outer loop
      vertex  -0.604300      -9.90210      0.182500    
      vertex   -5.55020      -2.89420       1.13560    
      vertex   -5.28450      -3.04620       1.79330    
    endloop
  endfacet
  facet normal   0.327152E-01 -0.205885     -0.978029    
    outer loop
      vertex  -0.615000      -9.90210     -0.142400    
      vertex   -6.15010      -3.58340      -1.65770    
      vertex   -5.37930      -2.89420      -1.77700    
    endloop
  endfacet
  facet normal   0.777985      0.583340      0.233352    
    outer loop
      vertex  -0.615000      -9.90210     -0.142400    
      vertex   -5.37930      -2.89420      -1.77700    
      vertex   -5.47610      -3.04620      -1.07430    
    endloop
  endfacet
  facet normal   0.526617     -0.205916     -0.824787    
    outer loop
      vertex  -0.456600      -9.90210     -0.436000    
      vertex   -4.44630      -3.58340      -4.56090    
      vertex   -3.72230      -2.89420      -4.27070    
    endloop
  endfacet
  facet normal   0.550420      0.583334      0.597293    
    outer loop
      vertex  -0.456600      -9.90210     -0.436000    
      vertex   -3.72230      -2.89420      -4.27070    
      vertex   -4.16380      -3.04620      -3.71540    
    endloop
  endfacet
  facet normal   0.700413      0.710009      0.728667E-01
    outer loop
      vertex   -7.91510      -2.97120     -0.121600    
      vertex   -1.26720      -9.53600     -0.558000E-01
      vertex   -7.83050      -2.94310      -1.20860    
    endloop
  endfacet
  facet normal  -0.229696     -0.384966     -0.893891    
    outer loop
      vertex   -1.26720      -9.53600     -0.558000E-01
      vertex   -8.49490      -3.65450     -0.731500    
      vertex   -7.83050      -2.94310      -1.20860    
    endloop
  endfacet
  facet normal   0.694224      0.710015     -0.118037    
    outer loop
      vertex   -7.65660      -2.97120       2.01030    
      vertex   -1.23550      -9.53600      0.286900    
      vertex   -7.86720      -2.94310      0.940700    
    endloop
  endfacet
  facet normal  -0.461463     -0.384914     -0.799308    
    outer loop
      vertex   -1.23550      -9.53600      0.286900    
      vertex   -8.37890      -3.65450       1.57870    
      vertex   -7.86720      -2.94310      0.940700    
    endloop
  endfacet
  facet normal   0.605946      0.710008     -0.358773    
    outer loop
      vertex   -6.42950      -2.97120       4.61790    
      vertex   -1.05100      -9.53600      0.710200    
      vertex   -7.00910      -2.94310       3.69460    
    endloop
  endfacet
  facet normal  -0.717018     -0.384914     -0.581143    
    outer loop
      vertex   -1.05100      -9.53600      0.710200    
      vertex   -7.25850      -3.65450       4.47350    
      vertex   -7.00910      -2.94310       3.69460    
    endloop
  endfacet
  facet normal   0.489520      0.710011     -0.506216    
    outer loop
      vertex   -4.97970      -2.97120       6.15360    
      vertex  -0.825800      -9.53600      0.962800    
      vertex   -5.78280      -2.94310       5.41640    
    endloop
  endfacet
  facet normal  -0.845161     -0.384947     -0.370835    
    outer loop
      vertex  -0.825800      -9.53600      0.962800    
      vertex   -5.81730      -3.65450       6.23350    
      vertex   -5.78280      -2.94310       5.41640    
    endloop
  endfacet
  facet normal   0.271531      0.710012     -0.649733    
    outer loop
      vertex   -2.39680      -2.97120       7.54450    
      vertex  -0.418500      -9.53600       1.19740    
      vertex   -3.41330      -2.94310       7.15040    
    endloop
  endfacet
  facet normal  -0.922159     -0.384984     -0.375485E-01
    outer loop
      vertex  -0.418500      -9.53600       1.19740    
      vertex   -3.14780      -3.65450       7.92390    
      vertex   -3.41330      -2.94310       7.15040    
    endloop
  endfacet
  facet normal  -0.151479      0.710014     -0.687702    
    outer loop
      vertex    2.37830      -2.97120       7.55040    
      vertex   0.346300      -9.53600       1.22020    
      vertex    1.32010      -2.94310       7.81250    
    endloop
  endfacet
  facet normal  -0.776041     -0.384924      0.499594    
    outer loop
      vertex   0.346300      -9.53600       1.22020    
      vertex    1.98210      -3.65450       8.29270    
      vertex    1.32010      -2.94310       7.81250    
    endloop
  endfacet
  facet normal  -0.528501      0.710013     -0.465368    
    outer loop
      vertex    6.37920      -2.97120       4.68720    
      vertex    1.00020      -9.53600      0.780000    
      vertex    5.68020      -2.94310       5.52390    
    endloop
  endfacet
  facet normal  -0.330959     -0.384986      0.861540    
    outer loop
      vertex    1.00020      -9.53600      0.780000    
      vertex    6.49810      -3.65450       5.52020    
      vertex    5.68020      -2.94310       5.52390    
    endloop
  endfacet
  facet normal  -0.626670      0.710010     -0.321202    
    outer loop
      vertex    7.33570      -2.97120       2.97520    
      vertex    1.16130      -9.53600      0.510200    
      vertex    6.86380      -2.94310       3.95800    
    endloop
  endfacet
  facet normal  -0.109042     -0.384959      0.916470    
    outer loop
      vertex    1.16130      -9.53600      0.510200    
      vertex    7.65570      -3.65450       3.75340    
      vertex    6.86380      -2.94310       3.95800    
    endloop
  endfacet
  facet normal  -0.704127      0.710010     -0.958238E-02
    outer loop
      vertex    7.89400      -2.97120     -0.591300    
      vertex    1.26710      -9.53600     -0.585000E-01
      vertex    7.90750      -2.94310      0.498800    
    endloop
  endfacet
  facet normal   0.309205     -0.384941      0.869605    
    outer loop
      vertex    1.26710      -9.53600     -0.585000E-01
      vertex    8.52620      -3.65450     -0.361000E-01
      vertex    7.90750      -2.94310      0.498800    
    endloop
  endfacet
  facet normal  -0.615398      0.710010      0.342304    
    outer loop
      vertex    6.55140      -2.97120      -4.44340    
      vertex    1.06970      -9.53600     -0.681700    
      vertex    7.10590      -2.94310      -3.50480    
    endloop
  endfacet
  facet normal   0.701140     -0.384931      0.600193    
    outer loop
      vertex    1.06970      -9.53600     -0.681700    
      vertex    7.37610      -3.65450      -4.27670    
      vertex    7.10590      -2.94310      -3.50480    
    endloop
  endfacet
  facet normal  -0.442932      0.710012      0.547444    
    outer loop
      vertex    4.41700      -2.97120      -6.56920    
      vertex   0.737600      -9.53600      -1.03190    
      vertex    5.28210      -2.94310      -5.90570    
    endloop
  endfacet
  facet normal   0.874598     -0.384971      0.294747    
    outer loop
      vertex   0.737600      -9.53600      -1.03190    
      vertex    5.24430      -3.65450      -6.72270    
      vertex    5.28210      -2.94310      -5.90570    
    endloop
  endfacet
  facet normal  -0.317365      0.710010      0.628622    
    outer loop
      vertex    2.93040      -2.97120      -7.35370    
      vertex   0.503100      -9.53600      -1.16440    
      vertex    3.91610      -2.94310      -6.88780    
    endloop
  endfacet
  facet normal   0.917120     -0.384946      0.103473    
    outer loop
      vertex   0.503100      -9.53600      -1.16440    
      vertex    3.70670      -3.65450      -7.67840    
      vertex    3.91610      -2.94310      -6.88780    
    endloop
  endfacet
  facet normal   0.178825E-01  0.710015      0.703959    
    outer loop
      vertex  -0.898100      -2.97120      -7.86500    
      vertex  -0.107800      -9.53600      -1.26380    
      vertex   0.190700      -2.94310      -7.92100    
    endloop
  endfacet
  facet normal   0.856900     -0.384962     -0.342822    
    outer loop
      vertex  -0.107800      -9.53600      -1.26380    
      vertex  -0.367900      -3.65450      -8.51840    
      vertex   0.190700      -2.94310      -7.92100    
    endloop
  endfacet
  facet normal   0.259335      0.710014      0.654695    
    outer loop
      vertex   -3.55290      -2.97120      -7.07400    
      vertex  -0.536600      -9.53600      -1.14930    
      vertex   -2.55010      -2.94310      -7.50170    
    endloop
  endfacet
  facet normal   0.686302     -0.384970     -0.617080    
    outer loop
      vertex  -0.536600      -9.53600      -1.14930    
      vertex   -3.28030      -3.65450      -7.87000    
      vertex   -2.55010      -2.94310      -7.50170    
    endloop
  endfacet
  facet normal   0.419046      0.710012      0.565935    
    outer loop
      vertex   -5.25360      -2.97120      -5.92150    
      vertex  -0.814300      -9.53600     -0.972500    
      vertex   -4.39460      -2.94310      -6.59280    
    endloop
  endfacet
  facet normal   0.504450     -0.384929     -0.772891    
    outer loop
      vertex  -0.814300      -9.53600     -0.972500    
      vertex   -5.19500      -3.65450      -6.76090    
      vertex   -4.39460      -2.94310      -6.59280    
    endloop
  endfacet
  facet normal   0.594940      0.710014      0.376731    
    outer loop
      vertex   -7.03540      -2.97120      -3.62870    
      vertex   -1.11020      -9.53600     -0.613400    
      vertex   -6.47630      -2.94310      -4.56460    
    endloop
  endfacet
  facet normal   0.191763     -0.384971     -0.902787    
    outer loop
      vertex   -1.11020      -9.53600     -0.613400    
      vertex   -7.28350      -3.65450      -4.43270    
      vertex   -6.47630      -2.94310      -4.56460    
    endloop
  endfacet
  facet normal  -0.725860     -0.397207      0.561564    
    outer loop
      vertex   -1.11020      -9.53600     -0.613400    
      vertex   -7.03540      -2.97120      -3.62870    
      vertex   -7.28350      -3.65450      -4.43270    
    endloop
  endfacet
  facet normal  -0.648061      0.667266     -0.367113    
    outer loop
      vertex   -6.47630      -2.94310      -4.56460    
      vertex   -7.28350      -3.65450      -4.43270    
      vertex   -7.03540      -2.97120      -3.62870    
    endloop
  endfacet
  facet normal  -0.879519     -0.397257      0.261980    
    outer loop
      vertex  -0.814300      -9.53600     -0.972500    
      vertex   -5.25360      -2.97120      -5.92150    
      vertex   -5.19500      -3.65450      -6.76090    
    endloop
  endfacet
  facet normal  -0.472065      0.667258     -0.576126    
    outer loop
      vertex   -4.39460      -2.94310      -6.59280    
      vertex   -5.19500      -3.65450      -6.76090    
      vertex   -5.25360      -2.97120      -5.92150    
    endloop
  endfacet
  facet normal  -0.917320     -0.397243      0.268524E-01
    outer loop
      vertex  -0.536600      -9.53600      -1.14930    
      vertex   -3.55290      -2.97120      -7.07400    
      vertex   -3.28030      -3.65450      -7.87000    
    endloop
  endfacet
  facet normal  -0.307960      0.667219     -0.678217    
    outer loop
      vertex   -2.55010      -2.94310      -7.50170    
      vertex   -3.28030      -3.65450      -7.87000    
      vertex   -3.55290      -2.97120      -7.07400    
    endloop
  endfacet
  facet normal  -0.870400     -0.397250     -0.290855    
    outer loop
      vertex  -0.107800      -9.53600      -1.26380    
      vertex  -0.898100      -2.97120      -7.86500    
      vertex  -0.367900      -3.65450      -8.51840    
    endloop
  endfacet
  facet normal  -0.554232E-01  0.667256     -0.742763    
    outer loop
      vertex   0.190700      -2.94310      -7.92100    
      vertex  -0.367900      -3.65450      -8.51840    
      vertex  -0.898100      -2.97120      -7.86500    
    endloop
  endfacet
  facet normal  -0.629129     -0.397276     -0.668108    
    outer loop
      vertex   0.503100      -9.53600      -1.16440    
      vertex    2.93040      -2.97120      -7.35370    
      vertex    3.70670      -3.65450      -7.67840    
    endloop
  endfacet
  facet normal   0.302656      0.667251     -0.680570    
    outer loop
      vertex    3.91610      -2.94310      -6.88780    
      vertex    3.70670      -3.65450      -7.67840    
      vertex    2.93040      -2.97120      -7.35370    
    endloop
  endfacet
  facet normal  -0.473918     -0.397251     -0.785871    
    outer loop
      vertex   0.737600      -9.53600      -1.03190    
      vertex    4.41700      -2.97120      -6.56920    
      vertex    5.24430      -3.65450      -6.72270    
    endloop
  endfacet
  facet normal   0.439528      0.667242     -0.601335    
    outer loop
      vertex    5.28210      -2.94310      -5.90570    
      vertex    5.24430      -3.65450      -6.72270    
      vertex    4.41700      -2.97120      -6.56920    
    endloop
  endfacet
  facet normal  -0.146000     -0.397249     -0.906023    
    outer loop
      vertex    1.06970      -9.53600     -0.681700    
      vertex    6.55140      -2.97120      -4.44340    
      vertex    7.37610      -3.65450      -4.27670    
    endloop
  endfacet
  facet normal   0.632383      0.667229     -0.393570    
    outer loop
      vertex    7.10590      -2.94310      -3.50480    
      vertex    7.37610      -3.65450      -4.27670    
      vertex    6.55140      -2.97120      -4.44340    
    endloop
  endfacet
  facet normal   0.324510     -0.397249     -0.858421    
    outer loop
      vertex    1.26710      -9.53600     -0.585000E-01
      vertex    7.89400      -2.97120     -0.591300    
      vertex    8.52620      -3.65450     -0.361000E-01
    endloop
  endfacet
  facet normal   0.744373      0.667241     -0.264181E-01
    outer loop
      vertex    7.90750      -2.94310      0.498800    
      vertex    8.52620      -3.65450     -0.361000E-01
      vertex    7.89400      -2.97120     -0.591300    
    endloop
  endfacet
  facet normal   0.671910     -0.397239     -0.625090    
    outer loop
      vertex    1.16130      -9.53600      0.510200    
      vertex    7.33570      -2.97120       2.97520    
      vertex    7.65570      -3.65450       3.75340    
    endloop
  endfacet
  facet normal   0.678699      0.667261      0.306805    
    outer loop
      vertex    6.86380      -2.94310       3.95800    
      vertex    7.65570      -3.65450       3.75340    
      vertex    7.33570      -2.97120       2.97520    
    endloop
  endfacet
  facet normal   0.804953     -0.397235     -0.440744    
    outer loop
      vertex    1.00020      -9.53600      0.780000    
      vertex    6.37920      -2.97120       4.68720    
      vertex    6.49810      -3.65450       5.52020    
    endloop
  endfacet
  facet normal   0.582476      0.667260      0.464205    
    outer loop
      vertex    5.68020      -2.94310       5.52390    
      vertex    6.49810      -3.65450       5.52020    
      vertex    6.37920      -2.97120       4.68720    
    endloop
  endfacet
  facet normal   0.909833     -0.397265      0.119931    
    outer loop
      vertex   0.346300      -9.53600       1.22020    
      vertex    2.37830      -2.97120       7.55040    
      vertex    1.98210      -3.65450       8.29270    
    endloop
  endfacet
  facet normal   0.195722      0.667238      0.718670    
    outer loop
      vertex    1.32010      -2.94310       7.81250    
      vertex    1.98210      -3.65450       8.29270    
      vertex    2.37830      -2.97120       7.55040    
    endloop
  endfacet
  facet normal   0.675349     -0.397247      0.621369    
    outer loop
      vertex  -0.418500      -9.53600       1.19740    
      vertex   -2.39680      -2.97120       7.54450    
      vertex   -3.14780      -3.65450       7.92390    
    endloop
  endfacet
  facet normal  -0.253155      0.667206      0.700534    
    outer loop
      vertex   -3.41330      -2.94310       7.15040    
      vertex   -3.14780      -3.65450       7.92390    
      vertex   -2.39680      -2.97120       7.54450    
    endloop
  endfacet
  facet normal   0.402714     -0.397226      0.824641    
    outer loop
      vertex  -0.825800      -9.53600      0.962800    
      vertex   -4.97970      -2.97120       6.15360    
      vertex   -5.81730      -3.65450       6.23350    
    endloop
  endfacet
  facet normal  -0.490885      0.667240      0.560199    
    outer loop
      vertex   -5.78280      -2.94310       5.41640    
      vertex   -5.81730      -3.65450       6.23350    
      vertex   -4.97970      -2.97120       6.15360    
    endloop
  endfacet
  facet normal   0.170336     -0.397226      0.901774    
    outer loop
      vertex   -1.05100      -9.53600      0.710200    
      vertex   -6.42950      -2.97120       4.61790    
      vertex   -7.25850      -3.65450       4.47350    
    endloop
  endfacet
  facet normal  -0.621500      0.667282      0.410454    
    outer loop
      vertex   -7.00910      -2.94310       3.69460    
      vertex   -7.25850      -3.65450       4.47350    
      vertex   -6.42950      -2.97120       4.61790    
    endloop
  endfacet
  facet normal  -0.163773     -0.397240      0.902983    
    outer loop
      vertex   -1.23550      -9.53600      0.286900    
      vertex   -7.65660      -2.97120       2.01030    
      vertex   -8.37890      -3.65450       1.57870    
    endloop
  endfacet
  facet normal  -0.727274      0.667262      0.160727    
    outer loop
      vertex   -7.86720      -2.94310      0.940700    
      vertex   -8.37890      -3.65450       1.57870    
      vertex   -7.65660      -2.97120       2.01030    
    endloop
  endfacet
  facet normal  -0.400449     -0.397242      0.825736    
    outer loop
      vertex   -1.26720      -9.53600     -0.558000E-01
      vertex   -7.91510      -2.97120     -0.121600    
      vertex   -8.49490      -3.65450     -0.731500    
    endloop
  endfacet
  facet normal  -0.743681      0.667299     -0.406295E-01
    outer loop
      vertex   -7.83050      -2.94310      -1.20860    
      vertex   -8.49490      -3.65450     -0.731500    
      vertex   -7.91510      -2.97120     -0.121600    
    endloop
  endfacet
  facet normal  -0.570508     -0.786552      0.236340    
    outer loop
      vertex  -0.602900      -9.55120      0.000000E+00
      vertex   0.000000E+00  -9.98850      0.000000E+00
      vertex  -0.426300      -9.55120      0.426300    
    endloop
  endfacet
  facet normal  -0.236340     -0.786552     -0.570508    
    outer loop
      vertex   0.000000E+00  -9.55120     -0.602900    
      vertex   0.000000E+00  -9.98850      0.000000E+00
      vertex  -0.426300      -9.55120     -0.426300    
    endloop
  endfacet
  facet normal   0.570508     -0.786552     -0.236340    
    outer loop
      vertex   0.602900      -9.55120      0.000000E+00
      vertex   0.000000E+00  -9.98850      0.000000E+00
      vertex   0.426300      -9.55120     -0.426300    
    endloop
  endfacet
  facet normal   0.570588      0.786484      0.236373    
    outer loop
      vertex   0.602900       2.35400      0.000000E+00
      vertex   0.000000E+00   2.79140      0.000000E+00
      vertex   0.426300       2.35400      0.426300    
    endloop
  endfacet
  facet normal   0.236373      0.786484     -0.570588    
    outer loop
      vertex   0.000000E+00   2.35400     -0.602900    
      vertex   0.000000E+00   2.79140      0.000000E+00
      vertex   0.426300       2.35400     -0.426300    
    endloop
  endfacet
  facet normal  -0.570588      0.786484     -0.236373    
    outer loop
      vertex  -0.602900       2.35400      0.000000E+00
      vertex   0.000000E+00   2.79140      0.000000E+00
      vertex  -0.426300       2.35400     -0.426300    
    endloop
  endfacet
  facet normal  -0.236373      0.786484      0.570588    
    outer loop
      vertex   0.000000E+00   2.35400      0.602900    
      vertex   0.000000E+00   2.79140      0.000000E+00
      vertex  -0.426300       2.35400      0.426300    
    endloop
  endfacet
  facet normal   0.894413      0.250601      0.370437    
    outer loop
      vertex    1.32410      -2.17730       1.32410    
      vertex    1.87250      -2.17730      0.000000E+00
      vertex   0.602900       2.35400      0.000000E+00
    endloop
  endfacet
  facet normal   0.370437      0.250601     -0.894413    
    outer loop
      vertex    1.32410      -2.17730      -1.32410    
      vertex   0.000000E+00  -2.17730      -1.87250    
      vertex   0.000000E+00   2.35400     -0.602900    
    endloop
  endfacet
  facet normal  -0.894413      0.250601     -0.370437    
    outer loop
      vertex   -1.32410      -2.17730      -1.32410    
      vertex   -1.87250      -2.17730      0.000000E+00
      vertex  -0.602900       2.35400      0.000000E+00
    endloop
  endfacet
  facet normal  -0.370437      0.250601      0.894413    
    outer loop
      vertex   -1.32410      -2.17730       1.32410    
      vertex   0.000000E+00  -2.17730       1.87250    
      vertex   0.000000E+00   2.35400      0.602900    
    endloop
  endfacet
  facet normal   0.923894      0.000000E+00  0.382648    
    outer loop
      vertex    1.87250      -5.01980      0.000000E+00
      vertex    1.87250      -2.17730      0.000000E+00
      vertex    1.32410      -2.17730       1.32410    
    endloop
  endfacet
  facet normal   0.382648      0.000000E+00 -0.923894    
    outer loop
      vertex   0.000000E+00  -5.01980      -1.87250    
      vertex   0.000000E+00  -2.17730      -1.87250    
      vertex    1.32410      -2.17730      -1.32410    
    endloop
  endfacet
  facet normal  -0.923894      0.000000E+00 -0.382648    
    outer loop
      vertex   -1.87250      -5.01980      0.000000E+00
      vertex   -1.87250      -2.17730      0.000000E+00
      vertex   -1.32410      -2.17730      -1.32410    
    endloop
  endfacet
  facet normal  -0.382648      0.000000E+00  0.923894    
    outer loop
      vertex   0.000000E+00  -5.01980       1.87250    
      vertex   0.000000E+00  -2.17730       1.87250    
      vertex   -1.32410      -2.17730       1.32410    
    endloop
  endfacet
  facet normal   0.236340     -0.786552      0.570508    
    outer loop
      vertex   0.000000E+00  -9.55120      0.602900    
      vertex   0.000000E+00  -9.98850      0.000000E+00
      vertex   0.426300      -9.55120      0.426300    
    endloop
  endfacet
  facet normal  -0.894381     -0.250611      0.370508    
    outer loop
      vertex  -0.602900      -9.55120      0.000000E+00
      vertex  -0.426300      -9.55120      0.426300    
      vertex   -1.32410      -5.01980       1.32410    
    endloop
  endfacet
  facet normal  -0.370508     -0.250611     -0.894381    
    outer loop
      vertex   0.000000E+00  -9.55120     -0.602900    
      vertex  -0.426300      -9.55120     -0.426300    
      vertex   -1.32410      -5.01980      -1.32410    
    endloop
  endfacet
  facet normal   0.894381     -0.250611     -0.370508    
    outer loop
      vertex   0.602900      -9.55120      0.000000E+00
      vertex   0.426300      -9.55120     -0.426300    
      vertex    1.32410      -5.01980      -1.32410    
    endloop
  endfacet
  facet normal   0.370508     -0.250611      0.894381    
    outer loop
      vertex   0.000000E+00  -9.55120      0.602900    
      vertex   0.426300      -9.55120      0.426300    
      vertex    1.32410      -5.01980       1.32410    
    endloop
  endfacet
  facet normal   0.894387     -0.250588      0.370511    
    outer loop
      vertex   0.426300      -9.55120      0.426300    
      vertex   0.602900      -9.55120      0.000000E+00
      vertex    1.87250      -5.01980      0.000000E+00
    endloop
  endfacet
  facet normal   0.370511     -0.250588     -0.894387    
    outer loop
      vertex   0.426300      -9.55120     -0.426300    
      vertex   0.000000E+00  -9.55120     -0.602900    
      vertex   0.000000E+00  -5.01980      -1.87250    
    endloop
  endfacet
  facet normal  -0.894387     -0.250588     -0.370511    
    outer loop
      vertex  -0.426300      -9.55120     -0.426300    
      vertex  -0.602900      -9.55120      0.000000E+00
      vertex   -1.87250      -5.01980      0.000000E+00
    endloop
  endfacet
  facet normal  -0.370511     -0.250588      0.894387    
    outer loop
      vertex  -0.426300      -9.55120      0.426300    
      vertex   0.000000E+00  -9.55120      0.602900    
      vertex   0.000000E+00  -5.01980       1.87250    
    endloop
  endfacet
  facet normal   0.382648      0.000000E+00  0.923894    
    outer loop
      vertex    1.32410      -5.01980       1.32410    
      vertex    1.32410      -2.17730       1.32410    
      vertex   0.000000E+00  -2.17730       1.87250    
    endloop
  endfacet
  facet normal  -0.923894      0.000000E+00  0.382648    
    outer loop
      vertex   -1.32410      -5.01980       1.32410    
      vertex   -1.32410      -2.17730       1.32410    
      vertex   -1.87250      -2.17730      0.000000E+00
    endloop
  endfacet
  facet normal  -0.382648      0.000000E+00 -0.923894    
    outer loop
      vertex   -1.32410      -5.01980      -1.32410    
      vertex   -1.32410      -2.17730      -1.32410    
      vertex   0.000000E+00  -2.17730      -1.87250    
    endloop
  endfacet
  facet normal   0.923894      0.000000E+00 -0.382648    
    outer loop
      vertex    1.32410      -5.01980      -1.32410    
      vertex    1.32410      -2.17730      -1.32410    
      vertex    1.87250      -2.17730      0.000000E+00
    endloop
  endfacet
  facet normal   0.236373      0.786484      0.570588    
    outer loop
      vertex   0.426300       2.35400      0.426300    
      vertex   0.000000E+00   2.79140      0.000000E+00
      vertex   0.000000E+00   2.35400      0.602900    
    endloop
  endfacet
  facet normal  -0.894412      0.250608      0.370437    
    outer loop
      vertex   -1.87250      -2.17730      0.000000E+00
      vertex   -1.32410      -2.17730       1.32410    
      vertex  -0.426300       2.35400      0.426300    
    endloop
  endfacet
  facet normal  -0.370437      0.250608     -0.894412    
    outer loop
      vertex   0.000000E+00  -2.17730      -1.87250    
      vertex   -1.32410      -2.17730      -1.32410    
      vertex  -0.426300       2.35400     -0.426300    
    endloop
  endfacet
  facet normal   0.894412      0.250608     -0.370437    
    outer loop
      vertex    1.87250      -2.17730      0.000000E+00
      vertex    1.32410      -2.17730      -1.32410    
      vertex   0.426300       2.35400     -0.426300    
    endloop
  endfacet
  facet normal   0.370437      0.250608      0.894412    
    outer loop
      vertex   0.000000E+00  -2.17730       1.87250    
      vertex    1.32410      -2.17730       1.32410    
      vertex   0.426300       2.35400      0.426300    
    endloop
  endfacet
  facet normal  -0.570588      0.786484      0.236373    
    outer loop
      vertex  -0.426300       2.35400      0.426300    
      vertex   0.000000E+00   2.79140      0.000000E+00
      vertex  -0.602900       2.35400      0.000000E+00
    endloop
  endfacet
  facet normal  -0.236373      0.786484     -0.570588    
    outer loop
      vertex  -0.426300       2.35400     -0.426300    
      vertex   0.000000E+00   2.79140      0.000000E+00
      vertex   0.000000E+00   2.35400     -0.602900    
    endloop
  endfacet
  facet normal   0.570588      0.786484     -0.236373    
    outer loop
      vertex   0.426300       2.35400     -0.426300    
      vertex   0.000000E+00   2.79140      0.000000E+00
      vertex   0.602900       2.35400      0.000000E+00
    endloop
  endfacet
  facet normal   0.570508     -0.786552      0.236340    
    outer loop
      vertex   0.426300      -9.55120      0.426300    
      vertex   0.000000E+00  -9.98850      0.000000E+00
      vertex   0.602900      -9.55120      0.000000E+00
    endloop
  endfacet
  facet normal   0.236340     -0.786552     -0.570508    
    outer loop
      vertex   0.426300      -9.55120     -0.426300    
      vertex   0.000000E+00  -9.98850      0.000000E+00
      vertex   0.000000E+00  -9.55120     -0.602900    
    endloop
  endfacet
  facet normal  -0.570508     -0.786552     -0.236340    
    outer loop
      vertex  -0.426300      -9.55120     -0.426300    
      vertex   0.000000E+00  -9.98850      0.000000E+00
      vertex  -0.602900      -9.55120      0.000000E+00
    endloop
  endfacet
  facet normal  -0.236340     -0.786552      0.570508    
    outer loop
      vertex  -0.426300      -9.55120      0.426300    
      vertex   0.000000E+00  -9.98850      0.000000E+00
      vertex   0.000000E+00  -9.55120      0.602900    
    endloop
  endfacet
endsolid MYSOLID
```
