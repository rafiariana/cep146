
# Lab 1
# Computer Systems In-Class Lab Exercises

## Exercise 1: System Hardware Detective (15-20 minutes)
**Format:** Solo or pairs  
**Objective:** Students will identify and analyze their computer's hardware components using built-in system tools.

### Instructions:
1. **Windows Users:** Open "System Information" (type `msinfo32` in Start menu)
   **Mac Users:** Hold Option key + Apple menu → "System Information"
   **Linux Users:** Open terminal and run `lscpu`, `lshw`, or `inxi -F`

2. **Find and record the following:**
   - Processor (CPU) brand, model, and number of cores: Processor	12th Gen Intel(R) Core(TM) i7-1255U, 2600 Mhz, 10 Core(s), 12 Logical Processor(s)
   - Total RAM amount and type (DDR4/DDR5): Installed Physical Memory (RAM)	16.0 GB, 35 = LPDDR5
   - Storage device type (HDD/SSD) and capacity: Size	475.07 GB (510,107,189,760 bytes), SSD
   - Operating System version: Version	10.0.22631 Build 22631

3. **Analysis Questions:**
   - Based on your CPU cores, how many tasks can your processor theoretically handle simultaneously? My processor has 12 logical processors, so it can theoretically handle 12 tasks at the same time. This improves multitasking and helps programs run more smoothly together.
   - Is your storage primarily HDD or SSD? What are the performance implications? My computer uses an SSD. SSDs are faster than HDDs, so my system boots faster, applications open quicker, and files transfer more efficiently.
   - How does your RAM amount compare to typical requirements for modern applications? My 16 GB of LPDDR5 RAM is suitable for modern applications. It is enough for multitasking, online learning, streaming, office work, and even some heavier programs like editing software and light gaming.

### Deliverable:
Complete a simple system specification sheet and answer the analysis questions.

---
## Lab Rubric

**Total Points: 2 marks**

## Requirements for Completion:
* **Exercise 1 (Required):** Complete system specification sheet with all hardware components identified AND answer all three analysis questions with thoughtful responses

## Lab Rubric:

| Criteria | Poor - 0 mark | Fair - 1 mark | Good - 2 marks |
|---|---|---|---|
| Lab Completion | Missing system specification data OR analysis questions not attempted OR answers lack depth (single sentence, vague responses that don't address the questions) | Successfully identified most hardware components and completed system specification sheet, but analysis questions show minimal effort or understanding | Successfully completed full system specification sheet with accurate hardware identification AND provided thoughtful analysis answers that demonstrate understanding of hardware implications |
