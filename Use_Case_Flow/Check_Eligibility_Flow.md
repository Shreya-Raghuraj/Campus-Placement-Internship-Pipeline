# Use-Case Flow Specification: Check Eligibility

## Use Case

**Check Eligibility**

## Primary Actor

**Student Applicant**

## Preconditions

1. The student has a registered profile in the system.
2. An active placement or internship drive is available.
3. The company eligibility criteria are configured in the system.

## Postconditions

1. The system records the student's eligibility status for the selected drive.
2. An eligible student can proceed with the application.
3. An ineligible student is prevented from proceeding and the applicable discrepancy reasons are available.

## Main Success Scenario

1. The student selects an active placement or internship drive.
2. The system retrieves the eligibility criteria for the selected company.
3. The system retrieves the student's academic details and backlog information.
4. The system compares the student's profile with the specified eligibility criteria.
5. The system determines that the student satisfies all eligibility requirements.
6. The system records the student as eligible for the selected drive.
7. The student is allowed to proceed with the application.

## Alternate Flow

**A1. Student does not satisfy the eligibility criteria**

1. The system identifies one or more eligibility discrepancies.
2. The system records the student as ineligible for the selected drive.
3. The system provides the applicable discrepancy reasons.
4. The student is prevented from proceeding with the application for that drive.
