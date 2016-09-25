# Results: The main text (not including Abstract, Methods, References and figure legends) [meaning intro + results + discussion] should be no more than 4,500 words. The main text of an Article can be organised in different ways and according to the authors' preferences, it may be appropriate to combine sections.

## Figure 1: Tissue enrichment, protein solubilization (only DDM), and immunoprecipitation
* 1A (WB): Body < heads < sieved tissues, successful protein enrichment
* 1B (WB): EGFP::Orco and myr::GFP solubilization in DDM, sups and pellets, at room temperature
* 1C (IHC): EGFP::Orco and myr::GFP expression in tissues
* 1D (IP-WB): EGFP::Orco and myr::GFP IP products

## Table 1: IP-MS top 30

## Figure 2: Immunoprecipitation-immunoblotting (IP-WB of selected proteins from Table 1)
## Figure 3: Changes on the odor-evoked activities upon RNAI of individual proteins (only ones with change)
* 3A (spike images): The recording window of paraffin oil stimulation and odor stimulation
* 3B (graphs): Only positive results (8/29)

## Figure 4: Decreased spontaneous activity upon RNAI of vir-1 and Rab5 (only ones with change)
* 4A (spike images): How vir-1 and Rab5 spontaneous activities look like, compared to the controls and orco1
* 4B (graphs): (2/29)

### S1: Overview of the procedure (diagram)
### S2: Temperature-sensitive EGFP::Orco solubilization in various laboratory detergents
### S3: The temperature-sensitive change in solubility is also shown with EGFP::Or47a and EGFP::Gr21a
### Table S4: List of 207 selected proteins (iBAQ ratio over 10)
### S5: The effect of RNAi on the odor-evoked activities (without change)
### S6: The effect of RNAi on the spontaneous activities (without change)

# Tissue enrichment, protein solubilization, and co-immunoprecipitation
The major advancement of our method was achieved by protein solubilization from the native tissues. The dendrite is a compartmentalized portion of a neuron resembling cilia \cite{}, and the protein-protein interactions in such environment cannot be represented by any current heterologous expression systems, especially when the cell’s functionality relies on a key protein which is not conserved in other animals. Concerning this fact, we decided to use native tissues lysates for our protein-protein interaction experiments of Orco.

Applying classic molecular biology tools rarely happened for studying ORs from tissues. Although IRs have been isolated from the olfactory tissues \cite{Ai_2013}, we have developed our own protocol to speed up the procedure (Supplementary Fig. S1). Initially several antibodies against Orco and a few ORs were tested on western blotting, but all tested antibodies failed to stably detect the desired proteins (data not shown). To solve the detection problem, we decided to use the EGFP-tagged version of Orco \cite{Benton_2006} for the following experiments.

Since Orco is exclusively expressed in the antennae and the maxillary palps \cite{Larsson_2004}, we utilized a homemade sieve to routinely collect antenna-sized small tissues (Supplementary Fig. S1). As a result, Orco was successfully enriched in the tissue lysate (Fig. 1A) and this method of tissue collection had been used in all of the following experiments. Next, we explored nine commonly-used laboratory detergents to find the best lysis buffer condition for the sieved tissues. In a previous report \cite{Carraher_2013}, seven out of the nine tested detergents were tested to solubilize Orco from Sf9 cells ***They also solubilized Orco from wheat germ cell-free system but I want to ignore this*** and DDM, SDS, and Zwittergent 3-16  successfully solubilized Orco. However, EGFP-tagged Orco from the native tissues showed very different solubility to the seven detergents (Supplementary Fig. S2). Additionally, we found that Orco solubility was sensitive to the temperature of sample preparation. When tissues were kept at freezing temperature up to the solubilization step, only a few detergents could effectively solubilize Orco (Supplementary Fig. S2). Meanwhile, all tested detergents solubilized Orco to a comparable level when the tissues were homogenized at room temperature (Supplementary Fig. S2). We assume that this happens because the wax covering the outer cuticle hardens if the temperautre is low, somehow trapping the hydrophobic components of cells. It was confirmed that the same temperature-senstivitity applies to other closely related seven-transmembrane proteins (Supplementary Fig. S3). We took the advantage over this temperature-sensitive solubilization behavior of Orco from the native tissues and used n-dodecyl β-D-maltoside (DDM), one of the best known mass spectrometry-compatible detergents, for the IP-MS experiment (Fig. 1B).

To perform IP-MS, we prepared a control fly line expressing membrane-tethered (myristoylated) GFP in Orco-positive cells. Although the control and the experimental lines showed different expression levels of the tag proteins both in the immunohistochemistry and western blotting (Fig. 2C and 2D), as we were going to verify the MS results with electrophysiology, the expression levels in flies were not adjusted. An excess of total protein for each sample was provided, and in such environment, IP could stably capture similar amount of the bait proteins (Fig. 2D), which could partially compensate the expression level issue. We expected that the native bait-prey complexes would somewhat dissociate over the course of tissue lysate preparation and re-assemble during the binding step of IP. Our method does not present the exact in vivo protein-protein interactions while it assures the prey proteins provided from the natural environment. All IP experiments were done with DDM-solubilized protein samples.

# Mass spectrometry and protein identification

* (Need help from KRISS...)
* Table 1.
* A few representative interactions from the selected 29 proteins were confirmed by western blotting (Fig. 3).

# Verification of the MS-identified proteins
Lastly, to verify the in vitro results in vivo, proteins with 10 or higher experimental-to-control iBAQ ratio was picked out and then ranked by their MS/MS values. We chose to work with the top 30 proteins from this list to check the knock-down effects in vivo, but since Cyt-b ranked at 21 was skipped as it had no publicly available fly line, eventually we tested the effects of RNAi with 29 proteins (Table 1).

Each protein was knocked down in saperate flies using Orco-GAL4 and UAS-RNAi, and 12-day-old males and females were used for the live-animal SSR. We assumed that any effect caused by the disruption of Orco function would be apparent in all OSNs, therefore the changes of the A neuron (expressing Or59b) activities from antennal basiconic 2 (ab2) sensilla were checked with methyl acetate (MA) as a representative measure. Within the 3-second interval, changes in spontaneous activities and odor-evoked responses were observed (Fig. 3 and 4). The odorant was applied for 0.5 second and the neuronal activities were recorded for three seconds, starting from one second ahead the odorant application (Fig. 3A). Out of the 29 tested RNAi lines, none showed increased odor-evoked responses, eight showed decreased odor-evoked responses (Fig. 3B), one showed decreased spontaneous activities in addition to decreased odor-evoked responses (Fig. 4), one showed a severe reduction of all SSR signals (Fig. 4), and 21 showed no notable changes (Supplementary Fig. S4 and S5). Note that the impact of Rab5-RNAi was so serious that we had to use a different kind of measurement to visualize the raw data (See Methods).