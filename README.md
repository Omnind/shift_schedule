
# Intelligent Shift Scheduling  
#### 智能排班软件

## Motivation:
A satisfactory shift schedule can be extremely hard to create. On the other hand, no matter how perfect the first schedule is at the time of launch, frequent adjustments are usually inevitable due to unforeseen circumstances like an employee's illness or a no-show. To ensure that there are always enough employees available to cover all shifts, a broadly applicable, intelligent shift scheduling system that can react to the events of each day is needed in the modern world. This software has been uniquely and innovatively designed and developed to efficiently address such issues using combinatorial optimization and artificial intelligence (AI) technologies. 

## Key features:
- A wide variety of employee shift scheduling problems are classified by the same number of shifts set on every day in a schedule cycle. Currently, one to eight shift arrangements per day in a cycle are supported.
- This software is furnished with innovatively developed scheduling engines and modeling tools that make it easier for users to create, update, and iteratively optimize shift schedules. It is no longer necessary to build an LP, MIP, or CSP model for a shift scheduling problem. Instead, the problem model is built in a simpler, more user-friendly way by entering parameters and constraints into a set of dialogs.
- It provides a collection of basic shift scheduling constraints for decision-making and model-building that are extracted and derived from common and frequently used schedule requests. Rather than being presented as mathematical formulas (e.g. a set of linear inequalities), these constraints are expressed by descriptive phrases in dialogs. Multiple basic constraints may be combined to generate more complex constraints to cope with the various requirements that arise in the real world.
- One of the most notable advantages this software delivers is its reactive scheduling capability, with which user can dynamically add or remove constraints to tackle the challenges of ongoing schedule adjusment. In order to create the least amount of perturbation when a new request comes in, a minimal number of altered shifts are sought in contrast to the existing schedule.
- Another characteristic of this software is its remarkable flexibility. It can be used to fulfill simple and complex scheduling tasks. The process of modeling, creating and revising schedules can be as easy as choosing an option and pressing a button. Moreover, sophisticated strategies and techniques are also available to deal with difficult issues (e.g., decomposition of a problem and merging multiple scheduling solutions to construct the final results).
- The total working hours, total shifts, total days off, total number of different shifts, and shift interval for each employee are comprehensively considered and processed in a scheduling cycle. By referring to the estimation results and applying optimization algorithms, a balance between the needs of employees and the company can be achieved.
- A cycle of a schedule may last one to seven days. The user can choose to terminate a scheduling process after one cycle of scheduling is complete or continue into the next cycle. In the latter case, the software will take the outcomes of the preceding cycle into account and ensure that the shifts between cycles also satisfy the constraints used inside a cycle.
- The scheduling outcomes will be shown in Gantt-charts and GUI tables. Integration tools are provided to communicate with external systems (e.g., import employee data into the software, export results to an excel file, and send results to employees via text message or social media. etc.).

## Examples:
### 1. Creating a schedule for 9 employees over a 7-day period, subject to the following constraints:
   - Each day is divided into three 8-hour shifts. Each shift type requires different number of employees.
     - A-shift：00:00-08:00（1 employee required）
     - B-sfhit：08:00-16:00（3 employees required）
     - C-shift：16:00-24:00（3 employees required）
   - Every day, no employee works more than one shift.
   - Number of shifts are evenly assigned to employees.
   - Each employee has at least one day off in the 7-day period.

Software solution:
![image](https://user-images.githubusercontent.com/84350533/195989630-e41d4abd-19a0-4b4e-9808-cd04854909ce.png)
In this shift schedule, 4 employees work for 48 hours and 5 employees work for 40 hours a week. The shifts assined to each employee are spaced by at least 16 hours.

### 2. Creating a schedule for 10 employees over a 7-day period, subject to the constraints as listed in example 1.

Software solution:
![image](https://user-images.githubusercontent.com/84350533/194903255-47e8b605-31fc-4276-b548-bc78046de343.png)
In this shift schedule, 9 employees work for 40 hours, 1 employee works for 32 hours a week. Each employee has at least two days off in the 7-day period and has different shift types on two consecutive days. The shifts assigned to each employee are spaced by at least 24 hours.

### 3. Creating a schedule for a hospital department over a 7-day period, subject to the following constraints:
- Each day is divided into three 8-hour shifts. Each shift type requires different number of employees on different level.
     - A-shift：23:30-07:30（1 Senior Nurse, 1 Nurse and 1 Assistant Nurse required）
     - B-sfhit：07:30-15:30（1 Senior Nurse, 3 Nurses and 2 Assistant Nurses required）
     - C-shift：15:30-23:30（1 Senior Nurse, 2 Nurses and 1 Assistant Nurse required）
   - Every day, no nurse works more than one shift.
   - No nurse works more than 40 hours in 7-day period.
   - Number of shifts are evenly assigned to nurses.
   - Each nurse has at least one day off in the 7-day period.
   - Nurse01 and Nurse02 do not work on the same shift.
   - Arrange AssistantNurse1 to work simultaneously with SeniorNurse1 as much as possible

Software solution:
![image](https://user-images.githubusercontent.com/84350533/215545886-3eb0e683-f04e-432d-93f5-15e03530c239.png)
In this shift schedule, the shifts assigned to each employee are different for two consecutive days, and they are spaced by at least 24 hours.

### 4. Creating a schedule for 35 employees over a 7-day period, subject to the following constraints:
   - Every day is divided into six 4-hour time slots. Each time slot requires different number of employees. 
     - A-slot：02:00-06:00（6 employee required）
     - B-slot：06:00-10:00（9 employees required）
     - C-slot：10:00-14:00（10 employees required）
     - D-slot：14:00-18:00（10 employees required）
     - E-slot：18:00-22:00（9 employees required）
     - F-slot：22:00-02:00（6 employees required)
   - Every day, 5 shifts are arranged as shown in the table below, where each shift contains two 4-hour time slots:
  ![image](https://user-images.githubusercontent.com/84350533/183245697-5dc5c5ad-f774-49d1-93ca-512be6bbd809.png)
   - Every day, no employee works more than one shift.
   - Each employee has two days off in the 7-day period. 
   - Number of shifts are evenly assigned to employees

Software solution:
![image](https://user-images.githubusercontent.com/84350533/219944533-d0661a77-8b62-42c3-a45a-3077948fc8e4.png)
In this shift schedule, each employee works for 40 hours a week. The shifts assigned to each employee are different for two consecutive days, and they are spaced by at least 24 hours.

## Note:
R&D for the software is in progress. The code that's been uploaded is incomplete. 
## Contact:
Email:weiran.aitech@gmail.com; weiran.aitech@ziggo.nl
