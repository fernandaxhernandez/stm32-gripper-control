# STM32-Based Robotic Gripper Control System

This repository contains the embedded control software for a two-degree-of-freedom robotic gripper implemented on an STM32F411 microcontroller (ARM Cortex-M4).

The project focuses on real-time control, task scheduling, and safe interaction between a high-level perception system and low-level actuation as part of a larger autonomous robotics platform.

---

## Overview

- Implemented low-level motor control for gripper articulation and grasping mechanisms.
- Designed a real-time task architecture using FreeRTOS to handle motion control, safety checks, and state monitoring.
- Enabled bidirectional communication with a Jetson Nano using USART and ROSserial for command execution and feedback.
- Integrated fault detection and emergency stop logic to ensure safe operation under error conditions.

---

## System Architecture

- **Microcontroller:** STM32F411 (ARM Cortex-M4, up to 100 MHz)
- **RTOS:** FreeRTOS
- **Communication:** USART + ROSserial
- **Peripherals:** ADC, Timers (PWM), GPIO
- **Integration:** Designed to interface with a higher-level perception and decision-making system running on a Jetson Nano

---

## Repository Structure

