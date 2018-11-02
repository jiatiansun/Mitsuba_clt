
### Mitsuba_clt

Mitsuba_clt is a extended renderer that has simulation tools for modern computational imaging  

### Project Title

Develop rendering tools for modern computational imaging  

### Project Description

I will try to develop rendering tools for modern computational imaging with professor Ioannis Gkioulekas next semester. 
With my project, I hope to alleviate the issue of lack of simulation tools for computational imaging research on modern cameras. Specifically, over the past two decades, computational photography research has resulted in the emergence of many new imaging modalities: From cameras that can record video at trillion frames per second, to cameras that can see around corners or through tissue and to cameras that can optically separate unscattered from scattered light. Unfortunately, computer graphics have not kept up. Even though nowadays we have access to high-performance and fully-physically-accurate rendering engines for simulating images captured by regular cameras, access to similar tools for these emerging types of cameras is still scarce. This greatly hinders computational imaging research, making it difficult to perform simulated experiments or investigate imaging design considerations.
Therefore, the purpose of my project is to develop software tools to alleviate these issues. The focus of the project will be on an expanding existing physically-accurate renderer, Mitsuba, so that it can simulate various modern types of imaging, including structured light, epipolar imaging, transient imaging, speckle imaging and light transport probing. 
The challenge I need to face in this project is to combine my knowledge of computational imaging and computer graphics to make correct rendering software. The testing process of the rendering tool will involve simulation of some computational imaging experiments that I have not learned before. Thus, I need to self-study a lot of new computational imaging techniques and study new published papers in the field. 
If the project is successful, it can be used by experiments simulation by computational imaging groups in US and facilitate their research process.
### Project Goals
- 100 % Goal: Expand Mitsuba, an existing physically based renderer, to simulate various modern types of imaging, including structured light, epipolar imaging, transient imaging, speckle imaging, and light transport probing.
- 75% Goal: Expand Mitsuba with less functionalities mentioned in the 100% goal
- 125% Goal: Make a new graphical interface for new features I add on to the Mitsuba renderer.
### MileStones
- 15300 MileStone: Finish structured light and light transport probing simulation by the end of the semester
- 15400 MileStones:
- - Feb 1st: Start experiment with different library that facilitates calculation of epipolar imaging--
- - Feb 15th: Add epipolar imaging feature to Mitsuba, the code should work in some general cases.
- - March 1st：Test my rendering software against different epipolar imaging experiments
- - March 22nd: Add transient imaging feature to Mitsuba, the code should work in some general cases
- - April 5th: Test my rendering software against different transient imaging experiments
- - April 19th: Add speckle imaging feature to Mitsuba, the code should work in some general cases
- - May 3rd: Test my rendering software against different speckle imaging experiments
### Literature Search
	To test the correctness of my software, I need to simulate many new computational imaging experiments. Thus, I researched papers of experiments of this kind, for example, Homogeneous Codes for energy-efficient illumination and imaging, by Mathew O’tool. Also, I need to read more rendering textbooks to strengthen my knowledge of rendering. Physically based rendering will be a great coding book for me to start with.  
	
### Resources Needed
	I will need Mitsuba renderer to conduct my research. I already have it installed. Preferably, I need to run Mitsuba on Linux where the multi-threading function of Mitsuba works. However, because I only have a Mac myself, I need to run Mitsuba on a AWS Linux server, where I can run rendering processes with more parallelism. 


