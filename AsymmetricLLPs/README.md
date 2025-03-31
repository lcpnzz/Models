= Asymmetric production of LLPs =

== Implementation Authors

Louie Corpe, Andreas Goudelis, Louise Millot

== Model description

This is a toy (or "kinematic template") model to study "asymmetric" production of hadronically decaying scalar long-lived particles (LLPs) at the LHC. The LLPs are are assumed to be the decay products of a gluon fusion-produced scalar mediator and decay into quark and tau pairs with partial widths proportional to their squared mass, much like the Standard Model Higgs boson. The scalar mediator production is modeled through an effective interaction with the bilinear of the gluon field strength tensor. 

The model is characterized by seven external parameters: the mediator and LLP masses, the two LLP lifetimes, the scale of the mediator-gluon effective interaction and the (dimensionful) mediator-LLP pair coupling.

A detailed description of the model can be found in https://arxiv.org/abs/2502.18021

IMPORTANT: in the default version of the model (i.e. when UFO files are generated with the model out-of-the-box), all internal parameters are computed assuming that the two LLPs can only decay into tau and light (i.e. not top) quark pairs. This is a critical point to keep in mind, because at the event generation level decays into top quark pairs are possible if kinematically accessible, but inconsistently accounted for. For this reason, we provide four UFO extractions (with self-explanatory names) in which all internal parameters are computed consistently for each mass regime. For further information and/or troubleshooting, don't hesitate to contact the authors.

== Files

* AsymmetricLLPs.tar.gz: The FeynRules implementation of the model along with UFO files and a sample notebook for UFO model file creation.

== Validation

The model files have been independently checked by several of the authors

== References

If you use these model files, please cite

* T. Chehab, L. Corpe, A. Goudelis, A. Haddad, L. Millot, '''Constraints on asymmetric production of long-lived scalars at the Large Hadron Collider''', arXiv:2502.18021

