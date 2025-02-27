# Technical solution in Ticketing 

Technical solution is a new **status** in the ticket interface, similar to Closed and Solved. Users can select a solution, but the ticket remains still open. 

# Interface display and function
The technical solution is in the "Estado" (Status) drop-down. After selecting it, the "Select Solution" drop down appears. When the user wants to close the ticket, the technical solution is selected by default, but the user can select another solution. 

![status](https://github.com/user-attachments/assets/3bd6de3a-f2e1-4703-97ac-16dd972e2768)

## Explanation of solutions shown

The solutions displayed for "Technical Solution" are similar to normal solutions, except that they are not mapped to a Ticket Type but to the Queue of the current user. So if the user is in the "CST.BA" queue, he will see the solutions mapped to "CST.BA", no matter what type is set to the ticket. 

# Administration 

The Solutions can be mapped from menu XXX - link 

# Developer details

- **DB:** table tsi.dbo.map.....
- Admin right: #123....
  


