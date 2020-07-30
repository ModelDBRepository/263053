This is the readme for the models associated with the paper:

Zbili M, Debanne D (2020) Myelination increases the spatial extent of
analog-digital modulation of synaptic transmission: a modeling study
Frontiers in Cellular Neuroscience 14:40

These NEURON files were contributed by M Zbili.

Here is an excerpt from the Materials and Methods section of the paper
(please see the paper and code for details):

"A multi-compartment model of a 36 days-old rat L5 pyramidal
neuron was simulated with NEURON 7.6. The neuronal morphology
was taken from a reconstructed neuron by Hay et al.
(2011) available on Neuromorpho.org (Ascoli et al., 2007;
Neuromorpho ID: NMO_07763; Neuron Name: C080418A-1-
SR)."

To run the model, compile the mod files and run the fig hoc files. The fig2_3.hoc file
reproduces the main results of fig 2 and 3 from the paper (extension of dADF and hADF
spatial extent by myelination). The fig4.hoc file reproduces the main results of 
fig 4 from the paper (weak influence of internodes length on dADF and hADF spatial extent).
The fig5.hoc file reproduces the main results of  fig 5 from the paper (great influence of 
myelin wraps number on dADF and hADF spatial extent).
Note that this files take a long time to compute (more than 20 muntes for fig5.hoc). Therefore,
you can find the screenshots of the results in jpeg format.

Otherwise the files unmyelinated_axon.hoc, hybrid_axon.hoc, myelinated_axon_1.hoc,
myelinated_axon_2.hoc, myelinated_axon_3.hoc, myelinated_axon_4.hoc, myelinated_axon_5.hoc,
myelinated_axon_6.hoc and myelinated_axon_7.hoc correspond to the different models
used in the paper (see Table 1 and 2 of the paper for full description). There are used in the fig
hoc files. Briefly, the somato-dendritic compartments morphology and biophysics are identical in 
all the models. The axonal collaterals morphology and biophysics are also identical.
The difference between the models are : 1) the presence or abscence of myelin
at the internodes of the main axon 2) the lengths of the internodes and 3) the number of 
myelin wraps ensheating the internodes. As explained in the paper, when the internodes are
myelinated, the nodes of Ranvier present high density of Nav and Kv channels to insure
spike propagation. The exact density of  Nav and Kv channels at nodes of Ranvier has been set
to presever AP waveform identical in all models when it is emitted from the resting membrane
potential (see paper for full explanation).

References:

Alcami, P., and El Hady, A. (2019). Axonal computations. Front. Cell. Neurosci.
13:413. doi: 10.3389/fncel.2019.00413

Alle, H., and Geiger, J. R. (2006). Combined analog and action potential coding
in hippocampal mossy fibers. Science 311, 1290–1293. doi: 10.1126/science.
1119055

Arancibia-Cárcamo, I. L., Ford, M. C., Cossell, L., Ishida, K., Tohyama, K.,
and Attwell, D. (2017). Node of Ranvier length as a potential regulator of
myelinated axon conduction speed. Elife 6:e23329. doi: 10.7554/eLife.23329

Arbuthnott, E. R., Boyd, I. A., and Kalu, K. U. (1980). Ultrastructural dimensions
of myelinated peripheral nerve fibres in the cat and their relation to conduction
velocity. J. Physiol. 308, 125–157. doi: 10.1113/jphysiol.1980.sp013465

Ascoli, G. A., Donohue, D. E., and Halavi, M. (2007). NeuroMorpho.Org:
a central resource for neuronal morphologies. J. Neurosci. 27, 9247–9251.
doi: 10.1523/JNEUROSCI.2055-07.2007

Atkinson, S. E., and Williams, S. R. (2009). Postnatal development of dendritic
synaptic integration in rat neocortical pyramidal neurons. J. Neurophysiol. 102,
735–751. doi: 10.1152/jn.00083.2009

Bakiri, Y., Káradóttir, R., Cossell, L., and Attwell, D. (2011). Morphological and
electrical properties of oligodendrocytes in the white matter of the corpus
callosum and cerebellum. J. Physiol. 589, 559–573. doi: 10.1113/jphysiol.2010.
201376

