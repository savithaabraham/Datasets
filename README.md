# Datasets
Dataset of 161 word problems from kinematics domain.
Each word problem annotated with equations required to solve it (lEquations), spans from word problem that has information about value of kinematics parameter (for eg. span_hv has spans associated with parameter horizontal velocity), and type of problem (5 types - 0 to 4).
Each instance has the followings slots:
lEquations - equations used to solve the problem

lSolutions - the solution, that is value of the queried parameter (annotated only for a few problems),
span_hv - has all the spans from word problem that gives information about the parameter horizontal velocity,
span_ha - has all the spans from word problem that gives information about the parameter horizontal acceleration,
span_hp - has all the spans from word problem that gives information about the parameter horizontal position,
span_vp - has all the spans from word problem that gives information about the parameter vertical position,
span_vv - has all the spans from word problem that gives information about the parameter vertical velocity,
span_va - has all the spans from word problem that gives information about the parameter vertical acceleration,
span_t - has all the spans from word problem that gives information about time,
span_angle - has all the spans from word problem that gives information about angle of projection,
span_velocity - has all the spans from word problem that gives information about the resultant velocity,
type - gives the category to which problem belongs. Has one of {0,1,2,3,4} as value, type 0 - horizontal motion, type 1 - vertical 
motion with velocity, type 2 - free fall, type 3 - horizontally projected from a height, type 5 - 2D motion. 

