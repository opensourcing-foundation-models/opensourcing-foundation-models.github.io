---
layout: default2
title: home
permalink: /
nav_order: 1
---

### Abstract

The open-sourcing paradigm for LLMs is largely shifting from only open-sourcing the final models to a more complete training recipe that allows everyone to reproduce the LLMs' training process, covering dataset preparation, training infrastructures, algorithm innovations, and evaluation.
This workshop aims to create a venue for the entire open-source community to get together to share recent achievements and collaborate for future open-source advances. It can also be a great chance for the NeurIPS community to participate and build upon the open-source ecosystem for research advances. The organizers will make their best efforts to link leading contributors from the US, China, and Europe for a global event.

### Invited Speakers

<div class="team-container">
    <div class="sponsor">
        <img src="/assets/img/speakers/ion_stoica.png" alt="Ion Stoica">
        <p><a href="https://people.eecs.berkeley.edu/~istoica/">Ion Stoica</a><br>UC Berkeley</p>
    </div>
    <div class="sponsor">
        <img src="/assets/img/speakers/junyang_lin.png" alt="Junyang Lin">
        <p><a href="https://justinlin610.github.io/">Junyang Lin</a><br>Alibaba Group</p>
    </div>
    <div class="sponsor">
        <img src="/assets/img/speakers/daya_guo.png" alt="Daya Guo">
        <p><a href="https://guoday.github.io/">Daya Guo</a><br>DeepSeek</p>
    </div>
    <div class="sponsor">
        <img src="/assets/img/speakers/noah_smith.png" alt="Noah Smith">
        <p><a href="https://nasmith.github.io/">Noah Smith</a><br>University of Washington & Allen Institute for AI</p>
    </div>
    <div class="sponsor">
        <img src="/assets/img/speakers/percy_liang.png" alt="Percy Liang">
        <p><a href="https://cs.stanford.edu/~pliang/">Percy Liang</a><br>Stanford University</p>
    </div>
    <div class="sponsor">
        <img src="/assets/img/speakers/leandro_von_werra.png" alt="Leandro von Werra">
        <p><a href="https://www.linkedin.com/in/lvwerra">Leandro von Werra</a><br>Hugging Face</p>
    </div>
</div>

### Organizers

<div class="team-container">
    <div class="team-member">
        <img src="/assets/img/organizers/yi_wu.png" alt="Yi Wu">
        <p><a href="https://jxwuyi.weebly.com/">Yi Wu</a><br>Tsinghua University & Ant Research</p>
    </div>
    <div class="team-member">
        <img src="/assets/img/organizers/haibin_lin.png" alt="Haibin Lin">
        <p><a href="https://sites.google.com/view/haibinlin/">Haibin Lin</a><br>ByteDance</p>
    </div>
    <div class="team-member">
        <img src="/assets/img/organizers/michael_luo.png" alt="Michael Luo">
        <p><a href="https://michaelzhiluo.github.io/">Michael Luo</a><br>UC Berkeley</p>
    </div>
    <div class="team-member">
        <img src="https://avatars.githubusercontent.com/u/35801754" alt="Zijian Zhang">
        <p><a href="https://www.linkedin.com/in/AndyZijianZhang/">Zijian Zhang</a><br>Tsinghua University & NVIDIA</p>
    </div>
    <div class="team-member">
        <img src="/assets/img/organizers/jiaxuan_gao.png" alt="Jiaxuan Gao">
        <p><a href="https://scholar.google.com/citations?user=UHSwL-wAAAAJ">Jiaxuan Gao</a><br>Tsinghua University & Ant Research</p>
    </div>
    <div class="team-member">
        <img src="/assets/img/organizers/chenyang_zhao.png" alt="Chenyang Zhao">
        <p><a href="https://zhaochenyang20.github.io/Chayenne/">Chenyang Zhao</a><br>UCLA & SGLang</p>
    </div>
    <div class="team-member">
        <img src="/assets/img/organizers/song_han.png" alt="Song Han">
        <p><a href="https://songhan.mit.edu/">Song Han</a><br>MIT & NVIDIA</p>
    </div>
</div>

### Program Committee

<html>
    <div class="team-container">
        <!-- <div class="team-member">
            <img src="/assets/img/organizers/olivier_pietquin.jpg" alt="Name 9">
            <p><a href="https://www.linkedin.com/in/opietquin/">Olivier Pietquin</a>
            <br>Cohere</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/kenny_smith.jpeg" alt="Name 9">
            <p><a href="http://www.lel.ed.ac.uk/~kenny/">Kenny Smith</a>
            <br>University of Edinburgh</p>
        </div> -->
    </div>
</html>

<style>

.button-container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px; /* Adjust the gap as needed */
    margin: 20px 0; /* Add some margin to the container */
}

.custom-button {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 8px;
}

/* Style for the team container */
.team-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* Display 3 members per row */
    gap: 5px;
    max-width: 1024px;
    padding: 20px;
}

@media (max-width: 512px) {
    .team-container {
        grid-template-columns: repeat(1, 1fr); /* Display 2 members per row on smaller screens */
    }
}

/* Style for each team member */
.team-member {
    text-align: center;
    /* background-color: #fff; */
    padding: 0px;
    width: 260px; /* Set a fixed width for consistent circle appearance */
    height: 260px; /* Set a fixed height for consistent circle appearance */
    /* box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1); */
    overflow: hidden; /* Hide any image overflow */
}

.team-member h3 {
    font-size: 16px;
    color: #333;
}

.team-member img {
    object-fit: cover;
    border-radius:50%;
    width: 200px;
    height: 200px;
    padding: 10px;
}

.sponsor-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    max-width: 1024px;
    padding: 20px;
}

.sponsor {
    flex: 0 0 calc(33.333% - 20px); /* Adjust width to account for gap */
    max-width: 280px;
    display: flex;
    flex-direction: column;
    text-align: center;
    font-size: 18px;
    font-weight: bold;
}

.sponsor img {  
    width: 100%;
    height: 280px;
    object-fit: cover;
    padding: 5px;
}

.caption {
    margin-top: 12px;
    flex-grow: 1;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
}

@media (max-width: 768px) {
    .sponsor {
        flex: 0 0 calc(50% - 20px); /* 2 columns on medium screens */
    }
}

@media (max-width: 468) {
    .sponsor {
        flex: 0 0 100%; /* 1 column on smaller screens */
    }
}

.right-half {
    flex: 1; /* Each figure takes up 50% of the available width */
    height: 500px; /* Set a fixed height for all figures (adjust the value as needed) */
}

.news-box {
    border: 1px solid #ccc;
    padding: 10px;
    width: 600px;
    margin: 0 auto;
    background-color: #f9f9f9;
}

@media (max-width: 600px) {
    .news-box {
        width: 100%; /* Adjust width to fit the screen */
    }
}
</style>

<br><br>
