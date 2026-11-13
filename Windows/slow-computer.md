# Scenario 01: Computer Running Slowly

**Category:** Windows Troubleshooting  
**Difficulty:** Beginner  
**Status:** Resolved

## 1. Problem Description

A user reported that their Windows computer was running slowly. Applications took longer to open, and the computer occasionally became unresponsive.

## 2. Possible Causes

- High RAM consumption.
- Too many applications running simultaneously.
- Too many browser tabs open.
- Background applications consuming system resources.
- Insufficient available storage space.

## 3. Investigation and Diagnosis

The technician opened Windows Task Manager using `Ctrl + Shift + Esc` to examine system resource usage.

Initial resource readings:

| Component | Usage |
|---|---:|
| CPU | 18% |
| Memory (RAM) | 95% |
| Disk | 12% |

The investigation identified high memory consumption as the main performance bottleneck.

Google Chrome was consuming approximately 4 GB of RAM out of the computer's 8 GB.

Further investigation identified several open browser tabs, including a resource-intensive online design application.

## 4. Troubleshooting Procedure

1. Asked the user when the problem started.
2. Opened Task Manager.
3. Examined CPU, memory and disk usage.
4. Identified high RAM consumption.
5. Investigated Chrome's memory usage.
6. Asked the user to save their work.
7. Closed unnecessary browser tabs with the user's permission.
8. Rechecked memory consumption.

## 5. Solution Implemented

Unnecessary browser tabs were closed after ensuring that the user's work was saved.

This reduced the amount of memory being consumed by Chrome.

## 6. Results and Verification

After troubleshooting, memory usage decreased from 95% to 58%.

The computer became more responsive, and applications opened normally.

The user was asked to confirm that the performance had improved.

## 7. Lessons Learned

- Task Manager is useful for identifying system resource bottlenecks.
- High RAM consumption can affect computer performance.
- Browser tabs and extensions can consume significant memory.
- User data should be protected before troubleshooting.
- Technicians should verify solutions before closing support cases.
- Proper documentation helps with future troubleshooting.

## 8. Tools Used

- Windows Task Manager
- Google Chrome
- Windows Operating System

## 9. Conclusion

The slow computer problem was resolved by identifying excessive RAM consumption and closing unnecessary browser tabs.

This exercise demonstrated the importance of systematic troubleshooting, resource monitoring, user communication and technical documentation.

---

**Author:** Kuronoi
**Project:** IT Troubleshooting Handbook  
**GitHub:** https://github.com/kuronoi-tech
