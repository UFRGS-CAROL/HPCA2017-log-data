Log files are organized as follow. Each line starting with #SDC depicts one execution with errors, the next lines starting with #ERR describe incorrect elements (integer or float values) of that faulty execution.

All #SDC lines have the following format: #SDC <date>;<execution information>;<number of incorrect elements>
Execution information can contain the input dimension, command line arguments, the number of repeated iterations or any useful information to re-execute the algorithm.
The Number of incorrect elements informs how many elements, and thus, how many #ERR lines will follow the #SDC line.

For #ERR lines, the element position will be enclosed in brackets. For example, [15, 9] informs that the elements are in row 15 and column 9. For LavaMD, the algorithm organized the 3D space in a single dimension
n vector. Thus, the element's position will have only one dimension. #ERR lines will also have a value informed as 'r' which is the value read after the error, and another value reported as 'e' which is the expected value in a correct execution.

Then, for example:
#ERR p [43,455] r: 255.058823529 e: 184.941176471
The line above informs that an element in row 43 and column 455 is incorrect. The incorrect value is 255.058823529 while the correct and expected value should be 184.941176471

For LavaMD, each vector position holds 4 elements, thus, each #ERR line will have 8 values with the 'r' and 'e' value for each element. For example:
#ERR p: [296413], ea: 1, v_r: 1.5706956787109375e+03, v_e: 1.5706956787109375e+03, x_r: -1.8865548706054688e+02, x_e: -1.8865548706054688e+02, y_r: -5.2588836669921875e+02, y_e: -5.2588836669921875e+02, z_r: 7.3376892089843750e+01, z_e: 7.3376831054687500e+01
shows the v, x, y, and z value with the 'r' and 'e' values.

