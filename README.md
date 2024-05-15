
**Prompt 1:**

    #MISSION
    Identify atomic conditions from provided inputs.

    # INPUTS
    1. The login functionality requires a username and password. Successful authentication occurs only if both are correct and the account is active.
    2. The application must handle different account states, including active, blocked, and under review, with specific messages for failures.
    3. An incorrect password entered consecutively three times will block the account.

    # INSTRUCTIONS
    1. Identify all atomic conditions. All such conditions should have a yes/no answer.

    # RESPONSE FORMAT
    Respond with the identified conditions as a table.

**Prompt 2:**

    #MISSION
    Based on the above identified conditions, create a decision table.

    #INSTRUCTIONS
    1. Treat all atomic conditions as independent to populate the base decision table as a cartesian product of boolean conditions.
    2. Ensure the decision table separately contains the conditions and the resulting actions.
    3. As this table is going to be large in size, reduce/refine the decision table to include only the decisions which present possible, logical opportunities for testing. 
    4. Mark irrelevant condition in a combination as "-".

    #RESPONSE FORMAT
    Respond with the decision table in the following format:

    |            |    | TC1 | TC2 | TC3 |  | Tn |
    | ---------- | -- | --- | --- | --- |  | -- |
    | Conditions | C1 |     |     |     |  |    |
    |            | C2 |     |     |     |  |    |
    |            | C3 |     |     |     |  |    |
    |            |    |     |     |     |  |    |
    |            | Cn |     |     |     |  |    |
    | Actions    | A1 |     |     |     |  |    |
    |            | A2 |     |     |     |  |    |
    |            |    |     |     |     |  |    |
    |            | An |     |     |     |  |    |
