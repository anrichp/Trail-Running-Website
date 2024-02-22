# Trail-Running-Website
## User Interface (Runners)
### Upcoming Events
```mermaid
graph LR
    A[Upcoming Events] --> B(Event 1 Details)
    A --> C(Event 2 Details)
    A --> D(More Events [Link]) 
```
### Add Events
```mermaid
graph TD
   A[Event Creation Form] --> B[Title, Date, Location, Description, etc.] 
   B --> C{Event is Valid?}
   C -- Yes --> D[Save to Database]
   C -- No --> A[Error Message - Revise]
```
### Past Results
```mermaid
graph LR
    subgraph Results
    A[Past Results] --> B(Filter by Event)
    B --> C(Event Name 1 Results)
    B --> D(Event Name 2 Results)
    end
```
## Administrator Interface
### Add Events
```mermaid
graph TD
   A[Event Creation Form] --> B[Title, Date, Location, Description, etc.] 
   B --> C{Event is Valid?}
   C -- Yes --> D[Save to Database]
   C -- No --> A[Error Message - Revise]
```
### Manage User Profiles
```mermaid
graph LR
    A[User Search] --> B[User Profile List]
    B --> C(Individual User Profile)
    C--> D[Edit Profile]
    C --> E[Suspend Account] 
    C --> F[Delete Account] 
```
