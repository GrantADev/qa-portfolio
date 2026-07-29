# Test Report

## Test Report ID
Test-001.md

## Build Version
v.0.01

## Tester
Grant Angell

## Test Date
7/29/2026

## Feature Tested
Player WASD Movement

## Test Objective
Verify that the player can move correctly using WASD keyboard input.

## Test Environment

- Platform: PC
- Operating System: Windows 11 Home
- Engine: Unity 2022.3.6f1
- Hardware:
    - CPU: AMD Ryzen 57535HS
    - GPU: NVIDIA GeForce RTX 4050 Laptop GPU (6GB VRAM)
    - RAM: 16GB DDR5
    - Storage: 512GB PCIe NVMe SSD

## Test Cases Executed

| Test Case | Result |

|Player moves forward using W key | Passed|
|Player moves left using A key | Passed|
|Player moves right using S key | Passed|
|Player moves backward using D key | Passed|
|Player moves diagonally using W + A keys | Passed|
|Player moves diagonally using W + D keys | Passed|
|Player moves diagonally using S + A keys | Passed|
|Player moves diagonally using S + D keys | Passed|
|Player stops movement after releasing movement keys | Passed|
|Player remains consistent after continuous input | Passed|


## Bugs Found

None


## Test Summary

Total Tests: 10

Passed: 10 

Failed: 0

Blocked: 0


## Overall Result

PASS


## Notes

Additional Observations: Gravity and physics-based movement were not tested because they were outside the scope of this test.