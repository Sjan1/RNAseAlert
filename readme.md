<head>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

<link rel="stylesheet" type="text/css" href="my_css.css">
</head>
<body>
<div id = "container">

# RNAse Alert Assay
This project is part of an attempt to repeat SHERLOCK protocol [Kellner at al (2019) Nature protocols](https://) in TSL. It started as a side project carried out during Corona virus lockdown.

## Overall Experimental strategy

1. RNAseAlet kit test 
2. Test with of and synthetic RNA
3. Use Isothermal amplification (SHERLOCK)
4. Test with a real sample

---

## Results

All the data are shared on GitHub [here](https://github.com/Sjan1/RNAseAlert)

[Link to experimental details - pipetting spreadsheet](https://github.com/Sjan1/RNAseAlert/tree/master/data)

---
<br/>
### Direct links to the results

#### RNAseAlert test
Spectrofluorimeter, 96-well format

#### Test 01: [Test of the old kit](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test01.html) 
The old kit is dead!
#### Test 02: [Fresh substrate works](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test02.html)
New substrate works!
#### Test 03: [DEPC inhibitor works](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test03.html)
DEPC inhibition works!

#### Test with Cas13a

#### Test 04: [Cas13 with guide and target RNA](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test04.html)
This did not work, repeat it with minor changes.
#### Test 05: [Repeat: Cas13 with guide and target RNA](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test05_RNA.html)
This did not work either.
#### Test 06: [New batch of Cas13 with guide and target DNA](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test06_DNA.html)
#### Test 06-2 benzoase: [New batch of Cas13 with guide and target DNA - benzoase treated and remeasured](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test06_DNA_Benz.html)
Something is wrong with the detection assay. We need to test the substrate and buffer, possible other components.
#### Test 07 substrate: [Test of different substrate batches in RNAaseAlert assay](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test07_Substrate.html)
Clearly we have to use more of substrate than is stated in Kellner's protocol. is our spectrofluorimeter working well?
#### Test 07-2 buffer: [Test of different buffers in RNAaseAlert assay only](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test07-2_Buffer.html)
Yes, buffer has influence on the assay. Again, is spectrofluorimeter all right?
#### Test 08-1: [Test of DNA target](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test08_DNA.html)
#### Test 08-2: [Test of DNA target 24h later](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test08_DNA.html)
#### Test 08-3: [Test of DNA target 24h later benzoase control](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test08_DNA.html)
Something must be fundamentally wrong.
#### Test 09-1: [Test of Cas13 purification stages-  quick and dirty](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test09_Cas13_initial.html)

#### Test 09-2: [Test of Cas13 purification stages - all with replicates](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test09-2_Cas13_all.html)
Yes, the protein is the problem. 

Sequencing of the original plasmid revealed, that an incorrect protein was expressed. When we rectify the problem, the next test should be decisive.

#### Test 11-2: [New "correct" Cas13a](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test11-2_correctCas13.html)
Partial success!!

#### Test 12: [Fluorescein test](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test12_Fluorescein.html)

We have a sensitivity issue with our plate reader or 
general set up such as plate type, volume, settings.

#### Test 13: [Orf1ab dilutions in 384-well plate](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test13_Orf1ab_Dilutions.html)

It starts to look good, despite the sensitivity is still not what they publish.

#### Test 18: [Josie #4, 200819](http://htmlpreview.github.io/?https://github.com/Sjan1/RNAseAlert/blob/master/S01_test18_Josie_200819.html)

Trying to find quantitative variable - gradient vs. sum of all data points. 

<br/><br/>


</div>
</body>