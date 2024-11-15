# MainSEL: Secure Record Linkage based on Mainzelliste and secure Multi-Party Computation

This is an aggregate repository for all components of MainSEL, a patient list and distributed record linkage system for medical institutions. It is powered by Mainzelliste ([Lablans et al, 2015](https://doi.org/10.1186/s12911-014-0123-5)), a patient list used by a multitude of German medical research institutions, biobanks and patient registries.

Our primary objective is to provide industry leading privacy guarantees and protect the patient's data to a degree, not seen before. To that end we employ cutting-edge hybrid secure Multi-Party Computation (sMPC) protocols in our distributed, decentralized record linkage system.

For more informations see our publication [Mainzelliste SecureEpiLinker
(MainSEL): Privacy-Preserving Record Linkage using Secure Multi-Party
Computation](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btaa764/5900257)

MainSEL consists of three repositories:

1. [The
Mainzelliste](https://github.com/medicalinformatics/MainzellisteSEL),
the patient list,
2. [The Secure Epilinker](https://github.com/medicalinformatics/SecureEpilinker), the sMPC preforming record linkage component, and 
3. [The Docker Deployment package](https://github.com/medicalinformatics/mainsel-docker), for easy and quick deployment and configuration.

Some documentation and how-to-guides can be found in the respective
repositories. Documentation concerned with the complete MainSEL system is published in
this repository. At the moment this documentation consists of the [MainSEL API
reference](docs/api_reference.md), more tutorials and how-to guides will be
added in the future.
