# Regression Test Report

## Regression Report ID

RR-001

## Build Version Tested

v0.0.2

## Previous Build Version

v0.0.1

## Tester

Grant Angell

## Test Date

7/31/26

# Purpose

Verify that the PlayerLook.cs changes fixed the player body rotation issue and confirm existing movement functionality was not affected.

# Change Summary

## Features Changed

- Player Camera Look / Player Rotation System

## Bugs Fixed

None


# Test Environment

- Platform: PC
- Operating System: Windows 11 Home
- Engine: Unity 2022.3.6f1
- Hardware:
-CPU: AMD Ryzen 5 7535HS
-GPU: Nvidia RTX 4050 Laptop GPU(6GB VRAM)
-RAM: 16GB DDR5
-Storage: 512GB PCIe NVMe SSD


# Regression Scope

Features tested to ensure existing functionality was not affected:

- Player WASD Movement
- Player Camera Look


# Regression Test Cases Executed

| Test Case ID | Feature Tested | Result |
| TC-001 | WASD Player Movement | PASS |
| TC-002 | Player Camera Look | FAIL| 


# Failed Tests

List any failed regression tests.

-TC-002 Caused player's body to face forward regardless of camera direction


# Bugs Discovered During Regression

| Bug ID | Title | Severity |
| BUG-001 | - Player WASD Movement
- Player Camera Look | High |


# Test Summary

Total Tests: 2

Passed: 1

Failed: 1 

Blocked: 0


# Regression Result

FAIL


# Risk Assessment

Same issue found in PlayerLook.cs for player body facing forward regardless of camera direction
