---
layout: default
title: Work Log
---
<h3 class="collapsible">Week 5: May 24, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Finish reading <em>High Throughput FPGA Configuration Using a Custom DMA Configuration Controller</em></li>
    <li>Test custom linux kernel on Ultra96v1</li>
    <li>Get PCAP scrubber working on the Ultra96v1</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
    <ul>
      <li><strong>Monday:</strong>:
        <ul>
          <li>Finished reading <em>High Throughput FPGA Configuration Using a Custom DMA Configuraiton Controller</em></li>
        </ul>
      </li>
    </ul>
  </div>
</div>

<h3 class="collapsible">Week 4: May 17, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Finish reading <em>Configuration Scrubbing Architectures for High-Reliability FPGA Systems</em></li>
    <li>Start reading <em>High Throughput FPGA Configuration Using a Custom DMA Configuration Controller</em></li>
    <li>Rebuild Linux kernel for Ultra96v1 and update the documentation.</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
    <ul>
      <li><strong>Monday</strong>:
        <ul>
          <li>Successfully rebuilt linux kernel for Ultra96v1 and submitted some updates for the documentation in <strong>byuccl/DTRA-URA</strong> repo.</li>
        </ul>
      </li>
      <li><strong>Tuesday</strong>:
        <ul>
          <li>Finished reading <em>Configuration Scrubbing Architectures for High-Reliability FPGA Systems</em></li>
        </ul>
      </li>
    </ul>
  </div>
</div>

<h3 class="collapsible">Week 3: May 10, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
    <ul>
      <li>Finish reading <em>Configuration Scrubbing Architectures for High-Reliability FPGA Systems</em></li>
      <li>Get Xilinx Tools set up on research machine</li>
      <li>Possibly rebuild Linux kernel for Ultra96v1 and update documentation where necessary.</li>
    </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
    <ul>
      <li><strong>Tuesday</strong>:
        <ul>
          <li>Got Vivado and PetaLinux 2019.2 set up on research computer.</li>
        </ul>
      </li>
    </ul>
  </div>
</div>

<h3 class="collapsible">Week 2: May 3, 2021</h3>
<div class="content">
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
    <ul>
      <li><strong>Monday</strong>:
        <ul>
          <li>Read abstracts for the following theses:
            <ul>
              <li><em>Configuration Scrubbing Architectures for High-Reliability FPGA Systems</em> - Aaron G. Stoddard</li>
              <li><em>High Throughput FPGA Configuration Using a Custom DMA Configuration Controller</em> - Peter W. Zabriskie</li>
              <li><em>Neutron Beam Testing Methodology and Results for a Complex Programmable Multiprocessor SoC</em> - Jordan D. Anderson</li>
            </ul>
          </li>
        </ul>
      </li>
    </ul>
  </div>
</div>

<h3 class="collapsible">Week 1: April 26, 2021</h3>
<div class="content">
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
    <ul>
      <li><strong>Monday</strong>:
        <ul>
          <li>Met with Dr. Wirthlin to discuss project for the fall, as well as went to IMMERSE orientation meeting.</li>
        </ul>
      </li>
      <li><strong>Tuesday</strong>:
        <ul>
          <li>Went through MPSoC notes that I wrote from last year.</li>
        </ul>
      </li>
      <li><strong>Wednesday</strong>:
        <ul>
          <li>Got Ubuntu installed on new computer in graduate student office.</li>
        </ul>
      </li>
      <li><strong>Thursday</strong>:
        <ul>
          <li>Got more software installed on new computer to get ready to work.</li>
          <li>Got GitHub site up and running.</li>
        </ul>
      </li>
    </ul>
  </div>
</div>

<script>
    let coll = document.getElementsByClassName("collapsible");
    let i;
    for (i = 0; i < coll.length; i++) {
        coll[i].addEventListener("click", (e) => {
            e.target.classList.toggle("active");
            let content = e.target.nextElementSibling;
            if (content.style.maxHeight) {
                content.style.maxHeight = null;
            }
            else {
                content.style.maxHeight = "500px";
            }
        });
    }
</script>
