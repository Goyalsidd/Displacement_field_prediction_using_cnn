# Displacement_field_prediction_using_cnn

I consider a beam configuration with circular holes with a single point load of
known magnitude at the top right end of the beam.
Then generated the random topologies of the beam by altering the number, position, and size of the holes in a random manner. 
I was given a data file and extracted prop files, displacement files and load files using the commands in linux. Now, using 500 displacement files (like displacement1, displacement2,..,) as y(output) with each file having 1681 rows and 3 columns, and 1 load file which we have to use 500 times and 500 property files (like prop1,prop2,...) with each prop file having 361 rows as inputs, now I uploaded these files using loop and train a cnn model predicting the displacement of elements of a cantilever beam given the load position(node element), properties of each element, load conditions.

I have also added some of these files in the repository as well.