Battefeld, A., Popovic, M. A., de Vries, S. I., and Kole, M. H. P. (2019).
High-frequency microdomain Ca2C transients and waves during early myelin
internode remodeling. Cell Rep. 26, 182.e5–191.e5. doi: 10.1016/j.celrep.2018.
12.039

Berthold, C. H., and Carlstedt, T. (1982). Myelination of S1 dorsal root
axons in the cat. J. Comp. Neurol. 209, 225–232. doi: 10.1002/cne.9020
90302

Bialowas, A., Rama, S., Zbili, M., Marra, V., Fronzaroli-Molinieres, L., Ankri, N.,
et al. (2015). Analog modulation of spike-evoked transmission in CA3 circuits
is determined by axonal Kv1.1 channels in a time-dependent manner. Eur.

J. Neurosci. 41, 293–304. doi: 10.1111/ejn.12787
Bischofberger, J., Geiger, J. R., and Jonas, P. (2002). Timing and efficacy of
Ca2C channel activation in hippocampal mossy fiber boutons. J. Neurosci. 22,
10593–10602. doi: 10.1523/JNEUROSCI.22-24-10593.2002

Bruno, R. M., and Sakmann, B. (2006). Cortex is driven by weak but synchronously
active thalamocortical synapses. Science 312, 1622–1627. doi: 10.1126/science.
1124593

Castelfranco, A. M., and Hartline, D. K. (2015). The evolution of vertebrate and
invertebrate myelin: a theoretical computational study. J. Comput. Neurosci. 38,
521–538. doi: 10.1007/s10827-015-0552-x

Christie, J. M., and Jahr, C. E. (2009). Selective expression of ligand-gated
ion channels in L5 pyramidal cell axons. J. Neurosci. 29, 11441–11450.
doi: 10.1523/JNEUROSCI.2387-09.2009

Cohen, C. C. H., Popovic, M. A., Klooster, J., Weil, M. T., Mobius, W., Nave, K. A.,
et al. (2020). Saltatory conduction along myelinated axons involves a periaxonal
nanocircuit. Cell 180, 311–322.e15. doi: 10.1016/j.cell.2019.11.039

Debanne, D., Bialowas, A., and Rama, S. (2013). What are the mechanisms for
analogue and digital signalling in the brain? Nat. Rev. Neurosci. 14, 63–69.
doi: 10.1038/nrn3361

Dover, K., Marra, C., Solinas, S., Popovic, M., Subramaniyam, S., Zecevic, D.,
et al. (2016). FHF-independent conduction of action potentials along
the leak-resistant cerebellar granule cell axon. Nat. Commun. 7:12895.
doi: 10.1038/ncomms12895

Gogan, P., Gueritaud, J. P., and Tyc-Dumont, S. (1983). Comparison of antidromic
and orthodromic action potentials of identified motor axons in the cat’s brain
stem. J. Physiol. 335, 205–220. doi: 10.1113/jphysiol.1983.sp014529

Hamada, M. S., Popovic, M. A., and Kole, M. H. (2017). Loss of saltation
and presynaptic action potential failure in demyelinated axons. Front. Cell.
Neurosci. 11:45. doi: 10.3389/fncel.2017.00045
Harris, J. J., and Attwell, D. (2012). The energetics of CNS white matter. J. Neurosci.
32, 356–371. doi: 10.1523/JNEUROSCI.3430-11.2012

Hay, E., Hill, S., Schürmann, F., Markram, H., and Segev, I. (2011).
Models of neocortical layer 5b pyramidal cells capturing a wide range of
dendritic and perisomatic active properties. PLoS Comput. Biol. 7:e1002107.
doi: 10.1371/journal.pcbi.1002107

Hu, H., and Agmon, A. (2016). Differential excitation of distally versus proximally
targeting cortical interneurons by unitary thalamocortical bursts. J. Neurosci.
36, 6906–6916. doi: 10.1523/JNEUROSCI.0739-16.2016

Hu, W., Tian, C., Li, T., Yang, M., Hou, H., and Shu, Y. (2009). Distinct
contributions of Nav1.6 and Nav1.2 in action potential initiation and
backpropagation. Nat. Neurosci. 12, 996–1002. doi: 10.1038/nn.2359

