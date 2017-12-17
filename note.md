# Multiple View Geometry in Computer Vision

## Chatpter 1 Introduction -- a Tour of Multiple View Ceometry

### 1.1 Introduction - the ubiquitous(无处不在的) projective Geometry
- Properties of geometry that are preserved by projective transfromations
    - Only straightness preserves(this is the most general requirement on the mapping)
    - Not shape
    - Not length
    - Not angles
    - Not distance
    - Not ratios of distances

- Euclidean Geometry
    - It describes angles and shapes of objects.
    - It is troublesome in one major respect such as intersection of lines.
        + add a concept **ideal points** at which parallel lines will meets
        + After adding these points the Euclidean plane will be the **projective space**
- **Coordinates**
    - A point in Euclidean 2 - space is represented by an ordered pair of real number (x, y)
    - A point in projective space is represented by an ordered pair of real number (x, y, 1)
    - **Homogeneous coordinates of the point**: two points are equivalent when they differ by a common multiple, such as (kx, ky, k) is equivalent to (x, y, 1).***if k equals 0, then the point at infinity arise***
    - points at infinity in the two-dimensional projective space form a line, usually called the **lien at inifnity**,in 3-dimensions, they will form the **plane at infinity**

- **Homogeneity**
    - In Euclidean geometry, all points are the same. There is no distinguished point. The whole of the space is homogeneous, even the origin.
    - When the space itself translating（just means **moving**）**and rotating** to a different position. The resulting operation is known as a **Euclidenan transform**
    - The space moving, rotating and finally stretching linearly possibly by different ratios in different directions. The resulting transformation is known as an **affine transforamtion(仿射变换)**
  
