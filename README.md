# Tech Exam: Software Engineering - Flutter

Do not be serious, we just want to know more about you. 
Please do the exam with fun and we will be waiting to discuss it with you in the next interview session :satisfied:

## Submission Instruction
Please create a private GitHub repo and add Following username for access natcha@swiftdynamics.co.th

Once done, please send us the repo link via email to the list from above follow the department that you apply position.

If you have any questions, please feel free to contact us via hr@swiftdynamics.co.th (HR) or natcha@swiftdynamics.co.th (Senior Software Engineer)

## Objectives

- Develop the `TODO` application with your familiar technology stack 
- Develop based on below _Business Requirements_ and one of the _Application Spec_  
- Please submit back to us after you got the email within 7 days or if you are not inconvenienced please inform us :dizzy:

## Business Requirements

As a Tech team, we would like to know your experience by developing the TODO application, so we can understand more about how we suit and how we can collaborate together.

You can develop more additional features as you want to make us ✨ **WOW** ✨ with you

## Definition of Done
- The data must consist of the following fields

| Field  | Data Type | Notes |
| ------ | --------- | ----- |
| ID | UUID |  |
| Title | String |  |
| Description | String |  |
| Created At Date Time | Date Time with Time Zone |  | 
| Image | String |  |
| Status | String  | Accept: `IN_PROGRESS` \| `COMPLETED` |

- The TODO application can `CREATE` a task with the following requirements
    - The `ID`, `Title`,`Date`, and `Status` fields must be required
    - The `ID` field must be `UUID` format
    - The `Title` field must not over `100 characters` 
    - The `Date` field must be `RFC3399 with Timezone` format
    - The `Status` field must accept only `IN_PROGRESS` or `COMPLETE` status
    - The `Image` field must be `Based64 Encode` format
- The TODO application can show the `LIST` of tasks with the following requirements
    - Can sort the data by `Title` or `Date` or `Status` fields
    - Can search the data by `Title` or `Description` fields
- The TODO application can `UPDATE` a task with the following requirements
    - Can update a task by `ID` field
    - Can update `Title`, `Description`, `Date`, `Image`, and `Status` fields corresponding to the requirements from the `CREATE` feature

## Application Specs

- **Must have**
    - Use `Flutter` frameworks
    - `Read` and `Write` the data from `JSON` file or `LocalStorage`
    - Develop the `State Management` by `Riverpod` or  `GetX`
    - Write the `UnitTest`
        - Code coverage more than 75%
    - UI pages based on Business Requirements
      - You can design the UI as you like    

- **It Would be Great If You Have**
    - Develop by the `Clean Architecture` principles
    - Build and Deploy application to any Application Distribution tools. For example, Google App Distribution, Apple Store Test Flight and etc.
    - Responsive UI suitable for mobile and tablet

 :sunglasses: _We are waiting to work with you_ :punch:
