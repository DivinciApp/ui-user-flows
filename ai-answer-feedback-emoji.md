```mermaid
graph TD;
    A[Auth0 Login] -->|Authenticated| B[Divinci AI Chat];
    B -->|Suggest + Choose Expert AI| C[Divinci Recommends a specialized AI];
    C -->|Expert AI suggested| D[User chooses to Add The Expert AI to the conversation];
    C -->|Expert AI not desired| E[User chooses to start a new conversation with the Expert AI];
    B -->|Suggest + Choose Expert AI| F[User votes up or down via short emoji list];
    F -->|Downvote| G[Feedback field drops down];
```