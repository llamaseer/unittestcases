- Does your method have parameters?
    - What will happen if any of the parameters
        - is missing?
        - is null?
        - is outside of expected boundaries?
        - is mismatched
            - of different type?
            - of invalid size?
- What's your logic?
    - Can some other code modify your input?
    - Which other code waits for your output?
    - What will happen if you output null?
    - What will happen if your code doesn't provide its output on time?
    - Does your logic have all possible outputs defined?
    - Are all branches still relevant? 
- Do you interact with data?
    - Do you CRUD data?
        - What will happen if you lose rights to CRUD?
        - What will happen if the data is missing?
        - Can you distinguish between no access and no data or corrupted data?
- Do you loop?
    - Are you sure you'll always exit the loop?
    - Are you sure you need to loop?
    - Do you exit quickly on error?
    - Do you not enter the loop if it's not necessary?
- Do you make unnecessary calls if the control flow doesn't run smoothly?
- Is there handling for all exceptions?
