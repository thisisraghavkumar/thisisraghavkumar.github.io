# Raghav Kumar
Last updated: 24 December, 2024

<style>
    @media (max-width: 768px) {
    #introcontainer {
      flex-direction: column;
    }
    #imgcontainer {
        width: 100%;
        align-self: center;
    }
  }
</style>

<div id="introcontainer" style="
    display: flex;
    align-items: flex-start;
    gap: 20px;
">
    <div id="imgcontainer" style="flex-shrink: 0;height: auto;max-width: 40%;">
        <img src="files/selfie.jpeg" alt="Profile Photo of Raghav Kumar" style="height: 290px;width: 100%;">
    </div>
    <div>
        <p>
            I'm a first year MS student at <b>The Pennsylvania State University, University Park</b> in College of Engineering studying Computer Science & Engineering. Before resuming my academic journey I had worked at Microsoft, Hyderabad as a Software Engineer for 4 years.
        </p>
        <p>
            I love to read, especially about History and Economics to learn about how we got here. I would humbly recommend you to check out the following works that have inspired me
            <ol>
                <li>Ayn Rand (The Fountainhead and Atlas Shrugged)</li>
                <li> Dale Carnegie (How to Win Friends and Influence People)</li>
                <li> <a href="https://acharyaprashant.org/">Acharya Prashant</a></li>
                <li> <a href = "https://www.youtube.com/playlist?list=PLIG8a9wNRHVu-Aw2VgUJacXlpsJMbF5Y_">Everything is Everything Podcast</a></li>
                <li><a href="http://bastiat.org/fr/cqovecqonvp.html">What we see and what we don't see</a> by Frédéric Bastiat</li>
            </ol>
        </p>
    </div>
</div>

Few interesting things that I have come across recently
1. [My Resume](files/Raghav_Kumar_Resume.pdf), well obviously.
2. I'm currently working on a semester long project to find out algortihmic or AI based methods to detect unexpected behaviour in systems built on Cardano. You can find our first draft proposal [here](https://github.com/thisisraghavkumar/MyLearnings/blob/master/Courses/CSE%20597-7%20PSU%20Sec%20Analysis%20of%20Emerging%20Systems/Research_Proposal.pdf).
3. **Machine Learning** is magic of mathematics. One set of tricks involves enlarging the input into many dimensions, which should make it more expressive and easier to learn. This can be done via the kernel trick (theoretically expanding input to infinite dimensions but only using output of a "kernel" function), or randomly sampling thousands of the infinite features, or multiplying the input with a random matrix obtaining a Gaussian projection. All these tricks should make the data easier to learn and the resulting model more accurate. Furthermore, linear classification can be done using either Stochastic Gradient Descent, or Support Vector Machines. So which pair of feature expansion and linear classifier works best? Check out the image below and head to [this Github page of mine](https://github.com/thisisraghavkumar/MyLearnings/blob/master/Courses/CSE%20597-8%20PSU%20Deep%20Neural%20Networks/Technique%20compare%20on%20titanic.md).
![graph showing comparative accuracy of linear classifier and feature expansion techniques](/files/output_9_0.png)
4. GPUs make computations fast, especially when you want to perform the same operation on all pieces of data. Multiplying two matrices is a computing problem which fits this bill perfectly. However, all code to compute matrix mutliplication using a GPU is not created equal, and some techniques are better than others. See the chart below and head to [this github repo](https://github.com/thisisraghavkumar/GPU_MatMul_Optimizations) to learn more.
![a chart showing performance of matrix multiplication CUDA codes](/files/Size%20obsv.001.png)
5. [My Writing.com Portfolio](https://www.writing.com/main/portfolio/view/kumarrg03)