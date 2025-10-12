---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a Postdoctoral Researcher in the [Autonomous Vision Group](https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/autonomous-vision/home/) at the University of Tübingen, working with [Prof. Andreas Geiger](https://www.cvlibs.net/). 
I received my DPhil in Engineering in 2025 from the [Active Vision Lab](https://www.robots.ox.ac.uk/~lav/) at the University of Oxford, under the supervision of [Prof. Victor Adrian Prisacariu](https://www.robots.ox.ac.uk/~victor/) and [Prof. Andrea Vedaldi](https://www.robots.ox.ac.uk/~vedaldi). Prior to that, I completed my MEng at Oxford, graduating with First-Class Honours.
My research focuses on reconstructing and understanding the 3D world from images and videos.

## Work Experience

* **University of Tübingen, Tübingen, Germany** (October 2025 - Present)
  * Postdoctoral Researcher
  * 3D reconstruction and scene understanding from images and videos

* **Niantic Labs, London, UK** (July 2024 - March 2025)
  * Research Intern
  * 3D mapping and visual localisation

* **Meta Reality Labs, Sunnyvale, US** (August 2023 - January 2024)
  * Research Intern
  * 3D understanding for indoor scenes

## Publications

<div class="publications-scroll">
  <div class="scroll-container">
    <div class="scroll-wrapper">
      <div class="publication-card">
        <h3>Seeing in the Dark: Benchmarking Egocentric 3D Vision with the Oxford Day-and-Night Dataset</h3>
        <p class="venue">NeurIPS 2025</p>
        <p class="authors">Zirui Wang¹, <strong>Wenjing Bian</strong>¹, Xinghui Li¹, Yifu Tao, Jianeng Wang, Maurice Fallon, Victor Adrian Prisacariu</p>
        <a href="https://oxdan.active.vision" target="_blank">Project Page</a>
        <img src="/images/odan.png" alt="Oxford Day-and-Night Dataset">
      </div>
      
      <div class="publication-card">
        <h3>Scene Coordinate Reconstruction Priors</h3>
        <p class="venue">ICCV 2025</p>
        <p class="authors"><strong>Wenjing Bian</strong>, Axel Barroso-Laguna, Tommaso Cavallari, Victor Adrian Prisacariu, Eric Brachmann</p>
        <a href="https://nianticspatial.github.io/scr-priors/" target="_blank">Project Page</a>
        <img src="/images/scr.png" alt="Scene Coordinate Reconstruction Priors">
      </div>
      
      <div class="publication-card">
        <h3>CatFree3D: Category-agnostic 3D Object Detection with Diffusion</h3>
        <p class="venue">3DV 2025 Oral</p>
        <p class="authors"><strong>Wenjing Bian</strong>, Zirui Wang, Andrea Vedaldi</p>
        <a href="https://bianwenjing.github.io/CatFree3D/" target="_blank">Project Page</a>
        <img src="/images/catfree.png" alt="CatFree3D">
      </div>
      
      <div class="publication-card">
        <h3>CrossScore: Towards Multi-View Image Evaluation and Scoring</h3>
        <p class="venue">ECCV 2024</p>
        <p class="authors">Zirui Wang, <strong>Wenjing Bian</strong>, Victor Adrian Prisacariu</p>
        <a href="https://crossscore.active.vision/" target="_blank">Project Page</a>
        <img src="/images/crossscore.png" alt="CrossScore">
      </div>
      
      <div class="publication-card">
        <h3>PoRF: Pose Residual Field for Accurate Neural Surface Reconstruction</h3>
        <p class="venue">ICLR 2024</p>
        <p class="authors">Jiawang Bian, <strong>Wenjing Bian</strong>, Victor Adrian Prisacariu, Philip Torr</p>
        <a href="https://porf.active.vision/" target="_blank">Project Page</a>
        <img src="/images/porf.png" alt="PoRF">
      </div>
      
      <div class="publication-card">
        <h3>NoPe-NeRF: Optimising Neural Radiance Field with No Pose</h3>
        <p class="venue">CVPR 2023 Highlight</p>
        <p class="authors"><strong>Wenjing Bian</strong>, Zirui Wang, Kejie Li, Jiawang Bian, Victor Adrian Prisacariu</p>
        <a href="https://nope-nerf.active.vision/" target="_blank">Project Page</a>
        <img src="/images/nopenerf.png" alt="NoPe-NeRF">
      </div>
      
      <div class="publication-card">
        <h3>Ray-ONet: Efficient 3D Reconstruction From A Single RGB Image</h3>
        <p class="venue">BMVC 2021</p>
        <p class="authors"><strong>Wenjing Bian</strong>, Zirui Wang, Kejie Li, Victor Adrian Prisacariu</p>
        <a href="https://rayonet.active.vision/" target="_blank">Project Page</a>
        <img src="/images/rayonet.png" alt="Ray-ONet">
      </div>
    </div>
  </div>
</div>

<style>
.publications-scroll {
  margin: 20px 0;
  position: relative;
}

.scroll-container {
  width: 100%;
  max-width: 800px;
  margin: 0 auto;
  padding: 20px 0;
}

.scroll-wrapper {
  display: flex;
  flex-direction: column;
  gap: 30px;
  padding: 0 20px;
}

.publication-card {
  width: 100%;
  padding: 25px;
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
  display: flex;
  flex-direction: column;
  text-align: center;
  box-sizing: border-box;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.publication-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.15);
}

.publication-card h3 {
  font-size: 1.2em;
  margin-bottom: 10px;
  color: #333;
  line-height: 1.3;
}

.publication-card .venue {
  font-weight: bold;
  color: #666;
  margin-bottom: 15px;
  font-size: 1em;
}

.publication-card .authors {
  margin-bottom: 20px;
  color: #555;
  font-size: 0.9em;
  line-height: 1.4;
}

.publication-card a {
  color: #007acc;
  text-decoration: none;
  margin-bottom: 20px;
  font-weight: 500;
}

.publication-card a:hover {
  text-decoration: underline;
}

.publication-card img {
  max-width: 100%;
  max-height: 250px;
  width: auto;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  object-fit: contain;
}

@media (max-width: 768px) {
  .publication-card {
    padding: 20px;
  }
  
  .publication-card h3 {
    font-size: 1.1em;
  }
  
  .scroll-wrapper {
    gap: 20px;
    padding: 0 15px;
  }
}
</style>


<!-- <br>

For a complete list of publications, please see my [publications page](/publications/). -->
