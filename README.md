# Summer-of-code-2025
Project Ideas
Below is a listing of possible projects that students might consider. We also encourage students to propose their own projects, though several of the following topics are relatively high on our priority list. Our priority list is flexible, and it is important that the topic matches the interest and background of the student.

When considering the following projects, don't be put off by the knowledge prerequisites -- you don't need to be an expert, and there is some scope for research and learning within the GSoC period. However, familiarity with and interest in the subject area and involved technologies will be helpful!

Street-Based Tessellation (momepy)
An urban space refers to a set of disjoint regions which are usually represented by a partition, e.g., census tract, hexagonal tessellation, grid-like partition. Therefore, a space can be defined as a union of region boundaries such that, 
In momepy, we have a definition of Morphological Tesselation (MT) and Enclosed Tessellation (ET) which are crucial for capturing urban morphology characteristics. MT is generated based on voronoi diagrams given building footprints, while ET is an enhanced version of MT that considers natural barriers such as street network, rivers and railways. However, street-based tessellation (ST) is a intuitive way to define a tessellation given natural barriers. ST is a tessellation version that inputs a street network and output city blocks containing geographic entities.

Morphological Tesselation (Code)
See example of ST code in Jupyter Notebook
Objective
Enhance momepy adding support to Street-Based Tessellation (ST)

Related Reading
Momepy paper (Link)
Morphological Tessellation (Link)
Enclosed Tessellation (Link)
Difficulty
It is considered medium-level project. Note that it will depend on the familiarity with python packaging development.

Skills:
knowledge of python (required)
familiarity with python packaging - OOP, tests, docs - (preferred)
spatial data science (preferred)
