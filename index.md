
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
- - Feb 1st: Start experiment with different library that facilitates calculation of epipolar imaging
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


# Updated Proposal 
### What I have Accomplished so far
- Expanded Mitsuba renderer by perspective projector, orthographic projector, coded perspective camera and orthographic camera.
- Improve the performance of projectors with importance sampling.
- Test separation of direct and global components of scenes using high frequency illumination in extended Mitsuba renderer.

### Meeting My Milestone
Yes, I have met the milestone I described in my original project proposal. The coded perspective and orthographic cameras I implemented met my original milestone of finishing the structured light simulation. I am still working on the light transport probing simulation. To achieve this, I need to coordinate the projector and the camera so that the camera received lights coming from only certain rows or columns of an all-white perspective projector.
Surprises

I need to face some unexpected challenges like finding the best way to read a large c++ project. The good thing is that now I find a helpful IDE CLion to achieve this goald. Another surprise for me is that I found the testing my project takes a lot more time than what I have expected.  Sometimes it takes me weeks to actually have one feature of my project fully tested and it is still possible for me to find new bugs after I add new features to the project.

### Update for 15400 MileStones
I don’t want to change much to my 15400 Milestone. Yet, after doing research this semester, I think it is the best to push back a little some of my milestones since the time I have during a semester is far less than what I have expected.
Here is the updated milestone:

- Feb 1st: Start experiment with different library that facilitates calculation of epipolar imaging
- Feb 15th: Add epipolar imaging feature to Mitsuba, the code should work in some general cases.
- March 1st：Test my rendering software against different epipolar imaging experiments
- March 22nd: Add transient imaging feature to Mitsuba, the code should work in some general cases
- April 5th~ May 2nd:: Test my rendering software against different transient imaging experiments
- May 3rd: Add speckle imaging feature to Mitsuba, the code should work in some general cases 
	
### Resources Needed
Since some of the computation in our rendering process requires a large amount of resources than what I have expected, so I lent an AWS account from my professor to make some computational heavy rendering. Also, sometimes I need to buy some meshes to test out my rendering algorithms

