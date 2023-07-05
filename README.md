![image](https://github.com/RIOSMPW/OpenSTDCell28/assets/100336131/902693d2-d390-476e-a3be-bf9a23f79c36)


# OpenSTDCell28

OpenSTDCell28 is short for Open standard cell library for open 28nm process.

An Open Standard Cell Library 28nm is a library of standard cells that is provided to the public without any licensing or copyright restrictions. The library is made up of pre-designed and pre-characterized standard cells that can be used in the design of integrated circuits.

The 28nm process node refers to the size of the transistors used in the library. A smaller process node allows for more transistors to be placed on a chip, leading to higher performance and lower power consumption.

Open Standard Cell Library 28nm is beneficial for designers who want to reduce the cost of designing an integrated circuit. The availability of a free and open-source library reduces the cost of licensing proprietary libraries and allows designers to focus on the actual design rather than the cost of the library.

In addition, the open-source nature of the library allows for customization and modification to meet the specific needs of a particular project. An Open Standard Cell Library 28nm is a valuable tool for designers who want to create custom integrated circuits.

Overall, an Open Standard Cell Library 28nm is an important resource for designers who want to create custom integrated circuits. The availability of a free and open-source library reduces the cost of designing an integrated circuit and allows for customization to meet the specific needs of a project.

## Standard Cell Library(SCL)

A standard cell library is a collection of pre-designed and pre-characterized digital logic circuits. These circuits are typically used in the design of integrated circuits. Standard cell libraries are designed to be reusable and modular, allowing designers to quickly and easily create complex circuits by combining pre-designed cells.

Standard cell libraries are an important tool for digital circuit designers, as they can significantly reduce the time and cost of designing a chip. Rather than designing every individual logic gate from scratch, designers can simply select the appropriate pre-designed cell from the library and connect them together to create the desired circuit.

Standard cell libraries are typically developed by semiconductor companies or third-party vendors and are often licensed for use by other companies. However, there are also open-source standard cell libraries available, such as the Open Standard Cell Library 28nm described in this document.

![b1bb7779196a46d0191c8ba78af8e6bf_Layout-of-cells-in-the-Standard-Cell-Library](https://github.com/RIOSMPW/OpenSTDCell28/assets/100336131/d5cb76f5-faf4-42b2-8e6c-a684dfbabf02)
Layout of cells in the Standard Cell Library(Source:Wei Man Chim)

In addition to reducing the time and cost of chip design, standard cell libraries also help to ensure design consistency and accuracy. By using pre-characterized cells, designers can be confident that the circuit will behave as expected and meet the desired specifications.

Overall, standard cell libraries are a valuable tool for digital circuit designers, allowing them to create complex circuits quickly, efficiently, and accurately.

## Design Flow of Standard Cell Library

The economic and efficiency of an ASIC design depends heavily upon the choice of the library. Hence it is important to build library that full fills the design requirement. The typical design flow of a SCL consists in designing a set of logical gates at the transistor level for a given technology process.

The design process begins with a specification that defines the system's logical and electrical requirements, including frequency, signal processing, and performance metrics. The design team then creates a high-level architecture of the system, identifying the main components and their connections. Using simulation, modeling, and testing, each component is then designed and optimized for performance, reliability, and manufacturability. The design is verified and validated through tests to ensure it meets specifications and performs well under different conditions.

We meticulously design and develop the Schematic to meet and exceed customer requirements, using the latest technology and industry best practices to ensure functionality, efficiency, reliability, and ease of use. Our experienced team follows a rigorous design process to deliver a high-quality product that exceeds customer expectations and results in a successful partnership.



![image](https://github.com/RIOSMPW/OpenSTDCell28/assets/100336131/d4420266-bcc5-4ea5-bad4-e631fc643caa)

Design Flow of a Standard Cell Library and the Tools used(Source:Sangmesh Melinmani)

Next, the layout is completed for each of the cells. Once the layout is confirmed to be clean of any design rule checking (DRC) and layout versus schematic (LVS) issues, an automated extraction tool is used to obtain the extracted circuit. This circuit includes not only the transistors that were drawn, but also all of the parasitics that were generated from the physical layers.

By obtaining a more realistic view, we can simulate and characterize the electrical behavior of the designed gate. The output of this characterization is stored in .LIB format, which can be used by the synthesizer. If the required specifications are not met, the layout is altered and re-characterized. With the electrical characteristics of each gate, a circuit can be synthesized from a high-level description.

Once the cells are characterized an abstract view of the layout is generated by the abstract generator. With the abstract views the P&R tool can easily assemble the IC from these predesigned blocks. The physical characteristics of the cells are in the .LEF file.

## About RIOS Lab

![image](https://github.com/riosmpw/OpenRPDK28/assets/109063674/6aae13c6-50a5-40c3-9a4e-ed4c79d41c20)


**Ecosystem Wants to be Free**

By David A. Patterson · Director of RIOS Lab

**RISC-V International Open Source Laboratory** (RIOS Lab) is a Shenzhen-based research facility focused on computer system architecture, supported by the Tsinghua-Berkeley Shenzhen Research Institute. As an Open Source and Nobel Prize Laboratory, RIOS Lab promotes open-source innovation and collaboration. Our philosophy is that the computer architecture ecosystem should be free for all to access and build upon.

In November 2019, RIOS Lab was officially unveiled. Under the leadership of 2017 A.M. Turing Award winner Prof. David A. Patterson and operational support from TBSI,  RIOS Lab will conduct cutting-edge research in RISC-V hardware and software technology. Patterson first proposed the Reduced Instruction Set Computer (RISC), an open and free instruction set architecture enabling a new era of processor innovation through open standard collaboration. Released in 2010, the latest Fifth Generation RISC has gained worldwide attention.

The name for the lab RIOS is also inspired by the Spanish word for “rivers.” It symbolizes the flow of information from many sources, coming together to create a whole that is greater than the sum of its parts.


