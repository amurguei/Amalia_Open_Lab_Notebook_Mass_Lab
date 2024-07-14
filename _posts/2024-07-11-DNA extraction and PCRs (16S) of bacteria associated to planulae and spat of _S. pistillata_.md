## Trial protocols and results from DNA extraction, PCR and electrophoresis for 16S microbiome sequencing.  

Using the [Zymo Quick-DNA/RNA Miniprep Plus Kit ](https://zymoresearch.eu/collections/quick-dna-rna-kits/products/quick-dna-rna-miniprep-plus-kit) on _Stylophora pistillata_ planulae and spat to extract associated bacterial DNA and further microbiome analysis. This post is based on  [fscucchia's](https://github.com/fscucchia) [protocol](https://github.com/fscucchia/FScucchia_Lab_Notebook-Mass_Lab/blob/master/_posts/2020-12-09-DNA-RNA-extraction-with-Zymo-kit.md). Unless specified, all steps took place in the [Mass lab](https://mass-lab.github.io/Open_Lab_Notebook_Mass_Lab/), University of Haifa. PCR, Gel preparation and electrophoresis were based on Mass Lab protocols kept by [Rachel Bober](https://github.com/RachelBober).

## Reagents preparation
1. Add 96 mL 100% ethanol (104 mL 95% ethanol) to the 24 mL DNA/RNA Wash Buffer concentrate before use. DNA/RNA Wash Buffer included with D7003T (Mini Prep Plus Kit) is supplied ready-to-use and does not require the addition of ethanol prior to use. Check kit contents and instructions to confirm prep steps.
2. Reconstitute the lyophilized (freeze-dried) DNase prior to use. Mix by inversion. Store frozen aliquots.
_Note: I ommited this steps, since everything was ready for use in the kit_.

## Notes on the samples (planulae and spat)
For this protocol, cryo vials grouping 10-15 planulae or 5-11 spats were used. After collection, they had been frozen with liquid nitrogen and stored at -80°C. The samples came from the 2023 field season for the BSF Climate Solutions grant, I used the following samples: 
Sample 1. 15/04/23. Swim 15 planula. Single colony. 
Sample 2. 11/04/23. Swim. 
Sample 26. 15/04/23. Swim. 
Sample 4. 11/04/23. 11 spat.
Sample 5. 11/04/23. Spat. 1 day old. 
Sample 6. 15/04/23. 5 spats. days. 

## Sample preparation

1. Take samples from -80°C freezer.
1. Add 500μl of  DNA/RNA shield new 2 ml Eppendorf tubes. 
2. Allow samples to de-freeze and transfer each to one of the 2 ml Eppendorf tube. 
3. Put samples into a disruptor genie for 15 mins at 2000 rpm with 0.25 ml beads. 
4. Proceed to DNA extraction steps. 

## DNA extraction
1. Set up and label yellow DNA spin colums and collection tubes. 
2. Add a volume equal to the sample to (600μl in my case here) of lysis buffer to each sample tube.
3. Also add 30μl of proteinase K and 60μl of PK DB. 
4. Finger flick to mix tubes.
5. Add 700μl (total volume) of sample gently to the yellow DNA spin column. 
6. Centrifuge at 16000 rcf (g) for 30 seconds. 
7. **Important** Save the flow through from this step: transfer to a new 1.5 ml tube labelled for RNA. 
8. Add 400μl DNA/RNA Prep Buffer gently to the yellow DNA spin column. 
9. Centrifuge at 16000 rcf (g) for 30 seconds. 
10. Discard flow through (Zymo kit waste).
11. Add 700μl DNA/RNA wash buffer gently to the yellow DNA spin columns. 
12. Centrifuge at 16,000 rcf (g) for 30 seconds
13. Discard flow through (Zymo kit waste)
14. Add 400 µl DNA/RNA Wash Buffer genetly to the yellow DNA spin columns
15. Centrifuge at 16,000 rcf (g) for 2 minutes
16. Discard flow through (Zymo kit waste)
17. Transfer yellow columns to new 1.5mL microcentrifuge tubes
18. Add 50 µl DNA/RNA-free water to each yellow DNA column by dripping slowly directly on the filter
19. Incubate at room temp for 5 minutes.
20. Centrifuge at 16,000 rcf (g) for 30 seconds.
21. Repeat steps 18-20 for a final elution volume of 100µl.
22. Label tubes, store at 4°C if quantifying the same day or the next (Nanodrop), if waiting longer store in -20°C.

### DNA extraction results (nano-drop or microplate reader)

I checked my DNA extraction results at the microplate reader in the Luzzatto Knaan lab with two drops per sample for my extraction products. Since the DNA extraction was successful, I continued with the 16S PCR.

| Sample        | 260/280 | ng/µL   |
|---------------|---------|---------|
| A (blank)     |         |         |
| B (sample 1)  | 1.885   | 30.915  |
|               | 1.855   | 32.435  |
| C (sample 2)  | 1.847   | 21.739  |
|               | 1.857   | 22.057  |
| D (sample 26) | 1.849   | 50.043  |
|               | 1.808   | 83.029  |
| E (sample 4)  | 1.831   | 11.678  |
|               | 1.739   | 28.775  |
| F (sample 5)  | 1.858   | 76.195  |
|               | 1.851   | 78.868  |
| G (sample 6)  | 1.87    | 19.889  |
|               | 1.727   | 36.437  |


## PCR

### Dilution of gDNA samples for PCR
1. Take out DNA extraction products from -20CC (or -4), if relevant.
2. Put them on ice until defrozen.
3. Mark new eppendorf tubes "1:10 gDNA + sample number" (this was determined due to the concentration of the DNA in my samples).
4. Add 90µl H20-RNA free to new tubes. 
5. Add 10µl of gDNA from the sample to new tubes. 
6. Mix gently (didn't vortex).

### Primers

- **Forward primer (926F for 16S)**
- ACACTGACGACATGGTTCTCAAGTGYC
- TM: 70.8°C.
- MW: 12599.7
- **Reverse primer (926F for 16S)** 
- TACGGTAGCAGAGACTTGGTCTCCGY
- TM: 65.3°C.
- MW: 12905.4
**Note**: Primers were diluted from their original concentration of 100µM (240 µl) to 10µM (10 µl of primer + 90µl of RNA-DNA free water) before use.


### GoTaq® Green Master Mix reaction setup for a 50µl volume 

For a 50µl reaction volume:

| Component                   | 1X Rec. Volume | 7.5X Rec. Volume | Final Conc.   |
|-----------------------------|----------------|------------------|---------------|
| GoTaq® Green Master Mix, 2X | 25µl           | 187.5µl          | 1X            |
| upstream primer, 10µM       | 5µl            | 37.5µl           | 1.0µM         |
| downstream primer, 10µM     | 5µl            | 37.5µl           | 1.0µM         |
| DNA template or H2O         | 10µl           |                  |               |
| BSA                         | 5µl            | 37.5 µl          |               |
| Total                       | 50µl           | 300µl            | 40 µl +10 µl  |

1. **Preparation** Gather all reagents and spin down gently before use. 
2. **Labeling** Label 7 (6 samples + one no template control, NTC) 0.1µl PCR tubes. 
3. **Master mix preparation** Prepare the master mix by combining all components (except the DNA templates) in a single tube. Spin down briefly.  
4. **Aliquoting master mix** Add 40µl of master mix to all the labelled PCR tubes.
5. **Adding DNA templates** Add 10µl of the diluted DNA template to the corresponding labeled PCR tubes. For the NTC, add 10µl of RNA-DNA free water instead of the DNA template. 
6. **Final mixing** Briefly spin down PCR tubes.

### PCR cycling conditions

Set up the PCR machine with the following conditions. Currently this PCR program is set up under Rhenium PCR machine at Mass Lab in folder Amalia/16S. Assemble PCR tubes. Distribution is not relevant. 

| ITC CS           | Temp | Time  | Cycles |
|------------------|------|-------|--------|
| Initial          | 95   | 3 min | 1      |
| Denaturation     | 95   | 30 s  | 28 t   |
| Annealing        | 55   | 45 s  | 28 t   |
| Elongation       | 72   | 45s   | 28 t   |
| Final extension  | 72   | 1 min | 1      |

## Make gel

Make a 1% agarose gel (1g agarose in 100 ml of 0.5XTBE).

 1. Use an Erlenmeyer flask to Weight 1g of agarose powder in an electronic analytical balance. If a smaller gel is needed, measure 0.5 grams instead. 
 2. Measure 100 ml of 0.5XTBE in a probete (for small size gel add 50 ml TBEx0.5 buffer). 
 3. Mix by swirling. 
 4. Put in the microwave for 2 minutes (or until properly disolved) in 30 seconds intervals. Swirl every 30 seconds. 
 5. Remove from the microwave and carefully cool down by putting the bottom of the Erlenmeyeyer under running water. Solution must be swirled to about 60°C. 
 6. Add 4µl RedSafe (which is stored in the 4°C fridge). Add 2µl if using a smaller gel. 
 7. Engage and seal the UV-transparent gel tray in the gel caster device. 
 8. Pour gel solution on the sealed UV-transparent gel tray. Avoid bubbles.
 10. Place a comb.
 11. Wait until the gel is consistent (∼45 minutes).
 12. Remove the comb. 

## Electrophoresis


1. Place the gel on the leveled gel stage of the running device.
2. Fill both sides of the running device tanks with 'used TBEX0.5 buffer'.
3. Submerge the gel in the UV-transparent tray on the leveled gel stage, ensuring wells are fully covered with buffer. Do not fill up to the maximum level until after loading samples.
2. Load 2 µl of DNA ladder (marker) and 5-6 µl of samples using filter tips and a pipettor. I used two ladders for this protocol DNL04 Take5 HR DNA ladder (250 bp-25kb range) and EuRx Perfect 100 bp DNA ladder (100 bp-2500 bp), loading each in one of the first two wells of the gel.
3. Add sample buffer if needed (usually 1 µl sample buffer to 5 µl sample, totaling 6 µl). _I skipped this step as it wasn´t needed_.
4. Cover the gel with 'used TBEX0.5 buffer' up to the maximum limit line.
5. Carefully place the safety lid ensuring it's correctly oriented (black to black, red to red).Locate the arrow sticker on the running device indicating the correct running direction. Adjust if necessary.
6. Set voltage to 110 V and start the run.Monitor for small bubbles and ensure samples run in a straight line from the wells.
7. When the front line reaches 2/3 of the gel after at least 60 minutes, switch off the power or press pause.
8. Remove the gel in the UV-transparent tray from the running device, leaving buffer in the device.
9. Transfer the gel from the UV-transparent tray to a smooth, transparent polypropylene plastic bag, ensuring no scratching and it's UV-transparent. Avoid bubbles.
10. Examine DNA bands under a UV lamp, if bands are observed, use gel camera to record results. _I was able to see bands, therefore I moved to the camera steps_

## Gel camera

1. Open the camera drawer and place the gel on the UV-transparent plastic bag, using the tray slits to position it in the middle of the camera tray.
2. Turn on the camera.
3. The gel camera features a touch screen.
4. Log in to the camera.
5. Allow the camera lamp to warm up, then press continue.
6. Select your designated folder.
7. Choose the 'safe red' filter and decide on automatic or manual exposure.
8. Adjust the photo parameters using the cursor.
9. Save the photo onto a disk-on-key.
10. Log out to return to the main screen of the camera.
11. From the main screen, switch off the camera.

My gel results, showing a successful extraction for 16S for all samples, and no contamination of the NTC. Please note it is to be expected for this set of primers to show two bands. 

![PCR Results](https://raw.githubusercontent.com/amurguei/Amalia_Open_Lab_Notebook_Mass_Lab/master/images/PCR_results_7_8_26_microbiome.png)