Kaller, M. S., Lazari, A., Blanco-Duque, C., Sampaio-Baptista, C., and JohansenBerg, H. (2017). Myelin plasticity and behaviour-connecting the dots. Curr.
Opin. Neurobiol. 47, 86–92. doi: 10.1016/j.conb.2017.09.014
Kole, M. H., Letzkus, J. J., and Stuart, G. J. (2007). Axon initial segment
Kv1 channels control axonal action potential waveform and synaptic efficacy.
Neuron 55, 633–647. doi: 10.1016/j.neuron.2007.07.031

Looney, G. A., and Elberger, A. J. (1986). Myelination of the corpus callosum in
the cat: time course, topography, and functional implications. J. Comp. Neurol.
248, 336–347. doi: 10.1002/cne.902480304

Rama, S., Zbili, M., Bialowas, A., Fronzaroli-Molinieres, L., Ankri, N., Carlier, E.,
et al. (2015). Presynaptic hyperpolarization induces a fast analogue modulation
of spike-evoked transmission mediated by axonal sodium channels. Nat.
Commun. 6:10163. doi: 10.1038/ncomms10163

Romand, S., Wang, Y., Toledo-Rodriguez, M., and Markram, H. (2011).
Morphological development of thick-tufted layer V pyramidal cells in the
rat somatosensory cortex. Front. Neuroanat. 5:5. doi: 10.3389/fnana.2011.
00005

Rushton, W. A. (1951). A theory of the effects of fibre size in
medullated nerve. J. Physiol. 115, 101–122. doi: 10.1113/jphysiol.1951.sp
004655

Sasaki, T., Matsuki, N., and Ikegaya, Y. (2012). Effects of axonal topology on
the somatic modulation of synaptic outputs. J. Neurosci. 32, 2868–2876.
doi: 10.1523/JNEUROSCI.5365-11.2012

Scott, R., Ruiz, A., Henneberger, C., Kullmann, D. M., and Rusakov, D. A. (2008).
Analog modulation of mossy fiber transmission is uncoupled from changes in
presynaptic Ca2C. J. Neurosci. 28, 7765–7773. doi: 10.1523/JNEUROSCI.1296-
08.2008

Shu, Y., Duque, A., Yu, Y., Haider, B., and McCormick, D. A. (2007a). Properties
of action-potential initiation in neocortical pyramidal cells: evidence from
whole cell axon recordings. J. Neurophysiol. 97, 746–760. doi: 10.1152/jn.009
22.2006

Shu, Y., Yu, Y., Yang, J., and McCormick, D. A. (2007b). Selective control of
cortical axonal spikes by a slowly inactivating KC current. Proc. Natl. Acad.
Sci. U S A 104, 11453–11458. doi: 10.1073/pnas.0702041104

Shu, Y., Hasenstaub, A., Duque, A., Yu, Y., and McCormick, D. A. (2006).
Modulation of intracortical synaptic potentials by presynaptic somatic
membrane potential. Nature 441, 761–765. doi: 10.1038/nature04720

Snaidero, N., Möbius, W., Czopka, T., Hekking, L. H., Mathisen, C., Verkleij, D.,
et al. (2014). Myelin membrane wrapping of CNS axons by PI(3,4,5)P3-
dependent polarized growth at the inner tongue. Cell 156, 277–290.
doi: 10.1016/j.cell.2013.11.044

Suminaite, D., Lyons, D. A., and Livesey, M. R. (2019). Myelinated axon physiology
and regulation of neural circuit function. Glia 67, 2050–2062. doi: 10.1002/
glia.23665

Wu, L. M., Williams, A., Delaney, A., Sherman, D. L., and Brophy, P. J.
(2012). Increasing internodal distance in myelinated nerves accelerates nerve
conduction to a flat maximum. Curr. Biol. 22, 1957–1961. doi: 10.1016/j.cub.
2012.08.025

Zbili, M., and Debanne, D. (2019). Past and future of analog-digital modulation
of synaptic transmission. Front. Cell. Neurosci. 13:160. doi: 10.3389/fncel.2019.
00160