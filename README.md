EXPERIMENT 05 AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL

NAME: ABINAYA R

REG.NO :212225230004

DATE :05.09.2026

Objective

To audit and monitor cloud activity in AWS using AWS CloudTrail by viewing and analyzing recorded AWS events and identifying important audit information such as user identity, event name, event time, AWS service, region, and operation status.

1. Requirements

• AWS Account

• Web Browser

• Internet Connection

• Amazon S3 access

• AWS CloudTrail

PART A — ACCESS AWS CLOUDTRAIL

Step 1: Login to AWS

Open the AWS Management Console.

Sign in using your AWS account.

In the AWS search bar, type CloudTrail.

Select AWS CloudTrail.

<img width="833" height="426" alt="Screenshot 2026-09-05 095002" src="https://github.com/user-attachments/assets/0e2b7d57-25a5-470b-9c39-5986f8ef31e4" />


Step 2: Open Event History

In the CloudTrail navigation menu, select Event history.

CloudTrail displays recent AWS activity.

Review the available events.

The Event History page may display information such as:

• Event time

• Username

• Event name

• Event source

• Resource type

• Resource name

<img width="830" height="322" alt="Screenshot 2026-09-05 095135" src="https://github.com/user-attachments/assets/44f1c106-72a7-49b5-b11a-27151bb0cdec" />


PART B — ANALYZE A CLOUDTRAIL EVENT

Step 3: Select an Event

From the Event History list, select an S3-related event.

Click the event to open its details.

Examine the event information and the event record/JSON.

For this experiment, a CreateBucket event can be used.

Step 4: Analyze the CreateBucket Event

The CreateBucket event indicates that an Amazon S3 bucket creation operation occurred.

Record the following information:

<img width="667" height="565" alt="Screenshot 2026-09-05 095206" src="https://github.com/user-attachments/assets/e024d4cd-cd5b-44a4-82e9-437cfe80af7b" />


Meaning of important fields

<img width="832" height="357" alt="Screenshot 2026-09-05 095226" src="https://github.com/user-attachments/assets/d83844aa-7d21-4d32-955b-73736f7061d0" />


PART C — IDENTIFY ANOTHER CLOUDTRAIL EVENT

Step 5: Select Another Event

Return to CloudTrail → Event history.

Select another event.

Open its details.

Record the important fields.

For example, an event such as:

AutomatedDefaultVpcCreation

may be present.

This event is associated with Amazon EC2.

Step 6: Analyze the Second Event

Record:

<img width="658" height="552" alt="Screenshot 2026-09-05 123509" src="https://github.com/user-attachments/assets/d4e5a96e-986b-4e64-a538-2a58c9e951b7" />


<img width="833" height="371" alt="Screenshot 2026-09-05 095546" src="https://github.com/user-attachments/assets/4b9e7dff-ed3b-437b-a27c-62048280eb36" />


PART D — COMPARE THE EVENTS

Step 7: Prepare the Audit Comparison

Compare the two CloudTrail events.

<img width="822" height="386" alt="Screenshot 2026-09-05 095559" src="https://github.com/user-attachments/assets/98bbee1c-060e-4193-8176-3e2049a2d8b4" />


PART E — SECURITY AUDIT ANALYSIS

Step 8: Identify Who, What, When and Where

For each event, identify:

WHO?

Who or which identity performed/generated the activity?

WHAT?

What AWS operation was performed?

WHEN?

At what date and time did the activity occur?

WHERE?

In which AWS Region did the activity occur?

RESULT?

Was the operation successful or did it generate an error?

Step 9: Prepare the Final Audit Table

<img width="826" height="155" alt="Screenshot 2026-09-05 095614" src="https://github.com/user-attachments/assets/daec4de1-7470-4e62-a260-230583a726d8" />


RESULT

The cloud activities in AWS were successfully audited using AWS CloudTrail Event History. Different AWS events were examined based on event time, user identity, event name, event source, AWS Region, read-only status, and error status. The experiment demonstrated how AWS CloudTrail provides an audit trail for monitoring, accountability, and investigation of cloud activities.
