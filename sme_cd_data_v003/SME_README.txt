Draft, Uncontrolled, Unofficial  Set of Matrix Examples 

At the most basic level, object grouping can be divided into three types. The first 
type of object interface grouping focuses the interfaces along the matrix diagonal. 
The second type of object interface grouping focuses the interfaces in the lower 
triangular section of the matrix. The third type of object interface grouping 
focuses the interfaces in the upper triangular section of the matrix. These three 
basic types are the first to be addressed by the standard matrix example set.

Each standard matrix has a size N, establishing an N by N square matrix. Each 
standard matrix has a specific number of connections. The “percent-full” gives an 
indication of the matrix interface density. “Percent-full” is found by dividing 
the number of specific interface relations in the matrix, by the number of possible 
relational interface that could exist. A matrix that is 100 percent full will not 
respond well to many types of analysis and evaluation. As described in the working 
paper, a matrix with a minimum number of interfaces (N-1) is also expected to 
perform poorly under many types of analysis and evaluation. The best results for 
automated analysis and evaluation are expected from matrices that have a 
percent-full rating of around 20 to 40 percent. One use being made of the set of 
standard matrix examples is testing of these expectations.

Assuming a matrix that has an object (or named entity) in each cell along the 
diagonal, the remaining matrix cells can have an entry in each row or there can 
be rows in the matrix with no entries. This basic difference in matrix structure 
(empty rows or no empty rows) also impacts matrix methods and evaluation 
approaches. The first set of standard examples addresses matrices with an object 
along the diagonal, and rows that have at least one entry in each row.

A naming convention has been developed to clearly identify each type of standard 
matrix. Each matrix name has the following components:

Name base for standard matrix example, SME, Analysis type, for example: 
grouping-diagonal:CD, grouping-upper-triangular:CU, grouping-lower-triangular:CL

Matrix size N, for example: 16, Interface percent-full, for example: 20 percent, 20P

Empty rows or no empty rows: no empty rows, NER 

Configuration type, ordered or disordered, for example disordered, DO

This results in a complete name of SME_CD_16_20P_NER_DO

The first set of standard matrix examples will be developed for the following sizes:

9x9, 16 x 16, 25 x 25, 36 x 36, 49 x 49, 64 x 64, 81 x 81, 100 x 100, 121 x 121, 144 x 144

The minimum interface percent-full is:
9 x 9 = 8/72 = 11.1 percent
16 x 16 = 15/240 = 6.25 percent 
25 x 25 = 24/600 = 4.0 percent 
36 x 36 = 35/1260 = 2.8 percent 
49 x 49 = 48/2352 = 2.0 percent 
64 x 64 = 63/4032 = 1.6 percent 
81 x 81 = 80/6480 = 1.3 percent 
100 x 100 = 99/9900 = 1.0 percent 
121 x 121 = 120/14520 = 0.8 percent 
144 x 144 = 143/20592 = 0.7 percent

The complete set of standard matrix examples is composed of the following 
percent-full interface values for each matrix size:
5 percent (except for 9 x 9 and 16 x 16 based on the previous “minimum 
interface full values”) 
10 percent (except for 9 x 9 based on the previous “minimum interface full values”) 
15 percent 
20 percent
25 percent
30 percent 
35 percent 
40 percent 
45 percent 
50 percent

Each size of matrix will have an example for each of the percent-full interface 
values. The complete set of standard examples for the described diagonal grouping 
is then approximately 100 matrix pairs (one base and one grouped or partitioned), 
for a total of 200 matrices. In a similar fashion the upper triangular will have 
200 matrices and the lower triangular grouping example sets will have 200 matrices. 
This comprises a total of around 600 matrices for the complete basic standard 
matrix set with no empty rows.

When matrices with empty rows are added to the above basic standard set, the 
expanded standard matrix set contains 1200 matrices. If the static and time-based 
matrix representations are addressed, that would create a standard matrix example 
set of 2400 matrices.

These matrices will be developed, published and discussed in an incremental 
fashion to encourage the development, comparison and discussion of common, 
verifiable matrix clustering algorithms and methods. The smaller-sized matrices 
are expected to perform well at all listed percent-full values. The larger 
matrices may not perform well at the higher percent-full values; and smaller 
percent values may need to be generated.

SHA 256 check sums for the incuded files:

SME_CD_09_20P_NER_DO_V003.txt:
d91197a233e5f2310c8cc600314acced82449fd9fa608a2ea64cfef2b4f31aee

SME_CD_09_25P_NER_DO_V003.txt:
dd9e4c17ee3954c7ee742bf1d687292723da7f150658af0f02dc6f5f3d6dce0b

SME_CD_09_30P_NER_DO_V003.txt:
e6089ee40fbeb4d625d421c547ae27e8d4e15197f21cbbadb0b498342bffa2f0

SME_CD_09_35P_NER_DO_V003.txt
6a36fc1cb73ad10f48d9338f9ae1239eb6edf3d45415cd0e90d0801ab41a3907

SME_CD_09_40P_NER_DO_V003.txt
abbd526cd26c6eec918b5c25773367c017789260f4d291767807ecf186de8876

SME_CD_09_45P_NER_DO_V003.txt:
d97fe4edb23bd198214614f884e9388a89b3aad04143061a9e9cc0c1910b4614

SME_CD_09_50P_NER_DO_V003.txt:
bf7600f57962fbd5b3331272c6c5cf697a7a010d688bb2d2f96fdaba37804366

SME_CD_16_20P_NER_DO_V003.txt:
e2fae3c4449a384ac7fca92fb52ad3fe51c695cc770d6c03d0d32b4329b2ac26

