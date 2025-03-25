# Embedded Testing
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Check Links](https://github.com/onmcu/awesome-embedded-testing/actions/workflows/links.yml/badge.svg)](https://github.com/onmcu/awesome-embedded-testing/actions/workflows/links.yml)

Curated list of tools and resources for testing Embedded and Low-level software

## Table of Contents
- [Embedded Testing](#embedded-testing)
  - [Table of Contents](#table-of-contents)
  - [Books, blogs and training materials](#books-blogs-and-training-materials)
  - [Test Frameworks](#test-frameworks)
    - [Rust Test Frameworks](#rust-test-frameworks)
    - [General Embedded Testing Frameworks](#general-embedded-testing-frameworks)
    - [Mocking and Hardware Simulation](#mocking-and-hardware-simulation)
    - [Embedded Integration & Continuous Integration (CI)](#embedded-integration--continuous-integration-ci)
    - [Static & Dynamic Analysis](#static--dynamic-analysis)
    - [Embedded-Specific Testing Techniques & Tools](#embedded-specific-testing-techniques--tools)
    - [Test Automation & Hardware-in-the-Loop (HIL)](#test-automation--hardware-in-the-loop-hil)
    - [Examples & Reference Projects](#examples--reference-projects)

## Books, blogs and training materials

## Test Frameworks
### Rust Test Frameworks
- **[embedded-test](https://crates.io/crates/embedded-test)** Rust test harness and runner for embedded devices ![Lang: Rust](https://img.shields.io/badge/Lang:-Rust-fe7d37)

### General Embedded Testing Frameworks
- **[Ceedling/Unity](https://github.com/ThrowTheSwitch/Ceedling)** – Popular C-based unit testing and build framework, great for small to medium-sized embedded projects. ![Lang: C](https://img.shields.io/badge/Lang:-C-blue)
- **[GoogleTest (gtest)](https://github.com/google/googletest)** – Widely used and highly customizable C++ testing framework, commonly adopted in embedded C++ projects. ![Lang: C++](https://img.shields.io/badge/Lang:-C++-violet)
- **[CppUTest](https://github.com/cpputest/cpputest)** – Flexible testing framework tailored specifically to embedded software, emphasizing memory safety and simplicity. ![Lang: C++](https://img.shields.io/badge/Lang:-C++-violet)
- **[Catch2](https://github.com/catchorg/Catch2)** – Modern C++ testing framework known for ease of use and expressive assertions, lightweight enough for embedded targets. ![Lang: C++](https://img.shields.io/badge/Lang:-C++-violet)

### Mocking and Hardware Simulation
- **[CMock](https://github.com/ThrowTheSwitch/CMock)** – Generates mock objects automatically for C, ideal for testing interactions with hardware-dependent code. ![Lang: C](https://img.shields.io/badge/Lang:-C-blue)
- **[Fake Function Framework (FFF)](https://github.com/meekrosoft/fff)** – Lightweight, simple mocking framework for C-based embedded software. ![Lang: C](https://img.shields.io/badge/Lang:-C-blue)
- **[Renode](https://github.com/renode/renode)** – Powerful framework for hardware simulation and testing, allowing execution and debugging of embedded binaries without actual hardware. ![Lang: Multi](https://img.shields.io/badge/Lang:-Multi-blueviolet)
- **[QEMU](https://github.com/qemu/qemu)** – Widely adopted open-source emulator, very useful for full-system simulation of embedded platforms during testing. ![Lang: Multi](https://img.shields.io/badge/Lang:-Multi-blueviolet)
- **[embedded-hal-mock](https://github.com/dbrgn/embedded-hal-mock)** – Mocks for testing embedded-hal based drivers without hardware access. ![Lang: Rust](https://img.shields.io/badge/Lang:-Rust-fe7d37)

### Embedded Integration & Continuous Integration (CI)
- **[PlatformIO](https://github.com/platformio/platformio-core)** – Cross-platform build tool and package manager, ideal for automating builds and tests for embedded projects. ![Lang: Multi](https://img.shields.io/badge/Lang:-Multi-blueviolet)
- **[Embench](https://github.com/embench/embench-iot)** – Open-source benchmarking suite specifically targeting IoT-class embedded systems. ![Lang: Multi](https://img.shields.io/badge/Lang:-Multi-blueviolet)
- **[Robot Framework](https://github.com/robotframework/robotframework)** – Generic acceptance-test automation framework, commonly used for higher-level integration and system tests. ![Lang: Python](https://img.shields.io/badge/Lang:-Python-3775A9)

### Static & Dynamic Analysis
- **[Cppcheck](https://github.com/danmar/cppcheck)** – Popular static analysis tool specifically tailored for C and C++ codebases. ![Lang: C/C++](https://img.shields.io/badge/Lang:-C/C++-fe7d37)
- **[Valgrind](https://github.com/paulfloyd/freebsd_valgrind)** – Dynamic analysis tool useful for memory leak detection and error tracking. ![Lang: Multi](https://img.shields.io/badge/Lang:-Multi-blueviolet)
- **[Clang Sanitizers](https://github.com/google/sanitizers)** – Effective runtime debugging tools for detecting memory safety errors in embedded C/C++ applications. ![Lang: C/C++](https://img.shields.io/badge/Lang:-C/C++-fe7d37)

### Embedded-Specific Testing Techniques & Tools
- **[Embedded Artistry's Embedded Testing Guides](https://github.com/embeddedartistry/embedded-resources)** – Curated resources and examples for best practices in embedded software testing. ![Lang: Multi](https://img.shields.io/badge/Lang:-Multi-blueviolet)
- **[Tracealyzer](https://github.com/Percepio)** *(Commercial with free tiers)* – Real-time trace visualization for debugging and performance analysis of embedded systems. ![Lang: Multi](https://img.shields.io/badge/Lang:-Multi-blueviolet)

### Test Automation & Hardware-in-the-Loop (HIL)
- **[Labgrid](https://github.com/labgrid-project/labgrid)** – Automation framework for hardware-in-the-loop testing, integrates smoothly with continuous integration. ![Lang: Python](https://img.shields.io/badge/Lang:-Python-3775A9)
- **[OpenHTF](https://github.com/google/openhtf)** – Hardware testing framework from Google designed for automated manufacturing tests and HIL testing. ![Lang: Python](https://img.shields.io/badge/Lang:-Python-3775A9)

### Examples & Reference Projects
- **[Nasa JPL's F Prime](https://github.com/nasa/fprime)** – NASA's open-source flight software framework, extensively tested and validated. ![Lang: C++](https://img.shields.io/badge/Lang:-C++-violet)
- **[LittlevGL](https://github.com/lvgl/lvgl)** – Embedded GUI library extensively using unit tests and automated integration testing. ![Lang: C](https://img.shields.io/badge/Lang:-C-blue)
