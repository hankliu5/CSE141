all: mm blockmm object_of_arrays array_of_objects 

mm: mm.c
	gcc -O3 mm.c -o mm 

blockmm: blockmm.c 
	gcc -O3 blockmm.c -o blockmm 

object_of_arrays: object_of_arrays.c
	gcc -O3 object_of_arrays.c -o object_of_arrays

array_of_objects: array_of_objects.c
	gcc -O3 array_of_objects.c -o array_of_objects

clean:
		rm -f blockmm mm object_of_arrays array_of_objects  