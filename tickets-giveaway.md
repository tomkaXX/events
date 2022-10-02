# Free tickets giveaway for a conferences 

```mermaid
sequenceDiagram
    participant Apply for a conference
    participant Buy a ticket yourself
    Apply for a conference->>Waiting for answer: Hello ,how to get a developer free/discounted ticket?
    loop Healthcheck
        Waiting for answer->>Waiting for answer: Relax and wait - sometimes it's take couple weeks to hear back from organizers.
    end
    Note right of Waiting for answer: Rational thoughts <br/>prevail!
    Waiting for answer-->>Apply for a conference: Great! You got a free ticket!
    Waiting for answer->>Buy a ticket yourself: Sorry bro, you have to buy ticket for yourself. 
    Buy a ticket yourself-->>Waiting for answer: Still coming!
```
