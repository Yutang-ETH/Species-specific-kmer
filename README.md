# Species-specific-kmer  
![image](https://github.com/user-attachments/assets/b717101e-55ad-4893-94f4-e494f58f9c5c)  
![image](https://github.com/user-attachments/assets/23c40a26-ab49-40f1-98ff-d281fb8924cc)  
```
What I have done:
1. obtain shared k-mers from three Lolium multiflorum (L. m) haplotype-reoslved genome assemblies
2. obtain shared k-mers from four Lolium perenne (L. p) haplotype-reoslved genome assemblies
3. compare above two sets of k-mers to get L. m specific k-mers and L. p specific k-mers
4. count these L. m and L. p specific k-mers in 10 L. p genotypes and 25 L. m genotypes that have high coverage whole-genome short-read sequencing data
5. take the number of L. m specific k-mers as the x coordinate and the number of L. p specific k-mers as the y coordinate, visualize these genotypes. Clearly it can be seen that L. p and L. m genotypes are separated 
6. further obtain the common L. m specific k-mers found in all 25 L. m genotypes, name this set as L. m specific core set
7. further obtain the common L. p specific k-mers found in all 10 L. p genotypes, name this set as L. p specific core set
8. align L.m and L.p core sets to genome assembly Kyuss v2.0 (L. p) to find their positions in Kyuss genome

In the above first image, the left panel corresponds to step 1-4, the right panel corresponds to the step 5
The second image shows an example of a genic locus where both L. m specific and L. p specific core sets are aligned to the assembly. Blue indicates L. p core k-mers, red indicates L. m core k-mers 
```
