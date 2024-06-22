---
title: 
date: 2024-06-11
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: 'github.cqelab.resume-projects'
    content:
      title: Superconducting Quantum Circuits
      text: |-
        Our superconducting qubit is a nano-fabricated electrical circuit made of superconducting aluminum thin-film structures on a high-resistivity Silicon substrate. When the device is cooled down to very close to absolute zero temperature (~10 mK) in our dilution refrigerators, it operates in the quantum regime, acting like an artificial atom, or in other words, a quantum bit (qubit). 

        <div style="width: 70%; margin: auto; text-align: justify;">
          <div style="text-align: center;">
            <img src="SCQ_circuit.jpg" alt="Micrograph of a superconducting qubit" style="width: 100%; display: block; margin: auto;">
          </div>

          **Fig** Micrograph (false colored) of a hybrid superconducting transmon qubit device. The qubit (orange) couples to its dedicated λ/4 readout (RO) resonator (turquoise), Z-control line (green), and XY-control line (blue). The entire device area, as outlined by the pink lines, is suspended on the 220 nm thick Si device layer, which is released from the underlying 3 μm thick oxide BOX layer of the Silicon-on-Insulator (SOI) chip.
        </div>

        We have the freedom to design Hamiltonian parameters for individual qubits (imagine creating your own periodic table for these artificial atoms!), and for the interaction between qubits. We develop exquisite quantum control of qubits and create distinct quantum phenomena like superposition and entanglement, using on-chip microwave circuits and room temperature electronics like arbitrary waveform generators, IQ mixers, and FPGAs. 
        

  - block: 'github.cqelab.resume-projects'
    content:
      title: Atomic-Scale Defects
      text: |-
        Material defects are ubiquitous. Seven decades ago, defects posed a significant challenge to the newborn semiconductor industry, and today they continue to be a major obstacle for the emerging quantum technology. In particular, the performance of solid-state quantum devices, such as superconducting quantum bits (qubits), is limited by atomic-scale defects at material surfaces and interfaces, posing a significant bottleneck to their scalability and practical utility. On the other hand, atomic-scale defects, once well-characterized, could be engineered into a useful quantum resource, as in the case of spin color centers in diamond.

        This research aims to gain a profound understanding of the material defects in superconducting quantum circuits, and to engineer the defects in our favor for next-generation solid-state quantum devices for quantum computation, quantum sensing, and quantum communication.

      # Upload project images to your `assets/media/` folder and reference the filename in the `image` option
      items:
        - title: Two-Level Systems (TLS)
          description: Two-Level System (TLS) defects are ubiquitous in amorphous materials. This includes all the surfaces and interfaces, making them the dominant source of energy relaxation for superconducting qubits. Their microscopic origin remains unknown.
          image: TLS_schematic.png
          url: ''
        - title: Thermally-activated Fluctuators (TF)
          description: Thermally-activated Fluctuators (TF), sometimes also called Two-Level Fluctuators (TLF). Many believed TF to be the source of the ubiquitous 1/f noise.
          image: TF_schematic.png
          url: ''

  - block: 'github.cqelab.resume-projects'
    content:
      title: Nanophononics
      text: |-
        Coming soon!


---