SME_CD_16_25P_NER_DO_V003.txt:
66b823fb51080883c5ba920e885375753d8e3cb248c53d0e6e89b02d6ad5b88a

SME_CD_16_30P_NER_DO_V003.txt:
66b61313376b94eca1949061021dae434793faeda4501ff049aa1413fb27f2a0

SME_CD_16_35P_NER_DO_V003.txt:
9c09f0f9616d3b543af574468cabb065845a6fcdd002ae18fabb404827ae5f30

SME_CD_16_40P_NER_DO_V003.txt:
0f81322991af3e2f1ef1433cfecc68b0c72db4500d6868fc07adcaa7de38ac21

SME_CD_16_45P_NER_DO_V003.txt:
74ead204ce1d40bd9a79fd4c25ecf61a903e455670cf49adafe748565945c4ec

SME_CD_16_50P_NER_DO_V003.txt:
00014bd2dec7bf8300752985b84b8f0131f3874bc9d8499cc1a42f29cebbd89d

SME_CD_25_20P_NER_DO_V003.txt:
2c610d07c186ffab1a921d30663e48402679004d6588a1e0d5d81fe9f9a6b5d8

SME_CD_25_25P_NER_DO_V003.txt:
772df442af4fdbeec68dab9556045ed2cbb8d4f6bde7c0a98030972b83c2370c

SME_CD_25_30P_NER_DO_V003.txt:
4a7b0451e5734bf0b6e7bc062aa7ef10749db2cff644a846a441024eed8b6ae9

SME_CD_25_35P_NER_DO_V003.txt:
0944dfe023d9b17129d8435fc47ee3bcc4ae0d813e9b559735429482e4efcd82

SME_CD_25_40P_NER_DO_V003.txt:
cc28e4e8b75324334172cec6a0b5d8980afdbd5e83da3f9693382fc079b2b8b4

SME_CD_25_45P_NER_DO_V003.txt:
4a7e10e07ad07476425a239f9150665ca0a2a2ee9d73818d2e96f5eba7c5b236

SME_CD_25_50P_NER_DO_V003.txt:
c25d96c27887e65ee3cab17bead9ecf01f529e32e5b8142491b0577ca6a44150

SME_CD_36_20P_NER_DO_V003.txt:
68b96d6e92f883ee2976eba2ee3bb8ca79a11bcd7702f556f88a8c25046cfc3d

SME_CD_36_25P_NER_DO_V003.txt:
26cad9058dd77ad0c58dd79754e7bfe4d94f289746c244f3dd0c87e4570b7ba5

SME_CD_36_30P_NER_DO_V003.txt:
619c4f761ea9cbb4ea067eae915f0ce3e314cdde1e1ca03abff6961d7e6311c7

SME_CD_36_40P_NER_DO_V003.txt:
b955f87a9b559d30f417ac113db6b8ae28f6f75573178db9a468a62b694c2adf

SME_CD_36_45P_NER_DO_V003.txt:
838878f7ca910f2d26b31af158e1bf842e7590715b8f5859543558340914817c

SME_CD_36_50P_NER_DO_V003.txt:
4935f814ebc3eae29d580c711a0505e294b69f29a7c0189178793185dd78dc33

SME_CD_49_20P_NER_DO_V003.txt:
e5695aed7b095c347adc5aeb412b0afb7d24793bea024227231a984a4126e476

SME_CD_49_25P_NER_DO_V003.txt:
1fba7f5a367604c73689a3ec1d51a4ca18525f4f943ee77b1ba6262d276c4756

SME_CD_49_30P_NER_DO_V003.txt:
d0117e89b9127cfc1628e2de50c345395b82f330b05a720deec654fa9fe738f5

SME_CD_49_35P_NER_DO_V003.txt:
cd480cdb9c51a579072b8a256c4334eb58e197c876a3feac359fea218d686224

SME_CD_49_40P_NER_DO_V003.txt:
86cb6bf936f0ddeeabe2511e0336653ce044fcf7d1b099b8afe1ce07460b8fb8

SME_CD_49_45P_NER_DO_V003.txt:
11f8e5609838bbaf5c6228ff47a2b7ab4bccd3af68f905bb5a163132546edd3f

SME_CD_49_50P_NER_DO_V003.txt:
cc8a9cfa5d2028be357e198598eede13e23127f07535b25658ed32311c54d06a

SME_CD_64_20P_NER_DO_V003.txt:
db6c962ccead8afc40cdd9a2ac60764d4e6e57af463f95a2d4e2d9b4d0dde954

SME_CD_64_25P_NER_DO_V003.txt:
6abf4180e3886bdc8ad68ce855079f5b8cdfe0d932ae0c562a49d38f18bf6124

SME_CD_64_30P_NER_DO_V003.txt:
44be0fbb64c02de0d3a4dfad45a81177dd469adff2c1bc5c98409cce6d3b504f

SME_CD_64_35P_NER_DO_V003.txt:
692a81de76ab7fd1dad538903fcf84ec599eff8b949e404e552671870146ffd4

SME_CD_64_40P_NER_DO_V003.txt:
762a0289fa928507ddace0f734dbd8f610b5689d5999f7f294889ed48f8d02c9

SME_CD_64_45P_NER_DO_V003.txt:
9cfac686bf6871bef398d95a503636aca2d2c7e5e63312d90877b7199a409dbe

SME_CD_64_50P_NER_DO_V003.txt:
e2aedc58e305ebe0a11114767ad5c294775643739e7272f9bb53f52e694dd8be






