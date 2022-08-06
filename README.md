
# Intelligent Shift Scheduling 
#### 智能排班

A satisfactory shift schedule can be extremely hard to create and adjust. This app is designed and developed to use AI optimization technologies to address such issues. It is powered by the following features:
- The number of shifts in each day is used to categorize and model a wide range of employee shift scheduling problems. Currently, 1/2/3/4/5/6/7/8 shifts per day are supported.
- It is furnished with innovatively developed scheduling engines that make it simpler for the user to create, update, and iteratively optimize employee shift schedules.
- It provides a collection of fundamental shift scheduling constraints for scheduling decision-making, which are extracted and derived from common and frequently used schedule requests. To satisfy numerous requirements in the real world, those constraints might be merged to form quite complicated constraints.
- Reactive scheduling with constraint addition and removal is a key component of the app's approach to handling often changing requirements. In response to the new request, a minimal number of adjusted shifts are sorted in comparison to the current schedule.
- Another characteristic of this app is its remarkable flexibility. It can be used to fulfill simple to complex scheduling tasks. The process of creating and revising schedules can be as easy as choosing an option and pressing a button. On the other hand, sophisticated strategies and techniques are available to deal with difficult issues (e.g., decomposition of a problem and merging multiple scheduling results to form the final results).
- Each employee's total working hours, total number of shifts, total number of days off, and total number of shift types are comprehensively considered and handled in a schedule cycle. To achieve a better balance between the needs of the employees and those of the companies, constraint adjustment and optimization algorithms are applied
- Observable results are shown in tables for the scheduled outcomes. To communicate with external systems, integration tools are available (e.g., import employee data into the system, output schedule results to an excel file, etc.).
- Using this app, managers' daily workloads will be eased and employees will be greatly motivated to increase their productivity and improve their quality of work. The schedule results will also provide management practical advice to optimize employee structure and lowering administrative costs.


## Shift Schedule Examples
1. Creating a schedule for 9 employees over a 7-day period, subject to the following constraints:
   - Each day is divided into three 8-hour shifts. Each shift requires different number of employees.
     - A-shift：00:00-08:00（1 employee required）
     - B-sfhit：08:00-16:00（3 employees required）
     - C-shift：16:00-24:00（3 employees required）
   - Every day, no employee works more than one shift.
   - Number of shifts are evenly assigned to employees.
   - Shifts assined to any employee are spaced by at least 16 hours.
   - Each employee has at least one day off in the 7-day period.

App Result:
![image](https://user-images.githubusercontent.com/84350533/119012794-a5a1a800-b996-11eb-8254-cbe54cebc874.png)
In this shift schedule，4 employees must work for 48 hours a week. others work for 40 hours a week.

2. Creating a schedule for 35 employees over a 7-day period, subject to the following constraints:
   - Every day is divided into six 4-hour time slots. Each time slot requires different number of employees. 
     - A-slot：02:00-06:00（6 employee required）
     - B-slot：06:00-10:00（9 employees required）
     - C-slot：10:00-14:00（10 employees required）
     - D-slot：14:00-18:00（10 employees required）
     - E-slot：18:00-22:00（9 employees required）
     - F-slot：22:00-02:00（6 employees required)
   - Every day, 5 shifts are arranged as shown in the table below:
  ![image](https://user-images.githubusercontent.com/84350533/183245697-5dc5c5ad-f774-49d1-93ca-512be6bbd809.png)
   - Every day, no employee works more than one shift.
   - Each employee takes two days off in the 7-day period. 
   - Number of shifts are evenly assigned to employees
   - Shifts taken by each employee are spaced by at least 24 hours.

App Result:
![image](https://user-images.githubusercontent.com/84350533/181852021-45e3dec2-4bf8-42b8-ab56-0e08492d99c3.png)
In this shift schedule，each employee works for 40 hours a week.

Email:weiran.aitech@gmail.com

30-07-2022, Eindhoven, The Netherlands.
