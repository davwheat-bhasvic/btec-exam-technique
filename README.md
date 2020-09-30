<p align="center">
  <img src="../../../common-assets/blob/main/images/bhasvic/bhasvic-rect-hills-text-small.png?raw=true">
</p>

# BTEC Computing Exam Technique

- [BTEC Computing Exam Technique](#btec-computing-exam-technique)
  - [Command words](#command-words)
    - [Describe](#describe)
      - [Example question](#example-question)
      - [Exemplar response](#exemplar-response)
    - [Explain](#explain)
      - [Example question](#example-question-1)
      - [Exemplar response](#exemplar-response-1)
    - [Discuss](#discuss)
      - [Example question](#example-question-2)
      - [Exemplar response](#exemplar-response-2)

## Command words

### Describe

Providing an account of something, or highlight a number of key features of a given topic. May be used in relation to the stages of a process.

*"Painting a picture with words!"*

#### Example question

> Benjin is a digital artist who creates digital graphics for a range of purposes.
> 
> Benjin uses a graphics tablet when he is creating graphics.
>
> Describe how **one** feature of a graphics tablet helps digital artists with their work.
> 
> <p align="right">[2 marks]</p>

#### Exemplar response

- graphics tablets support pressure-sensitive and tilt-supported styli
- styli allow artists to easily reproduce common artistic methods used on paper, such as shading, as well as allowing the artists to reproduce fluid movements and curves which would not be possible with a mouse

### Explain

Make a series of linked points and/or justify or expand on an identified point.

Some students miss out the linking step (e.g. in the answer below, they don't state that the touchscreen is used to enter the number plate). This is **critical**, else you'll only get half marks.

#### Example question

*From the [Car Park question](assets/Car%20Park%20Hardware%20Q.pdf).*

> Explain **two additional** input devices that could be used to meet the system specifications in **Figure 2**. 
> 
> <p align="right">[4 marks]</p>

#### Exemplar response

- a touchscreen **(1)**
  - driver taps characters on an on-screen keyboard to enter the vehicle number plate **(1)**
- a debit/credit card reader **(1)**
  - used to pay the parking fee calculated at the pay station **(1)**

### Discuss

Investigate a problem or scenario, showing reasoning or argument.

Talk about the key points – *in a logical order* – developing each point individually.

**Remember to tailer your knowledge to the specific scenario**, not just demonstrating your knowledge in general.

#### Example question

> Stephanie is a computer software designer who has just set up her own business.
> 
> Stephanie designs and creates computer software for a range of different devices and platforms, including traditional personal computers (PC) and mobile devices.
>
> Her work involves:
> - producing and compiling code
> - designing and building 3D environments for computer games
> - developing different versions of her software for different devices. 
>
> Stephanie wants to purchase a new desktop PC for use when she is designing and creating software.
> 
> Discuss the factors affecting Stephanie and her choice of computer system.

#### Exemplar response

Stephanie's system will need to be tailored to her needs, specifically in user experience, compatibility, cost, effectiveness, and security.

Stephanie will not have much money to spend on this system as she has only just set up her own business. She'll need to balance the cost of the system along with is efficiency and usability in her common tasks (code compilation, 3D design, and version control). She can save a lot of money by purchasing components separately and assembling a system herself, as opposed to purchasing a prebuilt system.

Code compilation times should be as low as possible (within reason) to provide less "empty time" (time where nothing can be done while waiting for code to compile). For this, a multi-core processor is important. This allows the code to be compiled in parallel, resulting in much faster compile times than a single-core processor. An idea CPU would be at least 4 cores (with SMT), or 6 cores (without SMT).

Furthermore, to aid in her 3D design, she would need a graphics card. For 3D design work, an integrated graphics chip inside an APU would not suffice, instead warranting a discreet GPU, such as an RTX 2060. Modern GPUs are very efficient, and 3D design would not need the best GPU available, so a mid-range graphics card would be enough for Stephanie, but a high-end graphics card would still be much better, if she can afford one.

Integrated development environments, such as the ones Stephanie may use, often need a lot of RAM to ensure they operate quickly, which is key to development. The bare minimum Stephanie could use is 8 GB RAM, but I would recommend at least 16 GB to provide the extra headroom she may need in the future. This would also be very helpful when running mobile emulators, such as the Android Emulator, to test her software on other devices easily.

As Stephanie's job will require her using the computer for extended periods of time, it's critical that the computer is comfortable and ergonomic to use. She should invest in a high quality office chair with appropriate back support, as well as a good keyboard and mouse, along with a wrist rest to support her wrist and prevent injuries such as RSI.

Stephanie will also need a lot of storage to store separate versions of her software for each of the different devices she is developing for. I would recommend Network Attached Storage for this purpose, as, if in RAID 10, it can provide large amounts of storage while allowing for redundancy in case a drive fails. She could also set up her router to allow her to access these files anywhere in the world.

Stephanie should make sure she selects a system that is compatible with the platforms she develops for. For example, if she wishes to develop for macOS or iOS, she must choose an Apple computer (or build a "Hackintosh"), otherwise she cannot use the tools needed to develop for these systems (XCode).
