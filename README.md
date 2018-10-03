# distance_between_2D_line_segments
There are many urls posting standard equations (from geometry or linear algebra) to calculate distance between lines, however these equations can have failure cases for vertical lines or offset segments. The calculations can also fail due to precision (segments very far from the origin suffer precision error).

This set of functions seeks to robustly calculate minimum distance between 2 line segments.

Intermediate functions including 'distance from point to segment' and 'distance from point to infinite line' are also exposed.
