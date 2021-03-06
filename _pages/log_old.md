---
layout: default
title: Work Log (Old)
---

<h3 class="collapsible">Week of October 4, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Learn how the Traffic Generator Hardware works.</li>
    <li>Begin learning how the NetFPGA switch works.</li>
    <li>Possibly start a rough design of a reference switch.</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
  <ul>
    <li><strong>Monday</strong>:
      <ul>
        <li>Updated documentation in GitHub repo to have a link to the repo that the traffic generator design is based on.</li>
      </ul>
    </li>
  </ul>
  </div>
</div>

<h3 class="collapsible">Week of September 27, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Validate traffic generator with wireshark.</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
  <ul>
    <li><strong>Monday</strong>:
      <ul>
        <li>Looked at code for traffic generator, and verified that the packets it's generating are being sent by the ZedBoard.</li>
      </ul>
    </li>
  </ul>
  </div>
</div>


<h3 class="collapsible">Week of September 13, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Validate traffic generator with wireshark.</li>
    <li>Read up on Xilinx TEMAC IP core.</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
  <ul>
    <li><strong>Monday</strong>:
      <ul>
        <li>Looked a little more into the code for the traffic generator.</li>
        <li>Tried figuring out how to program the NetFPGA board with the bit file I generated.</li>
      </ul>
    </li>
    <li><strong>Wednesday</strong>:
      <ul>
        <li>Using wireshark, got a packet capture of traffic from one of the traffic generator ethernet ports. Validated that tons of TCP packets were being sent.</li>
      </ul>
    </li>
  </ul>
  </div>
</div>

<h3 class="collapsible">Week of September 6, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Verify that the traffic generator works properly</li>
    <li>Understand better how the traffic generator works</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
  <ul>
    <li><strong>Monday</strong>:
      <ul>
        <li>Got necessary boards for testing the traffic generator from Dr. Wirthlin</li>
        <li>Started looking into the code for the traffic generator.</li>
      </ul>
    </li>
  </ul>
  </div>
</div>

<h3 class="collapsible">Week of August 30, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Finish building traffic generator on the zed board</li>
    <li>If there's time, look at network switch design for the zed board.</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
  <ul>
    <li><strong>Monday</strong>:
      <ul>
        <li>Finished building the traffic generator for the ZedBoard.</li>
        <li>Updated a lot of the documentation in <strong>fpga-networking-reliability</strong> to reflect all the problems I ran into when going through the building process.</li>
      </ul>
    </li>
    <li><strong>Wednesday</strong>:
      <ul>
        <li>Read up on the Ethernet FMC boards a little bit</li>
        <li>Looked at the switch design for the NetFPGA</li>
      </ul>
    </li>
  </ul>
  </div>
</div>

<h3 class="collapsible">Week of August 16, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Build the Reference Switch</li>
    <li>Start work on building the Traffic Generator</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
  <ul>
    <li><strong>Monday</strong>:
      <ul>
        <li>Verified that the reference switch generated a bitstream successfully.</li>
        <li>Started work on debugging why Arch won't boot on the ZedBoard</li>
      </ul>
    </li>
  </ul>
  <ul>
    <li><strong>Tuesday</strong>:
      <ul>
        <li>Got Arch Linux booting on a different Zedboard, verifying that my problem before was indeed the broken flash.</li>
        <li>Added a lot of clarifications and formatting updates to the documentation about setting up the traffic generator on the ZedBoard.</li>
        <li>Started working through setting up the traffic generator on the ZedBoard.</li>
      </ul>
    </li>
  </ul>
  </div>
</div>

<h3 class="collapsible">Week of August 9, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Get more familiar with FPGA networking reliability repo</li>
    <li>Attempt to get everything in that repo set up.</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
  <ul>
    <li><strong>Tuesday</strong>:
      <ul>
        <li>Got Vivado 2018.2 installed.</li>
        <li>Began going through the steps for building the reference switch onto NetFPGA.</li>
      </ul>
      <ul>
        <li><strong>Thursday</strong>:
          <ul>
            <li>Figured out the issue Vivado and the xc7k325t part.</li>
            <li>Started a build of the reference switch to be checked on Monday.</li>
          </ul>
        </li>
      </ul>
    </li>
  </ul>
  </div>
</div>


<h3 class="collapsible">Week 10: June 28, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Continue going through 427 labs.</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
  <ul>
  </ul>
  </div>
</div>

<h3 class="collapsible">Week 9: June 21, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Finish reading <em>Neutron Beam Testing Methodology and Results for a Complex Programmable Multiprocessor SoC</em></li>
    <li>Familiarize myself with the Zed Board</li>
    <li>Go through 427 labs.</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
  <ul>
    <li><strong>Monday</strong>:
      <li>Got PYNQ board for starting work on 427 labs.</li>
      <li>Read some documentation on the Zedboard.</li>
    </li>
    <li><strong>Tuesday</strong>:
      <li>Played around with the PYNQ board, and then found the correct website for the 427 labs.</li>
      <li>Started work on 427 Lab 1.</li>
    </li>
    <li><strong>Friday</strong>:
      <li>Debugged the network issues I was having with the Pynq board.</li>
      <li>Finished ECEn 427 Lab 1 and started working on Lab 2</li>
    </li>
  </ul>
  </div>
</div>

<h3 class="collapsible">Week 8: June 14, 2021</h3>
<div class="content">
  <em>Nothing from this week.</em>
</div>

<h3 class="collapsible">Week 7: June 7, 2021</h3>
<div class="content">
  <h5 class="collapsible">Goals</h5>
  <div class="sub-content">
  <ul>
    <li>Finish reading <em>Neutron Beam Testing Methodology and Results for a Complex Programmable Multiprocessor SoC</em></li>
    <li>Build Linux Kernel for the Zed Board</li>
  </ul>
  </div>
  <h5 class="collapsible">Log</h5>
  <div class="sub-content">
  <ul>
    <em>Didn't manage to get anything done this week.</em>
  </ul>
  </div>
</div>

<h3 class="collapsible">Week 6: May 31, 2021</h3>
<div class="content">
  <em>Nothing from this week.</em>
</div>

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
      <li><strong>Monday</strong>:
        <ul>
          <li>Finished reading <em>High Throughput FPGA Configuration Using a Custom DMA Configuraiton Controller</em></li>
          <li>Verified that basic linux kernel workds on Ultra96v1</li>
          <li>Built PCAP scrubber app and driver and got them working on the Ultra96v1.</li>
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
