# Tube gel digestion
### Developed in the Saito Lab by Vladimir Bulygin and Dawn Moran; adapted here by Noelle Held. See also Lu and Zhu Mol Cel Proteomics 2005

### Materials
Make everything in LCMS grade H2O, use only LCMS grade reagents
* 1M Tris HCL, pH 7.5
* 40% Bis-acrylmide L 29:1
* Ambic 25 (25mM ammonium bicarbonate)
* 1% Ammonium persulfate (10mg/1mL H2O)
* Ethanol washed 0.5mL and 2mL tubes, one each per sample
* TE buffer (10mM tris HCL, 1mM EDTA in water)
* At least 25ug sample protein (can be less but more difficult)
* gel fix solution ()
* gel destain solution ()
* 50/50 wash (50% ACN:50% 25mM ammonium bicarbonate)
* LCMS grade acetonitrile
* 10mM DTT in ambic 25 (make fresh solution) (1.55mg/mL)
* Ambic 25
* 55mM Ioda in ambic 25 (9.3mg/mL)
* TEMED (full concentration)
* 1% ammonium persulfate (10mg/mL)


### Preparation
* Day 1: Prepare premix on ice: 1 part Tris HCL, 3 parts 40% Bis-acryl L (typically 252uL Tris HCL, 736.5uL Bis-acryl L)
* Day 2: Prepare fresh DTT solution (I do not trust previously frozen, but you can get away with it!) You will need about 600ul per sample at 1.55mg/mL in ambic 25. Prepare also IODA solution if needed.
* Decide amount of protein to digest (I typically do 100ug digestions)
* Fill out the following table:

| Sample | Sample  conc | Vol to Digest | Premix | TEMED | APS | TE | Final Vol |
|--------|--------------|---------------|--------|-------|-----|----|-----------|
|        |              |               | 103    | 3     | 7   |    | 200       |
|        |              |               | 103    | 3     | 7   |    | 200       |
|        |              |               | 103    | 3     | 7   |    | 200       |
|        |              |               | 103    | 3     | 7   |    | 200       |
|        |              |               | 103    | 3     | 7   |    | 200       |
|        |              |               | 103    | 3     | 7   |    | 200       |
|        |              |               | 103    | 3     | 7   |    | 200       |
### Protocol
* Place sample in clean 0.5mL tube, then add TE buffer in volume recorded above (calculate such that final volume is 200uL)
* Add 103uL Premix to each sample
* Add 3uL TEMED and then 7uL APS and vortex. Work quickly. I usually add TEMED to all samples, then vortex, then add APS one by one vortexing each as I go.
* Allow to polymerize in thermomixer 1hr at 20C with no shaking START:
* Add 200uL gel fix solution to gels, incubate RT 20min
* Remove liquid, transfer gels to 2mL tubes (use a 200mL pipette tip to unstick the gels from the tubes)
* fix in 1200-1600uL gel fix solution (enough to cover) at RT 350RPM for 1 hr. START:
* Remove liquid, add 1600uL destain solution and incubate 2hrs RT 350RPM. This can be shortened to 1hr with no negative effects that I am aware of. START:
* Remove liquid, decant gels onto a clean surface and cut into 1mm cubes with a clean scalpel or razor blade, return to tube
* Add 1mL 50:50 wash, shake 350RPM for 1hr
<u> Note: This is a good place to break, gels can remain in incubator over night if needed </u>
* Remove first 50:50 wash solution, repeat wash step
* Dehydrate gels by adding 0.8mL acetonitrile, vortex, incubate RT 10min and remove supernatant. Repeat 2x until gels pieces are hard and white.
* Add 600uL DTT solution, mix 1hr 56C 350RPM
* Remove liquid, note how much was absorbed by the gels (to calculate hydrated gel volume)
* Add 600uL Ambic 25, vortex, and remove (rinse step)
* Add 600uL Ioda solution, incubate 1hr RT 350RPM
* Remove Ioda, add 1mL ambic, vortex, incubate 10min RT 350RPM and remove solution
* Dehydrate with 0.8mL ACN, 10min room temperature and remove solution, repeat 2x
* Meanwhile, resuspend 100ug trypsin in 1000uL ambic on ice, allow to sit at least 30 mins to dissolve fully OR use previously reconstituted trypsin.
* The desired trypsin:protein ratio in the digestion solution is 1:20. Calculate the desired concentration of trypsin to reach this amount below:

| Sample | ug protein | ug trypsin 1:20 | volume pellet | ug trypsin/ vol pellet |   | vol  trypsin | vol ambic |
|--------|------------|-----------------|---------------|------------------------|---|--------------|-----------|
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |

* Add the desired volume of trypsin and additional ambic 25 to each sample (see table above), incubate 37C for 20mins
* If new trypsin was reconstituted, freeze any extra trypsin in small aliquots to be used later
* Add minimal amount of Ambic 25 to ensure rehydrated gels are covered with liquid
* Vortex, briefly spin down and incubate 37C 350RPM overnight. Check pH, should be about 8. START:
* END of digestion period:
* Spin down, collect liquid supernatant into clean 1.5mL tubes
* Add 50uL peptide extraction buffer, incubate 20mins RT
* Spin down and collect suspension, combine with liquid supernatant from above
* Repeat extraction step, combining the suspensions
* Spin the samples 20mins at high speed to remove any remaining debris
* Collect the top 90% off the centrifuged samples and concentrate on speed vac on low (as needed). Note the volumes and calculate the final estimated concentration of protein. Typically we seek 1ug/uL mixtures that are diluted to 0.1ug/uL in Buffer B and acidified to pH 4 for LC-MS/MS analysis

| Sample | ug protein digested | Volume of sample after concentrating | Final concentration |
|--------|---------------------|------------------------------------- |---------------------|
|        |                     |                                      |                     |
|        |                     |                                      |                     |
|        |                     |                                      |                     |
|        |                     |                                      |                     |
|        |                     |                                      |                     |
|        |                     |                                      |                     |


