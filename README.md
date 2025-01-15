# SPR-GRIP-Guided-Reflectance-and-Precision-Measurement

GRIP-SPR

 

**SPR-GRIP**: **G**uided **R**eflectance and **P**recision **M**easurement

 

I enjoy working with a team on electronics, thin film technology, and biosensor topics.

 

http://www.lab.agh.edu.pl/

 

For the project, we have developed a Surface Plasmon Resonance (SPR) spectroscopy bench that automatically selects the optimal angle at which the highest plasmon resonances occur. 

The stand can operate in manual and automatic modes. In automatic mode, we check 3600 positions, giving more than 5 million points for analysis.

 

Our team developed the project over several months and required the competence and commitment of all team members.

![image](https://github.com/user-attachments/assets/2ea0bf25-9229-4a7c-b470-3db6a07ca8eb)

GRIP-SPR: Guided Reflectance and Precision Measurement
Learning the basics of SPR brings many educational values to different levels of education, from high school to college to PhD studies.

 

Here are some of the leading educational values and phenomena that can be explained on its basis:

 

SPR is an excellent tool for understanding surface plasmons or the oscillations of electrons at the metal-air interface. Learning about this phenomenon helps us understand the physics of electromagnetic waves and their interactions with matter, which has applications in many fields, such as optics and nanotechnology.

 

SPR makes it possible to explain how the intensity of light reflection changes depending on the change in refractive index, which is related to the presence of adsorbed molecules on the surface. This project is an excellent opportunity to learn about reflection, refraction, and wave interference phenomena.

SPR provides an opportunity to learn about this technology's applications in various fields, from molecular biology (in medical diagnostics and drug research) to chemistry and materials, where it is used to analyze thin-film coatings, nanostructured materials, or catalysts.

 

One crucial educational advantage of SPR is the real-time monitoring of molecular interactions. It introduces students to the kinetics of chemical reactions and the dynamics of molecular processes.

Through SPR, students can better understand complex biological and physical processes and learn how advanced technologies can solve real-world problems in the life sciences.

 

**Basic explanation:**

 

Surface plasmons are like "dancing" electrons on the surface of a metal. Imagine that the metal is a pond, and the electrons are small fish swimming in the water. When light (like sunlight) shines on the pond (the metal), some fish start moving to the rhythm of the light, creating waves in the water. These waves are surface plasmons. Instead of fish in the water, we have electrons on the metal surface.

![image](https://github.com/user-attachments/assets/422ae3c9-50f0-4bfa-844c-cbb8771781b5)

Basic explanation - surface plasmon resonance
**Key things to remember:**

Plasmons are electron waves. When light hits metal, the electrons on the surface start "swaying," creating waves.
They are on the surface – Surface plasmons are waves that don't spread throughout the metal but only on its surface, like waves on a pond.
They interact with light – Plasmons are created when light interacts with these electrons on the metal surface. It's like the light "pushes" the electrons into a dance.
 

**But from the beginning:**

 

SPR spectroscopy was developed in the 1970s by researchers at Lund University, including Erik Nylander, Knut Strömberg, and Pär Liedberg, who were the first to experimentally use the phenomenon of surface plasmons to analyze changes in the intensity of light reflected from thin-film metallic coatings. In the 1980s, the technique was refined and used in advanced research, and in the 1990s [1-3]. SPR has found widespread use in biotechnology, especially biosensors, to study biomolecular interactions such as proteins and DNA [4,5].

 

**SPR spectroscopy principle:**

 

Generation of surface plasmons: SPR is based on the resonance phenomenon of surface plasmons. Surface plasmons are electron waves that oscillate at the metal-air or metal-solution interface when the light of the appropriate wavelength is incident on the metal surface.

 

When light falls on a metallic surface at the right angle, resonance can occur between the light wave and surface plasmons. This phenomenon occurs only when the angle of incidence, the wavelength of light, and the material's refractive indices meet certain conditions. As a result, with resonance, some of the light energy is transferred to electrons on the metal surface, leading to a reduction in the intensity of the reflected light.

 

**Genesis of the project:**

 

A dedicated measurement stand was created to provide independent arm movement from 10 to 75 degrees to find the optimum resonance angle. The bench integrates a spectrometer (Ocean ST) operating from 350 to 800 nm and is controlled using the Arduino platform. In addition, the bench can be controlled from a PC using a python script and the spectrometer's API, making it easy to check all possible combinations of arm positions. Once the measurements are finished, the system generates a heatmap showing the arms' position and the maximum values measured during a given measurement.

![image](https://github.com/user-attachments/assets/70e6d3b7-81c8-481e-8d51-63c5ef677963)

Test heatmap with the five most significant values (marked)
This allows for quick and accurate analysis of the results depending on the angle and other parameters. The control uses an Arduino Mega with an LCD shield, two rotary encoders, a CNC shield with TMC2208 motors, and two reality stepper motors.

![image](https://github.com/user-attachments/assets/49adfb5c-83f1-4dab-9970-8e38dd91bcdd)

3D CAD model test stand
**The project includes:**

 

- Adjustable movable table

- 38x16mm sample holder

- Sample Holder

- Two arms on which the detector and illuminator are mounted

- Disk for easier visualization of the angle 

- Body

 

All parts are mounted on a 200x200mm optical plate with M6x16 screws and were printed from PETG on a BambLab A1 printer. 

 

An example of the characteristics of one scan depending on the angle can look like this.

![image](https://github.com/user-attachments/assets/d67ba9ec-9ce9-4037-a7dd-6e62f0e43327)

SPR Scanning Angle Response. SPR causes an intensity dip in the reflected light at the sensor surface. A shift in the curve represents molecular binding [6].
The angle at which the SPR resonance occurs changes for different concentrations and types of molecules adsorbed on the surface. By measuring these changes, information about the kinetics of the interaction, the number of molecules bound, and the adsorption characteristics of the material under study can be obtained.

In our laboratories, we want to use the device for two primary purposes 

Analysis of thin-film coatings, such as SPR, can be used to study changes in the optical properties of thin-film coatings, e.g., for protective or catalytic coatings, including real-time studies of biosensors and microfluidics systems.

 

Suppose you are interested in such topics or are looking for partners for research in the deposition and testing of properties of thin films of electronics or biosensors. In that case, we invite you to cooperate with us.

The measurement stand was fabricated under the realization of the SONATA BIS 2022/46/E/ST7/00008 project funded by the Polish National Science Centre (NCN)

**Sources:**

[1] K. Scott Phillips and Q. Cheng. "Recent advances in surface plasmon resonance based techniques for bioanalysis." Analytical and Bioanalytical Chemistry, 387 (2007): 1831-1840. https://doi.org/10.1007/S00216-006-1052-7.

[2] D. Souto, Jaqueline Volpe, C. C. Gonçalves, C. Ramos and L. Kubota. "A brief review on the strategy of developing SPR-based biosensors for application to diagnose neglected tropical diseases.." Talanta, 205 (2019): 120122 . https://doi.org/10.1016/J.TALANTA.2019.120122.

[3] Samuel S. Hinman, Kristy S McKeating, and Q. Cheng. "Surface Plasmon Resonance: Material and Interface Design for Universal Accessibility.." Analytical Chemistry, 90 1 (2018): 19-39. https://doi.org/10.1021/acs.analchem.7b04251.

[4] Samuel S. Hinman, Kristy S McKeating, and Q. Cheng. "Surface Plasmon Resonance: Material and Interface Design for Universal Accessibility.." Analytical Chemistry, 90 1 (2018): 19-39. https://doi.org/10.1021/acs.analchem.7b04251.

[5] Wenqiao An, Zhihao Sun, Pengmei Guo, Xiaobo Wang, and Sanyin Zhang. "Real-Time Detection of Dynamic Affinity between Biomolecules Using Surface Plasmon Resonance (SPR) Technology.." Journal of visualized experiments: JoVE, 199 (2023). https://doi.org/10.3791/65946.

[6] https://biosensingusa.com/technologies/surface-plasmon-resonance/surface-plasmon-resonance-work/

 

