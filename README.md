# DartGameSimulation
About Dart Game : consider a square and a circle in the center of the square which side of the square and the diameter of the
circle are 2 units and the circle's center is in (0,0). Hit happens when output is a point inside the circle so (x^2)+(y^2)<1 
or in the edge of the circle which (x^2)+(y^2)=1 , and hit is not happened if output is a point inside the square but not in
the circle and so (x^2)+(y^2)>1 !
0 <= random.random < 1    ---> *2
0*2 <= random.random *2 < 1*2   ---> 0 <= 2* random.random < 2 ---> -1 
0-1 <= 2*random.random -1 < 2-1 ---> -1 <= 2r-1 < 1
