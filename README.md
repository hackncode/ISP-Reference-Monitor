# Repy V2 Security Monitor

**Objective:** Build a Repy V2 reference monitor.

**Instructions:** Follow the provided [guidelines](https://github.com/SeattleTestbed/docs/blob/master/EducationalAssignments/ABStoragePartOne.md).

**Testing:** Explore and test other monitors using [these instructions](https://github.com/SeattleTestbed/docs/blob/master/EducationalAssignments/ABStoragePartTwo.md).

**Enhancements:** Improve your monitor's security by addressing weaknesses as described in [this document](https://github.com/SeattleTestbed/docs/blob/master/EducationalAssignments/ABStoragePartThree.md).

## Overview

Create a security layer for maintaining backup copies of files. Ensure valid files start with 'S' and end with 'E'. Applications use ABopenfile() to create or open a file. Files are created with a valid backup file (filename.a) and an empty write file (filename.b). When close() is called on the file, if both files are valid, the original data is replaced with the data of filename.b. If filename.b is not valid, no changes are made.

### Requirements

1. Do not modify or disable any RepyV2 API calls.
2. Check file contents on close() for 'S' and 'E'.
3. Update the original file with valid data on close().
4. Do not produce errors or output during normal or invalid operations.

### Design Paradigms

- Accuracy: Allow normal actions, only stop specific blocked actions.
- Efficiency: Use minimal resources for optimal performance.
- Security: Prevent attackers from bypassing security measures.

## Building and Testing

1. Develop your security layer.
2. Simulate attacks to identify vulnerabilities.
3. Execute your security layer with an attack program.

## References

- [RepyV2 API documentation](https://github.com/kcg295/docs/blob/master/Programming/RepyV2API.md).
- [Academic paper on security layers](https://ssl.engineering.nyu.edu/papers/cappos_seattle_ccs_10.pdf).


# Security System with Repy V2

**Objective:** Create a Repy V2 reference monitor.

**Instructions:** Follow [these guidelines](https://github.com/SeattleTestbed/docs/blob/master/EducationalAssignments/ABStoragePartOne.md).

**Testing:** Explore and test other monitors using [these instructions](https://github.com/SeattleTestbed/docs/blob/master/EducationalAssignments/ABStoragePartTwo.md).

**Enhancements:** Improve your monitor's security by addressing weaknesses per [these guidelines](https://github.com/SeattleTestbed/docs/blob/master/EducationalAssignments/ABStoragePartThree.md).

## Building and Testing

- Develop your security layer.
- Simulate attacks to identify vulnerabilities.
- Execute your security layer with an attack program.

## References

- Refer to [RepyV2 API documentation](https://github.com/kcg295/docs/blob/master/Programming/RepyV2API.md).
- Explore security concepts in the provided [academic paper](https://ssl.engineering.nyu.edu/papers/cappos_seattle_ccs_10.pdf).


