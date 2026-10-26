# Awesome Molecular Animation

A curated list of software, data, tutorials and reading for animating molecules, cells and other biological structures.

Entries are chosen for usefulness to scientists, educators and scientific animators. Prices and licenses change, so check each project's own page before you commit. Links were last checked on 2026-10-26.

## Contents

- [Animation and rendering tools](#animation-and-rendering-tools)
- [Structure viewers that make movies](#structure-viewers-that-make-movies)
- [Blender add-ons](#blender-add-ons)
- [AI tools](#ai-tools)
- [Structure and data sources](#structure-and-data-sources)
- [Tutorials and courses](#tutorials-and-courses)
- [Communities](#communities)
- [Papers and talks](#papers-and-talks)
- [Contributing](#contributing)
- [License](#license)

## Animation and rendering tools

- [Blender](https://www.blender.org/) - Free, open-source 3D suite for modeling, animation and rendering, released under the GPL.
- [Cinema 4D](https://www.maxon.net/en/cinema-4d) - Commercial 3D animation and motion graphics software from Maxon, with the Redshift renderer included.
- [Autodesk Maya](https://www.autodesk.com/products/maya/overview) - Commercial 3D animation and VFX software, with free one-year education access for eligible students and teachers.
- [Houdini](https://www.sidefx.com/products/houdini/) - Procedural 3D and simulation software; the free Apprentice edition is for personal non-commercial projects.
- [Molecular Maya (mMaya)](https://clarafi.com/tools/mmaya/) - Free Maya plugin from Clarafi to import, model and animate molecular structures; its page lists support for Maya 2018 to 2020.
- [SAMSON](https://www.samson-connect.net/) - Molecular design platform from OneAngstrom whose Animator saves movies as MP4, GIF or WebM; free for academic and nonprofit non-commercial use.
- [cellPACK](https://github.com/mesoscope/cellpack) - Open-source (MIT) Python tool that packs 3D molecular models into mesoscale models of cells and viruses.
- [CellPAINT](https://ccsb.scripps.edu/cellpaint/) - Free web and desktop app for painting illustrations of cells and viruses from structure-based molecules; images may be used commercially.
- [Illustrate](https://ccsb.scripps.edu/illustrate/) - David Goodsell's program for non-photorealistic molecular illustrations, with a web interface for PDB entries.

## Structure viewers that make movies

- [UCSF ChimeraX](https://www.cgl.ucsf.edu/chimerax/) - Visualization and analysis of structures and cryo-EM maps, with a movie command for scripted movies; free for academic, government, nonprofit and personal use.
- [PyMOL](https://pymol.org/) - Molecular visualization with key-frame, scene, trajectory and morph movies; Incentive builds are licensed by Schrödinger.
- [PyMOL open source](https://github.com/schrodinger/pymol-open-source) - Source code of the open-source foundation of PyMOL.
- [VMD](https://www.ks.uiuc.edu/Research/vmd/) - Visualization and analysis of large systems and simulation trajectories, with a Movie plugin; free of charge and includes source code.
- [Mol*](https://molstar.org/) - Open-source (MIT) web viewer used by the RCSB PDB, PDBe and AlphaFold DB that plays molecular dynamics trajectories.
- [MolViewStories](https://molstar.org/mol-view-stories/) - Builds interactive, step-by-step molecular stories on the web with Mol*.
- [YASARA](https://www.yasara.org/) - Molecular graphics, modeling and simulation for Windows, Linux, macOS and Android; YASARA View is free and can be extended with macros and movies.
- [OVITO](https://www.ovito.org/) - Visualization and analysis of particle-based simulations that renders animations of trajectories.

## Blender add-ons

- [Molecular Nodes](https://extensions.blender.org/add-ons/molecularnodes/) - Imports PDB entries, MD trajectories, cryo-EM and cryo-ET data and cellPACK ensembles into Blender with Geometry Nodes (GPL-3.0-or-later).
- [Molecular Nodes documentation](https://bradyajohnston.github.io/MolecularNodes/) - Installation, tutorials and node reference for Molecular Nodes.
- [Atomic Blender PDB/XYZ](https://extensions.blender.org/add-ons/atomic-blender-pdb-xyz/) - Blender extension that imports atoms from PDB and XYZ files.

## AI tools

- [Animiotics](https://animiotics.com/) - Web app that builds an editable 3D animation in Blender from a written description, using structures downloaded from the RCSB PDB; paid plans.
- [ChimeraX mcp command](https://www.cgl.ucsf.edu/chimerax/docs/user/commands/mcp.html) - Lets an MCP-capable AI assistant such as Claude Desktop, Cursor or VS Code with Copilot run ChimeraX commands.
- [MCP for Blender](https://github.com/ahujasid/mcp-for-blender) - Community plugin, formerly blender-mcp, that lets a language model control Blender; not made by Blender.
- [SAMSON AI](https://documentation.samson-connect.net/samson-release-notes/whats-new-in-samson-2023-r1/samson-ai/) - Assistant inside SAMSON that answers questions, runs commands and drafts Python scripts.
- [AlphaFold Server](https://alphafoldserver.com/) - Web service powered by AlphaFold 3 that predicts structures of proteins with DNA, RNA, ligands and ions; non-commercial use only.
- [Boltz](https://github.com/jwohlwend/boltz) - Open-source (MIT) models that predict biomolecular complex structures and binding affinity.
- [Google Veo](https://deepmind.google/models/veo/) - General text-to-video model with native audio; its clips are generated pixels, not built from molecular structures.
- [Runway](https://runway.com/) - General AI video and image generation platform; its outputs are not built from molecular structures.

## Structure and data sources

- [RCSB PDB](https://www.rcsb.org/) - wwPDB member that curates and annotates PDB data, with search, structure pages and downloads.
- [PDBe](https://www.ebi.ac.uk/pdbe/) - Protein Data Bank in Europe at EMBL-EBI, a founding member of the wwPDB.
- [PDBj](https://pdbj.org/) - Protein Data Bank Japan, which maintains the global PDB, BMRB and EMDB archives with tools for searching them.
- [wwPDB](https://www.wwpdb.org/) - Worldwide Protein Data Bank, the organization that manages the PDB archive and keeps it freely available.
- [AlphaFold DB](https://alphafold.ebi.ac.uk/) - Database of AlphaFold protein structure predictions, developed by Google DeepMind and EMBL-EBI.
- [EMDB](https://www.ebi.ac.uk/emdb/) - Electron Microscopy Data Bank, the public archive of cryo-EM volumes and representative tomograms.
- [PDB-IHM](https://pdb-ihm.org/) - Archive of structures from integrative or hybrid modeling, managed by the wwPDB.
- [ModelArchive](https://modelarchive.org/) - Repository that gives deposited theoretical models of macromolecular structures a stable DOI.
- [SWISS-MODEL Repository](https://swissmodel.expasy.org/repository) - Database of annotated 3D protein models from the SWISS-MODEL homology-modeling pipeline.
- [ESM Metagenomic Atlas](https://esmatlas.com/) - Open atlas of 617 million predicted metagenomic protein structures.
- [PubChem](https://pubchem.ncbi.nlm.nih.gov/) - Free chemistry database at NCBI, searchable by name, formula or structure; useful for ligands and small molecules.
- [UniProt](https://www.uniprot.org/) - Protein sequence and function database, useful for checking what a protein does before you animate it.
- [MDDB](https://mddbr.eu/) - Molecular Dynamics Data Bank, a European repository for biosimulation data.
- [GPCRmd](https://www.gpcrmd.org/) - Online platform for visualizing and analyzing GPCR molecular dynamics simulations.
- [NIH 3D](https://3d.nih.gov/) - Portal to download, share and create bioscientific and medical 3D models for printing and interactive visualization.
- [BodyParts3D](https://lifesciencedb.jp/bp3d/) - 3D models of human anatomy that you can select by part and embed or download.

## Tutorials and courses

- [PDB-101 Molecule of the Month](https://pdb101.rcsb.org/motm/motm-by-date) - Illustrated monthly explanations of molecules from the RCSB PDB, a good place to choose structures.
- [Guide to Understanding PDB Data](https://pdb101.rcsb.org/learn/guide-to-understanding-pdb-data/introduction) - PDB-101 guide to coordinates, resolution, biological assemblies and other data to check before animating.
- [Making Molecular Movies in ChimeraX](https://www.cgl.ucsf.edu/chimerax/data/movies-may2019/moviemaking.html) - Tom Goddard's movie-making tutorial for ChimeraX.
- [ChimeraX tutorials](https://www.cgl.ucsf.edu/chimerax/tutorials.html) - Official ChimeraX tutorials, including movies for cryo-EM and light microscopy.
- [ChimeraX Recipes](https://rbvi.github.io/chimerax-recipes/) - Examples of ChimeraX commands and Python scripts, including movie recording.
- [PyMOL Moviemaking Tutorial](https://pymol.org/tutorials/moviemaking/) - Camera key frames, scenes, object motion, trajectories and morphing in PyMOL.
- [PyMOL Wiki MovieSchool](https://pymolwiki.org/index.php/MovieSchool) - Community course on making movies in PyMOL.
- [VMD Movie Plugin](https://www.ks.uiuc.edu/Research/vmd/plugins/vmdmovie/) - Documentation for rotation and trajectory movies in VMD.
- [TCBG tutorials](https://www.ks.uiuc.edu/Training/Tutorials/) - Tutorials for VMD and related software from the University of Illinois group that makes it.
- [Molecular Nodes tutorials](https://bradyajohnston.github.io/MolecularNodes/tutorials/index.html) - Written tutorials covering installation, the Blender interface, fetching from the PDB, selections and trajectories.
- [Brady Johnston on YouTube](https://youtube.com/c/bradyjohnston) - Channel of the Molecular Nodes author, linked from its documentation.
- [Blender Manual](https://docs.blender.org/manual/en/latest/) - Official reference manual for Blender.
- [Clarafi](https://clarafi.com/) - Online courses in scientific visualization, including Molecular Maya, Maya dynamics and storyboarding.
- [ChimeraX Morph: Animate Two Protein Structures](https://animiotics.com/blog/chimerax-morph-animate-two-protein-structures/) - Tested ChimeraX recipe for morphing between two adenylate kinase structures and checking the generated frames (Animiotics blog).
- [Molecular Dynamics Movies: Report Simulation Time Correctly](https://animiotics.com/blog/molecular-dynamics-movies-report-simulation-time-correctly/) - How to keep simulation time and video frame rate apart in MD movies and captions (Animiotics blog).

## Communities

- [ChimeraX-users mailing list](https://mail.cgl.ucsf.edu/mailman/archives/list/chimerax-users@cgl.ucsf.edu/) - ChimeraX user mailing list and searchable archive.
- [pymol-users mailing list](https://sourceforge.net/projects/pymol/lists/pymol-users) - PyMOL user mailing list.
- [VMD-L](https://www.ks.uiuc.edu/Research/vmd/mailing_list/) - VMD user mailing list.
- [Molecular Nodes Discord](https://discord.gg/fvw6vT3vY9) - Chat server linked from the Molecular Nodes documentation.
- [Molecular Nodes discussions](https://github.com/BradyAJohnston/MolecularNodes/discussions) - Questions and ideas about Molecular Nodes on GitHub.
- [Mol* discussions](https://github.com/molstar/molstar/discussions) - Questions and ideas about Mol* on GitHub.
- [Blender Stack Exchange](https://blender.stackexchange.com/) - Question and answer site for Blender users.
- [Association of Medical Illustrators](https://ami.org/) - Global community of medical illustrators, with a directory of professional members.
- [VIZBI](https://vizbi.org/) - International community of scientists, illustrators and designers who visualize biological data, with an annual conference since 2010.

## Papers and talks

- [UCSF ChimeraX: Tools for structure building and analysis](https://doi.org/10.1002/pro.4792) - Meng et al., Protein Science, 2023.
- [UCSF ChimeraX: Meeting modern challenges in visualization and analysis](https://doi.org/10.1002/pro.3235) - Goddard et al., Protein Science, 2018.
- [Mol* Viewer: modern web app for 3D visualization and analysis of large biomolecular structures](https://doi.org/10.1093/nar/gkab314) - Sehnal et al., Nucleic Acids Research, 2021.
- [VMD: Visual molecular dynamics](https://doi.org/10.1016/0263-7855(96)00018-5) - Humphrey, Dalke and Schulten, Journal of Molecular Graphics, 1996.
- [cellPACK: a virtual mesoscope to model and visualize structural systems biology](https://doi.org/10.1038/nmeth.3204) - Johnson et al., Nature Methods, 2015.
- [BlendMol: advanced macromolecular visualization in Blender](https://doi.org/10.1093/bioinformatics/bty968) - Durrant, Bioinformatics, 2019.
- [Molecular movies... coming to a lecture near you](https://doi.org/10.1016/j.cell.2008.06.013) - McGill, Cell, 2008.
- [Animating the model figure](https://doi.org/10.1016/j.tcb.2010.08.005) - Iwasa, Trends in Cell Biology, 2010.
- [Visualizing protein interactions and dynamics: evolving a visual language for molecular animation](https://doi.org/10.1187/cbe.11-08-0071) - Jenkinson and McGill, CBE Life Sciences Education, 2012.
- [Bringing macromolecular machinery to life using 3D animation](https://doi.org/10.1016/j.sbi.2015.03.015) - Iwasa, Current Opinion in Structural Biology, 2015.
- [Visualization of biomolecular structures: state of the art revisited](https://doi.org/10.1111/cgf.13072) - Kozlíková et al., Computer Graphics Forum, 2017.
- [From atoms to cells: using mesoscale landscapes to construct visual narratives](https://doi.org/10.1016/j.jmb.2018.06.009) - Goodsell, Franzen and Herman, Journal of Molecular Biology, 2018.
- [Molecular graphics: bridging structural biologists and computer scientists](https://doi.org/10.1016/j.str.2019.09.001) - Martinez et al., Structure, 2019.
- [Drew Berry: Animations of unseeable biology](https://www.ted.com/talks/drew_berry_animations_of_unseeable_biology) - TED talk showing scientifically accurate animations of processes inside cells.
- [Janet Iwasa: How animations can help scientists test a hypothesis](https://www.ted.com/talks/janet_iwasa_how_animations_can_help_scientists_test_a_hypothesis) - TED talk on using 3D animation to explore scientific hypotheses.
- [WEHI.TV](https://www.wehi.edu.au/wehi-tv/) - 3D animations of medical research from the Walter and Eliza Hall Institute.

## Contributing

Suggestions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) first.

## License

[CC0 1.0 Universal](LICENSE). To the extent possible under law, the contributors have waived all copyright and related rights to this list.
