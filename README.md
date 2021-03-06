dame_dd
--------

Welcome to dame_dd, a python code that to compute the impact of dark matter substructure on direct detection experiments relying on dark matter-electron scattering.

To use simply do:

    >>> import dame_dd as de

There are three sub-modules: `de.ap` for astrophysics, `de.sc` for semiconductors, and `de.rt` for the scattering rates. A fourth one, `de.at` for atoms, will be added in the future.

For help on how to use these modules, type:

    >>> help(de.ap)
    >>> help(de.sc)
    >>> help(de.rt)


Policy
--------

Please cite [Buch, Buen-Abad, Fan, & Leung (2020)](https://arxiv.org/abs/2007.13750) if you use this
code or find it at all useful in your research.

The BibTeX entry for the paper is:

    @article{Buch:2020xyt,
		author = "Buch, Jatan and Buen-Abad, Manuel A. and Fan, Jiji and Leung, John Shing Chau",
		title = "{Dark Matter Substructure under the Electron Scattering Lamppost}",
		eprint = "2007.13750",
		archivePrefix = "arXiv",
		primaryClass = "hep-ph",
		doi = "10.1103/PhysRevD.102.083010",
		journal = "Phys. Rev. D",
		volume = "102",
		number = "8",
		pages = "083010",
		year = "2020"
	}
